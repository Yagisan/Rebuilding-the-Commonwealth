# Rebuilding the Commonwealth
 
![GitHub all releases](https://img.shields.io/github/downloads/Yagisan/Rebuilding-the-Commonwealth/total?logo=GitHub&style=for-the-badge)![GitHub issues](https://img.shields.io/github/issues/Yagisan/Rebuilding-the-Commonwealth?logo=GitHub&style=for-the-badge)

 Rebuilding the Commonwealth is a curated modlist designed for a settlement building focused playthrough. It is expected that players will not add additional mods or otherwise change this modlist.

[![patreon](assets/images/become_a_patron_button.png)](https://patreon.com/yagisan) [![ko-fi](assets/images/support_on_kofi_button.png)](https://ko-fi.com/yagisan)

- [Rebuilding the Commonwealth](#rebuilding-the-commonwealth)
- [Preamble](#preamble)
- [Quick Links](#quick-links)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
      - [Change Steams Update Behaviour](#change-steams-update-behaviour)
      - [Set the Game language to English](#set-the-game-language-to-english)
    - [Clean Fallout 4](#clean-fallout-4)
      - [Start Fallout 4](#start-fallout-4)
      - [Creation Club](#creation-club)
    - [Using Wabbajack](#using-wabbajack)
      - [Preparations](#preparations)
      - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
    - [Copy Game Folder Files](#copy-game-folder-files)
- [Starting the Game](#starting-the-game)
- [Updating](#updating)
- [Noteworthy Mods](#noteworthy-mods)
  - [Category 1](#category-1)
  - [Category 2](#category-2)
- [Creating your Character](#creating-your-character)
- [In-Game MCM Options](#in-game-mcm-options)
- [Other Post Installation FAQ](#other-post-installation-faq)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact and Technical Support](#contact-and-technical-support)

# Preamble



# Quick Links
- [Patreon](https://patreon.com/yagisan) contains update posts and provides a way of showing support for the project.
- [Ko-fi](https://ko-fi.com/yagisan) contains update posts and provides a way of showing support for the project.
- [Downloads](https://github.com/Yagisan/Rebuilding-the-Commonwealth/releases) for the most recent releases.
- [Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases) for the tool to install this modlist.
- [Issues](https://github.com/Yagisan/Rebuilding-the-Commonwealth/issues) for technical support with this mod list.
- [Nexus](https://www.nexusmods.com/fallout4/mods/53368) for user to user community support.

# Installation

## Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

It is unlikely that you are missing this. However it is needed for MO2 and several plugins, so please download it and install it anyway from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". This is [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Config

#### Disable the Steam Overlay

![Steam_General_Settings](assets/images/Steam_General_Settings.png)

The Steam Overlay can cause issues with ENB and is recommended to be turned off.
**Please note that this mod list does not use an ENB.**

Open the Properties window (right click the game in your Library->Properties), navigate to the _General_ tab and un-tick the _Enable the Steam Overlay while in-game_ checkbox. You should also un-tick the _Keep games saves in the Steam Cloud_.

#### Change Steams Update Behaviour

![Steam_Update_Settings](assets/images/Steam_Update_Settings.png)

Fallout 4 is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you, head over to the Properties window, navigate to the _Updates_ tab and change _Automatic updates_ to _Only update this game when I launch it_.

#### Set the Game language to English

![Steam_Language_Settings](assets/images/Steam_Language_Settings.png)

This modlist is in English, and most of the mods you find are in English. **I can not give support to people with a non-English game**.

Open the Steam Properties window, navigate to the _Language_ tab and select _English_ from the dropdown menu.

### Clean Fallout 4

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the `Fallout 4` folder in `Documents/My Games/`. This is especially true if you have been using Nexus Mod Manager or Vortex to manage your Fallout 4 Mods.

#### Start Fallout 4

![Fallout_Launcher](assets/images/Fallout_Launcher.png)

After you have done everything above and got a clean Fallout 4 installation ready, start the Launcher and open the _Options_ menu.

![Fallout_Launcher_Options](assets/images/Fallout_Launcher_Options.png)

1. Click on _Ultra_
2. Set the  _Resolution_ to your monitor's native values
3. Set _Antialiasing_ to _TAA_
4. **Do not** check _Windowed Mode_ and _Borderless_

**Start the game and exit once you're in the main menu.**

#### Creation Club

![Creation_Club_Purchased](assets/images/Creation_Club_Purchased.png)

If you own any items from the Creation Club, they are not automatically reinstalled when you install Fallout 4. To reinstall Creation Club items, you must launch the game, select the Creation Club menu option, select the purchased option, then download each Creation club item individually.

At the time of writing this document, Creation Club items are not supported in this mod list. However as I do own a lot of Creation Club content, this is subject to change in the future.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in a _working folder_.  The recommended working folder is `C:\WJ\WabbaJack`. This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder.

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. [Download the latest release from GitHub](https://github.com/Yagisan/Rebuilding-the-Commonwealth/releases). Extract it to a temporary folder. The recommended temporary folder is `C:\Temp\Rebuild`.
2. Open Wabbajack.
3. Click on Install form Disk. Set the target modlist to `C:\Temp\Rebuild\Rebuilding the Commonwealth.wabbajack`
4. Set the _installation location_. The recommended installation location is `C:\WJ\RtC`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder. **The rest of this document will assume you are using the recommended installation path.**
5. Set the _download location_. The recommended download location is `C:\WJ\RtC_downloads`.  This folder **must not** be in a _common folders_ like your Desktop, Downloads or Program Files folder.
6. Click the Go/Begin button
7. Wait for Wabbajack to finish
8. If you run into any issues see the next section. If the installation is successful, proceed to [Post-Installation](#post-installation).

#### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you will not loose progress.

**Could not download x**:

If a mod updated and the old files were deleted, it is impossible to download them. You will need to be patent and wait for me to update the modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

## Post-Installation

### Copy Game Folder Files

Copy all of the files from the `C:\WJ\RtC\Game Folder Files` directory into your game folder. Do not copy any other files.

# Starting the Game

Head over to the installation folder and locate an executable named `ModOrganizer.exe` and launch it. This will be `C:\WJ\RtC\ModOrganizer.exe` if you have followed the recommended settings. Once it is launched, there will be a dropdown box on the top right and a big run button right next to it. Ensure it is set to F4SE by selecting it in the dropdown box and then hitting the run button. You have to run F4SE through Mod Organizer 2 in order to play Rebuilding the Commonwealth.

# Updating

If this Modlist receives an update please check the [Changelog](CHANGELOG.md) before doing anything. The [Changelog](CHANGELOG.md) will advise if you will need to start a new game, or if your existing saves will continue working.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched.

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Noteworthy Mods

## Category 1

## Category 2

# Creating your Character

After starting a new game, you will start in the normal pre-war quest. Follow this quest as usual until you escape from the cryotube, then configure your mods before you actually start playing.

It is **very** important that you wait in this next to the cryotube, until all the messages in the top left corner have finished. Now would be an excellent time to go make a cup of tea or coffee. Once these messages have finished, press `ESCAPE` and create a manual save before you continue. You can now configure mods via the MCM to your liking, and proceed to exit the vault.

At this point a second group of mods will begin initialising, including all installed Creation Club content.

# In-Game MCM Options

# Other Post Installation FAQ

## Removing the Modlist

Simply delete the installation folder (`C:\WJ\RtC` if you have been following this guide) and that will remove it, but why would you want to?

## Contact and Technical Support

Please check the [Issues](https://github.com/Yagisan/Rebuilding-the-Commonwealth/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. If you believe you have found a bug, please file bug report [here](https://github.com/Yagisan/Rebuilding-the-Commonwealth/issues) with as much information as possible to replicate the issue. A [user to user only support forum](https://www.nexusmods.com/fallout4/mods/53368) is available on Nexus mods. Requests for support on any other platform will be ignored. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.
