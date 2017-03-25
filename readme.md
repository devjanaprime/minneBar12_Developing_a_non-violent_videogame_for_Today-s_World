Developing a non-violent videogame for Today's World
====================================================

by [devnari](http://devnari.com)

MinneBar12 3/25/2017 

Intro
---------
- Who are we
- What is Newt One?
- Level Play 4-5 min

Art Direction
-------------
![Models1](MO1.png)

![Models2](MO2.png)

![Colors1](Col1.png)

![Colors2](Col2.png)

![Colors3](Col3.png)

![Colors4](Col4.png)

![Colors5](Col5.png)

 
Platform/Controller support
---------------------------
 - pc/mac is easy on Unity
 - linux was an early target, but early tests were not fun
 - JavaScript for Unity demo
 - controller support/[UnCL](http://devjana.net/uncl/api)
 
 ![c0](c_supportedController.jpg)
 
 - decision to go for XBOne
 
 ![c1](c_sdk.jpg)
 
 - building for to XBOne
![c2](c_xboneBuild0.jpg)


Level Design
------------
![ld1](http://i.imgur.com/7Tycv2z.png)

![ld2](http://i.imgur.com/Eb5PyQw.png)

![ld3](http://i.imgur.com/5N15Xjq.png)

![ld4](http://i.imgur.com/9QY1C50.png)

![ld5](http://i.imgur.com/73OrrvT.png)

![ld6](LD5.png)

![ld7](LD6.png)

![ld8](LD7.png)
 
![ld9](LD8.png)

![ld10](LD9.png)

![ld11](LD10.png)

Level Music System
-------------------
- overview
![level music system](http://i.imgur.com/xkYgI2E.png)
- playable demo

Project Management/Evolution
----------------------------

Emergent Features/Adjustments
-----------------------------
- originally thought only back-forth movers would be enough

![simple mover](movers.gif)

- started using movers in creative ways in level editors

![ice platforms](manyMovers.gif)

- evoled to pathing movers

![path mover](pathMovers.gif)

- one level needs path a mover that stops at last position

- *outfits/lives/notes/coins*
- started as coins

![coins](coins.gif)

- 30/level
- became notes

![notes](notes.gif)

- 50 for an extra life

![extra life](lives.gif)

- asked "why do you have lives?" at MinneBar 2016
- observed many players stop playing when out of lives at TEDx Minne 2016
- now 50 for an outfit upgrade
- when player "dies" the respawn sound is more happy (respawn, not death)

- *Disruptors*
- started as Krystal's idea
- prototyped and iterated
- started as crystals only

![disruptor prototype](disruptors1.gif)
- evolved in a Slack convo
 
![disruptors convo](disruptors2.png)

![updated model](disruptors3.gif)
- juiced it

![juice](disruptors4.gif)
- added bubble

- *Leaderboards*
- still up from Alpha (http://devnari.com/newtOne/)
- too competitive for the game's philosophy

- *Enemies/NPCs*
- originally standard 3D platformer (jump on enemies)


Domains of Play, player interests profile
-----------------------------------------
![domains of play](newtDomains.png)

Project Management
------------------
 - mostly agile
 - stories/tasks = ticket
 - git + bitbucket 
 - Ovrlord
 - moved to monthly builds
