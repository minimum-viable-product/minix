Welcome to MINIX 5
==================

MINIX 5 is an open-source operating system designed to be highly reliable, flexible, and secure.
It is loosely based on previous versions of MINIX, but it is fundamentally different in many key ways.
MINIX 1 and 2 were intended as teaching tools;
MINIX 3 adds the new goal of being usable as a serious system on embedded computers and for applications requiring high reliability.

The operating system is extremely small, with the part that runs in kernel mode under 15000 lines of executable code.
The parts that run in user mode are divided into small modules, well insulated from one another.
For example, each device driver runs as a separate user-mode process so a bug in a driver
(by far the biggest source of bugs in any operating system) cannot bring down the entire OS.
In fact, most of the time when a driver crashes it is automatically replaced without requiring any user intervention,
without requiring rebooting, and without affecting running programs.
These features, the tiny amount of kernel code, and other aspects greatly enhance system reliability.
MINIX 5 is initially targeted at the following areas:

* Applications where very high reliability is required
* Embedded systems (e.g., cameras, DVD recorders, cell phones)
* Applications where the GPL is too restrictive (MINIX 5 uses a BSD-type license)
* Education (e.g., operating systems courses at universities)
