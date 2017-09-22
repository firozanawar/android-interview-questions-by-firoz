# android-interview-questions-by-firoz
Here is collection for all interview questions asked in different companies in India for an fresher to experienced android developer. 

### What is Android?

Android is an open-source, linux-based operating system that is used in mobiles, tablets, televisions and growing range of devices encompassing everything from wearable computing to in-car entertainment. It launched in 2003 and Andy Rubin is the founder of Android. Android is an open source project (led by Google but it doesn't belong to them) called AOSP (Android Open Source Project) which is equipped with rich components that allows developers to create and run apps that can perform both basic and advanced functions.

In other words, Android is a stack of software for mobile devices which includes an operating system, middleware and some key applications. The application executes within its own process and its own instance of Dalvik Virtual Machine. Many instances of Virtual Machines run efficiently by a DVM device. DVM executes Java languages byte code which later transforms into .dex format files. The 'purest' version of Android is often referred to as 'stock Android'. Google acquired Android in 2005. Java language is mainly used to write the android code even though other languages can be used. For software development, Android provides Android SDK (Software development kit). Google only charges manufacturers if they also install the Google apps portion of the OS.

*References:-*

https://www.androidpit.com/what-is-android

https://www.javatpoint.com/android-tutorial

https://www.tutorialspoint.com/android/android_overview.htm

http://heavy.com/tech/2013/06/what-is-android-os-operating-system-info-wiki/

https://recombu.com/mobile/article/what-is-android-and-what-is-an-android-phone_M12615.html#

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

### Q: What happens when activity rotated ?
Activity is recreated after each rotation by default and onCreate() method of activity called again. You can override this behaviour with *configChanges* attribute of the activity tag in AndroidManifest.

Life Cycle of orientation:-

onPause(); 

onSaveInstanceState(); 

onStop(); 

onDestroy(); 

onCreate(); 

onStart(); 

onResume();

