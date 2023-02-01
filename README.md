<picture>
  <img alt="FPP Logo" src="https://falconchristmas.github.io/images/fpp-logo.gif">
</picture>  

# FPP - Falcon Player

The Falcon Player (FPP) is an application used for managing and controlling animated light shows like you see on [The Great Christmas Light Fight](https://abc.com/shows/the-great-christmas-light-fight). Many of the competitors and winners use FPP in their shows. 

This program has two basic components to it and these components are the scheduler and the controller, however FPP has many more features and functionality beyond just animated light shows. It is used for landscape lighting and ambience lighting in both the inside out outside of the home and many more uses where someone wants to control individually addressable LEDs.

FPP is a lightweight, optimized, feature-rich sequence player and controller interface designed to run on low-cost Single Board Computers (SBC). It was originally created to run on the $35 Raspberry Pi, hence the middle 'P' in the short name but now the FPP supports many more systems. The FPP shorthand is still used but it is now just called Falcon Player.

It is still mostly commonly used on a Raspberry Pi (Pi Zero, Pi Zero W, Pi Zero W2, Pi 2, Pi 3, Pi 4) but can also be used on  a Beagle Bone (Black, Green, Pocket).

The scheduler component can be used to automate your light show to include scheduling around your local sunrise and sunset to avoid having to change your schedule due to the changes in the seasons. It supports multiple playlists, not only per day, but you could have several playlists scheduled to play in the same day. The scheduler supports interaction through API calls or through GPIO/MQTT events.

The controller component can be used to control hundreds of thousands of individually addressable LEDs per controller (ws28xx, etc) and also supports playing media files such as videos or pictures through HDMI or to overlay on a light model. FPP can also be used with various capes to control LED panels such as P10, P5, etc. and supports event processing for outputting dynamic data to the panels.

FPP aims to be controller agnostic, it can communicate using E1.31,DDP, DMX, Pixelnet, and Renard protocols to hardware from multiple hardware vendors. 

Download the latest version from [FPP Github Repository](https://github.com/FalconChristmas/fpp/releases)

FPP has way more functionality than what can be highlighted here.

## Where to find information
- [FPP Manual](https://falconchristmas.github.io/FPP_Manual.pdf)
- [Development Documentation in Github](https://github.com/FalconChristmas/fpp/blob/master/docs/README.md)
- [Wiki](http://falconchristmas.com/wiki/index.php/Main_Page)

## Still have a question? Here are some links to some helpful resources.
- [Falcon Player forums](http://falconchristmas.com/forum/index.php/board,8.0.html)
- [FPP Group on Facebook](https://www.facebook.com/groups/1554782254796752)
- [xLights Zoom Room](https://xlights.org/download/1944/)


