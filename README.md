# android-java-interview-questions-by-firoz
Here is collection for all interview questions asked in different companies in India for an fresher to experienced android developer. 

### Q: What is Android ?

Android is a widely used mobile operating system developed by Google, primarily designed for touchscreen devices such as smartphones and tablets. Here’s a detailed breakdown of what Android is:

### **1. History and Development**

- **Origins:** Android Inc., founded by Andy Rubin, Rich Miner, Nick Sears, and Chris White in 2003, originally created Android as an operating system for digital cameras. However, they soon realized the potential for a broader market in mobile devices.
  
- **Acquisition by Google:** In 2005, Google acquired Android Inc. The acquisition aimed to leverage Android's potential for mobile phones and other devices.

- **First Release:** The first commercial version, Android 1.0, was released in September 2008 on the HTC Dream (also known as the T-Mobile G1). 

- **Evolution:** Since its initial release, Android has gone through numerous updates, introducing new features and enhancements with each version. Major updates are named after desserts and sweets (e.g., Cupcake, Donut, Eclair) up until Android 14. Starting with Android 11, Google transitioned to a numerical naming scheme.

### **2. Architecture and Components**

- **Linux Kernel:** At its core, Android uses the Linux kernel, which provides a stable and secure foundation for the operating system. This kernel manages hardware abstraction, memory management, and device drivers.

- **Hardware Abstraction Layer (HAL):** The HAL is an interface between the hardware and the rest of the software stack. It allows Android to work with different hardware components (e.g., cameras, sensors) in a uniform way.

- **Android Runtime (ART):** ART replaces the older Dalvik virtual machine used in earlier versions of Android. It executes Android applications and optimizes performance through ahead-of-time (AOT) compilation.

- **Libraries:** Android includes a set of native libraries written in C/C++ that provide core functionality. Examples include the SQLite database, media libraries, and web rendering libraries.

- **Application Framework:** This layer provides high-level APIs for developers to build applications. It includes services like window management, resource management, and location services.

- **Applications:** The top layer includes the user-facing apps, which are either pre-installed by device manufacturers or downloaded from the Google Play Store. These apps are built using the Android SDK (Software Development Kit) and leverage the application framework.

### **3. Features**

- **Customizable User Interface:** Android offers a high degree of customization for both users and manufacturers. Users can change the appearance of their home screens, choose different launchers, and install various widgets.

- **Multitasking and Notifications:** Android supports multitasking, allowing users to switch between apps and manage multiple tasks simultaneously. The notification system is designed to keep users informed about updates and events without interrupting their current activities.

- **Google Services Integration:** Android integrates tightly with Google services such as Google Search, Google Maps, and Google Drive. The Google Play Store, which is the primary source for app downloads, is also a key component.

- **Security and Permissions:** Android incorporates a permissions model that allows users to control what data and features apps can access. Each app runs in a sandboxed environment to prevent unauthorized access to other apps or system resources.

- **App Ecosystem:** The Google Play Store and other app marketplaces offer millions of apps across various categories, from games and productivity tools to social media and utilities.

### **4. Variants and Customizations**

- **Stock Android:** Refers to the version of Android that is maintained by Google without modifications. It is often used in Google’s Pixel devices.

- **Custom Skins:** Device manufacturers like Samsung, OnePlus, and Xiaomi often modify Android with their own user interfaces and features. Examples include Samsung’s One UI, Xiaomi’s MIUI, and OnePlus’s OxygenOS.

- **Android Open Source Project (AOSP):** Android is open-source, meaning its source code is publicly available. AOSP provides the base code that manufacturers and developers can use to build and customize their versions of Android.

### **5. Ecosystem and Market Impact**

- **Global Reach:** Android is the most widely used mobile operating system globally, holding a significant share of the smartphone and tablet markets.

- **Diverse Devices:** Besides smartphones and tablets, Android is also used in other devices such as smartwatches (Android Wear), TV boxes (Android TV), and even automotive systems (Android Auto).

- **Community and Development:** Android has a large and active community of developers and enthusiasts. The availability of extensive documentation, developer tools, and a supportive ecosystem contributes to its ongoing evolution and innovation.

In summary, Android is a versatile and flexible operating system with a rich set of features and a broad user base. It supports a wide range of devices and offers extensive customization options for both users and developers.

### Q: What do you mean by Open Source Software?
Open Source Software (OSS) is a type of software that is characterized by its open availability and collaborative development model. Here's a detailed breakdown of what open source software entails:

### **1. Definition and Core Principles**

- **Source Code Availability:** At its core, open source software is defined by the availability of its source code. Source code is the human-readable instructions that make up a program. In open source software, this code is freely accessible to anyone.

- **Licensing:** Open source software is distributed under licenses that comply with the Open Source Definition established by the Open Source Initiative (OSI). These licenses grant users the freedom to view, modify, and distribute the software.

- **Collaboration and Transparency:** Open source projects are typically developed in a collaborative manner, allowing multiple contributors to work on the software. This collaboration is often facilitated through platforms like GitHub, GitLab, or Bitbucket, where contributors can propose changes, review code, and discuss improvements.

### **2. Key Characteristics**

- **Freedom to Use:** Users have the freedom to use the software for any purpose without restrictions.

- **Freedom to Modify:** Users can modify the source code to suit their needs or fix bugs. These modifications can be kept private or shared with others.

- **Freedom to Distribute:** Users can distribute the original software or their modified versions. Distribution can be done freely or commercially, depending on the license terms.

- **Community Involvement:** Open source projects often have a community of developers, users, and advocates who contribute to the project, provide support, and share knowledge.

### **3. Benefits**

- **Innovation:** Open source fosters innovation by allowing developers to build upon existing code. This collaborative environment can lead to rapid advancements and improvements.

- **Security:** Because the source code is open and accessible, security vulnerabilities can be identified and addressed more quickly by the community. The transparency allows for peer review and scrutiny, which can enhance the software's security.

- **Cost-Effectiveness:** Open source software is often free to use, which can reduce costs for individuals and organizations. Additionally, users can avoid vendor lock-in and have greater control over their software.

- **Customization:** Users can tailor open source software to their specific needs by modifying the source code. This level of customization is particularly valuable for businesses with unique requirements.

- **Educational Value:** Open source software provides valuable learning opportunities for developers. By studying and contributing to open source projects, developers can gain practical experience and improve their skills.

### **4. Examples of Open Source Software**

- **Operating Systems:** Linux is one of the most well-known open source operating systems. Variants include Ubuntu, Fedora, and Debian.

- **Web Browsers:** Mozilla Firefox is an open source web browser that allows users to inspect and modify its source code.

- **Development Tools:** The GNU Compiler Collection (GCC) and the Apache Software Foundation's tools (like Apache HTTP Server) are open source and widely used in software development.

- **Content Management Systems (CMS):** WordPress and Drupal are popular open source CMS platforms used for building websites and managing content.

- **Office Suites:** LibreOffice is an open source office suite that provides word processing, spreadsheets, and other office tools.

### **5. Open Source Licenses**

Different open source projects are distributed under various licenses, which define the terms under which the software can be used, modified, and distributed. Some common open source licenses include:

- **GNU General Public License (GPL):** Requires that any derivative works also be open source and distributed under the GPL license. This ensures that the code remains free and open.

- **MIT License:** Permits almost unrestricted use, modification, and distribution of the software, provided that the original copyright notice is included. It's known for its permissive nature.

