# 🕹 Sonny's TF2 config

My personal `Team Fortress 2` configuration. I wrote this config between 2012 - 2015, when I played the game competitively at the [European TF2 League](https://etf2l.org). The config is primarily intended for competitive play and I've used in `6v6` & `9v9` competitive tournaments. The majority of features are also useful for casual play. Do **not** expect any significant performance gains from this config, although it contains some optimizations. You can include your own graphical configurations and extend it.

> 🚧 This config doesn't support the new x64 bit TF2 client. It was developed, tested and used with the old x32 bit one **more than 10 years ago**.

---

## 🧩 Features

- Null-movement
- Callouts (🚧 WIP)
- Crouch Jump (CTap)
  - 💡 You'll need explicitly execute this script in your `soldier.cfg` file. In addition to that you'll have to rebind `MOUSE2` in every other class config
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
- Offline Jumping (🚧 WIP)
  - Provide 3 teleports (save/tp)
  - Health Regen
- Numpad class switcher

### Custom Binds:

| Key | Action |
|-----|--------|
|  `F2 ` |   Reloads the config     |
|  `/`   |   Toggles your viewmodels on/off     |
|  `F11` |   Checks if wait is enabled on the server     |
|  `F1` (Hold) |   All in one fix it button     |
|  `MOUSE4` (Hold) + `MWHEELUP` / `MWHEELDOWN` |   Viewmodel FOV switcher     |
|  `ALT` (Hold) + `6-0` (Non-numpad keys) |  switch through the 4 default loadout slots + a hidden 5th one   |
|  `END` |   Suicide    |
|  `TAB` |   Scoreboard, NET Graph, RED+BLU respawn times (when tournament mode is enabled) & map time left    |
|  `Numpad 1-9` |   Switches between the nine classes  |
|  `Numpad ENTER` |   1st Press: Turns OFF Text Chat. 2nd Press: Turns OFF Voice Chat. 3rd Press: Toggles ON Text And Voice Chat     |
|  `Pause` |   Pauses the game (does not work on all keyboards)     |

## 🔧 Installation

1. Download the master `ZIP` file or clone the repository.
2. Copy the contents of the artifact in the following directory: `\steamapps\common\Team Fortress 2\tf\custom\my_custom_files\cfg\`
3. 💡 **Optional:** Make the files & directories READ-ONLY to prevent any changes in the settings of this config.
4. Paste surfaceproperties.txt in `\custom\my_custom_files\scripts`.

❗ If you have any other configs created with `clugu` or some other config generator it is recommended that you remove all `*.cfg` files and reset all `cvars` via `steam://runsafe/440`

## 🛩 Launch options

`-novid -high -console -w XXXX -h XXXX -dxlevel XX`

💡 If you want the most of your machine use `-dxlevel 81` otherwise use `-dxlevel 95`.

💭Where `XXXX` insert a resolution 1x/2x/3x lower than your native one, it can help performance.
