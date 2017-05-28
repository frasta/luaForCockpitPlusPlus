# luaForCockpitPlusPlus

[Link to the PlayStore](http://google.fr)

Bored of losing your ennemie because you needed to press something in your cockpit?
Zoom in the cockpit takes too much time?

Cockpit++ for DCS could help you... the app can extend some panels from DCS onto your Android, the app extends your cockpit out of the monitor.

For now there are few panels, but the app is growing.

Available panels:
- PCA for Mirage 2000C by Razbam
- PPA for Mirage 2000C by Razbam
- RWR for F15C by Eagle Dynamic

----------- How to install the app ? ----------

1) Download the Cockpit++.lua
from here : https://github.com/frasta/luaForCockpitPlusPlus/archive/master.zip 

2) Go in C:\Users\yourUser\Saved Games\DCS\Scripts folder

3) Open the export.lua file (create it if not exist) and add the line:
local Cockpitpp=require('lfs');dofile(Cockpitpp.writedir()..'Scripts/Cockpit++.lua')

4) In the same folder, add the file Cockpit++.lua

5) Open the Cockpit++.lua and add the IP address of your Android phone (You will find it in the app, in "settings")
Trick: the LUA files must be saved before you launch DCS

6) In the app, go to Settings, add your computer's IP and the two ports which are in the Cockpit++.lua

7) Now it should work :)

8) Not working? check the previous steps and/or restart the app


Good flight sir! O7