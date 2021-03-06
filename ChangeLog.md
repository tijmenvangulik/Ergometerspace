---
layout: pageContent
title: Change log
nav-menu: true
show_tile: true
---
* 3.7.11
  - Start vr 3d widget rotating in race mode
  - Show essential values in vr mode dashboard
  - Fix crash when importing workout info
  - Android: change default export dir in the options (this feature will be made more user friendly in later versions)
* 3.7.10
  - Added sound effects to 3d/vr widget
  - Fix problem of shark game which was not loaded corrected after an refresh 
* 3.7.9
  - Added fog effect
  - Performance optimizations in 3d widget
* 3.7.8
  - Web XR support for vr devices
  - Fix floor of 3d boat which started flashing after some time
* 3.7.6
  - More info on for how to use Vr mode when starting vr.
* 3.7.5
  - VR now works in iOS
* 3.7.4
  - Fixes for 3d widget icons
  - VR now works in the iOS app
* 3.7.3 (web only)
  - Small user interface optimization.
* 3.7.2
  - Small user interface optimizations.
* 3.7.1
  - Improved visibility and usability of widget buttons in edit mode
* 3.7.0
  - New font and icons
* 3.6.23
  - Improved switch to widget edit mode
* 3.6.22
  - fix open button which was not always fully visible
* 3.6.21
  - Allow hide/show toolbar
  - Improved mobile tooltips
  - Improved loading animation and added micro animation for the logo
* 3.6.20 (web only update)
  - Update typescript
  - Fix plugin load bug , showing old typescript
  - Fix highcharts demo plugin example
