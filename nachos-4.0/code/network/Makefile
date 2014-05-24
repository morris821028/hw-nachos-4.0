# NOTE: this is a GNU Makefile.  You must use "gmake" rather than "make".
#
# Makefile for the network assignment
#    Defines set up assuming this assignment is done last 
#    If not, use the "bare bones"  defines below. 
#
# Copyright (c) 1992 The Regents of the University of California.
# All rights reserved.  See copyright.h for copyright notice and limitation 
# of liability and disclaimer of warranty provisions.

DEFINES = -DTHREADS -DUSER_PROGRAM -DFILESYS_NEEDED -DFILESYS -DNETWORK
INCPATH = -I../network -I../bin -I../filesys -I../userprog -I../threads -I../machine -I../lib
HFILES = $(THREAD_H) $(USERPROG_H) $(VM_H) $(FILESYS_H) $(NETWORK_H)
CFILES = $(THREAD_C) $(USERPROG_C) $(VM_C) $(FILESYS_C) $(NETWORK_C)
C_OFILES = $(THREAD_O) $(USERPROG_O) $(VM_O) $(FILESYS_O) $(NETWORK_O)

# bare bones version
# DEFINES =-DNETWORK
# INCPATH = -I../network -I../threads -I../machine -I../lib
# HFILES = $(THREAD_H) $(NETWORK_H)
# CFILES = $(THREAD_C) $(NETWORK_C)
# C_OFILES = $(THREAD_O) $(NETWORK_O)

include ../Makefile.common
include ../Makefile.dep
#-----------------------------------------------------------------
# DO NOT DELETE THIS LINE -- make depend uses it
# DEPENDENCIES MUST END AT END OF FILE
bitmap.o: ../lib/bitmap.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/bitmap.h
debug.o: ../lib/debug.cc ../lib/copyright.h ../lib/utility.h \
  ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc
hash.o: ../lib/hash.cc ../lib/copyright.h
libtest.o: ../lib/libtest.cc ../lib/copyright.h ../lib/libtest.h \
  ../lib/bitmap.h ../lib/utility.h ../lib/list.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc ../lib/hash.h \
  ../lib/hash.cc
list.o: ../lib/list.cc ../lib/copyright.h
sysdep.o: ../lib/sysdep.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc /usr/include/unistd.h \
  /usr/include/bits/posix_opt.h /usr/include/bits/environments.h \
  /usr/include/bits/confname.h /usr/include/getopt.h \
  /usr/include/sys/time.h /usr/include/sys/file.h /usr/include/fcntl.h \
  /usr/include/bits/fcntl.h /usr/include/sys/stat.h \
  /usr/include/bits/stat.h /usr/include/sys/socket.h \
  /usr/include/sys/uio.h /usr/include/bits/uio.h \
  /usr/include/bits/socket.h /usr/include/bits/sockaddr.h \
  /usr/include/asm/socket.h /usr/include/asm/sockios.h \
  /usr/include/sys/un.h /usr/include/bits/signum.h \
  /usr/include/bits/siginfo.h /usr/include/bits/sigaction.h \
  /usr/include/bits/sigcontext.h /usr/include/asm/sigcontext.h \
  /usr/include/bits/sigstack.h /usr/include/sys/ucontext.h
interrupt.o: ../machine/interrupt.cc ../lib/copyright.h \
  ../machine/interrupt.h ../lib/list.h ../lib/debug.h ../lib/utility.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc \
  ../machine/callback.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../filesys/synchdisk.h ../machine/disk.h ../threads/synch.h
