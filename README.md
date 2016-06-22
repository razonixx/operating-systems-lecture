# operating-systems-lecture

Workshops and labs for ITESM operating system lecture

This is a template for a operating system lectures ITESM GDL
in order to increase the level of knowledge on the undergraduate students of computer science careers. 
This is plan to be deliverable in a period of time of 4 to 6 mounts. 
It is adjustable  in time and order; however the expectations and basic topics should keep the essence of the plan.

Agenda: 

* OS Architecture
  * Introduction 
    * What is an Operating Systems
    * Operating System Structure
    * Operating System Operations
  * Process Management
     * Processes
     * Threads
     * CPU Scheduling
     * Process Synchronization
     * Deadlocks
  * Memory 
     * Main Memory
     * Virtual Memory
  * Storage Management
     * File System Interface
     * File System Implementation
     * Mass Storage Structure
     * I/O Systems 

* Linux (Kernel Space)
  * Elements on the Kernel 
    * Processes, Task Switching and Scheduling
    * Address Spaces and Privilege Levels
    * Introduction Virtual and Physical Address Spaces
       * Page Tables
       * Allocation of Physical Memory
       * Slab Cache
  * Timing
    * Jiffies
    * Inserting delays
    * Dynamic Timers
    * Timer Implementation
    * High Resolution Timers
  * Drivers
    * Network Drivers 
    * Block Drivers
    * Character Drivers
  * IOCTLs
    * Driver entry points for IOCTLs
    * Locked and Lockless IOCTLs
    * Defining IOCTLs
  * Unified Device Model and sysfs
  * Memory management and allocation
    * Kmalloc
    * Vmalloc
    * Bootmem
  * Transfer between user and kernel space
  * Power Management
    * ACPI and APM
  * Debugging techniques
    *	Kernel Debuggers
  * Linux boot process
    * The Linux x86 boot protocol
    * How is the kernel built?
    * Loading the kernel – bzImage boot protocol
    * The start_kernel() function


Bibliography: 
* Understanding the Linux Kernel, 3rd Edition. Daniel P. Bovet and Marco Cesati. Copyright © 2005 O'Reilly Media, Inc.
* Advanced Linux Programming. Mark Mitchell, Jeffrey Oldham and Alex Samuel. New Riders Publishing, 2001
* Operating System Concepts, Abraham Silberschatz, Peter B. Galvin
* Professional Linux Kernel Architecture, Wolfgang Mauerer