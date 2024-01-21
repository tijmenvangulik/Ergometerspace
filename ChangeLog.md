---
layout: pageContent
title: Change log
nav-menu: true
show_tile: true
--- 
* 5.1.0
  - show power curve advice in workout log
  - improved advice text
  - Show more smooth power curves in the workout log
  - Analytics template dashboard
  - Web: show warning when storage is 80% full
  - Allow adding powercurves to the workout log in the settings
  - Show relative distance while rowing in race widget and show the best with a crown
* 5.0.1
   - You can now open 3 workout history charts at the same time with different colors 
   - Small bug fix backup and restore for mobile devices
* 5.0.0
   - Offset in map widget so you can start where you left the previous time
   - Layout improvements
   - Allow remove stroke data or power curves
   - Fix backup restore compatibility problem
* 4.14.1
  - Small fix to prevent safari crash
* 4.14.0
  - Use new storage for web so local storage limit of 5mb is not a problem any more
  - Android and ios use native storage without memory limit
  - Fix bug that the settings of the settings dialog where not restored with a backup restore action
  - Bug fixes usb support android
  - Changed android bluetooth permissions android play store
* 4.12.3
  - Allow access more web storage
* 4.12.2
  - Fix power chart
* 4.12.1
  - Bug fix initial load vr widget (web only)
* 4.12.1
* 4.12.0
  - Fix wrong value heart rate average
  - Improved power and calories statistics
  - More fields in csv export
  - stroke count value widget
  - Statistics : calories and drag factor
  - Do not crash when storage is full
* 4.11.1
  - Improved performance app loading
  - Removed  y axis chart title chart when none 
* 4.11.0
  - Show dummy gray charts and values when there is no value
  - Make more space for the iphone notch in horizontal mode
  - Improved visibility show toolbar icon
  - fixed wrong recovery ratio in demo 
* 4.10.1
   -  X-mas edition with neon menu icons 
* 4.10.0
   - Export to Strava (strava time is only in seconds without mili seconds, this means that the speed displayed by strava is not accurate)
   - Directly show export link after export to Concept2 or Strava
* 4.9.0
   - Easier resize bottom widgets
   - Heart rate zones are now collected even if you do not have the heart rate zone widget visible. You can view the heart rate zones in the workout log. 
   - The heart rate zone percentage configuration is moved to the settings
   - Message with an option to show the workout log directly after the workout. This can be switched of in the settings
* 4.8.2
  - fix link icon in menu
  - Recalculate seasons when season start month is changed
  - Improved connection text for iOS
* 4.8.1
   - Replay with heart rate and correct heart rate zone in the log
   - Icons for menu items
   - More accurate calculation work time for power curve chart.
   - Hide bluetooth for limited hardware when not relevant
* 4.8.0
   - When heart rate zone widget is used then add the zones to the workout
   - Export zones to csv and json file
   - Fix import dialog not showing
   - Fix remove video not refreshing
   - Fix problem with ios export
* 4.7.2
   - Improved blue tooth permissions for for newer android versions
* 4.7.1
   - Fix for ble connection problem for newer android versions
* 4.7.0
   - Show power curves in workout log
   - Fix USB connection problem for newer android versions
* 4.6.0
   - Log just row in workout log when switched on in the setting
   - Improved interval workout log for blue tooth.
   - Added missing USB setting for android.
* 4.5.0
   - Workout charts have a zoom icon from where you can see a more detailed chart with a compare option
* 4.4.0
   - Option to hide connection panel for observer
   - Improved visibility of some icons and texts
   - Hide connection panel when replaying
   - Check "auto select dashboard" on  online rowing roles other than solo rower
   - Fix issue dialogs not re-opening after dashboard switch
* 4.3.1
   - Hot fix refresh dashboard switching dashboards when phone is in rotated vertical
* 4.3.0
   - Multiple dashboards (select a dashboard from the navigation bar)
   - Option to auto select dashboard on login 
* 4.2.1
   - Do not change column count in horizontal mode when pressing edit button
