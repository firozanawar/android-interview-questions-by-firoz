### Q: What is process in OS ? And what is diff b/w process and thread ?
A process is an instance of a program running in a computer. It is close in meaning to task , a term used in some operating systems. A process is basically a program in execution. The execution of a process must progress in a sequential fashion.
* Threads are used for small tasks, whereas processes are used for more 'heavyweight' tasks
* Threads within the same process share the same address space, whereas different processes do not.
* Threads share the address space of the process that created it; processes have their own address space.
* Threads have direct access to the data segment of its process; processes have their own copy of the data segment of the parent process.
* Threads can directly communicate with other threads of its process; processes must use interprocess communication to communicate with sibling processes.
* Threads have almost no overhead; processes have considerable overhead.
* New threads are easily created; new processes require duplication of the parent process.
* Threads can exercise considerable control over threads of the same process; processes can only exercise control over child processes.
* Changes to the main thread (cancellation, priority change, etc.) may affect the behavior of the other threads of the process; changes to the parent process do not affect child processes.

https://www.geeksforgeeks.org/difference-between-process-and-thread/

https://www.geeksforgeeks.org/introduction-of-process-management/

https://www.tutorialspoint.com/operating_system/os_processes.htm

https://www.studytonight.com/operating-system/operating-system-processes
