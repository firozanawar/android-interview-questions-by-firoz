### Q: What is Android ?

Android is an open-source, linux-based operating system that is used in mobiles, tablets, televisions and growing range of devices encompassing everything from wearable computing to in-car entertainment. It launched in 2003 and Andy Rubin is the founder of Android. Android is an open source project (led by Google but it doesn't belong to them) called AOSP (Android Open Source Project) which is equipped with rich components that allows developers to create and run apps that can perform both basic and advanced functions.

In technical words, Android is a stack of software for mobile devices which includes an operating system, middleware and some key applications (Diagram is below). The application executes within its own process and its own instance of Dalvik Virtual Machine. Many instances of Virtual Machines run efficiently by a DVM device. DVM executes Java languages byte code which later transforms into .dex format files. The 'purest' version of Android is often referred to as 'stock Android'. Google acquired Android in 2005. Java and Kotlin language is mainly used to write the android code, even though other languages can be used to write part of App like C/C++. For software development, Android provides Android SDK (Software development kit).

![Alt text](https://www.howtogeek.com/wp-content/uploads/2014/05/android-architecture.png.pagespeed.ce.aKAjPj1k0Q.png "Android architecture")

*To read more:-*

https://www.androidpit.com/what-is-android

https://www.javatpoint.com/android-tutorial

https://www.tutorialspoint.com/android/android_overview.htm

http://heavy.com/tech/2013/06/what-is-android-os-operating-system-info-wiki/

https://recombu.com/mobile/article/what-is-android-and-what-is-an-android-phone_M12615.html#

### Q: What do you mean by Open Source Software?
Open-source software (OSS) is a type of computer software in which source code is released under a license in which the copyright holder grants users the rights to study, change, and distribute the software to anyone and for any purpose. Open source software is usually developed as a public collaboration and made freely available.

### Q: Android is Based on Linux, But What Does That Mean?

To know about it read the below blogs..

https://www.howtogeek.com/189036/android-is-based-on-linux-but-what-does-that-mean/

https://www.unixmen.com/why-is-android-built-on-linux-kernel/

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