- **Apache License:** Allows users to use, modify, and distribute the software with fewer restrictions than the GPL. It also includes provisions for patents.

- **BSD License:** Similar to the MIT License, the BSD license is permissive and allows for both open and closed source derivative works.

### **6. Challenges and Considerations**

- **Quality Assurance:** While open source projects benefit from community contributions, the quality and reliability of the software can vary. It is essential to evaluate the project's health, including its maintenance, documentation, and community activity.

- **Support:** Open source software may lack formal customer support. However, many projects have active community forums and online resources where users can seek help.

- **Legal and Compliance Issues:** Users must comply with the terms of the open source license. Failure to do so can lead to legal issues, especially for organizations integrating open source software into proprietary products.

### **7. Open Source and the Modern Ecosystem**

Open source software has become a critical component of the modern technology landscape. It drives innovation in various fields, including web development, cloud computing, artificial intelligence, and more. Major tech companies and organizations often contribute to and rely on open source projects, furthering their development and integration into mainstream technology.

In summary, open source software represents a collaborative and transparent approach to software development, providing users with the freedom to use, modify, and distribute code. It fosters innovation, enhances security, and offers cost-effective solutions, while also presenting certain challenges that users and developers must navigate.

### Q: Android is Based on Linux, But What Does That Mean?
When we say that Android is based on Linux, it refers to several key aspects of how Android is structured and how it leverages the Linux operating system to provide its functionalities. Here’s a detailed explanation of what this means:

### **1. **Linux Kernel Foundation**

- **Kernel Basics:** The kernel is the core part of an operating system that manages hardware resources, such as CPU, memory, and peripheral devices. It acts as an intermediary between the hardware and the applications running on the system.

- **Linux Kernel:** Android uses the Linux kernel as its core. This means that many of the foundational tasks and services are managed by the Linux kernel, including process management, memory management, and hardware abstraction. The Linux kernel is open-source, which means its source code is available for modification and distribution.

### **2. **Android's Adaptation of Linux**

- **Customization:** Although Android is based on the Linux kernel, it’s not identical to a standard Linux distribution (like Ubuntu or Fedora). Google has customized the Linux kernel to better meet the needs of mobile devices. This customization involves changes to support specific hardware features, power management, and other mobile-specific requirements.

- **Android-Specific Patches:** Android includes patches and modifications to the standard Linux kernel to add functionality required by mobile devices. For example, it might include patches to improve support for touchscreens, battery management, or device drivers specific to mobile hardware.

### **3. **Layered Architecture**

- **Linux Kernel:** At the bottom of the Android stack is the Linux kernel, which provides basic system services and hardware abstraction. It manages low-level operations such as device drivers, process scheduling, and security.

- **Hardware Abstraction Layer (HAL):** Above the Linux kernel is the Hardware Abstraction Layer. The HAL provides a standard interface for hardware components, allowing Android to communicate with different hardware devices (e.g., cameras, sensors) in a uniform way.

- **Android Runtime (ART) and Libraries:** Above the HAL, Android includes the Android Runtime (ART), which executes application code, and a set of core libraries that provide essential functions to applications.

- **Application Framework:** This layer provides high-level services and APIs to Android applications. It includes components like Activity Manager, Window Manager, and Content Providers, which handle tasks such as user interfaces, resource management, and data sharing between apps.

- **Applications:** At the top layer are the applications themselves, which users interact with. These applications utilize the services and APIs provided by the Android framework to deliver functionality and user experiences.

### **4. **Security Model**

- **Security Enhancements:** The Linux kernel provides a robust security model that Android builds upon. Android adds additional layers of security, including app sandboxing, permission management, and secure boot processes.

- **Sandboxing:** Each app on Android runs in its own process and user space, isolated from other apps. This isolation is enforced by both the Linux kernel and the Android framework to prevent apps from accessing each other's data or system resources without permission.

### **5. **System Calls and APIs**

- **System Calls:** The Android operating system relies on system calls provided by the Linux kernel to perform low-level operations. These system calls are used for tasks such as file management, process control, and inter-process communication.

- **APIs:** Android provides higher-level APIs to applications, which are built on top of the system calls and services provided by the Linux kernel and the Android runtime. These APIs offer functionalities such as graphics rendering, location services, and data storage.

### **6. **Compatibility and Portability**

- **Device Compatibility:** By using the Linux kernel, Android can benefit from the extensive hardware support and stability provided by Linux. This compatibility helps Android run on a wide range of devices, from smartphones and tablets to wearables and TVs.

- **Portability:** The Linux kernel's portability allows Android to be adapted for different hardware architectures. For example, Android can run on ARM, x86, and other processor architectures, thanks to the underlying Linux kernel's support for these architectures.

### **7. **Open Source Collaboration**

- **Open Source Contribution:** Android’s use of the Linux kernel aligns with the open-source philosophy. Both Linux and Android benefit from contributions and improvements made by the global open-source community. While Android itself is open source, it also includes proprietary components developed by Google, such as Google Play Services.

### **In Summary**

Android is based on the Linux kernel, which means it uses the Linux kernel as its foundational layer for managing hardware resources and system operations. However, Android is not simply a version of Linux; it is a distinct operating system built on top of the Linux kernel with its own application framework, runtime environment, and user interface. The Linux kernel provides the low-level system functions, while Android adds layers of functionality and customization tailored for mobile devices, creating a unique and robust platform for running applications on a wide range of hardware.

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
### Q: Difference between COARSE & FINE_LOCATION?
Location can be determined by two ways:
* Using NETWORK_PROVIDER -  ACCESS_COARSE_LOCATION or ACCESS_FINE_LOCATION
* Using GPS_PROVIDER - ACCESS_FINE_LOCATION
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

### Q: How to create your own Event bus?
Useing the Observer pattern you can design your event bus. 

### Q: YouTube Player API ?

https://developers.google.com/youtube/android/player/

https://www.sitepoint.com/using-the-youtube-api-to-embed-video-in-an-android-app/

https://www.androidhive.info/2014/12/how-to-play-youtube-video-in-android-app/

http://stacktips.com/tutorials/android/youtube-android-player-api-example

### Q: Problem with Alarm Manager?
* More battery consuming
* not accurate or doesn't gurantee
* on some API it doesn't work properly.
### Q: What is order of process in android ? Foregorund->visible----------------->Empty
https://medium.com/google-developers/who-lives-and-who-dies-process-priorities-on-android-cb151f39044f

http://www.techotopia.com/index.php/Understanding_Android_Application_and_Activity_Lifecycles
### Q: Access level of content provider?
### Q: Synchronization in singlton class ?
### Q: Listview for generic screens?
### Q: xhdpi which API level ?
### Q: do Content provider uses the shared preferences?
No

### Q: If two fragment A& B. if B replace A what would be life cycle?
https://androidlearnersite.wordpress.com/2017/02/27/fragment-lifecycle-during-fragment-transaction/

https://stackoverflow.com/questions/42218546/understanding-fragments-lifecycle-methods-calls-during-fragment-transaction

https://stackoverflow.com/questions/12154157/fragment-methods-attach-detach-remove-replace-popbackstack

### Q: A & B two fragment in same activity same time. How to pass the data?
* Using interface callbacks.
* Event bus
* ViewModel
### Q: What is Alarm Manager ? Q: Advantages of  Alarm Manager ?Disadvantages?
Android AlarmManager allows you to access system alarm.
AlarmManager has access to the system alarm services. With the help of AlarmManager you can schedule execution of code in future. AlarmManager object can’t instantiate directly however it can be retrieved by calling Context.getSystemService(Context.ALARM_SERVICE). 

