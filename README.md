# agariosharp
Agar.io c# interface

This is a c# port of https://github.com/pulviscriptor/agario-client <br/>

I tried to stay as minimal as possible. <br/>

Look at AgarioGUI for example of how to use. <br/>

Clone websocket-sharp master branch and build it <br/>
Clone agariosharp <br/>
(The nuget version has a bug that prevents websockets to work on port 443 that agar.io sometimes use) <br/>
reference the websocket-sharp library you just built <br/>
Set AgarioGUI as startup project then build And run <br/>

Not all functionnalities are yet implemented but the game is functionnal.

It is for Mono (linux) as it uses Gtk. Although could easily be adapted to windows.


It connects to the official servers.

It is intended for botting purposes. 

But you can play : <br/>
mouse to naviguate <br/>
f to spectate <br/>
s to spawn <br/>
space to split <br/>
w to eject <br/>

I won't probably update the code frequently <br/>

Happy botting <br/>
