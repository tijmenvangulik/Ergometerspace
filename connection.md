# Connect to the ergometer

There are multiple ways too connect ergometer-space to a concept 2 ergometer:
* Usb (PM3-5)
* Bluetooth (PM-5)
* Install the Ergometer Data server (PM3-5) (deprecated) 

For the best connection experience you can download a native app in from the download menu. The native apps also have screen blanker prevention.

If you need more help, check the last chapter on this page.

## Use Usb to connect to a PM3-5

* Chrome with experimental features turned on 
  ( chrome://flags/#enable-experimental-web-platform-features )
* Desktop/laptop: Download and install the app from the the download menu. It is compatible with 
  - Mac OS X [download](https://ergometer-space.org/downloads/Ergometer-space-installer.pkg)
  - Windows [download](https://ergometer-space.org/downloads/Ergometer-space-installer.exe)
* Mobile: Download the mobile android app from the play store
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
    For android you need an OTG USB cable to connect your phone to the ergometer.

## Use bluetooth (PM5 only)

Selecting the ergometer connection menu the connection type "Bluetooth (PM5)".
Close the dialog and click on the pair ergometer in the main menu bar.

Compatible with:
* Browser chrome [download](https://www.google.com/chrome) compatible with 
  - MacOS X
  - Android
  - Chrome/ Chrome OS
  - Linux
  
  (if you do not like chrome any other chromium based browser will do. Like opera,brave,vialdi, future version of edge)
* Mobile: Ergometer-space app for android (native support, download the app from the play store)
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
* Desktop/laptop: Ergometer-space Desktop App (download from the download menu)
  - Mac OS X [download](https://ergometer-space.org/downloads/Ergometer-space-installer.pkg)
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

## Help I can not connect

First check the following things:

* Do you have the latest version of the ergometer-space app. A change log can be found [here](https://tijmenvangulik.github.io/Ergometerspace/ChangeLog.html)
* Blue tooth. Check if you are using the latest firmware version of the concept 2 Performance monitor. There are many [firmware fixes](https://www.concept2.com/service/monitors/pm5/firmware/timeline#rownew)  
* Android+Usb. Check if you connect using and special otg cable see this [link](https://www.concept2.nl/nl/service/software/ergdata/android-benodigdheden)
* Blue tooth: Ensure that you have switched blue tooth on the device before clicking on the connect button in ergometer-space
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