AlarmManager is always registered with intent. When an alarm goes off, the Intent which has been registered with AlarmManager, is broadcasted by the system automatically. This intent starts the target application if it is not running. It is recommended to use AlarmManager when you want your application code to be run at a specific time, even if your application is not currently running. For other timing operation handler should be used because it is easy to use.

Intent intent = new Intent(this, MyBroadcastReceiver.class);  

        PendingIntent pendingIntent = PendingIntent.getBroadcast(  
                                      this.getApplicationContext(), 234324243, intent, 0);  
                                      
        AlarmManager alarmManager = (AlarmManager) getSystemService(ALARM_SERVICE); 
        
        alarmManager.set(AlarmManager.RTC_WAKEUP, System.currentTimeMillis()  
                                      + (i * 1000), pendingIntent);  
                                      
        Toast.makeText(this, "Alarm set in " + i + " seconds",Toast.LENGTH_LONG).show();
 
#### Advantages of  Alarm Manager ?
It will run even when the device is on sleep mode. Handler will not work on standby.
may need to run or repeat beyond the scope of its lifecycle. This allows the application to perform some function even after the application process or all of its Android components have been cleaned up by the system.
have the ability to wake up the device when it is asleep if the alarm is urgent.
The benefits of the AlarmManager come into play when using inexact intervals or times to fire off Services. The Android system tries to batch alarms with similar intervals or times together in order to preserve battery life.
AlarmManager is a great candidate for scheduling if an application needs to perform a local event at an exact time or inexact interval.
 
#### Disadvantages of  Alarm Manager ?
consume more battery because it will wake up CPU and other chips
Some time fired multiple times.
One concern to consider while using the AlarmManager is that alarms are wiped out during device reboots. Applications need to register the RECEIVE_BOOT_COMPLETE permission in their Android Manifest and reschedule their alarms in a BroadcastReceiver.
setting an exact time for an application to sync with a server could put high strain on a server
documentation discourages using AlarmManager for scheduling network-related tasks.

### Q: Job scheduler ? Advantages?
The JobScheduler supports batch scheduling of jobs. The Android system can combine jobs so that battery consumption is reduced. JobManager makes handling uploads easier as it handles automatically the unreliability of the network. It also survives application restarts.
Here are example when you would use this job scheduler:
Tasks that should be done once the device is connect to a power supply
Tasks that require network access or a Wi-Fi connection.
Task that are not critical or user facing
Tasks that should be running on a regular basis as batch where the timing is not critical.
Implementation :
To implement a Job, extend the JobService class and implement the onStartJob and onStopJob. If the job fails for some reason, return true from on the onStopJob to restart the job. The onStartJob is performed in the main thread, if you start asynchronous processing in this method, return true otherwise false.
The new JobService must be registered in the Android manifest with the BIND_JOB_SERVICE permission.
// schedule the start of the service every 10 - 30 seconds
    public static void scheduleJob(Context context) {
        ComponentName serviceComponent = new ComponentName(context, TestJobService.class);
        JobInfo.Builder builder = new JobInfo.Builder(0, serviceComponent);
        builder.setMinimumLatency(1 * 1000); // wait at least
        builder.setOverrideDeadline(3 * 1000); // maximum delay
        //builder.setRequiredNetworkType(JobInfo.NETWORK_TYPE_UNMETERED); // require unmetered network
        //builder.setRequiresDeviceIdle(true); // device should be idle
        //builder.setRequiresCharging(false); // we don't care if the device is charging or not
        JobScheduler jobScheduler = context.getSystemService(JobScheduler.class);
        jobScheduler.schedule(builder.build());
    }
Util.scheduleJob(context);
public class TestJobService extends JobService {
    private static final String TAG = "SyncService";

    @Override
    public boolean onStartJob(JobParameters params) {
        Intent service = new Intent(getApplicationContext(), LocalWordService.class);
        getApplicationContext().startService(service);
        Util.scheduleJob(getApplicationContext()); // reschedule the job
        return true;
    }

    @Override
    public boolean onStopJob(JobParameters params) {
        return true;
    }

}
#### Advantages and disadvantages:
scheduled jobs persist through system reboots.
Disadva - it’s compatible only with API level 21 (Lollypop) and higher.
References:
http://toastdroid.com/2015/02/21/how-to-use-androids-job-scheduler/

http://www.vogella.com/tutorials/AndroidTaskScheduling/article.html

https://code.tutsplus.com/tutorials/using-the-jobscheduler-api-on-android-lollipop--cms-23562
### Q: What is handler ? & Handler Vs Thread?
both execute task asynchronously without blocking your current code,

The difference: Imagine you have a Runnable r = new Runnable{...}

When you use new Thread(r).start(), you actually created a new thread and run task asynchronously.

When you use new Handler().post(r) (or Message), you added the Runnable object to Looper and execute the code later in the same thread.

A Thread, generally MainThread or UIThread contains a Looper. When MainThread runs, it will loop the Looper and execute Runnable one by one.

When Thread is preferred:

When you're doing a heavy work like network communication, or decoding large bitmap files, a new thread is preferred. If a lot of thread is needed, maybe ExecutorService is preferred further. https://developer.android.com/reference/java/util/concurrent/ExecutorService.html

When Handler is preferred:

When you want to update UI objects (like TextView text) from other thread, it is necessary that UI objects could only be updated in UI Thread. Also, when you just want to run some light code later (like the delay for 300ms) you can use Handler because it's lighter and faster.
With handler you can also have things like MessageQueuing, scheduling and repeating.

Please also refer to Handler vs AsyncTask vs Thread
### Q: When to use AsyncTask, Handler, Service?
https://stackoverflow.com/questions/6964011/handler-vs-asynctask-vs-thread

https://tutorial.eyehunts.com/android/deference-between-handler-asynctask-thread-android/

https://www.slideshare.net/HoangNgoBuu/android-thread-handler-and-asynctask

https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a
### Q: Message and looper?
https://blog.mindorks.com/android-core-looper-handler-and-handlerthread-bd54d69fe91a

### Q: How Asynctask internally works? Create your own asynctask?
https://medium.com/@thiagoqvalle/an-inner-look-into-asynctask-7d87957941f3

https://stackoverflow.com/questions/10480599/how-asynctask-works-in-android

https://www.slideshare.net/blrdroid/internals-of-asynctask

https://codetheory.in/android-asynctask/

https://androidresearch.wordpress.com/2012/03/17/understanding-asynctask-once-and-forever/

### Q: difference between Thread and service?
* Service - if it is destroyed while performing its job, in the middle by Android due to low memory scenario. Then android will make sure that it will restart your service, if you have returned START_STICKY or START_REDELIVER_INTENT from onStartCommand().

* Thread - if it is destroyed by android in middle due to low memory, then android will not guarantee to restart it again. That means user lost his half work.
* Service - is a component of android, so it has priority levels to be considered while destroying an application due to low memory.

* Thread - is not a component of android, so android will not take thread priority into consideration while killing an application due to low memory.
I will try to explain this 3rd point.
Lets, say you have a requirement of connecting to internet from your activity. You can do it by using a service(with thread) or directly by creating a thread in activity. Consider the second scenario where you are connecting to internet in a thread. Then
i. What will happen if user closes the activity, while still thread is running in the background. Will that thread continue to run in back ground ? Answer is you can't really predict.

