# BlackBerry Manager
BlackBerry Manager provides an easy way to download, install and update ad-free BlackBerry apps on your Android device. Discover BlackBerry's Message Hub and experience other apps made by BlackBerry such as Calendar, Contacts, Keyboard, Launcher and more.

<b>Features of Blackberry Manager</b>
* Install BlackBerry apps on any device, even if the device is not listed as compatible on Play Store
* Access to the BlackBerry exclusive Keyboard
* Run the apps without advertising (no subscription required)
* Automatic notifications when updates are available
 
<b>System requirements to run BlackBerry apps</b>
* Android 5.0 (Lollipop) or better
* 2 GB or more of RAM and a screen density between 420 and 640 dpi
* 512 MB of free space on the internal SD card
* Tablets are partially supported
* Google Play Services must be installed on the device
* Installation of foreign apps must be enabled in Android settings

<b>Special requirements to run BlackBerry keyboard</b>
* BlackBerry Keyboard only works on arm64-v8a architecture

<b>Special Permission Requirements</b>
* GET_ACCOUNTS to read the Google account authentication token and to login to Google Play
* WRITE_EXTERNAL_STORAGE to save the downloaded apps to your SD card

<b>Why is BlackBerry Manager asking for Contacts permission?</b><br>
Since Android 6.0 (SDK 23), Android permissions are placed under different groups and all permissions from that group would be granted if one of them is granted. The GET_ACCOUNTS permission belongs to the permission group android.permission-group.CONTACTS, therefore the permission for contacts is requested. However, BlackBerry Manager does NOT access your contacts in any way. The app only reads your authentication token which is needed to login to the Google servers. To learn more about Android permissions, read the <a href="https://developer.android.com/guide/topics/permissions/requesting.html">Google developer documentation</a>.

<b>Installation</b><br>
Full install:
* Uninstall all original/unmodified BlackBerry apps from Play Store
* Install BlackBerry Manager. Then install all BlackBerry apps with BlackBerry Manager
* Do NOT run Hub+ Services to install apps from there

Partial install:
* Install the BlackBerry apps from Play Store (subscription required after 30 days to remove advertising) 
* Install BlackBerry Manager and then install the missing apps (i.e. the Keyboard) with BlackBerry Manager

If the partial install method is used, BlackBerry Manager hides apps that have been installed directly from Play Store, because they are not signature compatible. To use all apps from BlackBerry Manager, use the full install method.

<b>Security</b><br>
This app contains no malware and does not inject malware into the downloaded apps. The default Android developer signature is used to sign the downloaded and patched apps. That signature may cause a false malware alert in some Antivirus solutions. You can safely ingnore such warnings.

<b>About the author</b><br>
Cobalt is a <a href="http://www.dailyherald.com/article/20160625/business/160629372/">community trusted developer/reverse engineer, strongly dedicated to BlackBerry and its products</a>. His threads on CrackBerry.com about running BlackBerry apps on Android and vice versa have been viewed and discussed more than 6 million times.

<a href="http://cobalt232.github.io/blackberrymanager/">Download BlackBerry Manager</a>