* 4.1.0
  - Guard against converting the dashboard to a single column when editing in a dashboard while phone is hold vertical
* 4.0.0
  - Mobile horizontal allow multiple columns
  - Multi Dashboards 
    - Choose from template
    - Import
    - Export
    - Save dashboard as template
    - Nr of columns moved to dashboard settings
* 3.11.7
  - Fix high scores not always visible in the race widget
  - Pwa could not be installed and did not update
* 3.11.6
  - Fix connection problems with the app running on a iOS device. (the fix prevents you from getting the warning and it will make a direct peer2peer connection between the devices)
* 3.11.5
  - Improved save dialog for android
* 3.11.4
  - Upload to concept2 for android and iOS
* 3.11.3 IOS release with all the new features and bug fixes (some parts did not work any more due to apple changes)
  * Parts which do not work or work partly
    - Recording video and audio
    - When you connect to other rowers in a room you can get a waring. In this case only audio will not work and the connection may be slightly slower but other that that you can you can row together. This mainly due to apple limitation where I have to make a work around for. (The only way you do not get the warning if the browser/android user connects first and apple connects later)
* 3.11.2 (web and android) 
  * for android this release upgrades from version 3.8.2 to 3.11.2
  * fix app bar for small screen size
  * Disable concept2 upload for android (you will need to use the web app for this)
  * Note: Usb might not work on all android devices, still working on this
* 3.11.1 (web only)
  * Fix peer to peer connection problem (online rowing was broken due to changes in the browser)
  * fix white line in dialog in mobile mode
  * fix training update error
* 3.11.0 (web only)
  * Work out log statistics
* 3.10.8 (web only)
  * Workout log fix selection bug in workout log (select all + delete could delete more than visible in the filter)
* 3.10.7 (web only)
  * Workout log : added season filter
  * Options : added config for the start month of a season
* 3.10.6 (web only)
  * Fix select workout problem
* 3.10.5 (web only)
  - Complete overhaul of the workout logs.
     * Multi select in the list (and allow operations on multiple work outs)
     * More relevant fields in the list
     * Search
     * New details dialog which shows more values and charts
* 3.9.2 (web only)
  - Allow upload to concept2 log (select a work out log and click on send to concept2) (only upload time, distance, timestamp and weight class, no verification codes yet. configure the weight class in the settings) 
* 3.8.17 (web only)
  - Vr widget: Option to add rower reflections (more realistic but you need a good gpu for this)
  - Vr widget City is now the default world
* 3.8.14 (web only)
  - Vr widget: 4 more AI generated worlds
* 3.8.10 (web only)
  - Use wakeLock to prevent screen lock or dimming
* 3.8.9 (web only)
  - Map widget: load from gpx file
  - Fix url check problem in login link creation
* 3.8.8 (web only)
  - Dashboard: Allow more columns for more exact placing of widgets
* 3.8.7 (web only)
  - Minimum heart rate to calculate the heart rate percentage using the karvonen. (Read de description for usage.)
* 3.8.6 (web only)
  - Race widget now support fixed time workouts 
  - Option to highlight the rower in the race widget
  - Pace boat: better support fixed time work out
* 3.8.5 (web only)
  - Fix warning which is shown when blue tooth is available
  - Added platform info to intro text
* 3.8.4 (web only)
  - Added tenth of second to split time
  - Fix wrong minutes in row together widget split time.
* 3.8.3
  - In iOS web browser the app does not start
* 3.8.2
  - Warning in dialog when no connection options
* 3.8.1
  - Small bug fixes and text changes
  - Added privacy link to about page and improved privacy info.
* 3.8.0
  - Vr/3d widget: Full screen mode
  - Vr/3d widget: Names above rowers in vr mode when more than 2 rowers
  - Vr/3d widget: finish line
  - Improved notification boxes layout
  - Vr/3d widget: Fix loosing extra rowers when switching xr mode
* 3.7.12
  - pause vr widget on first start
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