ii. Assume that in continuation for above scenario, even after killing activity your thread continued to do its intended operation. Then there is a low memory situation arises in your phone. Then this application will be the first susceptible app to be killed as there is no priority for this application.

So bottom line is: If you want to do some heavy background functionality then it is always better to have a service with thread. If you feel that that background functionality to be alive as long as your activity is alive, then go for activity with thread or activity with async task.
### Q: How to create optimise listview with images?
### Q: what is getView()?
http://android.amberfog.com/?p=296

https://www.youtube.com/watch?v=wDBM6wVEO70
### Q: Launch mode in android?
https://medium.com/@iammert/android-launchmode-visualized-8843fc833dbe

https://blog.mindorks.com/android-activity-launchmode-explained-cbc6cf996802

https://medium.com/mindorks/android-launch-mode-787d28952959

https://medium.com/@ankit.sinhal/understand-activity-launch-mode-with-examples-721e85b6421e

https://medium.com/@kkunalandroid/launch-mode-in-android-a3f88afeee37

https://android.jlelse.eu/android-activity-launch-mode-e0df1aa72242

https://medium.com/@inzimamislam/android-launch-mode-8ba7d7660526
### Q: how to draw X on right top corner on any dialog?
### Q: What is pendingintent?
https://stackoverflow.com/questions/2808796/what-is-an-android-pendingintent

https://android.jlelse.eu/intent-vs-pendingintent-8ef2ad5824ed

https://codetheory.in/android-pending-intents/

https://www.journaldev.com/10463/android-notification-pendingintent
### Q: What is START_STICKY, START_NOT_STICKTY, START_REDELIVER_INTENT?
These are related to services. We all know that services keeps on running in the background and they also consume some memory to execute.

So, as more of the application runs on android device, the device memory keeps on getting low and when the time arises, when the device memory gets critically low, the android system starts terminating processes, so as to release the memory occupied by the processes.

But you might be doing some important task with the services, that could also get terminated as the service stops. so these concepts are to tell the android system what action you want to perform when the device memory gets stable and when it is ready to relaunch the services.

The simplest explanation of these could be,

START_STICKY- tells the system to create a fresh copy of the service, when sufficient memory is available, after it recovers from low memory. Here you will lose the results that might have computed before.

START_NOT_STICKY- tells the system not to bother to restart the service, even when it has sufficient memory.

