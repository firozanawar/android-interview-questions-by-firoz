# android-java-interview-questions-by-firoz
Here is collection for all interview questions asked in different companies in India for an fresher to experienced android developer. 

### Q: What is Android ?

Android is an open-source, linux-based operating system that is used in mobiles, tablets, televisions and growing range of devices encompassing everything from wearable computing to in-car entertainment. It launched in 2003 and Andy Rubin is the founder of Android. Android is an open source project (led by Google but it doesn't belong to them) called AOSP (Android Open Source Project) which is equipped with rich components that allows developers to create and run apps that can perform both basic and advanced functions.

In technical words, Android is a stack of software for mobile devices which includes an operating system, middleware and some key applications (Diagram is below). The application executes within its own process and its own instance of Dalvik Virtual Machine. Many instances of Virtual Machines run efficiently by a DVM device. DVM executes Java languages byte code which later transforms into .dex format files. The 'purest' version of Android is often referred to as 'stock Android'. Google acquired Android in 2005. Java and Kotlin language is mainly used to write the android code, even though other languages can be used to write part of App like C/C++. For software development, Android provides Android SDK (Software development kit).

![Alt text](https://www.howtogeek.com/wp-content/uploads/2014/05/android-architecture.png.pagespeed.ce.aKAjPj1k0Q.png "Android architecture")

*References:-*

https://www.androidpit.com/what-is-android

https://www.javatpoint.com/android-tutorial

https://www.tutorialspoint.com/android/android_overview.htm

http://heavy.com/tech/2013/06/what-is-android-os-operating-system-info-wiki/

https://recombu.com/mobile/article/what-is-android-and-what-is-an-android-phone_M12615.html#

### Q: What do you mean by Open Source Software?
Open-source software (OSS) is a type of computer software in which source code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the software to anyone and for any purpose. Open source software is usually developed as a public collaboration and made freely available.

### Q: Android is Based on Linux, But What Does That Mean?
https://www.howtogeek.com/189036/android-is-based-on-linux-but-what-does-that-mean/

https://www.unixmen.com/why-is-android-built-on-linux-kernel/

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

### Q: What happens when activity rotated ?
Activity is recreated after each rotation by default and onCreate() method of activity called again. You can override this behaviour with *configChanges* attribute of the activity tag in AndroidManifest. Calling setRetainInstance(true) on a Fragment is similar to setting the android:configChanges flag on an Activity. It signals to Android that you want to continue using the same instance of the current Fragment, so all of your member variables will remain untouched.

Life Cycle of orientation:-

onPause(); 

onSaveInstanceState(); 

onStop(); 

onDestroy(); 

onCreate(); 

onStart(); 

onResume();

https://medium.com/google-developers/activity-revival-and-the-case-of-the-rotating-device-167e34f9a30d

### Q: Explain about GCM implementation?

![Alt text](https://androidexample.com/upload/content/Push_notification_Workflow.png "Optional title")

### Q: Object class and its methods ?
The Object class is the parent class of all the classes in java by default.
* The Object class is beneficial if you want to refer any object whose type you don't know. Notice that parent class reference variable can refer the child class object, know as upcasting.
* Object class is present in java.lang package.
* Object class methods are available to all Java classes.

| Method | Description |
| --- | --- |
| public final Class getClass() | returns the Class class object of this object. The Class class can further be used to get the metadata of this class. |
| public int hashCode() | returns the hashcode number for this object. |
| public boolean equals(Object obj) | compares the given object to this object. |
| protected Object clone() throws CloneNotSupportedException | creates and returns the exact copy (clone) of this object. |
| public String toString() | returns the string representation of this object.|
| public final void notify() | wakes up single thread, waiting on this object's monitor.|
| public final void notifyAll() | wakes up all the threads, waiting on this object's monitor.|
| public final void wait(long timeout)throws InterruptedException | causes the current thread to wait for the specified milliseconds, until another thread notifies (invokes notify() or notifyAll() method). |
| public final void wait(long timeout,int nanos)throws InterruptedException | causes the current thread to wait for the specified milliseconds and nanoseconds, until another thread notifies (invokes notify() or notifyAll() method). |
| public final void wait()throws InterruptedException | causes the current thread to wait, until another thread notifies (invokes notify() or notifyAll() method). |
| protected void finalize()throws Throwable. | is invoked by the garbage collector before object is being garbage collected.

*Note :* Whenever we try to print any Object reference, then internally toString() method is called.
 
**hashCode() :** For every object, JVM generates a unique number which is hashcode. It returns distinct integers for distinct objects. A common misconception about this method is that hashCode() method returns the address of object, which is not correct. It convert the internal address of object to an integer by using an algorithm. The hashCode() method is native because in Java it is impossible to find address of an object, so it uses native languages like C/C++ to find address of the object.

**Use of hashCode() method :** Returns a hash value that is used to search object in a collection. JVM(Java Virtual Machine) uses hashcode method while saving objects into hashing related data structures like HashSet, HashMap, Hashtable etc. The main advantage of saving objects based on hash code is that searching becomes easy.

*Note :* Override of hashCode() method needs to be done such that for every object we generate a unique number.
 
**equals(Object obj) :** Compares the given object to “this” object (the object on which the method is called). It gives a generic way to compare objects for equality. It is recommended to override equals(Object obj) method to get our own equality condition on Objects.
 
**getClass() :** Returns the class object of “this” object and used to get actual runtime class of the object. It can also be used to get metadata of this class. The returned Class object is the object that is locked by static synchronized methods of the represented class. As it is final so we don’t override it.
 
**finalize() method :** This method is called just before an object is garbage collected. It is called by the Garbage Collector on an object when garbage collector determines that there are no more references to the object. We should override finalize() method to dispose system resources, perform clean-up activities and minimize memory leaks.
Note : finalize method is called just once on an object even though that object is eligible for garbage collection multiple times.
 
**clone() :** It returns a new object that is exactly the same as this object.

https://www.geeksforgeeks.org/object-class-in-java/

https://www.javatpoint.com/object-class

### Q: How to handle concurrent request in android ?
https://medium.com/@ali.muzaffar/using-concurrency-and-speed-and-performance-on-android-d00ab4c5c8e3

https://medium.com/@ali.muzaffar/handlerthreads-and-why-you-should-be-using-them-in-your-android-apps-dc8bf1540341

https://android.jlelse.eu/8-ways-to-do-asynchronous-processing-in-android-and-counting-f634dc6fae4e

https://www.lynda.com/Android-tutorials/Concurrent-programming-Android/560057/580097-4.html

### Q: Difference between gravity and layout_gravity ?
![Alt text](https://i.stack.imgur.com/nymDt.png "Optional title")

https://en.proft.me/2017/05/22/understanding-difference-gravity-layout-gravity/

### Q: Difference between add and replace in fragment ? and What do you mean by addToBackStack() in fragment?
#### fragmentTransaction.replace(int containerViewId, Fragment fragment, String tag)

Description - Replace an existing fragment that was added to a container. This is essentially the same as calling remove(Fragment) for all currently added fragments that were added with the same containerViewId and then add(int, Fragment, String) with the same arguments given here.

#### fragmentTransaction.add(int containerViewId, Fragment fragment, String tag)

Description - Add a fragment to the activity state. This fragment may optionally also have its view (if Fragment.onCreateView returns non-null) into a container view of the activity.

One more important difference between add and replace is: replace removes the existing fragment and adds a new fragment. This means when you press back button the fragment that got replaced will be created with its onCreateView being invoked. Whereas add retains the existing fragments and adds a new fragment that means existing fragment will be active and they wont be in 'paused' state hence when a back button is pressed onCreateView is not called for the existing fragment(the fragment which was there before new fragment was added). In terms of fragment's life cycle events onPause, onResume, onCreateView and other life cycle events will be invoked in case of replace but they wont be invoked in case of add.

When we press back button after in case of add()... onCreateView is never called, but in case of replace(), when we press back button ... oncreateView is called every time.

**Case1:-  Add a fragment to an activity without backstack, and press back button.**

MainActivity onCreate 

FirstFragment onAttach

FirstFragment onCreate

FirstFragment onCreateView

FirstFragment onActivityCreated

MainActivity onStart

FirstFragment onStart

MainActivity onResume

FirstFragment onResume

—-> Back button pressed, activity destroyed

FirstFragment onPause

MainActivity onPause

FirstFragment onStop

MainActivity onStop

FirstFragment onDestroyView

FirstFragment onDestroy

FirstFragment onDetach

MainActivity onDestroy



**Case2:-  Add a fragment to an activity with backstack, and press back button.**

MainActivity onCreate 

FirstFragment onAttach

FirstFragment onCreate

FirstFragment onCreateView

FirstFragment onActivityCreated

MainActivity onStart

FirstFragment onStart

MainActivity onResume

FirstFragment onResume

—-> Back button pressed, fragment removed, activity visible

FirstFragment onPause

FirstFragment onStop

FirstFragment onDestroyView

FirstFragment onDestroy

FirstFragment onDetach

—-> Back button pressed again, activity dismissed

MainActivity onPause

MainActivity onStop

MainActivity onDestroy



**Case3:- Add a fragment on top of another ADDED fragment with backstack,**

MainActivity onCreate 

FirstFragment onAttach

FirstFragment onCreate

FirstFragment onCreateView

FirstFragment onActivityCreated

MainActivity onStart

FirstFragment onStart

MainActivity onResume

FirstFragment onResume

—> Add the another fragment

SecondFragment onAttach

SecondFragment onCreate

SecondFragment onCreateView

SecondFragment onActivityCreated

SecondFragment onStart

SecondFragment onResume

—> Now back press, second fragment popped, first showing now.

SecondFragment onPause

SecondFragment onStop

SecondFragment onDestroyView

SecondFragment onDestroy

SecondFragment onDetach

—> back press again, activity dismissed

FirstFragment onPause

MainActivity onPause

FirstFragment onStop

MainActivity onStop

FirstFragment onDestroyView

FirstFragment onDestroy

FirstFragment onDetach

MainActivity onDestroy



**Case4:- Replaced a fragment on top of another ADDED fragment with backstack,**

MainActivity onCreate 73

FirstFragment onAttach

FirstFragment onCreate

FirstFragment onCreateView

FirstFragment onActivityCreated

MainActivity onStart

FirstFragment onStart

MainActivity onResume

FirstFragment onResume

—-> Replace second fragment with backstack

SecondFragment onAttach

SecondFragment onCreate

SecondFragment onCreateView

SecondFragment onActivityCreated

SecondFragment onStart

SecondFragment onResume

FirstFragment onPause

FirstFragment onStop

FirstFragment onDestroyView

—-> Back press, pop second fragment and show first one.

FirstFragment onCreateView

FirstFragment onActivityCreated

FirstFragment onStart

FirstFragment onResume

SecondFragment onPause

SecondFragment onStop

SecondFragment onDestroyView

SecondFragment onDestroy

SecondFragment onDetach

—-> back press again activity dismissed.

FirstFragment onPause

MainActivity onPause

FirstFragment onStop

MainActivity onStop

FirstFragment onDestroyView

FirstFragment onDestroy

FirstFragment onDetach

MainActivity onDestroy

https://developer.android.com/guide/components/fragments

https://stackoverflow.com/questions/18634207/difference-between-add-replace-and-addtobackstack

### Q: Difference between View and ViewGroup ?
https://stackoverflow.com/questions/27352476/difference-between-view-and-viewgroup-in-android

### Q: Difference between StringBuffer and StringBuilder ?
https://www.journaldev.com/538/string-vs-stringbuffer-vs-stringbuilder

StringBuffer was the only choice for String manipulation till Java 1.4 but it has one disadvantage that all of its public methods are synchronized. StringBuffer provides Thread safety but on a performance cost.

In most of the scenarios, we don’t use String in a multithreaded environment, so Java 1.5 introduced a new class StringBuilder that is similar to StringBuffer except thread safety and synchronization.

So if you are in a single threaded environment or don’t care about thread safety, you should use StringBuilder else use StringBuffer.

![Alt text](https://2.bp.blogspot.com/-QHIf55P3o2I/W_FZaQ8YuXI/AAAAAAAAMmY/WXb342XKhCQd2iVotRwJ77-XgXSlGcV3gCLcBGAs/s640/String%2Band%2BStringbuffer%2Band%2BStringBuilder.png "Optional title")

### Q: Difference between SOAP and REST ?
https://www.guru99.com/comparison-between-web-services.html

https://dzone.com/articles/difference-between-rest-and-soap-api
### Q: How to pass data between fragments 1. when fragment are in same activity and visible at same time 2. When fragment transition happens from one fragment to another fragments?
https://www.journaldev.com/14207/android-passing-data-between-fragments

https://inducesmile.com/android/android-fragment-how-to-pass-data-between-fragments-in-an-activity/

https://www.zoftino.com/passing-data-between-android-fragments-using-viewmodel

http://manishkpr.webheavens.com/android-passing-data-between-fragments/

https://www.tutorialspoint.com/how-to-pass-data-from-one-fragment-to-another-fragment-in-android

### Q: How to pass data between activities ?
https://www.dev2qa.com/passing-data-between-activities-android-tutorial/

https://medium.com/@peterekeneeze/passing-data-between-activities-2d0ef122f19d

https://www.survivingwithandroid.com/passing-data-between-activities-2/

### Q: Can we pass objects from one to another activity? If yes then how ?
https://stackoverflow.com/questions/2736389/how-to-pass-an-object-from-one-activity-to-another-on-android

https://coderwall.com/p/vfbing/passing-objects-between-activities-in-android

https://www.techjini.com/blog/passing-objects-via-intent-in-android/

https://en.proft.me/2017/02/28/pass-object-between-activities-android-parcelable/

### Q: Difference between sleep and wait ?
A wait can be "woken up" by another thread calling notify on the monitor which is being waited on whereas a sleep cannot. Also a wait (and notify) must happen in a block synchronized on the monitor object whereas sleep does not.
you call wait on Object itself (i.e. you wait on an object's monitor) whereas you call sleep on Thread.
while sleeping a Thread does not release the locks it holds, while waiting releases the lock on the object that wait() is called on.
synchronized(LOCK) 
{ Thread.sleep(1000); // LOCK is held 
} 
synchronized(LOCK) 
{ LOCK.wait(); // LOCK is not held 
}
sleep(n) says “I’m done with my timeslice, and please don’t give me another one for at least n milliseconds.” The OS doesn’t even try to schedule the sleeping thread until requested time has passed. .wait() says “I’m done with my timeslice. Don’t give me another timeslice until someone calls notify().” As with sleep(), the OS won’t even try to schedule your task unless someone calls notify() (or one of a few other wakeup scenarios occurs).

### wait()
* wait() method releases the lock.
* wait() is the method of Object class.
* wait() is the non-static method - public final void wait() throws InterruptedException { //...}
* wait() should be notified by notify() or notifyAll() methods.
* wait() method needs to be called from a loop in order to deal with false alarm.
* wait() method must be called from synchronized context (i.e. synchronized method or block), otherwise it will throw IllegalMonitorStateException

### sleep()
* sleep() method doesn't release the lock.
* sleep() is the method of java.lang.Thread class.
* sleep() is the static method - public static void sleep(long millis, int nanos) throws InterruptedException { //... }
* after the specified amount of time, sleep() is completed.
* sleep() better not to call from loop(i.e. see code below).
* sleep() may be called from anywhere. there is no specific requirement.

### Q: What is synchronization in multithreading in java ? Give real time example ?
When we start two or more threads within a program, there may be a situation when multiple threads try to access the same resource and finally they can produce unforeseen result due to concurrency issues.
Synchronization in java is the capability to control the access of multiple threads to any shared resource. It allow only one thread to access the shared resource.
### Why use Synchronization
The synchronization is mainly used to
To prevent thread interference. (fight between threads)
To prevent consistency problem. (abnormal and unexpected value change of resource)

Thread Synchronization
There are two types of thread synchronization.
* Mutual Exclusive
* Cooperation (Inter-thread communication in java)
### Mutual Exclusive
Mutual Exclusive helps keep threads from interfering with one another while sharing data. This can be done by three ways in java:
* by synchronized method
* by synchronized block
* by static synchronization
Example : Multiple threads on single file. Opening,closing and writing etc.
### Lock in Java
Synchronization is built around an internal entity known as the lock or monitor. Every object has an lock associated with it. By convention, a thread that needs consistent access to an object's fields has to acquire the object's lock before accessing them, and then release the lock when it's done with them.
When a thread invokes a synchronized method, it automatically acquires the lock for that object and releases it when the thread completes its task.
When a thread acquires a lock, it is said to have entered the monitor. All other threads attempting to enter the locked monitor will be suspended until the first thread exits the monitor.
### Q: What are third party library you have integrated ?
* Gson:  Gson is a Java library used for serializing and deserializing Java objects from and into JSON.
* Retrofit: "Retrofit turns your REST API into a Java interface
* EventBus
* Universal Image Loader
* Volley
* Picasso
* ExoPlayer
* many more...
### Q: What are Activity life cycle ? Explain each methods's purpose ?
https://developer.android.com/guide/components/activities/activity-lifecycle

https://blog.mindorks.com/android-activity-lifecycle

https://guides.codepath.com/android/Activity-Lifecycle

https://github.com/xxv/android-lifecycle

https://www.oreilly.com/library/view/head-first-android/9781449362171/ch04.html

https://medium.com/androiddevelopers/the-android-lifecycle-cheat-sheet-part-i-single-activities-e49fd3d202ab

https://codelabs.developers.google.com/codelabs/android-training-activity-lifecycle-and-state/#2
### Q: What are Fragment life cycle ? Explain each methods's purpose ?

https://developer.android.com/guide/components/fragments

https://blog.mindorks.com/android-fragments-and-its-lifecycle

https://medium.com/androiddevelopers/the-android-lifecycle-cheat-sheet-part-iii-fragments-afc87d4f37fd

https://google-developer-training.github.io/android-developer-advanced-course-concepts/unit-1-expand-the-user-experience/lesson-1-fragments/1-2-c-fragment-lifecycle-and-communications/1-2-c-fragment-lifecycle-and-communications.html

https://www.techyourchance.com/android-fragment-lifecycle-for-professional-developers/

http://landenlabs.com/android/info/activity-life-cycle/activity-life-cycle.html

https://proandroiddev.com/android-fragments-common-queries-common-mistakes-df2014da0b50
### Q: How to remove a fragments ? What are the ways/methods ?
https://stackoverflow.com/questions/38864271/remove-fragment-from-activity-when-clicking-button?rq=1

https://www.intertech.com/Blog/programmatically-working-with-android-fragments/

https://medium.com/@Zhuinden/simplified-fragment-navigation-using-a-custom-backstack-552e06961257

https://www.dev2qa.com/android-add-fragment-to-activity-dynamically-example/
### Q: Difference between service, thread, AsyncTask and intent service ?
![Alt text](http://i.stack.imgur.com/N1DNU.png "Optional title")

https://stackoverflow.com/questions/3264383/difference-between-service-async-task-thread

### Q: Can service be called from any other thread ?
### Q: How listener (e.g click) works in android ?
### Q: Difference between list and set ?
http://net-informations.com/java/cjava/list.htm

https://beginnersbook.com/2014/07/difference-between-list-and-set-in-java/

https://www.java67.com/2013/01/difference-between-set-list-and-map-in-java.html

### Q: Difference between COARSE & FINE_LOCATION?
Location can be determined by two ways:
* Using NETWORK_PROVIDER -  ACCESS_COARSE_LOCATION or ACCESS_FINE_LOCATION
* Using GPS_PROVIDER - ACCESS_FINE_LOCATION
### Q: Why String is immutable in java?
There are multiple reasons that String is designed to be immutable in Java.
Because java uses the concept of string literal.Suppose there are 5 reference variables,all refers to one object "sachin".If one reference variable changes the value of the object, it will be affected to all the reference variables. That is why string objects are immutable in java.

1. Requirement of String Pool
String pool (String intern pool) is a special storage area in Java heap. When a string is created and if the string already exists in the pool, the reference of the existing string will be returned, instead of creating a new object and returning its reference.
If string is not immutable, changing the string with one reference will lead to the wrong value for the other references.
(or)
 Caching: when compiler optimizes your String objects, it sees that if two objects have same value (a="test", and b="test") and thus you need only one string object (for both a and b, these two will point to the same object).
 
2. Allow String to Cache its Hashcode
The hashcode of string is frequently used in Java. For example, in a HashMap. Being immutable guarantees that hashcode will always the same, so that it can be cashed without worrying the changes.That means, there is no need to calculate hashcode every time it is used. This is more efficient.
(or)
Since Strings are very popular as HashMap key, it's important for them to be immutable so that they can retrieve the value object which was stored in HashMap. Since HashMap works in the principle of hashing, which requires same has value to function properly. Mutable String would produce two different hashcodes at the time of insertion and retrieval if contents of String was modified after insertion, potentially losing the value object in the map.

3. Security
String is widely used as parameter for many java classes, e.g. network connection, opening files, etc. Were String not immutable, a connection or file would be changed and lead to serious security threat. The method thought it was connecting to one machine, but was not. Mutable strings could cause security problem in Reflection too, as the parameters are strings.

4. Synchronization and concurrency: making String immutable automatically makes them thread safe thereby solving the synchronization issues.

5. Class loading: String is used as arguments for class loading. If mutable, it could result in wrong class being loaded (because mutable objects change their state).
In summary, the reasons include design, efficiency, and security.

https://www.journaldev.com/16928/java-string

https://www.javatpoint.com/java-string

https://www.geeksforgeeks.org/strings-in-java/

### Q: What is static binding and dynamic binding ?
* Static binding happens at compile-time while dynamic binding happens at runtime.
* Binding of private, static and final methods always happen at compile time since these methods cannot be overridden. Binding of overridden methods happen at runtime.
* Java uses static binding for overloaded methods and dynamic binding for overridden methods.
### Q: Can interface be final ? and give the Reason?
No. An interface is a pure abstract class. Hence, all methods in an interface are abstract , and must be implemented in the child classes. So, by extension, none of them can be declared as final. A final method can't be overridden.
If you declare a class final cannot extend it. If you make a method final you cannot override it and, if you make a variable final you cannot modify it. i.e. use final with Java entities you cannot modify them further.

If you make an interface final, you cannot implement its methods which defies the very purpose of the interfaces. 

https://www.tutorialspoint.com/can-we-declare-an-interface-as-final-in-java

### Q: Runtime Polymorphism ?
### Q: Which of the following is the immediate base class for Activity and Service classes?
Context
### Q: Webservice in android?
A web service is a standard for exchanging information between different types of applications irrespective of language and platform. For example, an android application can interact with java or .net application using web services.
Web services are open standard (XML, SOAP, HTTP etc.) based Web applications that interact with other web applications for the purpose of exchanging data.

### Q: How RecyclerView works with Android ?
Google released RecyclerView alongside CardView and Design Support Library in 2014 with the launch of Android Lollipop. 
The other benefits that RecyclerView provides over ListView include Layout Manager, Item Decoration and Item Animator.

RecyclerView handles a View by marking it either recycled or scraped. A recycled view is the view that has already been inflated and can be put in the cache for later reuse with or without new data binding. A scrap view on the other hand is the view that was detached from the layout at the time of creating, or rather a view that didn't become dirty during previous use. Think of it as a static view. Now, if there is a need for it, RecyclerView will use it with or without data binding. The benefit that a scrap view offers is that we can have a view in the system but there isn't any performance overhead with it when it's not being used

https://contextneutral.com/story/understanding-recyclerview-part-1-the-basics

https://android.jlelse.eu/understanding-recyclerview-a-high-level-insight-part-1-dc3f81af5720

https://android.jlelse.eu/understanding-recyclerview-components-part-2-1fd43001a98f

https://www.quora.com/What-is-RecyclerView-in-Android-and-how-does-it-work
### Q: How HashMap works ?Why we go for HashMap ?
HashMap is a part of collection in Java since 1.2. It provides the basic implementation of Map interface of Java. It stores the data in (Key,Value) pairs. To access a value you must know its key, otherwise you can’t access it. HashMap is known as HashMap because it uses a technique Hashing.[ Hashing](http://quiz.geeksforgeeks.org/hashing-set-1-introduction/) is a technique of converting a large String to small String that represents same String. A shorter value helps in indexing and faster searches.

Few important features of HashMap are:

- HashMap is a part of java.util package.
- HashMap extends an abstract class AbstractMap which also provides an incomplete implementation of Map interface.
- It also implements [Cloneable](https://docs.oracle.com/javase/7/docs/api/java/lang/Cloneable.html) and [Serializable](https://docs.oracle.com/javase/7/docs/api/java/io/Serializable.html) interface. K and V in the above definition represent Key and Value respectively.
- HashMap doesn’t allow duplicate keys but allows duplicate values. That means A single key can’t contain more than 1 value but more than 1 key can contain a single value.
- HashMap allows null key also but only once and multiple null values.
- This class makes no guarantees as to the order of the map; in particular, it does not guarantee that the order will remain constant over time. It is roughly similar to HashTable but is unsynchronized.

**Internal Structure of HashMap**

Internally HashMap contains an array of Node. and a node is represented as a class which contains 4 fields :

1. int hash
2. K key
3. V value
4. Node next

https://www.javatpoint.com/working-of-hashmap-in-java

https://www.geeksforgeeks.org/java-util-hashmap-in-java-with-examples/

https://www.geeksforgeeks.org/internal-working-of-hashmap-java/

https://www.youtube.com/watch?v=CojCE-ojdGY

https://www.youtube.com/watch?v=fSjxhOYPBRI

https://www.youtube.com/watch?v=c3RVW3KGIIE

### Q: How to update textview from intentservice ?

https://medium.com/@anitaa_1990/how-to-update-an-activity-from-background-service-or-a-broadcastreceiver-6dabdb5cef74

https://proandroiddev.com/intentservice-and-resultreceiver-70de71e5e40a

https://www.tutorialspoint.com/how-to-update-ui-from-intent-service-in-android

https://www.websmithing.com/2011/02/01/how-to-update-the-ui-in-an-android-activity-using-data-from-a-background-service/

https://www.mysamplecode.com/2011/10/android-intentservice-example-using.html

https://www.journaldev.com/20735/android-intentservice-broadcastreceiver
### Q: What is Handler and how it works?

https://medium.com/@ankit.sinhal/handler-in-android-d138c1f4980e

https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a

https://stackoverflow.com/questions/13954611/android-when-should-i-use-a-handler-and-when-should-i-use-a-thread

http://coderzpassion.com/what-is-the-use-of-handler-in-android/

https://www.youtube.com/watch?v=TN-CGfzvBhc

https://en.proft.me/2017/04/15/understanding-handler-android/

https://blog.nikitaog.me/2014/10/11/android-looper-handler-handlerthread-i/

https://pierrchen.blogspot.com/2015/08/android-concurrent-programming-looper.html

### Q: What is onNewIntent()?
This is called for activities that set launchMode to "singleTop" in their package, or if a client used the FLAG_ACTIVITY_SINGLE_TOP flag when calling startActivity(Intent). If you set to single top, the activity will not be launched if it is already running at the top of the history stack. It will not relaunch just show from stack.

https://developer.android.com/guide/components/activities/tasks-and-back-stack.html

http://www.helloandroid.com/tutorials/communicating-between-running-activities

https://justanapplication.wordpress.com/tag/onnewintent/

https://medium.com/@ankit.sinhal/understand-activity-launch-mode-with-examples-721e85b6421e

### Q: What is time and space complexity?
### Q: Alarm Manager ? 
This class provides access to the system alarm services. These allow you to schedule your application to be run at some point in the future. Registered alarms are retained while the device is asleep (and can optionally wake the device up if they go off during that time), but will be cleared if it is turned off and rebooted.
The Alarm Manager holds a CPU wake lock as long as the alarm receiver's onReceive() method is executing. 
Alarms do not fire when the device is idle in Doze mode
To start an Alarm Manager you need to first get the instance from the System. Then pass the PendingIntent which would get executed at a future time that you specify.

Disadvantage:-
* Consume battery

https://www.javatpoint.com/android-alarmmanager

https://www.journaldev.com/27681/android-alarmmanager-broadcast-receiver-and-service

https://codelabs.developers.google.com/codelabs/android-training-alarm-manager/index.html?index=..%2F..android-training#0

https://android.jlelse.eu/using-alarmmanager-like-a-pro-20f89f4ca720

https://www.androhub.com/android-alarmmanager/

https://androidclarified.com/android-example-alarm-manager-complete-working/

### Q: Job scheduler?
JobScheduler is an API for scheduling various types of jobs against the framework that will be executed in your application's own process. While a job is running, the system holds a wakelock on behalf of your app. For this reason, you do not need to take any action to guarantee that the device stays awake for the duration of the job.
Apps can schedule jobs while letting the system optimize based on memory, power, and connectivity conditions. The Android 5.0 Lollipop (API 21) release introduces a job scheduler API via the JobScheduler class.

*  the JobScheduler supports batch scheduling of jobs.
*  It also survives application restarts. 
* Jobs can be done when Wifi, power connect etc constraints  conditions

* JobService will run on the main thread
* Your JobService is actually going to be a Service that extends the JobService class. 
* onStartJob() is called by the system when it is time for your job to execute.
* jobFinished() requires two parameters: the current job, so that it knows which wakelock can be released, and a boolean indicating whether you’d like to reschedule the job. 

There’s only three things you need to do:
1. Create a JobService to handle your job
2. Add that JobService to the manifest
3. Schedule your job using a JobInfo object to define your conditions

a. To create JobService, you need to extend JobService class and implement its methods onStartJob and onStopJob. These call back methods return boolean value, false indicates that the job is complete and true tells that job is still running in the background, in this case you need to call jobFinished method to inform job scheduler about the finished state after the job is complete.

b.  To schedule a job, first you need to get JobScheduler instance by calling getSystemService on the context object passing JOB_SCHEDULER_SERVICE argument to it.
JobScheduler jobScheduler = (JobScheduler)getApplicationContext()
.getSystemService(JOB_SCHEDULER_SERVICE);

ComponentName componentName = new ComponentName(this,
        DownloadJobService.class);

JobInfo jobInfoObj = new JobInfo.Builder(1, componentName)
.setPeriodic(50000).setRequiresBatteryNotLow(true).build();

jobScheduler.schedule(jobInfo);

c.  To create a job that needs to be rerun if it fails, you need to use setBackOffCriteria() method passing time interval for the first time retry and retry policy which is used to calculate time interval for retries after first retry.
JobInfo jobInfoObj = new JobInfo.Builder(1, componentName)
      .setBackoffCriteria(6000, JobInfo.BACKOFF_POLICY_LINEAR).build();

d.  To create a job that stays as scheduled even after device reboots, you need call setPersisted() method on JobInfo.Builder passing true as value to it. This setting requires RECEIVE_BOOT_COMPLETED permission.

https://www.vogella.com/tutorials/AndroidTaskScheduling/article.html

https://www.zoftino.com/android-job-scheduler-example

https://blog.teamtreehouse.com/scheduling-work-jobscheduler

https://android.jlelse.eu/easy-job-scheduling-with-android-job-4a2c020b9742

https://www.intertech.com/Blog/android-development-tutorial-job-scheduler/

### Q: What is doze mode?
Doze mode is a feature in Marshmallow, which prevents certain tasks from running if your device is in idle state. Doze in devices reduces power consumption by deferring background CPU and Network activity for applications.

https://developer.android.com/training/monitoring-device-state/doze-standby

https://medium.com/mindorks/you-have-to-know-more-about-doze-mode-3d80f016f8ad

https://android.jlelse.eu/doze-and-app-standby-android-89ef1690742a

https://www.bignerdranch.com/blog/diving-into-doze-mode-for-developers/

### Q: Reverse  a sack ? reverse and array ?
### Q: How to create your own Event bus?
### Q: YouTube Player API ?
### Q: What is complexity of HashMap with node n?
### Q: Problem with Alarm Manager?
### Q: What is order of process in android ? Foregorund->visible----------------->Empty
### Q: Access level of content provider?
### Q: Synchronization in singlton class ?
### Q: listview for generic screens?
### Q: linkify class?
### Q: xhdpi which API level ?
### Q: fragment life cycle?
### Q: activity life cycle?
### Q: abstract class ? can abstract method be final ?
### Q: minimum screen measurement ? 720p, 1024p,240p
### Q: Remote FactoryClass?
### Q: content provider uses the shared preferences?
### Q: find middle element of linkedlist?
### Q: fail pass?
### Q: If two fragment A& B. if B replace A what would be life cycle?
### Q: A & B two fragment in same activity same time. How to pass the data?
### Q: GCM push notification implementation?
### Q: how to find unique element in array?
### Q: What is Alarm Manager ? Q: Advantages of  Alarm Manager ?Disadvantages?
### Q: Job scheduler ? Advantages?
### Q: What is handler ? & Handler Vs Thread?
### Q: When to use AsyncTask, Handler, Service?
### Q: Linkedlist intersecting point ?
### Q: Singleton ?
### Q:  Array to find unique element?
### Q: Message and looper?
### Q: How Asynctask internally works? Create your own asynctask?
### Q: difference between Thread and service?
### Q: How to create optimise listview with images?
### Q: what is getView()?
### Q: launch mode in android?
### Q: what is gravity and layout_gravity ?
### Q: how to dra X on right top corner on any dialog?
### Q: What is searching techniques ?
### Q: What is sorting ? explain some sorting techniques and write programs?
### Q: What is pendingintent?
### Q: What is START_STICKY, START_NOT_STICKTY, START_REDELIVER_INTENT etc?
### Q: Types of services in android ? what method to must override?
### Q: Java design pattern.
### Q: What is IBInder();
### Q: How to identify install and uninstall tracking of an application ?
### Q: What is the difference between Picaso and Glid ?
### Q: Explain about video streaming ?
### Q: Ad SDK integration ?
### Q: activity life cycle
### Q: How to pass data from activity to fragment and fragment to activity ?
### Q: How to handle memory leak using handler
### Q: How to pass data from one fragment to another?
### Q: Overloading and Overriding?
### Q: Sticky intent?
### Q: Components of Android ?
### Q: Fragment life cycle?
### Q: What is content provider ?
### Q: What if finally got exception ?
### Q: Write a program for fibonacci series?
### Q: Reverse a string using recursion ?
### Q: How to dump a Database to an  ArrayList?
### Q: Find duplicate in array?
### Q: 0->1 and 1->0  without using conditional operators?
### Q: Accessing variables in static context related problems?
### Q: Difference between Volley and Retrofit?
### Q: What is exception handling?
### Q: How many objects will get created in String problem?
### Q: What are Sensors?
### Q: If no column found then which exception ?
### Q: Difference between GCm and FCM.
### Q: What is URI path in android 7?
### Q: Batch count for number of messages like whatsapp
### Q: How to create facebook feed with smooth user experience. Uploading data from db to server. How to maintain local and server key
### Q: Map in android
### Q: Multiple fragments with viewpager with gridview. 
### Q: Abstract classes?
### Q: 2D matrix problem ?
### Q: Printing O, Printing O, Printing AO problem?
### Q: How to pass data between fragments using callbacks?
### Q: What is static blocks? Use?
### Q: How job scheduling works?
### Q: Generics in java ?
### Q:  What is intent?
### Q: What is service?
### Q: How to create aidl service?
### Q: Abstract classes?
### Q: Polymorphism ?
### Q: Method overriding & overloading ?
### Q: How to create different row in recyclerview?
### Q: JSON parsing?
### Q: final keyword ?
### Q: Why java not supported Multiple inheritance ? tell me solution?
### Q: Activity life cycle?
### Q: fragment life cycle ? Activity A1 has fragment A then replaced with B then C then D and from D to B. How memory will be created.
### Q: Difference types of services? What is bound service?
### Q: Difference between Process and Thread?
### Q: Difference between Thread and Asynctask?
### Q: How cardboard work in android? VR technologies
### Q: How voice search work?
### Q: 9 coin problems? There 9 coins with 1 heavy weghted coin. Find the fake coin? Worst case, best case etc?
### Q: How to arrange value in HashMap in incoming elements ways?
### Q: How to pass data between fragments using callbacks?
### Q: Can a thread can be started inside another thread? Can a Asyncttask can be started inside another AsyncTask?
### Q: How SyncAdapter works?
### Q: How Executors work?
### Q: Comparator and comparable ?
### Q: What is Eventbus ?
### Q: What do you mean by composition ?
### Q: What is Map ? Write a program to put and get value from HasMap ?
### Q: What is services ? Types ? Life Cycle ?
### Q: What is Activity ? Life cycle ?
### Q: What is Fragment and its life cycle ?
### Q: Diff b/w Intent, StickyIntent & PendingIntent ?
### Q: Difference between service and AsyncTask ?
### Q: difference between Service and threads ?
### Q: What is encapsulation ?
### Q: Android architecture ?
### Q: Android application components ?
### Q: ListView with search? How to filter results of basis on key entered ?
### Q: How to handle the unsent data ?
### Q: How to pass data between fragments ?
### Q: Sync Adapters ?
### Q: How to add column in existing table ? ALTER table .
### Q: Erro code ? 404, 500 etc.
### Q: What is difference between Parcelable and Serializable ?
### Q: What is deep and shallow copy ?
### Q: What is the difference between iterator and enumerator ?
### Q: What is the diff b/w comparator and comparable ?
### Q: What is weak reference ?
### Q: Limitation of proguard?
### Q: Diff b/w sparseArray and HashMap ?
### Q: How to interact b/w 2 fragments ?
### Q: How eventbus works internally ?
### Q: Puzzle : 1 to 100 people in circle shooting each left one. Give a generic solution for N and also find which one will be last ?
### Q: Design Problem - Deck of cards problem.
### Q: Diff b/w these 2
### Q: String a= “abcd”;
String a =new String(“abcd);
### Q: How you handle memory leaks in android ?
### Q: Diff between Object and Object reference ?
### Q: How payment integration works  ?
### Q: Write sorting algorithm ? Quick, Merge sort etc ?
### Q: What is executors ? How it works ?
### Q: How RecyclerView works ? Use of ViewHolders ?
### Q: How to send each visible row of RecyclerView data to server ?
### Q: What are callbacks RecyclerView have ?
### Q: There is an array. Find the f(frquency) >=length/2
Array ar=[1,1,2,2,3,5,1]
f(ar[i]) >=length/2
### Q: What is synchronous and Asynchronous request ?
### Q: What is the difference between activity, service and fragment?
### Q: Explain the MVP architecture in detail.
### Q: Explain about services in android ?
### Q: How to create Circular layout like progress bar with colors ?
### Q: How to sort an array ? What internally it does ?
### Q: How HashMap works ?
### Q: How to navigate from one activity to another and how to finish an activity. Given some scenario ?
### Q: Explain about FCM ?
### Q:: What is the difference between DVM and ART ?
### Q: What is android framework ?
### Q: How to access inbuilt classes ? Reflection or AIDl ?
### Q: What are the technologies you have worked on in Android ? AsyncTask, Services, Fragments etc 
### Q: Explain your most challenging product ? What was your role ?
### Q: How much you rate yourself in Android & Java out of 10 ?
### Q: What is key store ? How it works ?
### Q: What is the difference between and permissions and use-permissions ?
### Q: What is sensors ? How to get data from all sensors ?
### Q: What is reflection ? what is getAccess and invoke method ?
### Q:: How you save data in Realam ? disadvantegaes of realm ?
### Q: Transpose the metrixs.
### Q: Given a string. Find the repeated string how many times it has occurred ?
### Q: Given a string find the integer values in string and find the sum ?
### Q: given an array find the 3rd and 4th largest element ?
### Q: What is access modifiers ?
### Q: Difference between AsyncTask and Thread ?
### Q: Component of Android ?
### Q: Difference between comparator and comparable ?
### Q: Diff b/w ArrayList and Vector ?
### Q: What is SOAP ? How you worked on SOAP ?
### Q: Have you worked on firebase ?
### Q: Have you worked on Payment Integration ?
### Q: AsyncTask ? What are parameters ? What happens with AsyncTask when activity got rotated.? Executors in AsyncTask ?
### Q: Broadcast Life Cycle ?
### Q: Can we use SharedPreferences in ContentProvider ?
### Q: How Handler works ?
### Q: How annotations works ?
### Q: How to manage concurrent request in intent service ?
### Q: Find maxima element in an array where elements left and right side element is smaller.?
### Q: What do you mean by Serializable ?
### Q: What do you mean by SharedPreferences ?
### Q: How will you update the table of an existing application ?
### Q: What is content provider and contentresolver ?
### Q: How intent service works ?
### Q: What is new in Java 8 with interfaces ?
### Q: Payment sdk ? 
### Q: How will you display 5 coordinates on map ? What do you mean GeoFencing ?
### Q: Difference between add() and replace() in fragment ? can i directly use replace in case no fragment added previously ?
### Q: What do you mean by abstraction and interface ?
### Q: What is exception handling ?
### Q: Difference between Handler and Thread ?
### Q: How to achieve parallel request in android ?
### Q: What is difference between Serializable & Parcelable ? How parcelable is more faster than serializable ?
### Q: How to pass an entity object from one activity to another ?
### Q: What is onActivityCreated() in fragment life cycle ? Explain its use ?
### Q: What is Set ? LinkedHashSet ? TreeSet ?
### Q: difference b/w Array and ArrayList ?
### Q: facebook, twitter, linkedin, instagram integration ?
### Q: Admob integration ? Sometime it doesn't work in starting ? Why ?
### Q: How will you find height of an object using Sensore or Cameras ?
### Q: What do you abour Image Processing in android ?
### Q: Explain encapsulation and abstraction using real time example ?
### Q: Problem of find time using sand. Take 2 bottle and find 10 minutes, 12 minutes, and 9 minutes ?
### Q: What is AsyncTask ? Methods ? cancellable() ? DisAdvantages of AsyncTask ?
### Q: What do you mean by SYNC ? How android take care of syncing ?
### Q: Intent types ? 
### Q: Have you used FCM ? How to identify payload and do the deeplinkings?
### Q: What are FLAGs and launch mode in android ?
### Q: Activity 1->2->3->4. How to go to from 4 to one ?
### Q: If activity already in backstack and try to open it by passing an intent which method get called ?
### Q: Do you have idea of Game development UNITY?
### Q: How to display a toast in activity from a button click on fragment ? How to find instance of fragment in an activity ?
### Q: What is difference between RecyclerView and ListView ? How they works ? What is ViewHolder pattern ?
### Q: What is the difference between recycler view and list view?
### Q: About activity lifecycle ?
### Q: How would you pass data from 5 activities to one activity. Large chunks of data.
### Q: How do you pass data in Android ?
### Q: Intent use pass by value or reference.
### Q: Difference between Inner and Outer join and which one is faster ?
Some Puzzle Questions :
### Q: Find a submatrix inside a matrix 
### Q: Make an 8 sided dice from a coin.
### Q: 10 bags with balls, one bag is defective question.
### Q: Toggling doors question, every door in first pass, alternate in second pass ... till 100 doors.
### Q: 1000 wine bottles, one is poisoned, you have 10 prisoners question.
You can easily find answers to these on the web. I was able to answer 2 correctly and attempted the other two also. Reached half way in one of them.
### Q: Write a function which takes in the root node of a tree and outputs true or false depending on whether that tree is symmetric or not.
### Q: How would I search a name of a student in all of the Universities in India and how would I optimise it?  Using trie. Optimize using compression.
### Q: find the sum of odd positioned nodes of a BST. 
Questions about layouts in Android. Linear Relative etc.
### Q: What are android components ?
### Q: How to pass data between activities ?
### Q: How to pass data from activity to fragment ?
### Q: What is services ? Types and their differences
### Q: What is Broadcast ? Types ?
### Q: What is AsyncTask ? When to use? 
### Q: Advantage of asynctask loaders?
### Q: What is intent ?
### Q: What is RecyclerView? Difference with ListView ?
### Q: What is difference between declaring broadcast in Manifest and dynamic ?
### Q: How to get Bitmap's width and height ?
### Q: What is diff b/w  thread and handler?
### Q: Suppose there is mobile having x width and y height. When we touch it somewhere it has coordinate (x1,y1). There is an image having width x2,height y2, find the coordinate (x3,y3) with respective to device.
### Q: There is lift in 4th floor, there is 2 person one is 3rd floor and another one in 5th floor presses the button on same time. Where this lift will go?
### Q: AsyncTask,AsyncTask Loaders and their effects on UI rotation?
### Q: Passing data between activities and fragemtns
### Q: Difference between Serialazble and Parcelbale ? Why parcelable is fast ?
### Q: Sensors ? What are types of sensors ? Classes ?
### Q: Services ? Types ?
### Q: Broadcast receiver ? Can we get Broadcast Receiver in different process ?
### Q: Passing data from service to UI ?
### Q: Diffe b/w looper and handler ?
### Q: How to take care of below things 1. Securities 2. App optimization and refactoring 3. Reduce app size
### Q: On what basic you select network library ? Volley or Retrofit ?
### Q: How to design e-commmerse application with 60 different screesns?
### Q: How to find unique element in an array ?
### Q: What is job sceduler ? Why is recommanded ?
### Q: What is Executors ? How it works ?
### Q: Fragment life cycle ?
### Q: diff b/w asset and raw ?
### Q: What are flags in AppBar layout ? What is behavior ?
### Q: How to create custom behavior in AppBar layout?
### Q: Constraint layout ?
### Q: diff b/w throw and throws ?
### Q: What do you mean by errors ?
### Q: differnce between LRUcache and BitmapCache ?
### Q: Callbacks of Volley and Retrofit ? Asked many questions from volley and retrofit ?
### Q: Reflections ?
### Q: SSL in android?
### Q: GCM Implementation ?
### Q: What do you mean by weight and weight sum ?
### Q: How to place a bottom on bottom of screen for all devices?
### Q: What do you mean by anonymous class ?
### Q: What is fragment ?
### Q: How to update UI from service ?
### Q: Which class cannot be subclass in java ?
### Q: What is loaders? Synchronous or asynchronous ?
### Q: Did task has process in it ?
### Q: What is use of kernel in android ?
### Q: if TOGETHER is equal to RQEGRJCT then what will be for PAROLE ?
### Q: 1,2,512,27,58,121…… next number(248 ? 244 ? 198? 190?)
### Q: Q: What is diff b/w ListView and RecyclerView ?
### Q: What and all library you have integrated ?
### Q: What are diff process you have while designing app ?
### Q: What are the features in android Oreo ?
### Q: What is proguard in android ?
### Q: Difference b/w Volley and Retrofit ? Why retrofit is more efficient ?
### Q: What is SyncAdapter ?
### Q: What is RecyclerView ? Difference b/w ListView and RecyclerView ? How many rows get created by default in RecyclerView?
### Q: How to stop a thread ?
### Q: Diff b/w thread, service and AsyncTask ?
### Q: Map in android ? How to get location in android ? location APIs ? GeoFencing ?
### Q: Types of services in android ?
### Q: How to display music on lock screen ?
### Q: How to read data from OTG ?
### Q: Sensors ? How you pass sensors data to UI ?
### Q: How to pass data b/w activities and fragments ? How to get result back from activity ?
### Q: How to make connection using okhttp instead on Retrofit?
### Q: Diff b/w serializable and parcelable ?
### Q: There is an sorted array 5,4,3,2,0,1 shuffled due to some reason. How to find the origin (0) of that array. Take care of complexity?
### Q: Star pattern problem
### Q: How you can give runtime permission without user knowledge ? Using Accessibility service ? adb shell commands etc ?
### Q: Have you ever build android OS? Kernel drivers etc ?
### Q Difference between Object Oriented and MVP ? 
### Q Are you aware of Android componets, support libraries and third party libraries?
### Q Have you ever develop android SDK ? What are things you take care while developing any kind of library ?
### Q Have you ever worked on VideoPlayer, VideoView and ExoPlayer etc ?
### Q What is MVP, MVC, MVVP, MVVM ?
### Q What are the Ads integration you have done ?
### Q How you handle memory leaks ? and optimisation ?
