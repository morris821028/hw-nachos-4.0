[BLOG ARTICLE](http://morris821028.github.io/2014/05/24/hw-nachos4/)

關於 NachOS 4.0
=====
作為教學用作業系統，需要實現簡單並且儘量縮小與實際作業系統之間的差距，所以我們採用 Nachos 作為作業系統課程的教學實踐平臺。Nachos 是美國加州大學伯克萊分校在作業系統課程中已多次使用的作業系統課程設計平臺，在美國很多大學中得到了應用，它在作業系統教學方面具有一下幾個突出的優點：

* 採用通用虛擬機器
* 簡單而易於擴展	
* 物件導向性
* ... 略

> 簡單地來說，就是一個模擬作業系統的軟體

安裝
=====
課程頁面：http://networklab.csie.ncu.edu.tw/2014_os/osweb.html#download

* Platform: Linux or Linux over VMware 
		RedHat Linux 9.0 
	在 Ubuntu 上面運行無法
* Install steps
	* Get NachOS-4.0
			wget ../nachos-4.0.tar.gz
	* Get Cross Compiler
			wget ../mips-decstation.linux-xgcc.tgz
	* Move Cross Compiler to /
			mv ./mips-decstation.linux-xgcc.tgz /
	* Untar Cross Compiler
 			tar zxvf ./mips-decstation.linux-xgcc.tgz
	* Untar NachOS-4.0
			tar zxvf ./nachos-4.0.tar.gz
	* Make NachOS-4.0
			cd ./nachos-4.0/code
			make
	* Test if installation is succeeded
			cd ./userprog
			./nachos -e ../test/test1
			./nachos -e ../test/test2

預期運行結果
```
Total threads number is 1
Thread ../test/test1 is executing.
Print integer:9
Print integer:8
Print integer:7
Print integer:6
return value:0
No threads ready or runnable, and no pending interrupts.
Assuming the program completed.
Machine halting!
                                                                                
Ticks: total 200, idle 66, system 40, user 94
Disk I/O: reads 0, writes 0
Console I/O: reads 0, writes 0
Paging: faults 0
Network I/O: packets received 0, sent 0

Total threads number is 1
Thread ../test/test2 is executing.
Print integer:20
Print integer:21
Print integer:22
Print integer:23
Print integer:24
Print integer:25
return value:0
No threads ready or runnable, and no pending interrupts.
Assuming the program completed.
Machine halting!

Ticks: total 200, idle 32, system 40, user 128
Disk I/O: reads 0, writes 0
Console I/O: reads 0, writes 0
Paging: faults 0
Network I/O: packets received 0, sent 0
```

作業階段
=====

## Multiprogramming ##
執行下述指令
```
./nachos –e ../test/test1 –e ../test/test2
```
{% codeblock lang:cpp test1.c %}
#include "syscall.h"
main() {
	int n;
	for (n=9;n>5;n--)
		PrintInt(n);
}
{% endcodeblock %}

{% codeblock lang:cpp test2.c %}
#include "syscall.h"

main() {
    int n;
    for (n=20;n<=25;n++)
        PrintInt(n);
}
{% endcodeblock %}

在開始動工前，發現在 Multithread 操作會有錯誤，test1 程序會遞減輸出，而 test2 程序會遞增輸出，但是根據運行結果，兩個程式都會遞增輸出。

目標運行結果如下：
```
Total threads number is 2
Thread ../test/test1 is executing.
Thread ../test/test2 is executing.
Print integer:9
Print integer:8
Print integer:7
Print integer:20
Print integer:21
Print integer:22
Print integer:23
Print integer:24
Print integer:6
return value:0
Print integer:25
return value:0
No threads ready or runnable, and no pending interrupts.
Assuming the program completed.
Machine halting!
 
Ticks: total 300, idle 8, system 70, user 222
Disk I/O: reads 0, writes 0
Console I/O: reads 0, writes 0
Paging: faults 0
Network I/O: packets received 0, sent 0
```

* 為什麼兩個程式都會遞增輸出？  
明顯地是兩個程式匯入時，操作到相同區域的 code segment。如果發現各別遞增和遞減，但是輸出 `n` 的結果錯誤，則可以想到是 `context-switch` 上發生問題。

### 解決 ###

需要為 physical address 做標記，這個 physical address 就是在 main memory 裡面的位置。而每一個 process 都會有一個 AddrSpace，然後紀錄 logical address 所對應在 physical address，也就是 `pageTable` 對應到 `pageTable[i].physicalPage`。

也就是說，當要執行 process 某一頁的程序，則將會去找 pageTable 所對應的 physicalPage，然後去運行。在作業一開始給的代碼中，會發現所有程序的 physicalPage 都共用，如此一來當然會執行到同一份 code。

首先，我們需要一個全局的標記，來記錄 main memory page 的情況。
{% codeblock lang:cpp usrprog/addrspace.h %}
class AddrSpace {
  public:
	...
    static bool usedPhyPage[NumPhysPages];
  private:
	...
};
{% endcodeblock %}

接著，在 addrspace.cc 宣告實體，並且初始化是 `0`，表示全部都還沒有用過。

{% codeblock lang:cpp usrprog/addrspace.cc %}
#include "copyright.h"
#include "main.h"
#include "addrspace.h"
#include "machine.h"
#include "noff.h"
	...
bool AddrSpace::usedPhyPage[NumPhysPages] = {0};
	...
{% endcodeblock %}

當 process 執行成功後，將會釋放資源。此時將要把標記使用的 page 設回未使用。
{% codeblock lang:cpp usrprog/addrspace.cc %}
AddrSpace::~AddrSpace()
{
	for(int i = 0; i < numPages; i++)
		AddrSpace::usedPhyPage[pageTable[i].physicalPage] = false;
   delete pageTable;
}
{% endcodeblock %}

最後，就是稍微麻煩的地方，當將程序載入記憶體時，要去填入 `pageTable[]` 對應的 `physicalPage`，這裡使用線性時間去搜索第一個未使用的 page 進行填入。

載入確定後，便要開始執行，執行的時候要去算程序進入點，進入點的位置即是 main memory address。

`mainMemory[pageTable[noffH.code.virtualAddr/PageSize].physicalPage * PageSize + (noffH.code.virtualAddr%PageSize)]`

首先算出第幾頁，然後乘上 `PageSize` 就是 page base，而 page offset 則是 `code.address mod PageSize`。

最後，`page base + page offset` 就是我們所需要的程序進入點。

{% codeblock lang:cpp usrprog/addrspace.cc %}
bool AddrSpace::Load(char *fileName) {
    OpenFile *executable = kernel->fileSystem->Open(fileName);
    NoffHeader noffH;
    unsigned int size;

    if (executable == NULL) {
	cerr << "Unable to open file " << fileName << "\n";
	return FALSE;
    }
    executable->ReadAt((char *)&noffH, sizeof(noffH), 0);
    if ((noffH.noffMagic != NOFFMAGIC) && 
		(WordToHost(noffH.noffMagic) == NOFFMAGIC))
    	SwapHeader(&noffH);
    ASSERT(noffH.noffMagic == NOFFMAGIC);

// how big is address space?
    size = noffH.code.size + noffH.initData.size + noffH.uninitData.size 
			+ UserStackSize;	// we need to increase the size
						// to leave room for the stack
    numPages = divRoundUp(size, PageSize);
//	cout << "number of pages of " << fileName<< " is "<< numPages << endl;
// morris add
	pageTable = new TranslationEntry[numPages];
	for(unsigned int i = 0, j = 0; i < numPages; i++) {
		pageTable[i].virtualPage = i;
		while(j < NumPhysPages && AddrSpace::usedPhyPage[j] == true)
			j++;
		AddrSpace::usedPhyPage[j] = true;
		pageTable[i].physicalPage = j;
		pageTable[i].valid = true;
		pageTable[i].use = false;
		pageTable[i].dirty = false;
		pageTable[i].readOnly = false;
	}
// end morris add
    size = numPages * PageSize;

    ASSERT(numPages <= NumPhysPages);		// check we're not trying
						// to run anything too big --
						// at least until we have
						// virtual memory

    DEBUG(dbgAddr, "Initializing address space: " << numPages << ", " << size);

// then, copy in the code and data segments into memory
	if (noffH.code.size > 0) {
        DEBUG(dbgAddr, "Initializing code segment.");
	DEBUG(dbgAddr, noffH.code.virtualAddr << ", " << noffH.code.size);
// morris add
        	executable->ReadAt(
		&(kernel->machine->mainMemory[pageTable[noffH.code.virtualAddr/PageSize].physicalPage * PageSize + (noffH.code.virtualAddr%PageSize)]), 
			noffH.code.size, noffH.code.inFileAddr);
// end morris add
    }
	if (noffH.initData.size > 0) {
        DEBUG(dbgAddr, "Initializing data segment.");
	DEBUG(dbgAddr, noffH.initData.virtualAddr << ", " << noffH.initData.size);
// morris add
        executable->ReadAt(
		&(kernel->machine->mainMemory[pageTable[noffH.initData.virtualAddr/PageSize].physicalPage * PageSize + (noffH.code.virtualAddr%PageSize)]),
			noffH.initData.size, noffH.initData.inFileAddr);
// end morris add
    }

    delete executable;			// close file
    return TRUE;			// success
}
{% endcodeblock %}

-----

## Sleep() System call ##

撰寫自己的 Sleep function，將該 Thread 進入休眠。

### 測試檔案 ###

與一開始的 `test1.c` 很像，這裡先做個簡單測試。
{% codeblock lang:cpp /code/test/sleep.c %}
#include "syscall.h"
main() {
	int i;
	for(i = 0; i < 5; i++) {
		Sleep(10000000);
		PrintInt(50);
	}
	return 0;
}
{% endcodeblock %}
因為整個測試檔案是要能在 nachOS 上面跑，所以不能使用一般的編譯方式？所以把這些訊息寫入 `Makefile` 中，之後下 `$ make` 產出 `sleep` 即可。
{% codeblock lang:cpp /code/test/Makefile %}
...
all: halt shell matmult sort test1 test2 sleep
...
sleep: sleep.o start.o
	$(LD) $(LDFLAGS) start.o sleep.o -o sleep.coff
	../bin/coff2noff sleep.coff sleep
...
{% endcodeblock %}
> 如果無法在 `/code/test` 下 `$ make` 順利產出，則請參照 ** 其他指令 **，將原本下載的 `mips-decstation.linux-xgcc.gz` 解壓縮產生的 `/usr` 移動到正確位置。

### 解決 ###

首先，要模仿 `PrintInt()`，找到切入的宣告位置。努力地尾隨前人。

{% codeblock lang:cpp /code/userprog/syscall.h %}
...
#define SC_PrintInt	11
#define SC_Sleep	12
...
void PrintInt(int number);	//my System Call
void Sleep(int number);         // morris add
...
{% endcodeblock %}

接著，找一下 ASM。
以下部分就不得而知了，為什麼會出現在 `/code/test` 目錄下。
{% codeblock lang:cpp /code/test/start.s %}
	...
PrintInt:
	addiu   $2,$0,SC_PrintInt
	syscall
	j       $31
	.end    PrintInt

	.globl  Sleep
	.ent	Sleep
Sleep:
	addiu   $2,$0,SC_Sleep
	syscall
	j	$31
	.end	Sleep
	...
{% endcodeblock %}

最後，確定 nachOS 會處理我們的例外操作。

{% codeblock lang:cpp /code/userprog/exception.cc %}
	...
case SC_PrintInt:
	val=kernel->machine->ReadRegister(4);
	cout << "Print integer:" << val << endl;
	return;
case SC_Sleep:
	val=kernel->machine->ReadRegister(4);
	cout << "Sleep Time " << val << "(ms) " << endl;
	kernel->alarm->WaitUntil(val);
	return;
	...
{% endcodeblock %}

> 到這裡需要喘口氣，剛找了一陣子的代碼。接著才是重頭戲，因為你看到了 `kernel->alarm->WaitUntil(val);` 出現了。沒錯！我們需要撰寫那邊的代碼。

既然 kernel 存有 `alarm`，也就是說每隔固定一段間，就會呼叫 `Alarm::CallBack()`，因此，對於這個鬧鐘來個累加器 `Bedroom::_current_interrupt`，全局去記數，當作毫秒 (ms) 看待就可以，每加一次就相當於過了 1 毫秒 (ms)。

假設現在某一個 `time = _current_interrupt` 呼叫 `Sleep(x)` 後，將 `(Thread address, _current_interrupt + x)` 丟入 List，則期望在 `_current_interrupt + x` 的時候甦醒。因此，每當 _current_interrupt++ 就去檢查 List 中，誰的預期時間小於 _current_interrupt，就將其從 List 中清除。

> 這裡先不考慮 _current_interrupt Overflow 的問題，根據電腦效率，可能在 5 ~ 10 秒內就發生一次，此時會造成所有 Thread 沉眠很久。若察覺 Sleep 太久，則是發生 Overflow。

* 當有程序呼叫 `Sleep()` 時，會呼叫 `WaitUntil()`，然後將其丟入 `Bedroom` 安眠。
* 然後在 `CallBlack()` 被呼叫時，來去 `Bedroom` 檢查誰該醒來了。

{% codeblock lang:cpp /code/threads/alarm.h %}
#include "copyright.h"
#include "utility.h"
#include "callback.h"
#include "timer.h"
#include <list>
#include "thread.h"

class Bedroom {
    public:
        Bedroom():_current_interrupt(0) {};
        void PutToBed(Thread *t, int x);
	bool MorningCall();
	bool IsEmpty();
    private:
        class Bed {
            public:
                Bed(Thread* t, int x):
                    sleeper(t), when(x) {};
                Thread* sleeper;
                int when;
        };
	
	int _current_interrupt;
	std::list<Bed> _beds;
};

// The following class defines a software alarm clock. 
class Alarm : public CallBackObj {
  public:
    Alarm(bool doRandomYield);	// Initialize the timer, and callback 
				// to "toCall" every time slice.
    ~Alarm() { delete timer; }
    
    void WaitUntil(int x);	// suspend execution until time > now + x

  private:
    Timer *timer;		// the hardware timer device
    Bedroom _bedroom;
    void CallBack();		// called when the hardware
				// timer generates an interrupt
};
{% endcodeblock %}

確定有哪些 method 就可以開始實作了。

{% codeblock lang:cpp /code/threads/alarm.cc %}
void Alarm::CallBack() {
    Interrupt *interrupt = kernel->interrupt;
    MachineStatus status = interrupt->getStatus();
    bool woken = _bedroom.MorningCall();
    
    if (status == IdleMode && !woken && _bedroom.IsEmpty()) {// is it time to quit?
        if (!interrupt->AnyFutureInterrupts()) {
	    timer->Disable();	// turn off the timer
	}
    } else {			// there's someone to preempt
	interrupt->YieldOnReturn();
    }
}

void Alarm::WaitUntil(int x) {
    IntStatus oldLevel = kernel->interrupt->SetLevel(IntOff);
    Thread* t = kernel->currentThread;
    cout << "Alarm::WaitUntil go sleep" << endl;
    _bedroom.PutToBed(t, x);
    kernel->interrupt->SetLevel(oldLevel);
}

bool Bedroom::IsEmpty() {
    return _beds.size() == 0;
}

void Bedroom::PutToBed(Thread*t, int x) {
    ASSERT(kernel->interrupt->getLevel() == IntOff);
    _beds.push_back(Bed(t, _current_interrupt + x));
    t->Sleep(false);
}

bool Bedroom::MorningCall() {
    bool woken = false;

    _current_interrupt ++;

    for(std::list<Bed>::iterator it = _beds.begin(); 
        it != _beds.end(); ) {
        if(_current_interrupt >= it->when) {
            woken = true;
            cout << "Bedroom::MorningCall Thread woken" << endl;
            kernel->scheduler->ReadyToRun(it->sleeper);
            it = _beds.erase(it);
        } else {
            it++;
        }
    }
    return woken;
}
{% endcodeblock %}

到這裡我們就完成 `Sleep()` 製作。

在下一階段，將要加入排程的製作。

## Scheduling ##

目標完成 SJF, RR, FIFO。

### 待補 ###


其他指令
=====

* 打包轉移 // 交作業前，將檔案包出傳送，此指令不是壓縮用途
```
$ tar cvf FileName.tar DirName
```
* 複製資料夾 // 將 nachos gcc library 搬移至 `/usr/local/nachos ...`
```
$ cp -a DirName TARGET_PATH
```
* 轉移至 root 權限 // 如果指令權限不夠，需要下達此指令。
```
$ su
```

備忘
=====

* 網路上有幾個 Java 版本的 NachOS，架構稍微不同，如果發現文章說明有點怪怪的，請看一下他是用 JAVA 版本還是 C++ 版本。
* 至於怎麼將檔案從 Red Hat，這有點惱人，可以想辦法安裝其他瀏覽器，然後開 e-mail 送出，或者使用 terminal 上的 wget 安裝 ... 一堆辦法。最後我自己用 nodejs 寫一個簡單的 upload server 傳出來。

代碼下載
=====
[Github](https://github.com/morris821028/hw-nachos-4.0)
