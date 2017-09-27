# android-interview-questions-by-firoz
Here is collection for all interview questions asked in different companies in India for an fresher to experienced android developer. 

### Q: What is Android ?

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

### Q: Explain about GCM implementation?

![Alt text](https://androidexample.com/upload/content/Push_notification_Workflow.png "Optional title")

### Q: Object class and its methods ?
The Object class is the parent class of all the classes in java by default.
* The Object class is beneficial if you want to refer any object whose type you don't know. Notice that parent class reference variable can refer the child class object, know as upcasting.
* Object class is present in java.lang package.
* Object class methods are available to all Java classes.
* There are 12 methods in Object class:

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

### Q: How to handle concurrent request in android ?
### Q: Difference between gravity and layout_gravity ?
### Q: Difference between add and replace in fragment ?
### Q: Difference between View and ViewGroup ?
### Q: What do you mean by addToBackStack() in fragment?
### Q: Difference between StringBuffer and StringBuilder ?
### Q: Difference between SOAP and REST ?
### Q: How to pass data between fragments 1. when fragment are in same activity and visible at same time 2. When fragment transition happens from one fragment to another fragments?
### Q: How to pass data between activities ?
### Q: Can we pass objects from one to another activity? If yes then how ?
### Q: Difference between sleep and wait ?
### Q: What is synchronization in multithreading in java ? Give real time example ?
### Q: What are third party library you have integrated ?
### Q: What are Activity life cycle ? Explain each methods's purpose ?
### Q: What are Fragment life cycle ? Explain each methods's purpose ?
### Q: How to remove a fragments ? What are the ways/methods ?
### Q: Difference between service, thread, AsyncTask and intent service ?
### Q: Can service be called from any other thread ?
### Q: How listener (e.g click) works in android ?
### Q: Difference between list and set ?
### Q: Difference between COARSE & FINE_LOCATION?
### Q: why string is immutable in java?
### Q: What is static binding and dynamic binding ?
### Q: can interface be final ?
### Q: Runtime Polymorphism ?
### Q: Which of the following is the immediate base class for Activity and Service classes?
### Q: webservice in android?
### Q: How RecyclerView works with Android ?
### Q: How HashMap works ?
### Q: How HashMap works?
### Q: How to update textview from intentservice ?
### Q: What is handler and how it works?
### Q: What is onNewIntent()?
### Q: Why we go for HashMap ?
### Q: What is time and space complexity?
### Q: Alarm Manager ? 
### Q: Job scheduler?
### Q: what is doze mode?
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
### Q: Fragment life cycle ?
### Q: Diff b/w serializable and parcelable ?
### Q: There is an sorted array 5,4,3,2,0,1 shuffled due to some reason. How to find the origin (0) of that array. Take care of complexity?
### Q: Star pattern problem
### Q: How you can give runtime permission without user knowledge ? Using Accessibility service ? adb shell commands etc ?
### Q: Have you ever build android OS? Kernel drivers etc ?













