# Chatppl
It Hybrid Mobile Application built using Ionic Frame Work. Its a Chat application which allow user to find and add people near them using map and chat with them.

This App is calling REST API's from the [Node.js Server](https://github.com/khanani92/chatppl-server)

# Features 
- User can logined using their Facebook and Google Plus accounts.
- User can find people near them using map and can send request to them
- User can synchronize their contacts in the app and will be able to chat with their contacts.
-  User will be notified when someone is online in his contacts list is near user location.

# Plug-in Used 
 I am thankful to ngCordova  developers for developing  these easy to use plugin. Plugin used in this app are as following:
- Social plug-in for Facebook and Googel+ Login.
- In-app browser 
- GeoLocation (used to get and watch user location)
- Contacts (used to get users contacts info)
- Toast message (used to show user messages)

# Development Environment Setup

 Pre-requisites:
 -  Node.js
 - Cordova
 - Ionic

Install  **NodeJS** x64 distributions from its websites.

To install Cordova:

```bash
$ npm install cordova -g
```

To install Ionic

```bash
$ npm install ionic -g
```

# Plug-in Installation 

To install In-App Browser

```bash
cordova plugin add https://git-wip-us.apache.org/repos/asf/cordova-plugin-inappbrowser.git
```

To install GeoLocation

```bash
cordova plugin add cordova-plugin-geolocation
```

To install Contacts 

```bash
cordova plugin add cordova-plugin-contacts
```

To install Toast 

```bash
cordova plugin add https://github.com/EddyVerbruggen/Toast-PhoneGap-Plugin.git
```


# Runing Application.
 
Move to the Project Directry

```bash
$cd projectDirectry
```

- Adding API Key (same as on Node.js Server)
- Open file restangularConfig.js and your Key here
```bash
$cd www/js/config
```
```bash
var auth = 'API key'; //Change the API key 
```

- Adding Android Platform
 
```bash
$ionic platform add android
```

- Adding ios Platform
 
```bash
$ionic platform add ios
```

- Running in Browser
 
```bash
$ionic serve
```

- Running in emulator 
 
```bash
$ionic emulate android/ios
```

- Deploying app in mobile connected to computer via usb cable
 
```bash
$ionic run android/ios
```

- Create applcaiton file i.e .apk,etc.
 
```bash
$ionic build android/ios
```
#Screenshots of Application
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp17.jpg)
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp16.jpg)
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp15.jpg)
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp14.jpg)
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp13.jpg)
![]( https://github.com/khanani92/Chatppl/blob/master/www/img/screenshot/sp12.jpg)



#License
MIT





 
