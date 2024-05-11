---
layout: pageContent
title: Technical background
nav-menu: false
show_tile: false
permalink: TECHNICAL.html
---

# Internal ergometer driver

The source code of the ergometer driver which is used by ergometer-space is located in another repository:
  https://github.com/tijmenvangulik/ErgometerJS

Some plugin examples are open source, The rest of the software is not open source.

# Server

* Server written in Node.js which has very hight performance and had good deployment in the cloud
 (frameworks express, socket.io, jake)
* Type script is used generate the javascript. Type scripts makes the code more robust and increases the 
* Server architecture scales to multiple servers. The servers are deployed in the cloud using free services.
In total there are 4 servers.
  * data server which serves the data (html,css,javascript)
  * manager which functions as a dictionary where the rooms are
  * 2 room servers which manage each 3 rooms. This can scale to many servers which are spread over the internet. One room can only run on one server.

# Web app

* Html 5 features
  * websockets to your local driver
  * websockets to the server
  * web rtc peer to peer connection for audio and data
  * Most data is stored in the local storage of the client which reduces the server load and ensures that private data is kept private
  * animation frames for efficient animation
  * inline interactive svg
  * html 5 canvas drawing
* There is a 3d model for the animations. This will make it possible to later use real web 3d
* NTP time synchronization

# Data server (deprecated)

* Written in C++ and build on top of boost. 
* All code should be portable to other systems including embedded systems
* The data server is a web socket server which can server multiple ergometers. Multiple clients can also connect to one ergometer 
* ergometer scores are protected by a hash which is checked on the server. This way you can not tamper with the scores.
* You can write javascript/typescript plugins (). The editor knows the structure of the application and the libraries can can provide syntax checks and code completion.
* This version does not work any more on OS X El Capitan
  I can only fix this problem when concept2 releases a new version. 
  As alternative you can use chrome as browser and connect using blue tooth to a PM5.


