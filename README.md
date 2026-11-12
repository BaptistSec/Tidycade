# Tidycade

Browse free games, install the ones you want, then play from one library. Games download separately, so you do not need to download the whole collection.

## Download 0.15.1

| Your computer | Download |
| --- | --- |
| Ubuntu 22.04 or later, x86-64 | [Ubuntu archive](https://github.com/BaptistSec/Tidycade/releases/download/v0.15.1/tidycade-0.15.1-ubuntu-x86_64.tar.gz) |
| Windows 10 or later, x86-64 | [Windows ZIP](https://github.com/BaptistSec/Tidycade/releases/download/v0.15.1/tidycade-0.15.1-windows-x86_64.zip) |

[Release notes](https://github.com/BaptistSec/Tidycade/releases/tag/v0.15.1) | [SHA-256 checksums](https://github.com/BaptistSec/Tidycade/releases/download/v0.15.1/SHA256SUMS) | [SourceForge downloads](https://sourceforge.net/projects/tidycade/files/v0.15.1/)

These downloads are not for macOS, phones or ARM computers. Game availability and requirements differ between Windows and Ubuntu. Check each game's card before installing. The online library can change without a new launcher download.

## Install and play

1. Extract the complete archive to a folder you can write to. Do not run the program from inside an archive viewer.
2. On Windows, open `tidycade-windows-x86_64.exe`. On Ubuntu, open `tidycade-ubuntu-x86_64`. Allow it to run as a program if your file manager asks. Python is included.
3. The library opens in your existing browser. Choose a game, select Install and wait for the download to finish. Then select Play. Installed games are also listed on the Installed page.

Keep the supplied notices and folders beside the executable. Internet access is needed to download games. Do not run as root or administrator, or bypass security warnings automatically. The Windows executable is unsigned.

Optional Ubuntu applications-menu entry: run `python3 install-desktop.py` from the extracted folder. This registers that copy for your user without sudo. Run it again if you move the folder.

## Keep your games when updating

Close Tidycade and finish any games first. Keep the `home` folder beside the new executable to retain installed games, launcher-managed saves, favourites and settings. Extract the complete new archive and do not run both copies at once. Check the new copy before removing the old one.

Uninstall keeps launcher-managed saves. Some games also use their normal user-data folders, so keep those when moving to another computer.

## Using the library

Search for a game, browse by genre or return to Installed, Favourites and Recently played. These lists stay on your computer. Recently played records starts through the launcher, not time spent playing.

Keyboard and mouse work throughout. A native controller menu is also available for supported controllers. Return and game switching depend on the game, window system and operating system. This does not add controller support to games that do not have it.

Game-list updates are signed. A failed refresh keeps the last accepted list. Launcher updates are separate from game-list updates.

## Compatibility and licences

Ubuntu checks were run directly; Windows checks were under Wine, not on native Windows hardware. There is no claim that every game has been tested with every controller, GPU or audio setup. Each game keeps its own requirements.

Keep `LICENSE`, `LICENSING.md`, `THIRD_PARTY` and attribution notices with the launcher. Games, runtimes and artwork retain their own terms. Game and artwork notices are available through Credits.
