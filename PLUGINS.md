---
layout: pageContent
title: Plugins
nav-menu: false
show_tile: false
permalink: PLUGINS.html
---

# Development environment

Plugins can be developed within the application. The plugins are written in typescript/javascript. 
The editor knows the definitions of the application api and the used libraries. This way it can
give you full code completion support while editing. Saving the data will directly result into a 
update source. It is best to write and debug code in chrome.

A view examples plugins with one or more widgets can be installed from the "add from web" option.

## Publish your plugin

The plugins are stored on github. You can fork te repository an push your own plugin

  https://github.com/tijmenvangulik/Ergometerspace/tree/master/data/plugins

You can also send it to me using mail: tijmen@vangulik.org

## Monaco editor

To see what is possible open a popup menu. For more info on the editor:

[https://microsoft.github.io/monaco-editor]

To save ctrl S or mac command S. The widgets loaded by the plugin will be refreshed. When you get an
typescript error during the save the code will not be saved.

All code is stored in your local storage. Clearing te browser history can remove all your code. It is best to export your code once in a while.

# Used frameworks

| name | version | note | url |
|------|---------|------|-----|
| jquery | 1.8.3 | | |
| jquery ui | 1.9.2 | | | Only for animation
| highcharts | | gauge and charts| |
| socket.io|  | for server communcation | |
| bootstrap | 3.3.7 | | |
| FileSaver | | | |
| require | | dynamic loading extra scripts| |
| Font awesome |  | Icons | |
| jquery.ui.theme.font-awesome | | Better icons for jquery ui based on font awesome | |
| typescript | 1.4.2 | | [http://www.typescriptlang.org] (The editor is based on this version, for my own code I use 1.6.2 but I keep it backwards compatible with 1.4.2) |
| Validator |
| jasny-bootstrap  |
| openlayer |
| bootstrap-slider |
| bootstrap-select |
| bootstrap-dialog |
| Monaco editor |
| gridstack |

# Java script / type script

Type script reference [http://www.typescriptlang.org]

Included typescript (javascript) definitions:

All API definitions are stored here:

[http://www.vangulik.org/Ergometer/typescripts/]

| Name | link |
|------|------|
| The application API | [http://www.vangulik.org/Ergometer/typescripts/ErgometerApp.d.ts] |
| Highcharts | [http://www.vangulik.org/Ergometer/typescripts/highcharts.d.ts] |
| jquery | [http://www.vangulik.org/Ergometer/typescripts/jquery.d.ts] |
| jquery-ui | [http://www.vangulik.org/Ergometer/typescripts/jqueryui.d.ts] |
| Require | [http://www.vangulik.org/Ergometer/typescripts/require.d.ts] |
| Save as | [http://www.vangulik.org/Ergometer/typescripts/SaveAs.d.ts] |

All definitions can be viewed in the First Application API link. There are some important object which are
documented in the following table:

| object | Description |
|--------|-------------|
| app | The global application object |
| app.dashboard  The main dashboard controller object |
| pm3.monitor | the connection to the ergometer | 
| ergometerServerClient.connection | connection to the server | 
| app.plugins | plugin manager|
| newsTickers.infoTicker | shows news | 
| newsTickers.statusTicker | shows none blocking errors and info messages|


## Debugging
It is best to use chrome for debugging. The internal scripts are shown in the source group named (no domain)
The name of your plugin will be used as name of the source. You should open an fresh debugger window after you update the script. If you do not do this you will not see your recent changes.

Settings break points in the debugger of the browser does not always work. The workaround is to add the debugger command to a line to stop it. You can add these break points by hand or your can click in the gutter margin. The break points only work if update the script and start a fresh new browser debugger.

You do not need to connect your computer to the ergometer for every test run. On the toolbar there is a button to play test data. Be default it plays back a recording of 100m. You can press the record button to record your own data. 

## writing widgets
There are a number of examples on writing widgets. All these widgets inherit from the ErgometerWidget or an higher class. It is possible you want to write a widget which is based on an existing div in the html page or you want to dynamically create the div. The ErgometerWidget always creates its own div. The  ErgometerWidget is defined the following way:

```javascript
         class ErgometerWidget  extends dashboard.Widget {
		public initControl() {
			//make a new div within the main control (by default the widgets uses an existing)
			this.controller.$mainControl.append(
				"<div id='"+this.name+"'' ></div>")
			super.initControl();

		}
	}
```

### Widget inheritance
| class | description |
|-------|-------------|
| dashboard.Widget | base widget class |
| -> ergometerWidgets.ErgometerWidget |base widget class for all ergometer widgets |
| -> -> ergometerWidgets.CanvasWidget |For all widgets which show a animation on a canvas | 
| -> -> ergometerWidgets.HighChartWidget | For chart widgets | 
| -> -> -> ergometerWidgets.GaugeWidget | for gauge widgets|
| -> -> ergometerWidgets.ValueWidget | for displaying one value |
| -> -> -> ergometerWidgets.StrokeValueWidget | for displaying a stroke value | 
| -> -> -> ergometerWidgets.TrainingValueWidget | for displaying training value | 

## Utility functions

The main application object contains some useful routines
  
```javascript
class ErgometerApp {
  //show an error on top of the page which the user has to click away
  showTopError(messageText : string)
  
  //show an error in the news ticker
  showError(text : string)
  
  //ask for an confirmation with yes, no as ansers
  confirmYesNo(text : string,yesAnswer? : () =>void,noAnswer? : () =>void  ) 

  //ask for a confirm message
  interface ConfirmButtons {
    [name: string] : ()=>void;
 }
 confirm(text : string,buttons : ConfirmButtons    )
}
var app : ErgometerApp;

```

Some handy utility functions

```javascript
  module utilities {
    //format to a time value
    function formatTimeValue(value: number, digits: number): string;
    //format a relative date to a time
    function formatRelativeTime(date: Date): string;
    //check if an value is a number
    function isNumber(n): bool;
    //html 5 time out routine needed for animations
    function requestTimeout(fn: any, delay: number);
    //draw an ellipse on a canvas
    function ellipse(context: CanvasRenderingContext2D, cx, cy, rx, ry: number): void;
}
```

Widgets subscribe them selves to ergometer data events to receive information. This is done on the visible changed method. This way a widget only receives data when it is visible. Ergometer Events are located in the pm3.monitor.pubsubs object. 

```javascript
 	     public visibleChanged() {
	    		    	
	    	if (this.visible) {
	    		pm3.monitor.pubsubs.subStrokeDataUpdate(this, this.strokeDataUpdate);
	    		pm3.monitor.pubsubs.subTrainingDataUpdate(this, this.trainingDataUpdate); 
	    		this.paint();
	    	}
	    	else { 
	    		pm3.monitor.pubsubs.unsubStrokeDataUpdate(this,this.strokeDataUpdate);
	    		pm3.monitor.pubsubs.unsubTrainingDataUpdate(this,this.trainingDataUpdate); 
	    	}
	    	super.visibleChanged();
	    }
```

| Event | Description |
|-------|-------------|
| subStrokeDataUpdate | Send at the end of the stroke with stroke data |
| subPowerCurveUpdate | Send the power curve at the end of a stroke |
| subTrainingDataUpdate | when the training changes this event will be called|
| subNewStrokePhase | Change of stroke phase, Idle,Catch/drive/Dwell/Recovery | 
| subLiveForceUpdate | When force curve data is available it is directly send. This costs extra performance|
| subError | monitor error happened|
| subStarted | monitor start |
| subStopped | monitor stopped |
| subHistoryUpdate | history information added |
