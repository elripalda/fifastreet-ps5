# FIFA Street for PS5

**FIFA Street (2012, Xbox 360) running natively on a jailbroken PS5**, at up to 1440p and 60 fps.

[![Get it on RecompStore](https://recompstore.com/assets/press/badge-dark.svg)](https://recompstore.com/game/PPSA92012)

> ### Built on ReStreet by SamuelitoDaVila
> This port is based on **[ReStreet](https://github.com/samuelit0davila/fifa-street-pc-port)**, SamuelitoDaVila's recompilation of FIFA Street for PC, and its game fixes. Their work is the backbone of this project: this release takes it to the PS5. Go check out and support the original project.

## What's in it
- 720p, 1440p or 2160p (experimental), FXAA, and 60 fps with even frame pacing
- PlayStation button prompts throughout the game, and a DualSense in the menus (or the Xbox originals, if you prefer)
- The game's achievements as trophies: a popup when you earn one, and your progress on the hub's Trophies page
- A hub made for the DualSense: start the game, change settings, back up your saves, play your own menu music

## What you need
- A jailbroken PS5 that runs homebrew apps from `/data/homebrew/`
- Your **own** copy of FIFA Street (2012) for Xbox 360. No game files are included.

## Install
1. Download `PPSA92012.zip` from [Releases](../../releases) and copy the `PPSA92012` folder to `/data/homebrew/` on your PS5.
2. Copy the files from your extracted disc into its `GameData` folder (the same files ReStreet keeps in its `GameData` folder on PC):

```
/data/homebrew/PPSA92012/GameData/default.xex
/data/homebrew/PPSA92012/GameData/fifadllzf.xex.dll
/data/homebrew/PPSA92012/GameData/data0.big ... data7.big (+ .bh)
/data/homebrew/PPSA92012/GameData/data/...
```

Launch it from your homebrew launcher. The hub opens first: press START GAME.

## Credits
- **[SamuelitoDaVila](https://github.com/samuelit0davila)**: [ReStreet](https://github.com/samuelit0davila/fifa-street-pc-port), the recompilation and game fixes this port is built on
- **Emran_Ahm3d**: ReStreet's module loading, game data and FootballCompEng fixes
- **[elripalda](https://github.com/elripalda)**: the PS5 port, the hub, the PlayStation buttons and the trophies
- **[ReXGlue](https://github.com/rexglue/rexglue-sdk)**: the static recompiler and runtime; **[Xenia](https://github.com/xenia-project/xenia)**: the emulator its code comes from
- Thanks to ps5-payload-dev, mihawk-99 and Nazky for the PS5 toolchain, and to everyone who played the test builds

*An unofficial fan project, not affiliated with or endorsed by EA, FIFA, Microsoft or Sony. No game files are included.*
