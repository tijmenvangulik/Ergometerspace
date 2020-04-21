* 3.0.2
  - Improved team animation in race widget
  - Chat/speak to own team only option
  - When rowing in a team , you can only share the curve with your team
  - When activating audio microphone in is by default muted and fixed problem that it was not muted when a user loged in at later time.
  - For team rooms: Give more insight when users can not connect to each other. (error handling and connection state in the team dialog) Also made some connection stability improvements. (Please contact me if users could not connect and make screen shots of the error messages, Keep in mind that the team feature is still experimental)
* 3.0.0
  - Added Experimental team rower room which supports rowing in teams and watching the race as observer. The feature is also available for private rooms.
* 2.9.4
 - fix problem that training data is not always up to date after joining room in the new peer to peer rooms
* 2.9.3
  - race widgets now shows other rowers rowing when you do not have a active training.
* 2.9.2
   - Added peer to peer expermimental public and private rooms. These rooms reduce the delay between updates and give a better rowing experience. 
   - Improved documentation of the workout log and the login.
   - Fix problem that the audio controls became visible 
* 2.9.1
   - New Race values widget which shows the ergometer values of other rowers in your room
   - Increased contrast of text in race widget
   - Added an example plugin on how to write your own race values widget
* 2.9.0
  - Chat widget can now use audio so you can talk to each other while rowing.
* 2.8.0
  - Disconnect button for bluetooth
  - Moved help to the navbar menu
* 2.7.9
  - Allow stop scanning while scanning for blue tooth or web hid device
  - fix bug switching between usb - blue tooth while connecting
* 2.7.8
  - On some android devices the app could not connect to the PM5 using blue tooth. Made a fix for this.
* 2.7.7 
  - Improved docs 
* 2.7.6 
  - Added docs and hints on may places in the gui.
  - External documents marked with icon.
  - Fix problem that you had to click on the download menu item twice.
* 2.7.4
  - Hide test button
* 2.7.3
  - Fix for downloading dataserver
* 2.7.2
  - New bluetooth drivers which mainly fixes bluetooth issues
  - Web hid (web usb) fixes to make usb work in the latest chrome canary browser.
* 2.7.0
  - Public highscore for shark game
  - Fix boat model problem in android vr mode
  - Android blue tooth fixes (In the next version I do an large update the android blue tooth drivers, since it does not work stable any more on my android device.)
* 2.6.4
  - android: less often show the new version available
  - Added power curves to workout log. , curves will be visible in exports and when you choose "Show in Widgets" in the powercurve history widget
* 2.6.3
  - Export csv, set separators in options
  - Export unique file name
  - "show in widgets" bugs in history log
  - Android : Open csv exports in excel or other spreadsheet
* 2.6.2
  - android bug fixes
* 2.6.1
  - fix mobile scroll problem vr and map widget
  - fix cordova/android internet connection problem
  
* 2.6.0
  - Fix VR animation problems
  - Fix android BLE security problem
  - New initial version of shark VR game

* 2.5.3
  - Fix closing widget problem on cordova/mobile.
  - When entering vr mode, reset the rotation

* 2.5.2
  - Fix error when starting the demo replay.
  - Fix VR widget head rotation and camera movements problems

* 2.5.1
  - Power curve history widget
  - New record and replay features
    * Pause option
    * export/import a recording. (your can give your coach the file so he can analyze it using ergometer-space)
    * Record a (short) video together with all your data. The data and the video are synchronized during play back.
    * after import the history widgets shows all data in the recording
  
* 2.4.9
  - fix pace boat starting too slowly in animation

* 2.4.8
  - More race track widget animation fixes
  
* 2.4.7
  - More efficient USB communication
  - Improved warning messages
  - Fix race widget animation problem when pauzing in between

* 2.4.6
  - Improved Version management (and notify about updates)

* 2.4.5
  - Increased USB accuracy. This fixes animation problems.
  - Added record and replay widget
  - Target Android SDK 28

* 2.4.3
  - Fix broken power compare curve (also fixes the advisor)

* 2.4.2
  - improve usb stability
  
* 2.4.1
  - Added USB support for PM3-5
  - Bluetooth connection fixes
  - Fix that you could not return from the options help page

* 2.2.1
  - Added USB support for PM3-5
  - Bluetooth connection fixes
  - Fix that you could not return from the options help page

* 2.2.0:
  - 3D and Vr rowing
  - Animation in the map and race widgets are more smooth

* 2.1.0
  - improve usb stability CSV export from single workout
  - Pace boat , flat work out using split time and using an exact stored work out. 
    This will allow you to race against your selves or use an race of some one else (using the workout import feature)

* 2.0.12
  - Added workout log

* 2.0.11
  - Fixed problem when loading plugin from file.
