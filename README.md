# 🕹 Sonny's TF2 config

My personal `Team Fortress 2` configuration. Initially I wrote this config 9 years ago, when I played the game competitively. Then it was mostly based on performance & gameplay improvements. I've decided to rewerite the config for `2023`, but this time focusing only gameplay improvements. Most of the features, part of this config, I've used in `6v6` & `9v9` competitive environments. I also find them useful for casual play as well. Do not expect any significant performance gains
from this config. You can include your own graphical configurations and extend this config.

---

## 🧩 Features

- Null-movement
- Callouts
- Crouch Jump (CTap)
- Auto record tournament demos
- Disabled tutorials
- Custom viewmodel FOV switcher
  - Hold `MOUSE4` and move the scroll up or down in order to increase/decrease viewmodel FOV
- Loadout switcher
  - Hold `ALT+6-9` to switch through the 4 default loadout slots + a hidden 5th one
- Custom server admin mode
  - Up to as many servers as you wish. list of configs and maps changable on the moment with a simple command such as: `blands` instead of 2x `rcon changelevel cp_badlands` / `ecp6` instead of `!rcon exec etf2l_6v6_5cp`; open it for how to use it and more features
- Micspam loopback script
- Chat & Voice toggles
- In-game memory compactor
  - Frees up memory
- 4 different network presets
  - Chris' Bad
  - Chris' Good
  - m0re
  - Mine (Default)
- Netgraph presets
- Built in respawn timer
  - Useful in competitive to keep track of medic respawns etc, it shows everytime you hit `TAB`
- Instant `FIX` button.
  - Restarts sound, hud, heartbeat and records a temp demo
- Wait Tester (`F11`)
- Sourcemod plugin lister (listplugins)
- Offline Jumping
  - Provide 3 teleports (save/tp)
  - Health Regen
- Numpad class switcher

Custom Binds:

- `F2` = Reloads the config
- `/` = Toggles your viewmodels on/off
- `F11` = Checks if wait is enabled on the server
- Holding down `F1` = All in one fix it button
- Holding down `MOUSE4` and moving the scroll wheel up and down = Viewmodel FOV switcher
- `END` = Suicide
- `Pause` = Pauses the game (does not work on all keyboards)
- `1-9` = Switches classes on the numpad
- `Keypad ENTER` = 1st Press: Turns OFF Text Chat. 2nd Press: Turns OFF Voice Chat. 3rd Press: Toggles ON Text And Voice Chat.
- Hold `ALT+6-9` to switch through the 4 default loadout slots + a hidden 5th one.

## 🔧 Installation

Download the master ZIP file or copy RAW text of your desired config and drag and drop your .cfg file in:
"Steam\steamapps\common\Team Fortress 2\tf\custom\my_custom_files\cfg\autoexec.cfg"
Remember to rename your desired config to autoexec.cfg. Do not paste eg:autoexec_CORE.cfg

Optional: Make sure to make this file READ-ONLY to prevent any changes in the settings of this config.

Paste surfaceproperties.txt in /custom/my_custom_files/scripts.

If you have any other configs created with clugu or some other config generator it is recommended that you download the CORE
version because some of the features may not be working correctly.

## 🛩 Launch options

If you want the most of your machine use -dxlevel 81 otherwise use 95.

-novid -console -w XXXX -h XXXX -dxlevel XX
  
  > It is recommended that you remove dxlevel after the first start. It is known to cause crashes on some systems.

Where XXXX insert a resolution 1x/2x/3x lower than your native one, it helps performance a lot.

These are the launch options that I have the most success with. Feel free to add your own or refer to the config itself for more options.

