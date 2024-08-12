MINIX 3 Developers Guide Table of Contents
==========================================

The Developers Guide provides information on how to hack on MINIX 5.
If you're new to MINIX 5 development, you should start here.


Newcomers/beginners
-------------------

1. Introduction
   - Cross-compiling MINIX 5
   - Compiling MINIX 5
2. Developing MINIX 5
   - Overview of MINIX 5 architecture
   - Programming in MINIX 5
   - Tracking Current
   - Test Suite
3. Contributing
   - Using Git
   - Coding Style
   - Commit Message Format
   - Ideas for volunteers to work on


Tutorials
---------

1. Live update and rerandomization
2. Device Driver Programming in MINIX 5
3. Debugging tips - Serial out, GDB
4. Adding a new Kernel Call
5. Performance measurement
6. Using Eclipse in MINIX 5 with Remote Explorer
7. Using GCOV to gather service code coverage info


Reference documentation
-----------------------

1. Micro-kernel
   - Overview of MINIX 5 micro-kernel
   - Kernel system calls API
   - Memory grants
   - Message passing
2. Drivers
   - Overview of MINIX 5 drivers
   - The Block Device protocol
   - The Data Link (inet-ethernet) protocol
   - The I2C Device Protocol
   - The RTC Protocol
3. Servers
   - Overview of MINIX 5 servers
   - VM Internals
   - VFS Internals
4. Userland
   - Overview of Minix userland
   - Guide to Porting Software
   - Minix-specific
     - Useful tools specific to MINIX 5
   - NetBSD
     - Porting NetBSD Userland
     - Step by Step porting Guide for NetBSD userland
   - pkgsrc
     - Pkgsrc Guide
     - Bootstrapping and bulk-building with Pkgsrc
     - Syncing the MINIX 5 pkgsrc Repository with Upstream
     - Pkgsrc Upstreaming
     - Pkgsrc on ARM (not yet working)
5. Machine-dependent
   - i386
     - X86 CPU Reference Manuals
   - ARM
     - Building MINIX 5 for ARM
     - Test Suite
     - Testing Minix/arm
6. Miscellaneous
   - Early Boot - technical details of kernel getting loaded and its memory layout
   - From power-on to the login prompt...
   - Magic debugging keys


MINIX 3 Old Developers Guide Table of Contents
----------------------------------------------

As discussed on [minix3](https://groups.google.com/forum/#!topic/minix3/3Pe2KYxfqHE), here is the old developers guide table of contents:

1. Programming
   - Useful tools specific to MINIX 3
   - Device Driver Programming in MINIX 3
   - I2C Device Driver Programming in MINIX 3
   - I2C /dev Interface
   - Adding support for new BeagleBone Capes
   - Using Eclipse in MINIX3 with Remote Explorer
   - POSIX and MINIX 3
   - Programming in MINIX 3
   - X86 CPU Reference Manuals
   - Performance measurement
   - Adding a new Kernel Call
   - Debugging tips - Serial out, GDB
   - Using GCOV to gather servers code coverage info
2. Rebuilding the System
   - Tracking Current
   - Rebuilding the System
   - Crosscompile MINIX
   - Building MINIX for ARM
   - Test Suite
   - Testing Minix/arm
3. API Documentation
   - The MINIX 3 API
   - The Kernel API
   - The VFS-FS protocol
   - The Data Link (inet-ethernet) protocol
   - The Block Device protocol
   - The I2C Device Protocol
   - The RTC Protocol
   - The DataStore API
   - The System Event Framework (SEF)
   - The VTreeFS library
   - VM calls
4. Internals
   - From power-on to the login prompt...
   - Early Boot - technical details of kernel getting loaded and its memory layout
   - VM Internals
   - VFS Internals
   - I2C Internals
   - EDID Reading
   - Userspace scheduling
5. Writing or Porting Software
   - Guide to Porting Software
   - Porting NetBSD Userland
   - Pkgsrc Guide
   - Bootstrapping and bulk-building with Pkgsrc
   - Syncing the Minix pkgsrc Repository with Upstream
   - Pkgsrc Upstreaming
6. Source Code
   - Using Git
   - Coding Style
   - Commit Message Format
7. TODO
   - Ideas for volunteers to work on