stats.o: ../machine/stats.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/stats.h
timer.o: ../machine/timer.cc ../lib/copyright.h ../machine/timer.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
alarm.o: ../threads/alarm.cc ../lib/copyright.h ../threads/alarm.h \
  ../lib/utility.h ../machine/callback.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/cstring \
  /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/string.h /usr/include/xlocale.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/wordsize.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/sys/types.h /usr/include/bits/types.h \
  /usr/include/bits/typesizes.h /usr/include/time.h \
  /usr/include/sys/select.h /usr/include/bits/select.h \
  /usr/include/bits/sigset.h /usr/include/bits/time.h \
  /usr/include/sys/sysmacros.h /usr/include/bits/pthreadtypes.h \
  /usr/include/bits/sched.h /usr/include/alloca.h \
  /usr/include/c++/3.2.2/new /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/iosfwd /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/stdio.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/wchar.h /usr/include/bits/wchar.h \
  /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/signal.h \
  /usr/include/bits/initspin.h /usr/include/bits/sigthread.h \
  /usr/include/c++/3.2.2/cwchar /usr/include/c++/3.2.2/ctime \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_list.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../lib/debug.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/stats.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
kernel.o: ../threads/kernel.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../threads/main.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/thread.h ../machine/machine.h ../machine/translate.h \
  ../userprog/addrspace.h ../filesys/filesys.h ../filesys/openfile.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h ../threads/synchlist.h \
  ../threads/synchlist.cc ../lib/libtest.h ../machine/elevatortest.h
main.o: ../threads/main.cc ../lib/copyright.h ../threads/main.h \
  ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
scheduler.o: ../threads/scheduler.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
synch.o: ../threads/synch.cc ../lib/copyright.h ../threads/synch.h \
  ../threads/thread.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../lib/list.h ../lib/debug.h ../lib/list.cc \
  ../threads/main.h ../network/netkernel.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h
synchlist.o: ../threads/synchlist.cc ../lib/copyright.h \
  ../threads/synchlist.h ../lib/list.h ../lib/debug.h ../lib/utility.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc \
  ../threads/synch.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/scheduler.h \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synchlist.cc
thread.o: ../threads/thread.cc ../lib/copyright.h ../threads/thread.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/switch.h ../threads/synch.h \
  ../lib/list.h ../lib/debug.h ../lib/list.cc ../threads/main.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/scheduler.h ../machine/interrupt.h ../machine/callback.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../filesys/synchdisk.h ../machine/disk.h
elevatortest.o: ../machine/elevatortest.cc ../lib/copyright.h \
  ../machine/elevatortest.h ../machine/elevator.h ../lib/utility.h \
  ../machine/callback.h ../lib/list.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc \
  ../threads/synch.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/scheduler.h \
  ../machine/interrupt.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h
elevator.o: ../machine/elevator.cc ../lib/copyright.h \
  ../machine/elevator.h ../lib/utility.h ../machine/callback.h \
  ../lib/list.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc \
  ../threads/kernel.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../threads/main.h ../network/netkernel.h ../userprog/userkernel.h \
  ../filesys/synchdisk.h ../machine/disk.h ../threads/synch.h
addrspace.o: ../userprog/addrspace.cc ../lib/copyright.h \
  ../threads/main.h ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h ../bin/noff.h
exception.o: ../userprog/exception.cc ../lib/copyright.h \
  ../threads/main.h ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h ../userprog/syscall.h
synchconsole.o: ../userprog/synchconsole.cc ../lib/copyright.h \
  ../userprog/synchconsole.h ../lib/utility.h ../machine/callback.h \
  ../machine/console.h ../threads/synch.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../lib/list.h ../lib/debug.h ../lib/list.cc \
  ../threads/main.h ../network/netkernel.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../filesys/synchdisk.h ../machine/disk.h
userkernel.o: ../userprog/userkernel.cc ../lib/copyright.h \
  ../userprog/synchconsole.h ../lib/utility.h ../machine/callback.h \
  ../machine/console.h ../threads/synch.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../lib/list.h ../lib/debug.h ../lib/list.cc \
  ../threads/main.h ../network/netkernel.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../filesys/synchdisk.h ../machine/disk.h
console.o: ../machine/console.cc ../lib/copyright.h ../machine/console.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
machine.o: ../machine/machine.cc ../lib/copyright.h ../machine/machine.h \
  ../lib/utility.h ../machine/translate.h ../threads/main.h \
  ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../userprog/addrspace.h ../filesys/filesys.h ../filesys/openfile.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
