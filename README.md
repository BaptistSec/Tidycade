# Tidycade

A small games library: choose **Install**, then **Play**. Games download only when you choose them.

## Download Tidycade

| Your computer | Download | What you get |
| --- | --- | --- |
| **Ubuntu, 64-bit Intel/AMD** | **[Download Ubuntu 0.8.0](https://github.com/BaptistSec/Tidycade/releases/download/v0.8.0/tidycade-0.8.0-ubuntu-x86_64.tar.gz)** | 12 games available to install. Portable preview. [Instructions and limits](https://github.com/BaptistSec/Tidycade/releases/tag/v0.8.0). |
| **Windows, 64-bit Intel/AMD** | **[Download Windows Test 8](https://github.com/BaptistSec/Tidycade/releases/download/windows-test-8/tidycade-windows-test-8.zip)** | 8 games available to install. Windows test release. [Test notes and limits](https://github.com/BaptistSec/Tidycade/releases/tag/windows-test-8). |

Neither download is for macOS, phones or ARM computers. The Windows download is a test, not the full Ubuntu library.

**Use the named downloads above, not GitHub's automatic "Source code" links.** Those contain this downloads page, not the ready-to-run program. The optional `.sha256` files are download-integrity checks, not programs.

## Open it and play your first game

1. Download the file for your computer, then **extract the whole archive** to a writable folder. Do not open the program from inside the ZIP/archive viewer.
2. On Ubuntu, double-click **`tidycade-ubuntu-x86_64`**. On Windows, open **`Tidycade-Windows-TEST.exe`**. Tidycade opens Library in your default browser. No Python installation is needed.
3. Try **Pocket the Place** first: choose **Install**, wait for it to finish, then **Play**. Other games work the same way. Installed games also have their own **Installed** page.

On Ubuntu, if needed, use Properties > Permissions to allow executing the program. Do not run as root/administrator or automatically bypass security warnings. The unsigned Windows test may show an unknown-publisher warning; stop if unsure.

This is extract-then-open, not a one-click installer. Keep the included README, test notes and `docs/` notices with the program.

## What's new

- A full-width featured game and genre-based browse sections make the library easier to explore.
- Search titles, descriptions and creators, filter by genre, or sort by name and download size. Press Ctrl+K to jump to search.
- Hover or arrow-select a card for three-second gameplay previews. Featured rotation stays paused while you browse, then resumes 15 seconds after leaving, three seconds after Install or six seconds after Play.
- Mindustry and SuperTux join Ubuntu. Their game files and Mindustry's Java runtime download automatically when you choose Install; no separate system setup is needed.

Keep Tidycade running during downloads. Browser reloads keep the job while the program is running. Quitting Tidycade or rebooting interrupts downloads; they restart from the beginning. Installation results do not survive launcher restarts.

## Available games

**Ubuntu:** Pocket the Place, Platform Pests, OpenTTD, SuperTuxKart, Shattered Pixel Dungeon, Xonotic, Naev, OpenTyrian, Widelands, OpenHV, Mindustry and SuperTux.

**Windows Test 8:** Pocket the Place, OpenTTD, OpenTyrian, OpenHV, Shattered Pixel Dungeon, VoxeLibre (with Luanti), Warzone 2100 and Cataclysm: Bright Nights. This is a test release; see its download page for requirements and known issues.

Games need internet to install, and larger downloads can exceed 1 GB. Third-party game packages come unchanged from their official sources. Mindustry and SuperTux also use small Tidycade setup components, including SuperTux compatibility libraries with notices and full source. Hardware requirements and first-run prompts still apply. Offline support varies by game. Not every level or computer configuration has been tested.

Keep `home/` beside the program when updating. Uninstall keeps launcher save folders. Browser-game progress depends on the same browser profile and game address. Some native games also use their normal user folders for saves/settings.

## Earlier downloads

Older releases and their files remain available unchanged: [Ubuntu 0.4.0](https://github.com/BaptistSec/Tidycade/releases/tag/v0.4.0), [Windows Test 2](https://github.com/BaptistSec/Tidycade/releases/tag/windows-test-2), and [all releases](https://github.com/BaptistSec/Tidycade/releases).

Artwork credits and licences are included in the `docs/` folder in each download and through Credits in the library.
