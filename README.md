
[website](https://ergometer-space.org/)

# Browser compatibility

* Chrome
  - The only browser which I have really tested.
  - On unix and mac it should be possible to connect to a PM5 using bluetooth
* Firefox
* Internet explorer
  - Web sockets to other domains are by default not allowed. You need to add the website to the local intranet websites to make it work.
* Safari
  - Errors missing

Apart from the usefull functionality is the website also a test bed for new web technologies.

[Connecting to the ergometer](connection.md)

_Nerd mode on_

# Technical background

## Server

* Server written in Node.js which has very hight performance and had good deployment in the cloud
 (frameworks express, socket.io, jake)
* Type script is used generate the javascript. Type scripts makes the code more robust and increases the 
* Server architecture scales to multiple servers. The servers are deployed in the cloud using free services.
In total there are 4 servers.
  * data server which serves the data (html,css,javascript)
  * manager which functions as a dictionary where the rooms are
  * 2 room servers which manage each 3 rooms. This can scale to many servers which are spread over the internet. One room can only run on one server.
## Web app
* Html 5 features
  * websockets to your local driver
  * websockets to the server
  * app cache. Which makes it possible to use all the ergometer controls without internet connection.
  * Most data is stored in the local storage of the client which reduces the server load and ensures that private data is kept private
  * animation frames for efficient animation
  * inline interactive svg
  * html 5 canvas drawing
* There is a 3d model for the animations. This will make it possible to later use real web 3d
* NTP time synchronization
## Data server
* Written in C++ and build on top of boost. 
* All code should be portable to other systems including embedded systems
* The data server is a web socket server which can server multiple ergometers. Multiple clients can also connect to one ergometer 
* ergometer scores are protected by a hash which is checked on the server. This way you can not tamper with the scores.
* You can write javascript/typescript plugins (). The editor knows the structure of the application and the libraries can can provide syntax checks and code completion.
* This version does not work any more on OS X El Capitan
  I can only fix this problem when concept2 releases a new version. 
  As alternative you can use chrome as browser and connect using blue tooth to a PM5.

## Writing plugins:
[Plugins](PLUGINS.md)
