---
layout: pageContent
title: Connect to the ergometer
nav-menu: true
show_tile: false
---

# Contents

- [Contents](#contents)
- [Connect to the ergometer](#connect-to-the-ergometer)
  - [Overview](#overview)
  - [Use Usb to connect to a PM3-5](#use-usb-to-connect-to-a-pm3-5)
  - [Use bluetooth (PM5 only)](#use-bluetooth-pm5-only)
- [Help I can not connect](#help-i-can-not-connect)

# Connect to the ergometer

There are multiple ways too connect ergometer-space to a concept 2 ergometer:
* Usb (PM3-5)
* Bluetooth (PM-5)

For the best connection experience you can download a native app in from the download menu. The native apps also have screen blanker prevention.

If you need more help, check the last chapter on this page.

## Overview

|          |                 | USB PM3-5 | PM5 Blue tooth |
|----------|-----------------|-----------|----------------|
| Mac os X | Web browser(*)  | &#9745;   | &#9745;        |
| Windows  | Web browser(*)  | &#9745;   | &#9745;        |
| Android  | Web browser(*)  | &#9744;   | &#9745;        |
|          | Native app      | &#9745;   | &#9745;        |
| IOS      | Web browser(**) | &#9744;   | &#9745;        |
|          | Native app      | &#9744;   | &#9745;        |

(*) Chromium based web browser like chrome, edge, brave, vialdi, opera (some browser blue tooth must first be enabled using a flag, in chrome and edge it works directly)
(**) Use special web browser app "blue fy"  or "ble browser"

## Use Usb to connect to a PM3-5

* Web: Chromium based browsers like chrome, edge.
 
* Mobile: Download the mobile android app from the play store
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
    For android you need an OTG USB cable to connect your phone to the ergometer.
  - iOS not available. Only PM5

## Use bluetooth (PM5 only)

Selecting the ergometer connection menu the connection type "Bluetooth (PM5)".
Close the dialog and click on the pair ergometer in the main menu bar.

Compatible with the following platforms:
* Web: Chromium based browsers like chrome, edge.
* Mobile: Ergometer-space app for android (native support, download the app from the play store)
  - [Android play store](https://play.google.com/store/apps/details?id=org.tijmenvangulik.ergometerspace&gl=NL)
  - Chrome browser running on an android device. If it is not already installed you can download it from the [play store](https://play.google.com/store/apps/details?id=com.android.chrome&referrer=utm_source%3Dhelp-center%26utm_medium%3Dhc-answer%26utm_campaign%3Dhelp-center-mg) Start the [website](https://ergometer-space.org) and use the chrome function "add to home screen" to add the ergometer app to your home screen.
  - [Apple app store](https://apps.apple.com/us/app/ergometer-space/id1548193188)  
    (the ios version does not have usb, audio,vr or video support )
    
* Desktop/laptop: 
  The desktop apps and the "Ergometer Data server" are deprecated because the browser solution works as fine for both usb and blue tooth.
  
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