# Tidycade

A small games library: choose **Install**, then **Play**. Games download only when you choose them.

## Download Tidycade

| Your computer | Download | What you get |
| --- | --- | --- |
| **Ubuntu, 64-bit Intel/AMD** | **[Download Ubuntu 0.4.0](https://github.com/BaptistSec/Tidycade/releases/download/v0.4.0/tidycade-0.4.0-ubuntu-x86_64.tar.gz)** | 10 games available to install. Portable preview. [Instructions and limits](https://github.com/BaptistSec/Tidycade/releases/tag/v0.4.0). |
| **Windows, 64-bit Intel/AMD** | **[Download Windows Test 2](https://github.com/BaptistSec/Tidycade/releases/download/windows-test-2/tidycade-windows-test-2.zip)** | 5 games available to install. Checked under Wine; **not yet verified on native Windows**. [Test notes and limits](https://github.com/BaptistSec/Tidycade/releases/tag/windows-test-2). |

Neither download is for macOS, phones or ARM computers. The Windows download is a test, not the full Ubuntu library.

**Use the named downloads above, not GitHub's automatic "Source code" links.** Those contain this downloads page, not the ready-to-run program. The optional `.sha256` files are download-integrity checks, not programs.

## Open it and play your first game

1. Download the file for your computer, then **extract the whole archive** to a writable folder. Do not open the program from inside the ZIP/archive viewer.
2. On Ubuntu, double-click **`tidycade-ubuntu-x86_64`**. On Windows, open **`Tidycade-Windows-TEST.exe`**. Tidycade opens Library in your default browser. No Python installation is needed.
3. Try **Pocket the Place** first: choose **Install**, wait for it to finish, then **Play**. Other games work the same way. Installed games also have their own **Installed** page.

On Ubuntu, if needed, use Properties > Permissions to allow executing the program. Do not run as root/administrator or automatically bypass security warnings. The unsigned Windows test may show an unknown-publisher warning; stop if unsure.

This is extract-then-open, not a one-click installer. Keep the included `START-HERE.txt` and `attribution/` folder with the program.

## What's new

- Tidycade branding inside the app, separate Library and Installed pages, and clearer Naev/OpenHV covers.
- Downloads run in the background with progress, **Cancel** and **Retry**. Browser reloads keep the job while Tidycade is running.
- Ubuntu adds **OpenHV** (10 games). Windows adds **OpenTyrian, OpenHV and Shattered Pixel Dungeon** (5 games).

Quitting Tidycade or rebooting interrupts downloads; they restart from the beginning. Installation results do not survive launcher restarts. There is no download-resume-after-reboot feature.

## Available games

**Ubuntu:** Pocket the Place, Platform Pests, OpenTTD, SuperTuxKart, Shattered Pixel Dungeon, Xonotic, Naev, OpenTyrian, Widelands and OpenHV.

**Windows Test 2:** Pocket the Place, OpenTTD, OpenTyrian, OpenHV and Shattered Pixel Dungeon. Wine menu/setup loads are not native Windows or full gameplay approval. See the release notes for the earlier OpenTyrian Wine display issue and repeat result.

Games need internet to install, and larger downloads can exceed 1 GB. Third-party game packages come unchanged from their official sources. Hardware requirements and first-run prompts still apply. No all-games offline or every-computer guarantee. OpenHV reached a skirmish map on Ubuntu; that is not a full playthrough of the library.

Keep `home/` beside the program when updating. Uninstall keeps launcher save folders. Browser-game progress depends on the same browser profile and game address. Some native games also use their normal user folders for saves/settings.

## Earlier downloads

Older releases and their files remain available unchanged: [Ubuntu 0.3.0](https://github.com/BaptistSec/Tidycade/releases/tag/v0.3.0), [Windows Test 1](https://github.com/BaptistSec/Tidycade/releases/tag/windows-test-1), and [all releases](https://github.com/BaptistSec/Tidycade/releases). The repo's former name redirects here, so older game-package links still work.

This public repo contains the downloads page and release files. Development source, private history and test evidence stay private. Artwork credits and licences are bundled with the downloads. No launch promotion yet.
