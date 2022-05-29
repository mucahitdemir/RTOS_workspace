# FreeRTOS Workspace
Hello! This is my FreeRTOS workspace for you to use or improve.
**
Real-time Operating System (RTOS)** is an operating system intended to serve real time application that process data as it comes in, mostly without buffer delay.
It offers priority-based scheduling, which allows you to separate analytical processing from non-critical processing.

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


### Resources


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





