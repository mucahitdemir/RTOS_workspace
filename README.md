# FreeRTOS Workspace
Hello! This is my FreeRTOS workspace for you to use or improve.

**What is a Real-Time Operating System (RTOS)?**

Real-time operating system (RTOS) is an operating system intended to serve real time application that process data as it comes in, mostly without buffer delay. The full form of RTOS is Real time operating system.

In a RTOS, Processing time requirement are calculated in tenths of seconds increments of time. It is time-bound system that can be defined as fixed time constraints. In this type of system, processing must be done inside the specified constraints. Otherwise, the system will fail.

RTOS is intended to serve real time application that process data as it comes in, mostly without buffer delay.
It offers priority-based scheduling, which allows you to separate analytical processing from non-critical processing.

Components of RTOS

![image](https://user-images.githubusercontent.com/43001724/170870949-2064a6ca-ee6b-4592-8360-1c4a0339f5cc.png)

Here, are important Component of RTOS
**
The Scheduler**: This component of RTOS tells that in which order, the tasks can be executed which is generally based on the priority.

**Symmetric Multiprocessing (SMP)**: It is a number of multiple different tasks that can be handled by the RTOS so that parallel processing can be done.

**Function Library**: It is an important element of RTOS that acts as an interface that helps you to connect kernel and application code. This application allows you to send the requests to the Kernel using a function library so that the application can give the desired results.

**Memory Management**: this element is needed in the system to allocate memory to every program, which is the most important element of the RTOS.

**Fast dispatch latency**: It is an interval between the termination of the task that can be identified by the OS and the actual time taken by the thread, which is in the ready queue, that has started processing.

User-defined data objects and classes: RTOS system makes use of programming languages like C or C++, which should be organized according to their operation.

**Important components of RTOS system are**: 
1)The Scheduler
2) Symmetric Multiprocessing
3) Function Library
4) Memory Management
5) Fast dispatch latency
6) User-defined data objects and classes

Three types of RTOS:
1) Hard time 
2) Soft time
3) Firm time

RTOS system occupy very less memory and consume fewer resources

Performance is the most important factor required to be considered while selecting for a RTOS.

General-Purpose Operating System (GPOS) is used for desktop PC and laptop while Real-Time Operating System (RTOS) only applied to the embedded application.
Real-time systems are used in Airlines reservation system, Air traffic control system,etc.

The biggest drawback of RTOS is that the system only concentrates on a few tasks.
**Source**: guru99


### Resources
Link: https://drive.google.com/file/d/17fOjfd6AAOkZf2FAZU5G6fVhqYxifY-q/view?usp=sharing
Link: 


## Configuration
The configuration of the kernel is set in FreeRTOSConfig.h
configTOTAL_HEAP_SIZE: This must be enough space to allocate all tasks including the idle task. If the kernel does’t start it could be that the heap is too small.

| Examples      | Description           |
| ------------- | ----------------------|
| Example -1    | Creating tasks        |   
| Example -2    | LED Tasks             |
| Example -3    | LED Block Task        |
| Example -4    | LED Periodic Task     |
| Example -5    | LED Task Notifty      |
| Example -6    | Binary Semaphore      |
| Example -7    | CountingSemaphore     |
| Example -8    | Queue Timers Task     |
| Example -9    | Mutual Exclusion      |
| Example -10   | Queue Management      |
| Example -11   | Logging into SD-Card  |
| Example -12   | Software Timers       |
| Example -13   | Ethernet UDP Server   |
| Example -14   | Ethernet UDP Client   |


Note: There is a problem about 001Task and 002LEDTasks, exist a github submodule, I will fix ASAP





