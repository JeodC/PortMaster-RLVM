## RLVM For PortMaster
The following games are known to run:

- [Air Standard Edition](https://vndb.org/r87)
- [Clannad Regular Edition](https://vndb.org/r303) / [Full Voice](https://vndb.org/r13) / [Clannad HD](https://store.steampowered.com/app/324160)
- [Kanon Standard Edition](https://vndb.org/r274) / [All Ages](https://vndb.org/r275)
- [Little Busters!](https://vndb.org/r175) / [Ex Edition](https://vndb.org/r1944)
- [Planetarian: The Reverie of a Little Planet](https://store.steampowered.com/app/316720)
- [Tomoyo After: It's A Wonderful Life](https://store.steampowered.com/app/462990)

Check [rlvm status.txt file](https://github.com/eglaysher/rlvm/blob/master/STATUS.TXT) for more.

The following games were tested and will _not_ currently run:

- Clannad Side Stories
- Kanon HD
- Little Busters! English Edition (Steam)
- Planetarian HD

## How to Use
Add the runtime files `rlvm.squashfs` and `rlvm.squashfs.md5` to `PortMaster/libs`. Add game assets to `ports/[yourgame]/gamedata`. The following information may help:

## Patches
- Air Standard Edition has an [English Patch](https://winter-confetti.blogspot.com/2014/04/air-standard-edition-2005-english-patch.html). Other versions and patches are untested.
- Kanon has an [English Patch](https://www.gamepressure.com/download.asp?ID=77952) that can be applied to the [Standard or All Ages editions](https://vndb.org/v33).
- Little Busters has an [English Patch](http://dl.blicky.net/lb/lb-english-6.0.exe) that can be applied to the [Regular Edition](https://vndb.org/r175). Other editions are untested.

## Known Issues
- Air Standard Edition
    - Unable to find purchase location
    - Can't save and load games due to missing right-click context menu
- Clannad HD
    - Movie unable to play (unsupported by rlvm)
- Kanon (Both Editions)
    - Can't save and load games due to missing right-click context menu
- Little Busters! (Ex)
    - Many graphical glitches and blank screens during CG events, but all text displays
    - Baseball minigame does not work
- Planetarian: The Reverie of a Little Planet
    - Delisted from Steam
- Tomoyo After: It's A Wonderful Life
    - Textbox rendering has some problems
    - Dungeon crawling minigame does not work
    
## Contributing
The upstream repository is no longer active. For the PortMaster Rlvm, a fork was created and improved on: https://github.com/JeodC/rlvm. If you want to help bring more visual novels to PortMaster, consider improving the fork!