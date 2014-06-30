geep-kernel-training
====================

GEEP's kernel training

Linux kernel development training program was held on 21, 22, 28, 29 June and 5, 6 July.

I conducted the day-4 of this program.

Days 1 and 2: Basics of Linux Kernel.

1. Introduction to Kernel, On-line resources, Kernel Recompilation, Build system, Versioning, Top level architecture.

2. Kernel modules. Types of device drivers. Concept of System calls.

3. Character device driver and file operations.

4. Concepts of /proc, /sys file systems to understand system details. Kernel process management: task structure, thread_info, signals.

5. Interrupt architecture, bottom halves, tasklets, softirqs work queues, kthreads.

6. Kernel synchronization, spin locks, RCU locks, atomic operations scheduling_while_atomic.


Days 3 and 4:Programming in kernel space.

1. Timers

2. Memory management: kmalloc, vmalloc, kmem_cache_alloc. Memory zones, slab allocator, page allocation and management, process maps in kernel memory.

3. Kernel debugging: demonstration on a VM, oops debugging. Tracers, dynamic debug(debugfs).

4. Tools like objdump, lsof, fuser, strace, ltrace, netstat, /proc files, sysfs.

5. Kernel Debuggers: gdb, kdb, kgdb


Days 5 and 6: Embedded systems, network-storage stacks.

1. Embedded systems, Kernel Tuning.

2. Introduction to networking, block drivers, SCSI stacks.

3. Understanding process of kernel mailing list, git.

4. Patches, patch sanities like dealing with 64 bit environment, architectures, tools like smatch.

5. Tracing, profiling and other.