START_REDELIVER_INTENT- tells the system to restart the service after the crash and also redeliver the intents that were present at the time of crash.
### Q: Types of services in android ? what method to must override?
https://www.journaldev.com/1827/java-design-patterns-example-tutorial
### Q: What is IBInder();
### Q: How to identify install and uninstall tracking of an application ?
### Q: What is the difference between Picaso and Glid ?
![Alt text](https://i.stack.imgur.com/TdLCr.png "Optional title")

https://medium.com/@multidots/glide-vs-picasso-930eed42b81d

https://stackoverflow.com/questions/29363321/picasso-v-s-imageloader-v-s-fresco-vs-glide

https://yourwebsitefirst.com/picasso-vs-glide-advantage-disadvantage/

https://inthecheesefactory.com/blog/get-to-know-glide-recommended-by-google/en
### Q: Explain about video streaming ?
Some commons topics used in video streaming ExoPLayer, HLS, .m3u8, DASH, WebRTC, Bitrate, ts, akamai,CDN, 
### Q: Ad SDK integration ?
FAN, AdMob, IMA
### Q: How to pass data from activity to fragment and fragment to activity ?
Using Interface callback,
Event Bus
ViewModel
### Q: How to handle memory leak using handler?
Make handler null on destroy else it can throw memory leak.
### Q: How to pass data from one fragment to another?
Using Interface callback,
Event Bus
ViewModel
### Q: Components of Android ?
Activity, Service, Broadcast reciver, content provider.
### Q: What is content provider ?
### Q: Difference between Volley and Retrofit?
#### Volley-

* No automatic parsing
* Caching Mechanism
* Retry policy
* inbuilt image loading support

#### Retrofit-

* Automatic JSON parsing
* No Caching mechanism
* no retry policy
* no Image loading

https://www.quora.com/What-is-the-difference-between-retrofit-and-volley-in-Android

https://medium.com/@ali.muzaffar/is-retrofit-faster-than-volley-the-answer-may-surprise-you-4379bc589d7c

https://www.truiton.com/2015/04/android-volley-vs-retrofit-better-approach/

http://www.tothenew.com/blog/retrofit-vs-volley/

https://stackoverflow.com/questions/16902716/comparison-of-android-networking-libraries-okhttp-retrofit-and-volley

https://vickychijwani.me/retrofit-vs-volley/
### Q: What are Sensors?
https://developer.android.com/guide/topics/sensors/sensors_overview

https://source.android.com/devices/sensors/sensor-types

https://www.tutorialspoint.com/android/android_sensors.htm

https://www.javatpoint.com/android-sensor-tutorial

https://www.vogella.com/tutorials/AndroidSensor/article.html

https://www.journaldev.com/25691/android-sensors
### Q: If no column found then which exception ?
android.database.sqlite.SQLiteException: table RejectList has no column named Number
### Q: Difference between GCM and FCM.
https://developers.google.com/cloud-messaging/faq

https://krify.co/what-is-gcm-fcm-cloud-based-messaging/
### Q: Batch count for number of messages like whatsapp or Facebook?
It is launcher property.
### Q: How to create facebook feed with smooth user experience. Uploading data from db to server. How to maintain local and server key?
### Q: Maps in android?
https://www.journaldev.com/10365/android-google-maps-api

https://www.journaldev.com/10380/android-google-maps-example-tutorial

https://www.vogella.com/tutorials/AndroidGoogleMaps/article.html

https://abhiandroid.com/programming/googlemaps

https://www.androidhive.info/2013/08/android-working-with-google-maps-v2/
### Q: Multiple fragments with viewpager with gridview?
### Q: How to pass data between fragments using callbacks?
Create an interface and implement to activity and throw callback from one fragment to another using interface callback.
### Q: How job scheduling works?
### Q: What is intent?
An Intent is a messaging object you can use to request an action from another app component. Although intents facilitate communication between components in several ways. 

https://developer.android.com/guide/components/intents-filters

https://www.vogella.com/tutorials/AndroidIntent/article.html

https://www.youtube.com/watch?v=FH1Ym1KjJNc
### Q: What is service? Difference types of services ? Life CycleWhat is bound service?
A service is a component that runs in the background to perform long-running operations without needing to interact with the user and it works even if application is destroyed. or Android service is a component that is used to perform operations on the background such as playing music, handle network transactions, interacting content providers etc. It doesn't has any UI (user interface).

https://www.vogella.com/tutorials/AndroidServices/article.html

https://proandroiddev.com/deep-dive-into-android-services-4830b8c9a09

https://medium.com/mindorks/mastering-android-service-of-2018-a4a1df5ed5a6

https://www.simplifiedcoding.net/android-service-example/
### Q: How to create AIDL service?
### Q: How to create different row in recyclerview?
https://medium.com/@droidbyme/android-recyclerview-with-multiple-view-type-multiple-view-holder-af798458763b

https://www.codexpedia.com/android/android-recyclerview-with-multiple-different-layouts/

https://www.journaldev.com/12372/android-recyclerview-example

https://zocada.com/android-creating-custom-recyclerview-adapter-multiple-view-items/

https://guides.codepath.com/android/Heterogenous-Layouts-inside-RecyclerView
### Q: JSON parsing?
* Manual parsing by JSONObejct and JSOnArray etc
* GSON
* Other parsing libraries..
### Q: fragment life cycle ? Activity A1 has fragment A then replaced with B then C then D and from D to B. How memory will be created.
### Q: Difference between Thread and Asynctask?
### Q: How cardboard work in android? VR technologies?
### Q: How voice search work?
### Q: Can a thread can be started inside another thread? Can a Asyncttask can be started inside another AsyncTask?
### Q: How SyncAdapter works?
https://developer.android.com/training/sync-adapters/creating-sync-adapter

https://github.com/codepath/android_guides/wiki/Server-Synchronization-(SyncAdapter)

https://www.oodlestechnologies.com/blogs/How-to-use-Sync-Adapter-In-Android/

http://blog.udinic.com/2013/07/24/write-your-own-android-sync-adapter/

http://blog.udinic.com/2013/07/24/write-your-own-android-sync-adapter/
### Q: How Executors work?
### Q: What is Eventbus ? How eventbus works internally?
EventBus is an open-source Android library that simplifies communication between Activities, Fragments, Threads, and Services, with less code and better quality. 

https://dzone.com/articles/what-is-eventbus-library-and-how-does-it-work

http://greenrobot.org/eventbus/

http://blogs.innovationm.com/what-is-eventbus-library-and-how-does-it-work/
### Q: ListView with search? How to filter results of basis on key entered ?
### Q: How to handle the unsent data ?
### Q: How to add column in existing table ? ALTER table.
### Q: Erro code ? 404, 500 etc.
### Q: What is difference between Parcelable and Serializable ?
**Serializable:** 

- Serializable is a standard Java interface. You can just implement Serializable interface and add override methods.The problem with this approach is that reflection is used and it is a slow process. This method create a lot of temporary objects and cause quite a bit of garbage collection. Serializable interface is easier to implement.
- Serialization is a marker interface, which implies the user cannot marshal the data according to their requirements. In Serialization, a marshaling operation is performed on a Java Virtual Machine (JVM) using the Java reflection API. This helps identify the Java objects member and behavior, but also ends up creating a lot of garbage objects. **Due to this, the Serialization process is slow in comparison to Parcelable.**

**Parcelable:** 

- Parcelable process is much faster than serializable. One of the reasons for this is that we are being explicit about the serialization process instead of using reflection to infer it. It also stands to reason that the code has been heavily optimized for this purpose. 10 times faster and use less resources.
- In Parcelable, developers write custom code for marshaling and unmarshaling so it creates less garbage objects in comparison to Serialization. The performance of Parcelable over Serialization dramatically improves (around two times faster), because of this custom implementation.

References:-

- https://www.3pillarglobal.com/insights/parcelable-vs-java-serialization-in-android-app-development
### Q: What is deep and shallow copy ?
- https://dzone.com/articles/java-copy-shallow-vs-deep-in-which-you-will-swim

- http://www.jusfortechies.com/java/core-java/deepcopy_and_shallowcopy.php

- http://www.java67.com/2013/05/difference-between-deep-copy-vs-shallow-cloning-java.html

- https://www.cs.utexas.edu/~scottm/cs307/handouts/deepCopying.htm

- https://www.youtube.com/watch?v=A5QbxGvpRKU
### Q: Limitation of proguard?
https://www.guardsquare.com/en/proguard/manual/limitations

http://www.dre.vanderbilt.edu/~schmidt/android/android-4.0/external/proguard/docs/manual/limitations.html
### Q: How payment integration works  ?
### Q: What is executors ? How it works ?
### Q: How RecyclerView works ? Use of ViewHolders ?
### Q: How to send each visible row of RecyclerView data to server ?
### Q: What are callbacks RecyclerView have ?
### Q: What is synchronous and Asynchronous request ?
### Q: Explain the MVP architecture in detail.
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
### Q:: How you save data in Realam ? disadvantegaes of realm ?
### Q: What is SOAP ? How you worked on SOAP ?
### Q: Have you worked on firebase ?
### Q: Have you worked on Payment Integration ?
### Q: AsyncTask ? What are parameters ? What happens with AsyncTask when activity got rotated.? Executors in AsyncTask ?
### Q: Broadcast Life Cycle ?
### Q: Can we use SharedPreferences in ContentProvider ?
### Q: How Handler works ?
### Q: How to manage concurrent request in intent service ?
### Q: Find maxima element in an array where elements left and right side element is smaller.?
### Q: What do you mean by SharedPreferences ?
### Q: How will you update the table of an existing application ?
### Q: What is content provider and contentresolver ?
### Q: How intent service works ?
### Q: What is new in Java 8 with interfaces ?
### Q: Payment sdk ? 
### Q: How will you display 5 coordinates on map ? What do you mean GeoFencing ?
### Q: Difference between add() and replace() in fragment ? can i directly use replace in case no fragment added previously ?
### Q: Difference between Handler and Thread ?
### Q: How to achieve parallel request in android ?
### Q: How to pass an entity object from one activity to another ?
### Q: What is onActivityCreated() in fragment life cycle ? Explain its use ?
### Q: facebook, twitter, linkedin, instagram integration ?
### Q: Admob integration ? Sometime it doesn't work in starting ? Why ?
### Q: How will you find height of an object using Sensore or Cameras ?
### Q: What do you abour Image Processing in android ?
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
### Q: How would you pass data from 5 activities to one activity. Large chunks of data.
### Q: How do you pass data in Android ?
### Q: Intent use pass by value or reference.
### Q: Difference between Inner and Outer join and which one is faster ? 
### Q: What is Broadcast ? Types ?
### Q: What is AsyncTask ? When to use? 
### Q: Advantage of asynctask loaders?
### Q: What is RecyclerView? Difference with ListView ?
### Q: What is difference between declaring broadcast in Manifest and dynamic ?
### Q: How to get Bitmap's width and height ?
### Q: What is diff b/w  thread and handler?
### Q: Suppose there is mobile having x width and y height. When we touch it somewhere it has coordinate (x1,y1). There is an image having width x2,height y2, find the coordinate (x3,y3) with respective to device.
### Q: AsyncTask,AsyncTask Loaders and their effects on UI rotation?
### Q: Sensors ? What are types of sensors ? Classes ?
### Q: Broadcast receiver ? Can we get Broadcast Receiver in different process ?
### Q: Passing data from service to UI ?
### Q: Diffe b/w looper and handler ?
### Q: How to take care of below things 1. Securities 2. App optimization and refactoring 3. Reduce app size
### Q: On what basic you select network library ? Volley or Retrofit ?
### Q: How to design e-commmerse application with 60 different screesns?
### Q: What is job sceduler ? Why is recommanded ?
### Q: What is Executors ? How it works ?
### Q: diff b/w asset and raw ?
### Q: What are flags in AppBar layout ? What is behavior ?
### Q: How to create custom behavior in AppBar layout?
### Q: Constraint layout ?
### Q: What do you mean by errors ?
### Q: differnce between LRUcache and BitmapCache ?
### Q: Callbacks of Volley and Retrofit ? Asked many questions from volley and retrofit ?
### Q: SSL in android?
### Q: What do you mean by weight and weight sum ?
### Q: How to place a bottom on bottom of screen for all devices?
### Q: What is fragment ?
### Q: How to update UI from service ?
### Q: Which class cannot be subclass in java ?
### Q: What is loaders? Synchronous or asynchronous ?
### Q: Did task has process in it ?
### Q: What is use of kernel in android ?
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
### Q: How you can give runtime permission without user knowledge ? Using Accessibility service ? adb shell commands etc ?
### Q: Have you ever build android OS? Kernel drivers etc ?
### Q Are you aware of Android componets, support libraries and third party libraries?
### Q Have you ever develop android SDK ? What are things you take care while developing any kind of library ?
### Q Have you ever worked on VideoPlayer, VideoView and ExoPlayer etc ?
### Q What is MVP, MVC, MVVP, MVVM ?
### Q What are the Ads integration you have done ?
### Q How you handle memory leaks ? and optimisation ?

### **************************************************************
# General Questions (Java, DS, Alog, other logical questions) 
### **************************************************************

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

### Q: Difference between StringBuffer and StringBuilder ?
https://www.journaldev.com/538/string-vs-stringbuffer-vs-stringbuilder

https://www.geeksforgeeks.org/stringbuffer-class-in-java/

https://www.geeksforgeeks.org/stringbuilder-class-in-java-with-examples/

StringBuffer was the only choice for String manipulation till Java 1.4 but it has one disadvantage that all of its public methods are synchronized. StringBuffer provides Thread safety but on a performance cost.

In most of the scenarios, we don’t use String in a multithreaded environment, so Java 1.5 introduced a new class StringBuilder that is similar to StringBuffer except thread safety and synchronization.

So if you are in a single threaded environment or don’t care about thread safety, you should use StringBuilder else use StringBuffer.

![Alt text](https://2.bp.blogspot.com/-QHIf55P3o2I/W_FZaQ8YuXI/AAAAAAAAMmY/WXb342XKhCQd2iVotRwJ77-XgXSlGcV3gCLcBGAs/s640/String%2Band%2BStringbuffer%2Band%2BStringBuilder.png "Optional title")

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



\### wait()

\* wait() method releases the lock.

\* wait() is the method of Object class.

\* wait() is the non-static method - public final void wait() throws InterruptedException { //...}

\* wait() should be notified by notify() or notifyAll() methods.

\* wait() method needs to be called from a loop in order to deal with false alarm.

\* wait() method must be called from synchronized context (i.e. synchronized method or block), otherwise it will throw IllegalMonitorStateException


\### sleep()

\* sleep() method doesn't release the lock.

\* sleep() is the method of java.lang.Thread class.

\* sleep() is the static method - public static void sleep(long millis, int nanos) throws InterruptedException { //... }

\* after the specified amount of time, sleep() is completed.

\* sleep() better not to call from loop(i.e. see code below).

\* sleep() may be called from anywhere. there is no specific requirement.

https://www.youtube.com/watch?v=L95658yXRgI

https://www.youtube.com/watch?v=TCd8QIS-2KI

### Q: What is synchronization in multithreading in java ? Give real time example ?

When we start two or more threads within a program, there may be a situation when multiple threads try to access the same resource and finally they can produce unforeseen result due to concurrency issues.

Synchronization in java is the capability to control the access of multiple threads to any shared resource. It allow only one thread to access the shared resource.

\### Why use Synchronization

The synchronization is mainly used to

To prevent thread interference. (fight between threads)

To prevent consistency problem. (abnormal and unexpected value change of resource)

Thread Synchronization

There are two types of thread synchronization.

\* Mutual Exclusive

\* Cooperation (Inter-thread communication in java)

\### Mutual Exclusive

Mutual Exclusive helps keep threads from interfering with one another while sharing data. This can be done by three ways in java:

\* by synchronized method

\* by synchronized block

\* by static synchronization

Example : Multiple threads on single file. Opening,closing and writing etc.

\### Lock in Java

Synchronization is built around an internal entity known as the lock or monitor. Every object has an lock associated with it. By convention, a thread that needs consistent access to an object's fields has to acquire the object's lock before accessing them, and then release the lock when it's done with them.

When a thread invokes a synchronized method, it automatically acquires the lock for that object and releases it when the thread completes its task.

When a thread acquires a lock, it is said to have entered the monitor. All other threads attempting to enter the locked monitor will be suspended until the first thread exits the monitor.

### Q: Difference between list and set ?

http://net-informations.com/java/cjava/list.htm

https://beginnersbook.com/2014/07/difference-between-list-and-set-in-java/

https://www.java67.com/2013/01/difference-between-set-list-and-map-in-java.html

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

https://javarevisited.blogspot.com/2010/10/why-string-is-immutable-or-final-in-java.html

### Q: What is static binding and dynamic binding ?

- Static binding happens at compile-time while dynamic binding happens at runtime.
- Binding of private, static and final methods always happen at compile time since these methods cannot be overridden. Binding of overridden methods happen at runtime.
- Java uses static binding for overloaded methods and dynamic binding for overridden methods.

### Q: Can interface be final ? and give the Reason?

No. An interface is a pure abstract class. Hence, all methods in an interface are abstract , and must be implemented in the child classes. So, by extension, none of them can be declared as final. A final method can't be overridden.
If you declare a class final cannot extend it. If you make a method final you cannot override it and, if you make a variable final you cannot modify it. i.e. use final with Java entities you cannot modify them further.

If you make an interface final, you cannot implement its methods which defies the very purpose of the interfaces. 

https://www.tutorialspoint.com/can-we-declare-an-interface-as-final-in-java

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

### Q: What is time and space complexity?

### Q: linkify class?

Linkify take a piece of text and a regular expression and turns all of the regex matches in the text into clickable links. This is particularly useful for matching things like email addresses, web URLs, etc. and making them actionable. Alone with the pattern that is to be matched, a URL scheme prefix is also required. Any pattern match that does not begin with the supplied scheme will have the scheme prepended to the matched text when the clickable URL is created. For instance, if you are matching web URLs you would supply the scheme http://. If the pattern matches example.com, which does not have a URL scheme prefix, the supplied scheme will be prepended to create http://example.com when the clickable URL link is created. 

https://developer.android.com/reference/android/text/util/Linkify.html

http://www.sanfoundry.com/java-andorid-program-demonstrate-linkify-class/

http://www.aviyehuda.com/blog/2011/01/27/android-creating-links-using-linkfy/

https://android-developers.googleblog.com/2008/03/linkify-your-text.html

http://www.indelible.org/ink/android-linkify/

### Q: Abstract class ? can abstract method be final ?

A class that is declared with abstract keyword, is known as abstract class in java. It can have abstract and non-abstract methods (method with body). Achieve abstraction in java using abstract class.
No. abstract method can’t be final because it has to overridden by other class.

https://www.journaldev.com/1582/abstract-class-in-java

https://www.geeksforgeeks.org/abstract-classes-in-java/

https://beginnersbook.com/2013/05/java-abstract-class-method/

### Q: Remote FactoryClass?

### Q: What is searching techniques ?

### Q: What is sorting ? explain some sorting techniques and write programs?

### Q: Java design pattern.

### Q: Overloading and Overriding? Polymorphism ?
https://www.tutorialspoint.com/java/java_polymorphism.htm

https://www.geeksforgeeks.org/polymorphism-in-java/

https://www.geeksforgeeks.org/polymorphism-in-java/

### Q: What if finally got exception ?

https://beginnersbook.com/2013/04/java-finally-block/

https://stackoverflow.com/questions/3779285/exception-thrown-in-catch-and-finally-clause

### Q: Write a program for fibonacci series?

### Q: Reverse a string using recursion ?

### Q: How to dump a Database to an  ArrayList?

### Q: Find duplicate in array?

### Q: 0->1 and 1->0  without using conditional operators?

### Q: Accessing variables in static context related problems?

### Q: What is exception handling?

https://www.journaldev.com/1696/exception-handling-in-java

https://www.geeksforgeeks.org/exceptions-in-java/

https://beginnersbook.com/2013/04/java-exception-handling/
### Q: How many objects will get created in String, related problem?

### Q: Abstract classes?

Abstract class in Java is similar to interface except that it can contain default method implementation. An abstract class can have an abstract method without body and it can have methods with implementation also.

abstract keyword is used to create a abstract class and method. Abstract class in java can’t be instantiated. An abstract class is mostly used to provide a base for subclasses to extend and implement the abstract methods and override or use the implemented methods in abstract class.

https://www.journaldev.com/1582/abstract-class-in-java

https://www.geeksforgeeks.org/abstract-classes-in-java/

https://www.javatpoint.com/abstract-class-in-java

https://beginnersbook.com/2013/05/java-abstract-class-method/

https://www.guru99.com/java-abstract-class-method.html

### Q: What is static blocks? Use?

1. A static block is a block of code which contains code that executes at class loading time.

2. A static keyword is prefixed before the start of the block.

3. All static variables can be accessed freely

4. Any non-static fields can only be accessed through object reference,thus only after object construction.

5. multiple static blocks would execute in the order they are defined in the class.

6. All static blocks executes only once per classloader

7. A typical static block looks like

   `static{``// code for static block``}`

   http://www.bullraider.com/java/core-java/scjp-ocjp/290-static-non-static-block

   https://www.geeksforgeeks.org/g-fact-79/

   ### Q: Generics in java ?

   ### Q: Method overriding & overloading ?

   ### Q: 9 coin problems? There 9 coins with 1 heavy weghted coin. Find the fake coin? Worst case, best case etc?

   ### Q: How to arrange value in HashMap in incoming elements ways?

   ### Q: Comparator and comparable ?

   Comparable and Comparator both are interfaces and can be used to sort collection elements.

    

   | **Comparable**                                               | **Comparator**                                               |
   | ------------------------------------------------------------ | ------------------------------------------------------------ |
   | 1) Comparable provides **single sorting sequence**. In other words, we can sort the collection on the basis of single element such as id or name or price etc. | Comparator provides **multiple sorting sequence**. In other words, we can sort the collection on the basis of multiple elements such as id, name and price etc. |
   | 2) Comparable **affects the original class** i.e. actual class is modified. | Comparator **doesn't affect the original class** i.e. actual class is not modified. |
   | 3) Comparable provides **compareTo() method** to sort elements. | Comparator provides **compare() method** to sort elements.   |
   | 4) Comparable is found in **java.lang** package.             | Comparator is found in **java.util** package.                |
   | 5) We can sort the list elements of Comparable type by **Collections.sort(List)** method. | We can sort the list elements of Comparator type by **Collections.sort(List,Comparator)** method. |

   - http://javarevisited.blogspot.in/2011/06/comparator-and-comparable-in-java.html
