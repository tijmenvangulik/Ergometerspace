# Introduction

Ergometer rowing web app for concept2

Uses bluetooth or a data-server to connect your phone to the concept2 ergometer with a PM5. (A performance monitor with a lower number does not support bluetooth, it is possible to upgrade the performance monitor)

Features
- Create your own dashboard with values and gauges and other widgets
-  Row together over the internet
 * See each other and projected positions
 * Publish a high score
 * Chat 
 * Traffic light
- You can load your own map with a predefined course and show your rowing position on the map.
- View your power curve and compare it with an base curve
- Make your own base curve
- View history of your race
- Row stroke advisor which bases is based on the user defined base curve.
- Get warnings when user defined stroke value limits are exceeded
- Plugins 

[Website](https://ergometer-space.org/)

# Browser compatibility

* Chrome
  - The only browser which I have really tested.
  - On unix and mac it should be possible to connect to a PM5 using web bluetooth
* Firefox
* Internet explorer
  - Web sockets to other domains are by default not allowed. You need to add the website to the local intranet websites to make it work.
* Safari

Apart from the usefull functionality is the website also a test bed for new web technologies.

## Topics

[Writing plugins](PLUGINS.md)

[Creating an map with a route](Maps/README.md)

[Connecting to the ergometer](connection.md)

[Technical background](TECHNICAL.md)
