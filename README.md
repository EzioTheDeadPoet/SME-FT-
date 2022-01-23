
![status](https://img.shields.io/badge/dynamic/json?label=Status&query=Status&url=https%3A%2F%2Fraw.githubusercontent.com%2Fwabbajack-tools%2Fmod-lists%2Fmaster%2Freports%2Fsmeft%2Fstatus.json&style=for-the-badge)
![version](https://img.shields.io/badge/dynamic/json?label=version&query=%24%5B%3F%28%40.links.machineURL%3D%3D%22smeft%22%29%5D.version&url=https%3A%2F%2Fraw.githubusercontent.com%2Fwabbajack-tools%2Fmod-lists%2Fmaster%2Fmodlists.json&style=for-the-badge)

**This modlist is meant as a basis to start your own Skyrim modding journey, it includes all the essential fixes & tools.**

Originally created by Luca (EzioTheDeadPoet), now maintained by trawzified and Luca.

## Index
Soon to be updated.

## Description

This modlist is a utility for modders, to speed up their initial modding setup, or for people who want to play vanilla Skyrim with all the unofficial patches and fixes.
It can also be utilized as a test bench for developing new mods on a stable base.

If you want to learn more about modding Skyrim, you could read up on it on [the /r/skyrimmods wiki](https://www.reddit.com/r/skyrimmods/wiki/begin2) or follow the [lessons on the Learn to Mod page](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/Main.md) on how to get started.

### What's included in this list?

Previously, SMEFT included profiles for people that want to use specific animation engines. However, the best option is clearly [Nemesis](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main/releases/latest) unless you want a very particular set of animal mods found on LoversLab.

The list contains mods that fall into 4 categories.

#### Tools
- [BethINI](http://nexusmods.com/skyrimspecialedition/mods/4875)
- [BodySlide and Outfit Studio](http://nexusmods.com/skyrimspecialedition/mods/201)
- [deorder's MO2 Plugins](https://github.com/deorder/mo2-plugins)
   - **Merge Plugins Hide**: Hide / unhide plugins that were merged using *Merge Plugins* or *zMerge*.
   - **Sync Mod Order**: Sync mod order from current profile to another while keeping the (enabled/disabled) state intact.
- [Dynamic Distant Objects LOD - DynDOLOD](https://www.nexusmods.com/skyrim/mods/59721)
   - This does **NOT** include the resources found on the same page.
- [LOOT](https://github.com/loot/loot)
- [NifSkope](https://github.com/niftools/nifskope)
- [Papyrus Compiler App (Mod Organizer 2 Integration) SE](http://nexusmods.com/skyrimspecialedition/mods/23852)
- [SSEEdit](https://nexusmods.com/skyrimspecialedition/mods/164)
- [SSELODGen](https://www.nexusmods.com/skyrimspecialedition/mods/6642)
- [Synthesis](https://github.com/Noggog/Synthesis)
- [Unofficial Mator Smash Updated](https://www.nexusmods.com/skyrimspecialedition/mods/39378)
- [Wrye Bash](https://www.nexusmods.com/skyrimspecialedition/mods/6837)
- [zEdit](https://github.com/z-edit/zedit)

### Mods



## Installation

### Step 1 - Preparing the Wabbajack installation environment

First off - ensure your game is completely vanilla, no mods installed and downgraded to version SE 1.5.97.0 using the [Downgrade Patcher](https://www.nexusmods.com/skyrimspecialedition/mods/57618) it usually updates shortly after a game update releases. Make sure to install the game **outside** of your Program Files directories (not in the default Steam location!). This can cause issues for certain mods because Windows restricts permissions to these folders via UAC. If you already have a Steam Library in Program Files and still want to install Skyrim outside of it, Steam won't let you (not on the same drive that is). You can bypass this by using [this tool by LostDragonist.](https://github.com/LostDragonist/steam-library-setup-tool/releases)

Create a Wabbajack folder and an installation folder on the root of your drive. An instance of Mod Organizer 2 will be installed into the installation directory, and Wabbajack itself will stay inside the Wabbajack folder.


Example:
- `C:\Wabbajack` (Wabbajack folder)
- `C:\SMEFT` (Installation folder, where Mod Organizer 2 will be installed)

### Step 2 - Downloading Wabbajack

Get [the latest Wabbajack build](https://www.github.com/wabbajack-tools/wabbajack/releases/latest) from GitHub (the executable file named `Wabbajack.exe`).

Place it in the Wabbajack folder.

### Step 3 - Downloading the modlist

Start `Wabbajack.exe` in the Wabbajack folder and click on 'Browse Modlists'. Now select 'Only Utility Lists' at the top right, you should now be able to see SMEFT. Press the big download button in the corner.

This'll download the modlist file which is basically a set of instructions Wabbajack will use to replicate my SMEFT installation on your computer.

### Step 4 - Starting installation via Wabbajack

Select your installation folder in Wabbajack and point it to the folder you created in step 1.	

Downloads will be automatically stored in a subdirectory (`C:\SMEFT\downloads`), but if you would like to save space on the installation drive, create an empty Downloads folder on the drive you wish to store the downloaded files on and select that folder instead.

Now start your installation by clicking on the blue play button on the right.

### Step 5 - Copying Game Folder Files

Once your installation is complete, proceed to go to your Skyrim game directory.

Copy all the files inside the Game Folder Files directory (in the installation directory) into your Skyrim game directory.

**WARNING: Only copy the files inside the Game Folder Files directory (`skse64_loader.exe` etc) into your Skyrim folder, not the entire installation folder!**

### Step 6 - Post-installation

After copying the Game Folder Files into your base game directory, go to your installation directory (`C:\SMEFT`), proceed into the `tools\BethINI` folder. Make sure Mod Organizer 2 and Skyrim are closed and start `BethINI.exe`. Select *Skyrim Special Edition* in the drop-down menu and proceed after reading the warning. Go to the *Setup* tab on the far-left of BethINI and select *Browse...* in the Mod Organizer drop-down menu. Browse to your installation folder and select `ModOrganizer.exe` inside. Now select the SMEFT profile in the Profiles drop-down menu, below the Mod Organizer label. Click *Yes* if BethINI asks whether it may modify custom INI files.

Go back to the Basic tab, check the box next to *Recommended Tweaks* and select the preset you think is right for your PC. Modern PCs should be fine with the *Medium* or *High* preset. People with high end PCs - I would recommend against the *Ultra* preset even with your RTX 3090 and Ryzen 9 5950X, unless you're going for a screen archery setup. The lost performance is better spent upping the settings quality of your favorite ENB preset. Click *Save and Exit* after you've applied the settings.

You can make your game update save by making it steam update independant using this [guide](https://github.com/LivelyDismay/Learn-To-Mod/blob/main/lessons/Setting%20up%20Stock%20Game%20for%20Skyrim%20SE.md) for integrating your skyrim installation into your MO2 instance.
*If you plan to make a Wabbajack list this is how all of them do it, SMEFT is the Exception because Wabbajack can't source the Creation Kit (it could but that would require everyone to install it before trying to install any modlist including any Creation Kit file) and SMEFT depends on all tools being available.*

### Step 7 - Running the game & notes

Start the game by launching `ModOrganizer.exe` in the installation directory, then select *SKSE* from the drop-down menu at the top right. Click *Run* next to it.

Important to know:

- You will need to re-run Synthesis after adding your own mods, and re-run Nemesis when adding mods that require it.
- If you plan to run DynDOLOD, do not forget to grab the resources from the Nexus page and if available the dependencies for any added weather mods and the likes.

## Ultrawide Fix

[Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778) contains the necessary mods for ultrawide monitor users. Download and install these mods using Mod Organizer 2. The first file is found under the *Main Files* section of the mod files page, the rest are under *Optional Files*.

- `Complete Widescreen Fix for SkyUI 5.2 SE Alpha - 2560x1080`
  - Place this mod under `SkyUi` and keep both active (Patch)
- `Better Dialogue Control Widescreen Fix`
  - Disable `Better Dialogue Control` and place this mod under it (Replacer)
- `Better MessageBox Control Widescreen Fix`
  - Disable `Better MessageBox Control` and place this mod under it (Replacer)
- `SkyUI SE - Flashing Savegames FIx[sic] - Widescreen Fix`
  - Disable `Flashing Savegames Fix` and place this mod under it (Replacer)
- `Race Menu SE - Widescreen Fix (Optional Files)`
  - Place this mod under `RaceMenu` and keep both active (Patch)

Alternatively, an easier option that will result in a less vanilla-looking UI is [Dear Diary](https://www.nexusmods.com/skyrimspecialedition/mods/23010). It includes support for 21:9 and 32:9.

## FAQ

### Why is there no cleaned texture / audio mod included? [unofficial performance optimized textures AKA (UPOT)](https://www.nexusmods.com/skyrimspecialedition/mods/21166), [Cleaned Skyrim SE Textures](https://www.nexusmods.com/skyrimspecialedition/mods/38775) or [Unofficial High Definition Audio Project](https://www.nexusmods.com/skyrimspecialedition/mods/18115) the short reasoning is size,
Mods like that are very large sized (would triple the installation size) and not very useful for people that simply want to have a setup to test their newly developed mod on. There are plans for a SMEFT version that do include these types of mods, but it's not here just yet :)

### Are there ultrawide options available?
Not included by default, but there are the instructions in the [Ultrawide Fixes Section](#ultrawide-fix).


## Credits and Thanks
- You, for actually reading the entirety of the README
- Akalonian for clearing up some of the installation instructions early on
- Lively and LadyZeefa for encouraging Luca to create this list
- ForgottenGlory for making SME(FT) possible due to his early support
- Halgari and everyone on the Wabbajack Team
- All the mod authors that made the mods featured in this list
- Luca for originally creating SME(FT)
- Special thanks to all the other people listed [here](https://eziothedeadpoet.github.io/AboutMe/HALLOFFAME.html) that support the project

## Contact
I (trawzified) am usually available on the [Wabbajack Discord](https://discord.gg/wabbajack). You may also message me on GitHub. Mod suggestions are alright, but keep in mind that they should be within the scope of the project.

**Do not contact mod authors with issues, approach me first. It's far more likely that there's an issue with this list rather than their mod, and we don't want to waste their time.**
