TaskyAzure for iOS & Android
============================
There are a number of sample projects using the same Azure Mobile Services instance:

* iOS with MonoTouch

* Android for Mono for Android

* Windows Phone 7

* Mac-OSX with MonoMac

* Windows 8 sample provided by Microsoft


![screenshot](https://raw.github.com/conceptdev/TaskCloud/master/Azure/Screenshots/Screenshots_sml.png)

This sample has a very basic implementation of Microsoft's new (Sep-2012) Azure Mobile Services API.

It is loosely based on this article (ie the syntax for the REST requests)
[chrisrisner.com/Windows-Azure-Mobile-Services-and-](http://chrisrisner.com/Windows-Azure-Mobile-Services-and-iOS) however the Mono-for-Android application code is based on the existing Tasky samples (and uses MonoTouch.Dialog).

The Windows Phone 7 version uses the 'unofficial' [Azure Mobile Services Client](https://github.com/kenegozi/azure-mobile-csharp-sdk}

Use the [Azure Getting Started](https://www.windowsazure.com/en-us/develop/mobile/tutorials/get-started/) code to first set-up the Windows 8 sample app. The iOS, Android and Windows 8 apps will then read/write to the same TodoList !