### Q: What do you mean by composition ?
Java composition is achieved by using instance variables that refers to other objects.  If you are looking for code reuse and the relationship between two classes is has-a then you should use composition rather than inheritance. Benefit of using composition in java is that we can control the visibility of other object to client classes and reuse only what we need.

https://www.geeksforgeeks.org/association-composition-aggregation-java/

https://www.javatpoint.com/q/5101/what-is-composition-in-java?

https://www.journaldev.com/1325/composition-in-java-example

https://youtu.be/VfTiLE3RZds 
### Q: What is Map ? Write a program to put and get value from HasMap ?
### Q: What is encapsulation ?
https://www.tutorialspoint.com/java/java_encapsulation.htm

https://www.geeksforgeeks.org/encapsulation-in-java/
### Q: What is weak reference ?
http://javapapers.com/core-java/java-weak-reference/

http://www.programmr.com/blogs/what-every-java-developer-should-know-strong-and-weak-references
### Q: Runtime Polymorphism ?
### Q Difference between Object Oriented and MVP ? 
### Q: What is complexity of HashMap with node n?
### Q: Find middle element of linkedlist?
### Q: fail pass in DS?
### Q: How to find unique element in array?
### Q: 2D matrix problem ?
### Q: Printing O, Printing O, Printing AO problem?
### Q: Linkedlist intersecting point ?
### Q: Singleton ?
It is simple, as a java, Android also supporting singleton. -
Singleton is a part of Gang of Four design pattern and it is categorized under creational design patterns.
* Static member : This contains the instance of the singleton class.
* Private constructor : This will prevent anybody else to instantiate the Singleton class.
* Static public method : This provides the global point of access to the Singleton object and returns the instance to the client calling class.

