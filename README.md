# Introduction

Ergometer rowing web app for concept 2

Uses bluetooth or a data-server to connect your phone to the concept 2 ergometer with a PM5. (A performance monitor with a lower number does not support bluetooth, it is possible to upgrade the performance monitor)

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
- 3d and VR using a headset

[Website](https://ergometer-space.org/)

# Platform compatibility

## connect using bluetooth to a PM5

| App                   |Mac OS X | Windows      | Android | iOS         |
|-----------------------|---------|--------------|---------|-------------|
|Ergometer space web    |Yes (*4) | Yes          | >=6 (*1)|             | 
|Ergometer space native |Yes      | Yes          | >=5.1   | No          |


- (*1) Not yet tested, should work
- (*2) Code is compiling but need a better bluetooth solution
- (*4) Chrome browser supports web bluetooth. For windows not yet but this will come in the future.

## connect using the data server to an older PM

The data server can connect to the performance monitor using blue tooth 
In all versions of ergometer space you can connect to an ergometer data server running in on the network.
The data server runs only on:

- Windows (all versions)
- Mac OS X less or equal to 10.10 (concept 2 api does not work any more on new mac os X) 

Apart from the usefull functionality is the website also a test bed for new web technologies.

## Topics

[Writing plugins](PLUGINS.md)

[Creating an map with a route](Maps/README.md)

[Connecting to the ergometer](connection.md)

[Technical background](TECHNICAL.md)

