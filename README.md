# Chocolate-Doom Plus

Welcome to the official Chocolate-Doom Plus!

This project is a fork of Chocolate-Doom that aims to implement the ability to raise or decrease the static limits according to Doom+ or Doom v1.2 respectively. 

These are the static limits of Doom plus: http://prboom-plus.sourceforge.net/doom-plus.features.html

Link to the original hack: https://www.doomworld.com/idgames/utils/exe_edit/doomhack

Doom v1.2 had lower static limits than later versions, because they were raised to accomodate Doom 2 which has bigger levels. Doom v1.2 compatibility is not the main objective though, it's only to make it easy to change the limits. Some changes are documented here: https://tcrf.net/Doom_(PC,_1993)/Revisional_Differences

## How to enable the new limits from Doom Plus?

![screenshot at 2016-11-20 02 51 14](https://cloud.githubusercontent.com/assets/6194072/20461441/7b183a88-aecc-11e6-99bb-aee2bf33b2a2.png)

## How to build it by yourself on Linux:

1. Download the source code from the GitHub repository.
2. Make sure all of this is installed: `gcc make automake libsdl1.2-dev libsdl-net1.2-dev libsdl-mixer1.2-dev python-imaging`
3. Go into the extracted folder and execute `./autogen.sh`. Some new files will appear, you shouldn't have to type `./configure`.
4. Then you can run `make`, which will build the binaries.
5. To remove the debugging symbols from the binaries, you can use `strip src/chocolate-*`.