* create private instance
* create private constructor
* use getInstance() of Singleton class

public class Logger{ 

private static Logger objLogger; 

private Logger(){ //ToDo here } 

public static Logger getInstance() { 

if (objLogger == null) 

{ objLogger = new Logger(); 

} 

return objLogger; 

} 

}
### Q:  Array to find unique element?
### Q: final keyword ? What is blank final variable ?
A blank final variable in Java is a final variable that is not initialized during declaration.
If we have more than one constructors or overloaded constructor in class, then blank final variable must be initialized in all of them.
Blank final variables are used to create immutable objects (objects whose members can’t be changed once initialized).

https://www.geeksforgeeks.org/final-keyword-java/

https://www.geeksforgeeks.org/final-keyword-java/
### Q: Why java not supported Multiple inheritance ? tell me solution?
https://www.geeksforgeeks.org/java-and-multiple-inheritance/

### Q: Puzzle : 1 to 100 people in circle shooting each left one. Give a generic solution for N and also find which one will be last ?
### Q: Design Problem - Deck of cards problem.
### Q: Diff b/w these 2
### Q: String a= “abcd”;
String a =new String(“abcd);
### Q: Diff between Object and Object reference ?
https://coderanch.com/t/407807/java/difference-object-object-reference

https://www.hacktrix.com/difference-between-object-and-reference-in-java
### Q: Write sorting algorithm ? Quick, Merge sort etc ?
### Q: There is an array. Find the f(frquency) >=length/2
Array ar=[1,1,2,2,3,5,1]
f(ar[i]) >=length/2

### Q: How to sort an array ? What internally it does ?
### Q: What is reflection ? what is getAccess and invoke method ?
### Q: Transpose the metrixs.
### Q: Given a string. Find the repeated string how many times it has occurred ?
### Q: Given a string find the integer values in string and find the sum ?
### Q: given an array find the 3rd and 4th largest element ?
### Q: What is access modifiers ?
### Q: Diff b/w ArrayList and Vector ?
### Q: How annotations works ?
### Q: What do you mean by Serializable ?
Java provides a mechanism, called object serialization where an object can be represented as a sequence of bytes that includes the object's data as well as information about the object's type and the types of data stored in the object. object can be serialized on one platform and deserialized on an entirely different platform.
Serialization in java is a mechanism of writing the state of an object into a byte stream. It is mainly used to travel object's state on the network (known as marshaling). The reverse operation of serialization is called deserialization. Serializable is a marker interface (has no data member and method).

https://www.geeksforgeeks.org/serialization-in-java/
### Q: What do you mean by abstraction and interface ?
https://javapapers.com/core-java/abstract-and-interface-core-java-2/difference-between-a-java-interface-and-a-java-abstract-class/
### Q: What is difference between Serializable & Parcelable ? How parcelable is more faster than serializable ?
https://android.jlelse.eu/parcelable-vs-serializable-6a2556d51538
https://stackoverflow.com/questions/3323074/android-difference-between-parcelable-and-serializable
### Q: What is Set ? LinkedHashSet ? TreeSet ?
### Q: difference b/w Array and ArrayList ?
### Q: Explain encapsulation and abstraction using real time example ?
### Q: Problem of find time using sand. Take 2 bottle and find 10 minutes, 12 minutes, and 9 minutes ?
### Q: Find a submatrix inside a matrix 
### Q: Make an 8 sided dice from a coin.
### Q: 10 bags with balls, one bag is defective question.
### Q: Toggling doors question, every door in first pass, alternate in second pass ... till 100 doors.
### Q: 1000 wine bottles, one is poisoned, you have 10 prisoners question.
### Q: Write a function which takes in the root node of a tree and outputs true or false depending on whether that tree is symmetric or not.
### Q: How would I search a name of a student in all of the Universities in India and how would I optimise it?  Using trie. Optimize using compression.
### Q: find the sum of odd positioned nodes of a BST.
### Q: There is lift in 4th floor, there is 2 person one is 3rd floor and another one in 5th floor presses the button on same time. Where this lift will go?
### Q: How to find unique element in an array ?
### Q: diff b/w throw and throws ?
https://beginnersbook.com/2013/04/difference-between-throw-and-throws-in-java/
### Q: Reflections ?
### Q: What do you mean by anonymous class ?
https://www.geeksforgeeks.org/anonymous-inner-class-java/
### Q: if TOGETHER is equal to RQEGRJCT then what will be for PAROLE ?
### Q: 1,2,512,27,58,121…… next number(248 ? 244 ? 198? 190?)
### Q: There is an sorted array 5,4,3,2,0,1 shuffled due to some reason. How to find the origin (0) of that array. Take care of complexity?
### Q: Star pattern problem
### Q: Reverse  a stack ? reverse and array ?
### Q: Diff b/w sparseArray and HashMap ?
Sparse arrays can be used to replace hash maps when the key is a primitive type. There are some variants for different key/value type even though not all of them are publicly available.

Benefits are:

- Allocation-free
- No boxing

Drawbacks:

- Generally slower, not indicated for large collections
- They won't work in non-android project

 

- The SparseArray is made to be **memory efficient** than using the regular HashMap, that is does not allow multiple gaps within the array not like HashMap.
- SparseArray is the choice you should make when your map key is an integer, and those integers are not sequential, meaning not 0, 1, 2, 3, 4, ... n - but more like, 43, 2045, 12, 5.
- Main purpose of SparseArray in Android development is to have a memory efficient integer to object mapping.

References:-

- http://gunhansancar.com/sparsearray-vs-hashmap/

### Q: What is weak reference ?

http://javapapers.com/core-java/java-weak-reference/

http://www.programmr.com/blogs/what-every-java-developer-should-know-strong-and-weak-references



### 2020 quetions 

Image loading library mechanism

How to manage imageview in recyclerview if downloading image from url without third party.

If you pass activitys context in Singleton object and activity is destroyed. what will happen? 

Implement Asynctask class same as android.

What is viewholder pattern.

How recycling works in recylerview?

Why is constraint layout better in performance

Q:View Lifecycle

Q:HashMap internal functionality

Q:How many objects if string concatenated

Q:Try catch(Exception){} catch(NullPointrException){} - Output

Q:Public method in base class and overridden function is protected.. what will happen?

Q:Usecase of Viewmodel

Q: kth smallest or kth largest without sorting.

Q: Max sum between two nodes in a binary tree

Q:What is Viewmodel factory

Q: How repository object is created and passed to viewmodel.

Q: ViewModel vs Android ViewModel

Q: MVVM sample code

Q: Caching in Volley (Netwoprk layer optimizxations)

Q: What is the use of DiffUtil?

Q: MVVM Vs MVP

Q: What is Clean Architecture?

Q: Difference between ViewModel and Presenter?

Q: Sub Component and Scopes in Dagger2?

Q: Drawbacks of Dagger and how Dagger2 is different from Dagger?

Q: How to handle 2 classes dependency in each other?

Q: What is repository in MVVM?

Q: How to upload aar?

Q: What is lifecycle of Livedata?

Q: How ViewModel works internally?

Q: Does Workmanger works in background?

Q: Type of Livedata?

Q: Diff btw MVP & MVVM?

Q: What is illegalStateException ?

Q; What is memory leak ? How it comes? How to handle it ?

Q: What is out of memory error ? How to handle it ?

Q: Ordered HashMap ?? Answer - LinkedHashMap

Q: explain ViewModel? Advantages?

Q; What is window leak?

Q: While attaching a fragment IllegalStateException comes? Why it comes ?

Q: Given a JSON, design an App showing cities in list with sorted order based on the score of cities.

⇒ What is memory leak? What tools are used to detect and find the leak ?

⇒ How LeakCanary works internally ?

⇒ What is gc ? How does GC work ? How does JVM know the object is ready for gc ?

"⇒ Give 2 classes A and B, A having object of B, and B having object of A,