* 3.6.16 (web only update)
  - Ergometer space can now be used offline in chromium bases browsers You can also install the website as an app. [Information on how to install](https://medium.com/progressivewebapps/how-to-install-a-pwa-to-your-device-68a8d37fadc1)
* 3.6.14
  - Fix usb communication problem for newer PM5 devices (only fails with some hardware combinations)
* 3.6.12
  - Fix blue tooth connection problem
  - IOS fixes
* 3.6.11
  - Connection settings tabs now look better on small screens
  - New icon android
  - Simplified the downloads and the connection types by removing deprecated features (native desktop app && data server)
* 3.6.10
  - Fix scrolling issues in widget edit mode
  - Fix scroll to top problem when clicking on a menu item
  - Fix scroll problem in ios
  - App now available in the apple app store
* 3.6.9
  - Better Ios support (native ios version available in test flight, you can request an invitation to test it)
  - Improved colors and visibility power curve and history widget
  - Heart rate zones, active zone now visible
  - Small textual changes
  - Easier to select widgets on mobile phones
* 3.6.8 (web only)
  - Improved blue tooth connection (especially for android).
  - Fix iOS close button widget wrongly positioned
  - Fix that some settings where not saved
* 3.6.7
  - Fix connection type was not always filled in options
* 3.6.6
  - Layout changes
  - Removed confusing debug drop down in power charts
  - Minor performance enhancements
* 3.6.5
  - Restructure options dialog
  - Quick feedback option
* 3.6.4
  - Small hot fix on new enter room dialog
* 3.6.3
  - Reorganized the main menu. It is now more mobile friendly.
  - Room login is now moved to a new more mobile friendly dialog .
  - Language selection is moved to the options
  - Fixed problem with not visible help buttons in widget arrange mode
  - Easier scrolling in widget arrange mode on mobile phones.
* 3.6.2
  - Optimized race track and value widgets
    - More options (Relevance/Alphabetically/Do not sort)
    - Show relative position option
    - Scaling and size fixes
    - Better performance
    - Show column borders race values widget
  - Vr widgets now sorts rowers alphabetically (prevents track switches during racing)
* 3.6.1
  - When the team captain exits the room/team the system now chooses a new team captain and the race continues with only a short interruption. This will only work correctly when all team members use at least version 3.6.1.
  - Fixed login link captain assignment problem when using multiple teams
* 3.6.0
  - Login links. This function will help you to organize a race with many rowers. You can create a link to let users directly login into a room and join a team. The link can be copy pasted into a mail which you send to the rowers. It is also possible to include a prepared dashboard in the link.
* 3.5.3
  - Improved layout of history settings dialog
  - Fix bug that the map widget lost the zoom factor when the dialog is opened/closed after an refresh
  - The row together race/race values/map/vr widgets stopped working when another row together widget was closed. This is a breaking changes for the plugins which are using events.
  - Android: Removed elastic bounce (showing the hidden menu)
  - Android: fix white border in dialog header
* 3.5.2
  - New style menu and toolbar
  - Fixed half visible widget close icon on android
  - Improved style race widget
  - Improved performance of the race widgets (should use less energy)
  - More help full error messages for team rowing
* 3.5.1
  - race track widget:
    - More smooth relative position animation
    - Fixed wrong text formatting of distance and warning 
    - Improved styling
  - New demo recording
* 3.5.0
  - Better connectivity for Team rowing. In the previous versions some users could not connect due to network limitations. (especially mobile networks) This is now fixed. There are a view limitations:
    - All the rowers must use the latest version 3.5.0
    - When your network does not support direct connections the communication goes via the central server. This can sometimes result in a bit slower updates. 
    - Audio is only supported for users which are directly connected.
* 3.4.9
  - The shark starts at a larger distance. This make it easier to start with the shark game.
* 3.4.8 (android only)
  - fix usb connection problem which som times happens if you connect for the first time
* 3.4.7 (android only)
  - Fix connection problem for android 9 and 10.
  - upgrade to android api level 29
* 3.4.6
  - Fix wrong android build
* 3.4.5
  - New documentation web site
  - New introduction page
  - Proved demo recording
* 3.4.4
  - Extra option to work around limited blue tooth hardware.  Use this if you have blue tooth connection problems.This is sometimes the case when using cheaper or older phones.
  - For android 10 added extra permissions for blue tooth
* 3.4.3
  - Fix double power curves (for newer concept2 firmware)
  - Fix shark game does not restart
  - Fix shark game flashing high scores while rowing
  - Hide App reload menu item for android (because it breaks the blue tooth)
* 3.4.2
  - You can now connect to an usb in chromium based browers 
* 3.4.1
  - Fix broken functionality when heart rate monitor was not connected
* 3.4.0
  - Widget which shows your heart rate as percentage of the  max rate. (you need to set the max heart rate in the options)
  - Heart rate zone widget with configurable zones.
  - Performance improvement setting back history data.
* 3.3.0
  - Connect to a blue tooth heart rate device or include the heart rate data from the concept2 performance monitor.
* 3.2.0
  - Value widgets have now mini spark lines to quickly see the trend. (you can switch is off in the widget options)
  - Some value widgets have a mini pie chart to see the progress  (you can switch is off in the widget options)
  - The row together values widgets also has spark lines and pie charts.  
  - The row together values widgets options are moved to the options which is only visible in widget edit mode.
  - Improved version message
  - Improved performance row together and battery usage when using blue tooth
* 3.1.4
  - Added recovery percentage (recovery time / total stroke time) *100%
  - History widget Leave out 0 y values (Gives better results not using start y on 0)
  - History widget show more horizontal lines
  - Fix power curve history was correctly set back when viewing history for a second time
  - Fix power curve history reset when start rowing after viewing an history
* 3.1.1
  - Backup and restore function
  - All rooms are now by default team rooms. It is still possible to create backwards compatible private rooms
  - Desktop apps: Added link to download when new version is shown
* 3.1.0
  -  Support for fixed time work out. (race widget do not support this)
  -  Give a warning when an unsupported type is used
* 3.0.12
  - Renamed widget "Race values" to "Values of rowers" because it can be used for more than just a race
  - Blue tooth did not show the correct power value (USB worked correctly)
  - Improved description of training/workout
* 3.0.11
  - Power percentage value widget. Show current power as % of the max power (The max power can be configured in the options)
  - Race values widget. Show power and power percentage of other rowers. (All rowers will need the latest version)
* 3.0.10
  - Allow scrolling in Map widget for desktop (not mobile, because it will block scrolling down the page)  
  - Undefined was shown in the work out log
  - For readability values are display bold and labels normal
  - Allow change font size of values in widget modify mode.
  - Race values widget: show as table or cards.
* 3.0.8
  - Fix exit team room problem
* 3.0.7
  - Better logging to make fixing problems easier
* 3.0.6
  - More team room fixes
* 3.0.5
  - Hot fix: The 3.0.4 broke the audio in the old rooms, now both rooms work
* 3.0.4
  - Fix disconnect problems when audio is switched on or off
  - Reconnect button in the teams dialog
* 3.0.3
  - Show other rowers in team dialog (renamed teams menu item for this)
  - Make connecting to team rooms more robust
* 3.0.2
  - Improved team animation in race widget
  - Chat/speak to own team only option
  - When rowing in a team , you can only share the curve with your team
  - When activating audio microphone in is by default muted and fixed problem that it was not muted when a user logged in at later time.
  - For team rooms: Give more insight when users can not connect to each other. (error handling and connection state in the team dialog) Also made some connection stability improvements. (Please contact me if users could not connect and make screen shots of the error messages, Keep in mind that the team feature is still experimental)
* 3.0.0
  - Added Experimental team rower room which supports rowing in teams and watching the race as observer. The feature is also available for private rooms.
* 2.9.4
  - fix problem that training data is not always up to date after joining room in the new peer to peer rooms
* 2.9.3
  - race widgets now shows other rowers rowing when you do not have a active training.
* 2.9.2
   - Added peer to peer experimental public and private rooms. These rooms reduce the delay between updates and give a better rowing experience. 
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
  - Fix for downloading data server
* 2.7.2
  - New bluetooth drivers which mainly fixes bluetooth issues
  - Web hid (web usb) fixes to make usb work in the latest chrome canary browser.
* 2.7.0
  - Public high score for shark game
  - Fix boat model problem in android vr mode
  - Android blue tooth fixes (In the next version I do an large update the android blue tooth drivers, since it does not work stable any more on my android device.)
* 2.6.4
  - android: less often show the new version available
  - Added power curves to workout log. , curves will be visible in exports and when you choose "Show in Widgets" in the power curve history widget
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
  - Fix race widget animation problem when pausing in between

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

