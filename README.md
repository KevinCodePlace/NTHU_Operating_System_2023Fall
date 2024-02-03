# NTHU_Operating_System_2023Fall

## 1. MP1: System Call in NachOS
- Goal: To understand the Linux environment, how system calls are implemented by the operating system, and the difference between user mode and kernel mode.
- Tasks:
  - Trace and analyze specific system calls (SC_Halt, SC_Create, SC_PrintInt) to understand their implementation, the basic operations and data structures in a file system, and how NachOS handles asynchronous I/O.
  - Implement four I/O system calls (Open, Write, Read, Close) in NachOS, ensuring proper handling of file operations, maintaining the OpenFileTable, and adhering to constraints like not using standard IO functions or modifying certain directories.
  - Write a detailed report covering the implementation, observed system call behaviors, encountered challenges, and any feedback.

## MP2: Multi-Programming
- Goal: To grasp memory management and the implementation of the page table mechanism in NachOS.
- Tasks:
  - Trace and explain the code path starting from the execution of a user program to its loading into the memory, detailing the functions involved in thread and address space management.
  - Implement page table modifications to support multiprogramming, handle memory exceptions, and ensure proper allocation and deallocation of physical memory.
  - Prepare a report explaining the implementation details, how NachOS handles memory management for threads, and addressing specific questions related to memory allocation, page tables, and process management.

## MP3: CPU Scheduling
- Goal: To replace the default round-robin CPU scheduling algorithm in NachOS with a multilevel feedback queue and understand the process lifecycle management and context switch mechanism.
- Tasks:
  - Trace and describe the code paths for different process states (New→Ready, Running→Ready, etc.) and understand the lifecycle of a process in NachOS.
  - Implement a multilevel feedback queue scheduler with an aging mechanism, ensuring proper scheduling, preemption, priority updating, and handling of different queue levels (L1, L2, L3).
  - Document the implementation, provide debugging information, and adhere to specific rules regarding code modification and timer alarm handling.

## MP4: File System
- Goal: To enhance NachOS native file system to support larger file sizes and subdirectory structures.
- Tasks:
  - Understand and document the current file system implementation, including management of free block space, directory data structures, and inode information.
  - Modify the file system code to support file I/O system calls, larger file sizes (up to 32KB), and subdirectory structures.
  - Optionally, tackle bonus assignments to further enhance file size support, implement multi-level header sizes, and support recursive operations on directories.
  - Verify the implementation with specific commands and ensure proper formatting of output.

## Pthreads Programming Assignment: Producer-Consumer Problem
- Goal: To understand multi-thread programming with the pthread library in a Linux environment.
- Tasks:
  - Implement a producer-consumer problem using threads, ensuring thread safety and proper synchronization.
  - Create and manage multiple threads (Reader, Producer, Consumer, ConsumerController, Writer) to handle the processing of items, with dynamic scaling of consumer threads based on the workload.
  - Document the code structure, implementation details, and compile, run, and test instructions.
Provide debugging and verification scripts to test and validate the implementation.


| Item | Grade | Item | Grade | Item | Grade |  Item | Grade |  Item | Grade | 
| ---- | ----- | ---- | ----- | ---- | ----- | ---- | ----- | ---- | ----- | 
| MP1 | 92  |  MP2 | 88  | MP3 | 93.25  | MP4 | 90  | Pthreads | 100  |