 Is this object garbage collected ? If Yes Why, If No Why?"
 
⇒ Given 1 array, sum given, find the pairs and no. of pairs?

⇒ Tell me a practical example or situation which can cause the leak ?

⇒ Explain MVVM ? Why MVVM ? VM in MVVM and Why ?

⇒ How memory leak is handled by VM?

⇒ How to handle challenges? Memory optimisation ?

⇒ Difference b/w TextureView and SurfaceView ? Which is recommended to use and why ?

⇒ How can you find which activity is on top ?

⇒ Launch modes ?

⇒ Communication between Threads ?

⇒ What is thread safety ?

⇒ What is a Handler ? How Handler work internally ? Looper? Message Queue ? Can there be 2 Message Queues ?

⇒ How to fix handler leaks?

⇒ What is a static handler ?

⇒ Custom view related question ? How to create a custom view in android ?

⇒ What is hashcode and equal in Object class? Purpose ?

⇒ Do you know Kotlin ?

⇒ What is final in java ?

"⇒ What is an open keyword in kotlin ? explain in detail ? open with class and method ? 

Why not make it open by default ?"

⇒ Explain overriding in details with a real time example ?

⇒ Reference type in java ? 4 types? What is WeakReference ? Use ?

⇒ How objects travel? Serialization and DeSerialization?

⇒ Given 2 LinkedIn and find the intersection point? Check if they crossed ?

⇒ What is DASH ? How DASH works ? HLS vs DASH ?

"⇒ What is preferable to use if a video is 10 sec ? and another video is 1 hr movie ?

 DASH or mp4? Why not use VideoView ?"
 
⇒ How mp4 gets played using MediaPlayer? Internal?

⇒ How to update UI from background thread ?

Diff btw getFragmentManager && getChildFragmentManager 

What is the best approach to download a video from api.

Can service run without thread?

What is Foreground services ? 

What is the restriction in service on API level 28. ? What would be the solutoin?

What is backstack ? Exaplain in deatil? What goes inside the backstack ?

Diff btw ActivityContext and Application context? Where to use which and why ?

Can a dynamic view in activity can be created using Application context ?

What are the type of fragment transactions ? 

What is the meaning of addToBackStack with null parameter?

What is the use of thread pool executors ?

What design pattern you have used in your current project ?
