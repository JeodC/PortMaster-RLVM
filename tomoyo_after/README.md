## Installation
Get the game from Steam - [Tomoyo After: It's A Wonderful Life](https://store.steampowered.com/app/462990). Install the `rlvm` runtime and add your game assets to `ports/tomoyo_after/gamedata`. File structure below:

```
tomoyo_after/gamedata
├───bgm
├───dat
├───g00
├───gan
├───koe (safe to remove if not using voices)
├───mov (not used atm but might be usable in the future; safe to remove)
└───wav
└───Gameexe.ini
└───Seen.txt
```

This is a big port!! The Steam edition is roughly 2.54GB total of gamedata!

## Notes
- Known Issues
    - Dungeon crawling minigame does not work

You should be able to use older editions of Tomoyo After if you have them. The following are confirmed working:

- [Tomoyo After - Perfect Edition (JP)](https://vndb.org/r35173) with [Unofficial English Patch](https://vndb.org/r1476)

## Default Gameplay Controls
| Button | Action |
|--|--|
|Select|Back|
|Start|Start|
|A|Accept|
|B|Cancel / Open Menu|
|L1|Scroll back dialog|
|R1|Scroll forward dialog|
|L2|Fast forward dialog|
|D-Pad / Sticks|Move cursor|

## Thanks
Kloptops - Original port  
eglaysher - Rlvm original  
a1batross - Rlvm SDL2 fork  
Testers and Devs from the PortMaster Discord  