mipssim.o: ../machine/mipssim.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../machine/mipssim.h ../threads/main.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/thread.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/scheduler.h ../lib/list.h \
  ../lib/list.cc ../machine/interrupt.h ../machine/callback.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h \
  ../filesys/synchdisk.h ../machine/disk.h ../threads/synch.h
translate.o: ../machine/translate.cc ../lib/copyright.h ../threads/main.h \
  ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
synchdisk.o: ../filesys/synchdisk.cc ../lib/copyright.h \
  ../filesys/synchdisk.h ../machine/disk.h ../lib/utility.h \
  ../machine/callback.h ../threads/synch.h ../threads/thread.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../lib/list.h ../lib/debug.h ../lib/list.cc \
  ../threads/main.h ../network/netkernel.h ../userprog/userkernel.h \
  ../threads/kernel.h ../threads/scheduler.h ../machine/interrupt.h \
  ../machine/stats.h ../threads/alarm.h ../machine/timer.h \
  /usr/include/c++/3.2.2/list /usr/include/c++/3.2.2/bits/stl_list.h
disk.o: ../machine/disk.cc ../lib/copyright.h ../machine/disk.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../threads/synch.h
directory.o: ../filesys/directory.cc ../lib/copyright.h ../lib/utility.h \
  ../filesys/filehdr.h ../machine/disk.h ../machine/callback.h \
  ../lib/bitmap.h ../filesys/directory.h ../filesys/openfile.h \
  /usr/include/stdio.h /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/bits/types.h /usr/include/bits/wordsize.h \
  /usr/include/bits/typesizes.h /usr/include/libio.h \
  /usr/include/_G_config.h /usr/include/wchar.h /usr/include/bits/wchar.h \
  /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/string.h /usr/include/xlocale.h
filesys.o: ../filesys/filesys.cc ../lib/copyright.h ../machine/disk.h \
  ../lib/utility.h ../machine/callback.h ../lib/bitmap.h \
  ../filesys/directory.h ../filesys/openfile.h ../filesys/filehdr.h \
  ../filesys/filesys.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../filesys/pbitmap.h
openfile.o: ../filesys/openfile.cc ../lib/copyright.h \
  ../filesys/filehdr.h ../machine/disk.h ../lib/utility.h \
  ../machine/callback.h ../lib/bitmap.h ../filesys/openfile.h \
  ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../threads/main.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/thread.h ../machine/machine.h ../machine/translate.h \
  ../userprog/addrspace.h ../filesys/filesys.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../threads/synch.h
filehdr.o: ../filesys/filehdr.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../threads/main.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../threads/thread.h ../machine/machine.h ../machine/translate.h \
  ../userprog/addrspace.h ../filesys/filesys.h ../filesys/openfile.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h ../filesys/filehdr.h \
  ../lib/bitmap.h
fstest.o: ../filesys/fstest.cc ../lib/copyright.h ../lib/debug.h \
  ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../threads/scheduler.h ../lib/list.h ../lib/list.cc \
  ../machine/interrupt.h ../machine/callback.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
pbitmap.o: ../filesys/pbitmap.cc ../lib/copyright.h ../filesys/pbitmap.h \
  ../lib/bitmap.h ../lib/utility.h ../filesys/openfile.h
netkernel.o: ../network/netkernel.cc ../lib/copyright.h \
  ../network/netkernel.h ../userprog/userkernel.h ../threads/kernel.h \
  ../lib/debug.h ../lib/utility.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h \
  ../machine/callback.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h ../threads/main.h \
  ../network/post.h ../machine/network.h ../threads/synchlist.h \
  ../threads/synchlist.cc
