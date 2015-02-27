Sonny's TF2 config
===========

Please scroll to the bottom on how to install it and make a back up of your CFG folder.
You can always refer to the config by opening it in a text editor like notepad++. There is described almost anything you will need and how it works.

The config is written to take the most advantage out of my PC with a moderate graphical sacrifice, it
consists of multiple layers and a great deal of features. It may be unstable on some machines and I can't guarantee that you are not going to get crashes and stability issues on CPU's with less than 4 cores. The config is based around in-game customizability, proper use of hardware resources, AIO packaging and gaining advantage over the enemy. 

Recommended for competitive players aswell as players getting into TF2. 

Here are some of the features:

- Custom server admin mode (Up to as many servers as you wish; list of configs and maps changable on the moment with a simple command such as: blands instead of 2x rcon changelevel cp_badlands / ecp6 instead of !rcon exec etf2l_6v6_5cp; open it for how to use it and more features).
- In-game memory compactor (Frees up memory; it frees up memory everytime when you move if there is memory to be cleared.)
- Chat & Voice toggle (ON/OFF)
- Loadout switcher (Hold ALT+6-9 to switch through the 4 default loadout slots + a hidden 5th one.)
- 3 different network presets (Chris BAD&GOOD; m0re's and my personal network settings that can be used straight in-game by typing a simple alias in the console.)
- Netgraph presets.
- Built in respawn timer. (Very useful in competitive to keep track of medic respawns etc; it shows everytime you hit TAB)
- Instant FIX button. (Restarts sound, hud; heartbeat and records a temp demo.)
- Null-movement.
- Wait Tester (F11).
- Sourcemod plugin lister (cmd:listplugins)
- Custom Viewmodel FOV switcher (Hold MOUSE4 and move the scroll up or down in order to increase/decrease VMFOV; very smooth, useful on the go)
- Security settings (Inspired by Rhapsody's TF2 Config)


Custom Binds:

- "F2" = Reloads the config.
- "/" = Toggles your viewmodels on/off. 
- "F11" = Checks if wait is enabled on the server.
- Holding down "F1" = All in one fix it button.
- Holding down "Mouse4" and moving the scroll wheel up and down = Viewmodel FOV switcher.
- "END" = Suicide.
- "Pause" = Pauses the game(Does not work on all keyboards).
- "1-9" = Switches classes on the numpad.
- "Keypad ENTER" = 1st Press: Turns OFF Text Chat. 2nd Press: Turns OFF Voice Chat. 3rd Press: Toggles ON Text And Voice Chat.
- Hold "ALT+6-9" to switch through the 4 default loadout slots + a hidden 5th one.

Startup time may be slow so don't worry the game is preloading its necessary files. 
I am looking for general feedback and hopefully, if there is enough interest I will be making more changes and improvements.

Here is a benchmark:
- CPU: Intel Core 2 Quad Q6600 overclocked  to 2.80 GHz; standart 2 fan cooling
- GPU: Nvidia GeForce GTS250 DK Edition 1 GB DDR3 
- RAM: 2x2 A-Data (Unknown MhZ)
- HDD: Recycled 500 GB Hitachi drive
- OS: Win 7 Ultimate x64

2639 frames 38.561 seconds 78.44 fps (14.61 ms/f) 2.761 fps variability.
Using meb's benchmark 1 demo with 341.44 Nvidia drivers; lo: -novid -console  -w 1280 -h 1024.

I get constant 150 fps in competitive servers almost everywhere with small drops on some middles (~138-144 fps), but the game doesn't choke on itself.
In valve pubs I get around ~120-150 fps with no serious drops.

The REWORKED version.
=========

This is a modification of the main config that removes some useless binds and replaces them with console commands(aliases).
There are no major features removed and there is no performance loss. For now this has its own version in the near future it may be changed in the main config.

Installation
=========

Download the master ZIP file or copy RAW text of your desired config and drag and drop your .cfg file in:
"Steam\steamapps\common\Team Fortress 2\tf\custom\my_custom_files\cfg\autoexec.cfg"
Optional: Make sure to make this file READ-ONLY to prevent any changes in the settings of this config.
Paste surfaceproperties.txt in /custom/my_custom_files/scripts.

If you have any other configs created with clugu or some other config generator it is recommended that you download the REWORKED version because some of the features may not be working correctly.

Launch options
=========

If you want the most of your machine use -dxlevel 81 otherwise use 95.
-novid -console  -w XXXX -h XXXX
Where XXXX insert a resolution 1x/2x/3x lower than your native one, it helps performance a lot.
These are the launch options that I have the most success with. Feel free to add your own or refer to the config itself for more options.

