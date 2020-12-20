---
layout: pageContent
title: Connect to the ergometer
nav-menu: true
show_tile: false
---

# Contents

- [Contents](#contents)
- [Connect to the ergometer](#connect-to-the-ergometer)
  - [Use Usb to connect to a PM3-5](#use-usb-to-connect-to-a-pm3-5)
  - [Use bluetooth (PM5 only)](#use-bluetooth-pm5-only)
  - [Ergometer Data server (deprecated)](#ergometer-data-server-deprecated)
- [Help I can not connect](#help-i-can-not-connect)

# Connect to the ergometer

There are multiple ways too connect ergometer-space to a concept 2 ergometer:
* Usb (PM3-5)
* Bluetooth (PM-5)
* Install the Ergometer Data server (PM3-5) (deprecated) 

For the best connection experience you can download a native app in from the download menu. The native apps also have screen blanker prevention.

If you need more help, check the last chapter on this page.

## Use Usb to connect to a PM3-5

* Web: Chromium based browsers like chrome, brave,vialdi,opera, te latest edge.
 
* Desktop/laptop: Download and install the app from the the download menu. It is compatible with 
  - Mac OS X [download](https://ergometer-space.org/downloads/Ergometer-space-installer.pkg) (works till 10.15, Not big sur, use browser instead)
  - Windows [download](https://ergometer-space.org/downloads/Ergometer-space-installer.exe)
* Mobile: Download the mobile android app from the play store
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
    For android you need an OTG USB cable to connect your phone to the ergometer.

## Use bluetooth (PM5 only)

Selecting the ergometer connection menu the connection type "Bluetooth (PM5)".
Close the dialog and click on the pair ergometer in the main menu bar.

Compatible with the following platforms:
* Web: Chromium based browsers like chrome, brave,vialdi,opera, te latest edge.
* Mobile: Ergometer-space app for android (native support, download the app from the play store)
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
  - Chrome browser running on an android device. If it is not already installed you can download it from the [play store](https://play.google.com/store/apps/details?id=com.android.chrome&referrer=utm_source%3Dhelp-center%26utm_medium%3Dhc-answer%26utm_campaign%3Dhelp-center-mg) Start the [website](https://ergometer-space.org) and use the chrome function "add to home screen" to add the ergometer app to your home screen.
  - iOS: I do not support iOS. There is one work arround to run the app on an iPhone. Install the [WebBLE browser app](https://apps.apple.com/us/app/webble/id1193531073) or [blue fy ble browser](https://apps.apple.com/us/app/bluefy-web-ble-browser/id1492822055) on your iPhone. The start the [website](https://ergometer-space.org) in the browser. There are a view limitations:
    - Vr widget does not work (best to close this widget)
    - The top statusbar does look a bit strange when scolling.
    - There is no sleep prevention.
    - Only blue tooth (PM5 support)
* Desktop/laptop: Ergometer-space Desktop App (download from the download menu)
  - Mac OS X [download](https://ergometer-space.org/downloads/Ergometer-space-installer.pkg) (works till 10.15, Not big sur, use browser instead)
  - Windows [download](https://ergometer-space.org/downloads/Ergometer-space-installer.exe)
  
## Ergometer Data server (deprecated)

Connect with USB to an PM3-5. This connection type is deprecated because it is much easier to connect using the desktop app.

Go to the download menu and download and install the Ergometer Data server  
Compatible with:
* Windows with installer [download](https://ergometer-space.org/downloads/setup.exe)
* Windows without installer [download](https://ergometer-space.org/downloads/ErgometerDataServer.zip) (Some anti virus program think that the installer is an virus. This is not correct. If this is the case you can download the zip and do the installation
      manually. Just copy the files into an folder in the programs and make a link to it.)</li>
   
* Mac OS X 10.11 and below [download](https://ergometer-space.org/downloads/Install%20Ergometer%20Data%20Server.dmg) Mac OS X Ergometer Data Server <br> This version does not work any more on OS X El Capitan
      I can only fix this problem when concept2 releases a new version.<br>
      As alternative you can use chrome as browser and connect using bluetooth to a PM5. 

The server can be used to connect multiple ergometers to one or more browsers.

# Help I can not connect

First check the following things:

* Do you have the latest version of the ergometer-space app. A change log can be found [here](https://tijmenvangulik.github.io/Ergometerspace/ChangeLog.html)
* Blue tooth. Check if you are using the latest firmware version of the concept 2 Performance monitor. There are many [firmware fixes](https://www.concept2.com/service/monitors/pm5/firmware/timeline#rownew)  
* Android+Usb. Check if you connect using and special otg cable see this [link](https://www.concept2.nl/nl/service/software/ergdata/android-benodigdheden)
* Blue tooth: Ensure that you have switched blue tooth on the device before clicking on the connect button in ergometer-space
* Android + bluetooth connection problems: On some phones you need to enalbe location access in the privacy settings of your android device. [Some more info on how to do this](https://tileteam.zendesk.com/hc/en-us/articles/217069598-How-to-Turn-Location-On-or-Off-with-your-phone-or-tablet-) There is an option in the options "Work around limited blue tooth hardware". You try this feature if the you can still not a make it work. You may have to restart the app after switching on the feature.
* Browser: First try if it works in chrome. If you try to connect using Usb in chrome, please first read the guide how to do this because this in an feature which currently in beta test phase in chrome.
* Check if you selected the correct connection type in the options.
  
Still having problems. Please mail me [tijmen@vangulik.org](mailto:tijmenvangulik.org) or [open an issue](https://github.com/tijmenvangulik/Ergometerspace/issues)

To be able to help you more quickly please mention the following in your mail issue please mention the following:
- version ergometer app
- Platform ergometer app (android/mac/pc/brower) In case of an browser which browser
- Version operating system (version of mac/pc/android)
- Type of the performance monitor PM3/4 or 5. 
- Performance monitor firmware version
- Please describe exactly did not work. Did you get an error message? Where dit the connection go wrong.
- If you have also worked with other ergometer apps on the same device could that app connect without problems?