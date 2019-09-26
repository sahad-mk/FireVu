# FireVu
![Firevu logo](https://github.com/sahad-mk/FireVu/blob/master/Images/Firevu_Splash.png)

## Introduction
FireVu is an intentionally vulnerable Android application developed for Android open source security. The initial goal was to demonstrate the misconfigured Firebase database of mobile apps. I have added a few more vulnerabilities for learning purpose.

###### Vulnerabilities of this app:

1. Misconfigured Firebase backend.
2. Vulnerable Exported content provider.
3. Vulnerable Exported activities.
4. Insecure data storage.
5. Insecure logging.
6. Android Backup vulnerability.
7. Application Debuggable.

For Misconfigured Firebase vulnerability reference, ![Misconfigured Firebase Writeup](https://github.com/sahad-mk/FireVu/blob/master/Misconfigured%20Firebase%20Database.pdf)

## Prerequisites

     1. Supported Version: Android 9 (pie) device or use genymotion android 9 emulator.

     2. Supported(Tested) screen sizes :1080*1920 and 1080*2010.
 
     3. Install Open GApps and ARM translation in genymotion.

     5. App requires internet for user login (Firebase Authentication).

## Installation
     
        1. Download the FireVu.apk file.
        
        2. Open apk file and tap 'Install'.
        
        3. Enable Install Unknown apps.
        
        4. Drag and drop the FireVu.apk file into genymotion emulator.
        
        5. Disable verify apps over USB.
 
## Screenshots

1. The following screenshot shows the attack suraface of the application.

   ![Firevu attack_surface](https://github.com/sahad-mk/FireVu/blob/master/Images/attack_suraface.png)

2. User Registration (Enable Internet Access).

   <img src=https://github.com/sahad-mk/FireVu/blob/master/Images/register.png height="100" width="50">
   
   You can use any random email id. There is no email verification (can't register with an email which is already exist)
   
3. User Login (Enable Internet Access)

   
   <img src="https://github.com/sahad-mk/FireVu/blob/master/Images/login.png" height="100" width="50">
        
        
      