post.o: ../network/post.cc ../lib/copyright.h ../network/post.h \
  ../lib/utility.h ../machine/callback.h ../machine/network.h \
  ../threads/synchlist.h ../lib/list.h ../lib/debug.h ../lib/sysdep.h \
  /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../lib/list.cc \
  ../threads/synch.h ../threads/thread.h ../machine/machine.h \
  ../machine/translate.h ../userprog/addrspace.h ../filesys/filesys.h \
  ../filesys/openfile.h ../threads/main.h ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/scheduler.h \
  ../machine/interrupt.h ../machine/stats.h ../threads/alarm.h \
  ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synchlist.cc
network.o: ../machine/network.cc ../lib/copyright.h ../machine/network.h \
  ../lib/utility.h ../machine/callback.h ../threads/main.h ../lib/debug.h \
  ../lib/sysdep.h /usr/include/c++/3.2.2/backward/iostream.h \
  /usr/include/c++/3.2.2/backward/backward_warning.h \
  /usr/include/c++/3.2.2/iostream \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++config.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/os_defines.h \
  /usr/include/features.h /usr/include/sys/cdefs.h \
  /usr/include/gnu/stubs.h /usr/include/c++/3.2.2/ostream \
  /usr/include/c++/3.2.2/ios /usr/include/c++/3.2.2/iosfwd \
  /usr/include/c++/3.2.2/bits/stringfwd.h \
  /usr/include/c++/3.2.2/bits/fpos.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++io.h \
  /usr/include/c++/3.2.2/cstdio /usr/include/c++/3.2.2/cstddef \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stddef.h \
  /usr/include/stdio.h /usr/include/bits/types.h \
  /usr/include/bits/wordsize.h /usr/include/bits/typesizes.h \
  /usr/include/libio.h /usr/include/_G_config.h /usr/include/wchar.h \
  /usr/include/bits/wchar.h /usr/include/gconv.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/stdarg.h \
  /usr/include/bits/stdio_lim.h /usr/include/bits/sys_errlist.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/gthr-default.h \
  /usr/include/pthread.h /usr/include/sched.h /usr/include/time.h \
  /usr/include/bits/sched.h /usr/include/bits/time.h \
  /usr/include/xlocale.h /usr/include/signal.h /usr/include/bits/sigset.h \
  /usr/include/bits/pthreadtypes.h /usr/include/bits/initspin.h \
  /usr/include/bits/sigthread.h /usr/include/c++/3.2.2/cwchar \
  /usr/include/c++/3.2.2/ctime /usr/include/c++/3.2.2/bits/functexcept.h \
  /usr/include/c++/3.2.2/exception_defines.h \
  /usr/include/c++/3.2.2/exception \
  /usr/include/c++/3.2.2/bits/char_traits.h \
  /usr/include/c++/3.2.2/cstring /usr/include/string.h \
  /usr/include/c++/3.2.2/bits/localefwd.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/c++locale.h \
  /usr/include/c++/3.2.2/clocale /usr/include/locale.h \
  /usr/include/bits/locale.h /usr/include/langinfo.h \
  /usr/include/nl_types.h /usr/include/iconv.h /usr/include/libintl.h \
  /usr/include/c++/3.2.2/climits \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/limits.h \
  /usr/lib/gcc-lib/i386-redhat-linux/3.2.2/include/syslimits.h \
  /usr/include/limits.h /usr/include/bits/posix1_lim.h \
  /usr/include/bits/local_lim.h /usr/include/linux/limits.h \
  /usr/include/bits/posix2_lim.h /usr/include/bits/xopen_lim.h \
  /usr/include/c++/3.2.2/cctype /usr/include/ctype.h \
  /usr/include/endian.h /usr/include/bits/endian.h \
  /usr/include/c++/3.2.2/string /usr/include/c++/3.2.2/memory \
  /usr/include/c++/3.2.2/bits/stl_algobase.h \
  /usr/include/c++/3.2.2/cstdlib /usr/include/stdlib.h \
  /usr/include/bits/waitflags.h /usr/include/bits/waitstatus.h \
  /usr/include/sys/types.h /usr/include/sys/select.h \
  /usr/include/bits/select.h /usr/include/sys/sysmacros.h \
  /usr/include/alloca.h /usr/include/c++/3.2.2/new \
  /usr/include/c++/3.2.2/bits/stl_pair.h \
  /usr/include/c++/3.2.2/bits/type_traits.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_types.h \
  /usr/include/c++/3.2.2/bits/stl_iterator_base_funcs.h \
  /usr/include/c++/3.2.2/bits/concept_check.h \
  /usr/include/c++/3.2.2/bits/stl_iterator.h \
  /usr/include/c++/3.2.2/bits/stl_alloc.h /usr/include/c++/3.2.2/cassert \
  /usr/include/assert.h /usr/include/c++/3.2.2/bits/stl_threads.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/atomicity.h \
  /usr/include/c++/3.2.2/bits/stl_construct.h \
  /usr/include/c++/3.2.2/bits/stl_uninitialized.h \
  /usr/include/c++/3.2.2/bits/stl_raw_storage_iter.h \
  /usr/include/c++/3.2.2/bits/stl_function.h \
  /usr/include/c++/3.2.2/bits/basic_string.h \
  /usr/include/c++/3.2.2/algorithm /usr/include/c++/3.2.2/bits/stl_algo.h \
  /usr/include/c++/3.2.2/bits/stl_heap.h \
  /usr/include/c++/3.2.2/bits/stl_tempbuf.h \
  /usr/include/c++/3.2.2/bits/basic_string.tcc \
  /usr/include/c++/3.2.2/bits/ios_base.h /usr/include/c++/3.2.2/streambuf \
  /usr/include/c++/3.2.2/bits/streambuf.tcc \
  /usr/include/c++/3.2.2/bits/basic_ios.h \
  /usr/include/c++/3.2.2/bits/streambuf_iterator.h \
  /usr/include/c++/3.2.2/bits/locale_facets.h \
  /usr/include/c++/3.2.2/cwctype /usr/include/wctype.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_base.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/ctype_inline.h \
  /usr/include/c++/3.2.2/bits/codecvt.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/codecvt_specializations.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/time_members.h \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/messages_members.h \
  /usr/include/c++/3.2.2/bits/basic_ios.tcc \
  /usr/include/c++/3.2.2/bits/ostream.tcc /usr/include/c++/3.2.2/locale \
  /usr/include/c++/3.2.2/bits/locale_facets.tcc \
  /usr/include/c++/3.2.2/cerrno /usr/include/errno.h \
  /usr/include/bits/errno.h /usr/include/linux/errno.h \
  /usr/include/asm/errno.h /usr/include/c++/3.2.2/cmath \
  /usr/include/math.h /usr/include/bits/huge_val.h \
  /usr/include/bits/nan.h /usr/include/bits/mathdef.h \
  /usr/include/bits/mathcalls.h /usr/include/c++/3.2.2/bits/cmath.tcc \
  /usr/include/c++/3.2.2/limits \
  /usr/include/c++/3.2.2/i386-redhat-linux/bits/cpu_limits.h \
  /usr/include/c++/3.2.2/typeinfo /usr/include/c++/3.2.2/istream \
  /usr/include/c++/3.2.2/bits/istream.tcc ../network/netkernel.h \
  ../userprog/userkernel.h ../threads/kernel.h ../threads/thread.h \
  ../machine/machine.h ../machine/translate.h ../userprog/addrspace.h \
  ../filesys/filesys.h ../filesys/openfile.h ../threads/scheduler.h \
  ../lib/list.h ../lib/list.cc ../machine/interrupt.h ../machine/stats.h \
  ../threads/alarm.h ../machine/timer.h /usr/include/c++/3.2.2/list \
  /usr/include/c++/3.2.2/bits/stl_list.h ../filesys/synchdisk.h \
  ../machine/disk.h ../threads/synch.h
# DEPENDENCIES MUST END AT END OF FILE
# IF YOU PUT STUFF HERE IT WILL GO AWAY
# see make depend above
