# SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

![(thumbnail)](/SME-FT-Thumbnail.png)

![status](https://img.shields.io/endpoint?url=https://build.wabbajack.org/lists/status/smeft/badge.json&style=for-the-badge&label=status)
![version](https://img.shields.io/badge/dynamic/json?label=version&query=%24%5B%3F%28%40.links.machineURL%3D%3D%22smeft%22%29%5D.version&url=https%3A%2F%2Fraw.githubusercontent.com%2Fwabbajack-tools%2Fmod-lists%2Fmaster%2Fmodlists.json&style=for-the-badge)

**THIS MODLIST IS MEANT AS A BASIS TO START YOUR OWN MODDING JOURNEY AND INCLUDES ALL THE FIXES AND TOOLS KNOWN TO ME WITH A FEW ADDED RECOMMENDATIONS!!!**

## Update Team

- Luca\|EzioTheDeadPoet
- trawzified

## Index
<!-- markdownlint-disable MD033 -->
<ul>
   <li><a href="#general-description">General-Description !IMPORTANT!</a></li>
   <li><a href="#installation">Installation</a></li>
   <li><a href="#notes">Notes</a></li>
   <li><a href="#ultrawide-fix">UltraWide Fix</a></li>
   <li><a href="#reasoning-and-future-plans">Reasoning and Future Plans</a></li>
   <li><a href="#credits-and-thanks">Credits and Thanks</a></li>
   <li><a href="#contact">Contact</a></li>
   <li><a href="#changelog">Changelog</a></li>
</ul>
<!-- markdownlint-enable MD033 -->

## **GENERAL-DESCRIPTION**

### **What is this list trying to offer ?**

In short, this list intendeds to offer what I was searching for when moving from Skyrim Legendary Edition to Skyrim Special Edition at the end of 2019.
It got refined, has grown, and became a resource.

- For LE players to make an easy move to SE with a ready to mod setup.
- For SE players wanting a fast ready to mod setup.
- For SE mod and patch authors as a test bench.

This modlist is a utility for modders, to speed up their initial MO2 setup.
For people who just want a vanilla experience with all the unofficial patches and fixes.

If you want to learn more about modding Skyrim, I recommend [this Guide](https://www.reddit.com/r/skyrimmods/wiki/begin2) on how to get started.

This modlist comes with the most (I do not want to make the absolute claim it has all, even tho I am pretty sure) common tools and fixes for Skyrim Special Edition, so modlist creators and modders have an easier way of getting a stable initial vanilla setup with little effort.

Some of the mods you might want to change, based on personal preference. They are found in the `Optional but highly recommended mods` section.

**Now have fun using this as a basis for your modlists, or your test bench for your mods or patchers.**

### **What is included in this List ?**

- This list contains these of 4 categories:

   1. **Tools** (Accessible over the run menu and the shortcuts)
      - [BethINI](http://nexusmods.com/skyrimspecialedition/mods/4875)
      - [BodySlide and Outfit Studio](http://nexusmods.com/skyrimspecialedition/mods/201)
      - [deorder's MO2 Plugins](https://github.com/deorder/mo2-plugins)
         - **Merge Plugins Hide**: Hide / unhide plugins that were merged using `Merge Plugins` or `zMerge`
         - **Sync Mod Order**: Sync mod order from current profile to another while keeping the (enabled/disabled) state intact
      - [Dynamic Distant Objects LOD - DynDOLOD](https://www.nexusmods.com/skyrim/mods/59721)
         - This does **NOT** include the resources found on the same modpage.
      - [LOOT](https://github.com/loot/loot)
      - [NifSkope](https://github.com/niftools/nifskope)
      - [Papyrus Compiler App (Mod Organizer 2 Integration) SE](http://nexusmods.com/skyrimspecialedition/mods/23852)
      - [SSEEdit](http://nexusmods.com/skyrimspecialedition/mods/164)
      - [SSELODGen](https://www.nexusmods.com/skyrimspecialedition/mods/6642)
      - [Synthesis](https://github.com/Noggog/Synthesis)
      - [Unofficial Mator Smash Updated](https://www.nexusmods.com/skyrimspecialedition/mods/39378)
      - [Wrye Bash](https://www.nexusmods.com/skyrimspecialedition/mods/6837)
      - [zEdit](https://github.com/z-edit/zedit)

   2. **Game Fixes and Patches**
      - [Actor Movement Limit Fix](https://www.nexusmods.com/skyrimspecialedition/mods/32349?tab=files)
      - [Animation Limit Crash Fix SSE](https://www.nexusmods.com/skyrimspecialedition/mods/31146)
      - [Assorted mesh fixes](http://nexusmods.com/skyrimspecialedition/mods/32117)
      - [Believable Crime Report Radius](https://www.nexusmods.com/skyrimspecialedition/mods/2802)
      - [Better Dialogue Controls](http://nexusmods.com/skyrimspecialedition/mods/1429)
      - [Better MessageBox Controls](http://www.nexusmods.com/skyrimspecialedition/users/3238634)
      - [Better Jumping SE](https://www.nexusmods.com/skyrimspecialedition/mods/18967)
      - [Bug Fixes SSE](https://www.nexusmods.com/skyrimspecialedition/mods/33261)
      - [Console Commands Extender](https://www.nexusmods.com/skyrimspecialedition/mods/28210)
      - [Copy and Paste in Console](http://nexusmods.com/skyrimspecialedition/mods/30928)
      - [Critters Aint Snitches](http://nexusmods.com/skyrimspecialedition/mods/15134)
      - [Dwemer Gates Don't Reset](https://www.nexusmods.com/skyrimspecialedition/mods/26331)
      - [Engine Fixes](http://nexusmods.com/skyrimspecialedition/mods/17230)
      - [Enhanced Reanimation](https://www.nexusmods.com/skyrimspecialedition/mods/43500)
      - [Equip Enchantment Fix](https://www.nexusmods.com/skyrimspecialedition/mods/42839)
      - [Essential Favorites](https://www.nexusmods.com/skyrimspecialedition/mods/42997) (See Note 4. in [Notes](#notes).)
      - [Fast Travel Speed Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1503)
      - [Favorite Misc Items](https://www.nexusmods.com/skyrimspecialedition/mods/42750)
      - [First Person Sneak Strafe-Walk Stutter Fix](http://nexusmods.com/skyrimspecialedition/mods/31165)
      - [Fix Note icon for SkyUI (SKSE64 plugin)](https://www.nexusmods.com/skyrimspecialedition/mods/32561)
      - [Fixed body collision](http://nexusmods.com/skyrimspecialedition/mods/10849)
      - [Fixed Dragon Stalking Fix](https://www.nexusmods.com/skyrimspecialedition/mods/37230)
      - [FloraFixer - Mutagen Patcher and Data](https://www.nexusmods.com/skyrimspecialedition/mods/42057) (read Note 3. in [Notes](https://github.com/EzioTheDeadPoet/SME-FT-#4-notes))
      - [hank's gamepad and controller fixes](https://www.nexusmods.com/skyrimspecialedition/mods/42492)
      - [Keyboard Shortcuts Fix](https://www.nexusmods.com/skyrimspecialedition/mods/3620?tab=description)
      - [Logical Outfits and Classes for The Dark Brotherhood Forever](https://www.nexusmods.com/skyrimspecialedition/mods/43483)
      - [Modern Brawl Bug Fix](http://nexusmods.com/skyrimspecialedition/mods/1473)
      - [More Informative Console](http://nexusmods.com/skyrimspecialedition/mods/19250)
      - [Move it Dammit - for Skyrim Special Edition](https://www.nexusmods.com/skyrimspecialedition/mods/752)
      - [Multiple Floors Sandboxing](https://www.nexusmods.com/skyrimspecialedition/mods/4524)
      - [No More Standing Too Close SSE](https://www.nexusmods.com/skyrimspecialedition/mods/4784)
      - [No Silly Physics Damage - Carts Pots Bones etc](https://www.nexusmods.com/skyrimspecialedition/mods/36132)
      - [No Spinning Death Animation](http://nexusmods.com/skyrimspecialedition/mods/1432)
      - [NPC AI Process Position Fix - SSE](https://www.nexusmods.com/skyrimspecialedition/mods/40261)
      - [powerofthree's Tweaks](http://nexusmods.com/skyrimspecialedition/mods/51073)
      - [Raven Rock - Fix Exit on Horseback](https://www.nexusmods.com/skyrimspecialedition/mods/14075)
      - [Scrambled Bugs](http://nexusmods.com/skyrimspecialedition/mods/43532)
      - [SkyUI](http://nexusmods.com/skyrimspecialedition/mods/12604)
      - [SkyUI SE - Flashing Savegames Fix](http://nexusmods.com/skyrimspecialedition/mods/20406)
      - [SSE Display Tweaks](https://www.nexusmods.com/skyrimspecialedition/mods/34705)
      - [Unofficial Skyrim Special Edition Patch](http://nexusmods.com/skyrimspecialedition/mods/266)
      - [Whiterun Tower Fix](https://www.nexusmods.com/skyrimspecialedition/mods/14365)

   3. **Mod Resources**
      - [.NET Script Framework](https://www.nexusmods.com/skyrimspecialedition/mods/21294)
      - [Address Library for SKSE Plugins](https://www.nexusmods.com/skyrimspecialedition/mods/32444)
      - [ConsoleUtilSSE](http://nexusmods.com/skyrimspecialedition/mods/24858)
      - [FileAccess Interface for Skyrim SE Scripts](http://nexusmods.com/skyrimspecialedition/mods/13956)
      - [Fuz Ro D-oh - Silent Voice](https://www.nexusmods.com/skyrimspecialedition/mods/15109)
      - [JContainers SE](http://nexusmods.com/skyrimspecialedition/mods/16495)
      - [PapyrusUtil SE](http://nexusmods.com/skyrimspecialedition/mods/13048)
      - [powerofthree's Papyrus Extender](https://www.nexusmods.com/skyrimspecialedition/mods/22854)
      - [Project New Reign - Nemesis Main](https://github.com/ShikyoKira/Project-New-Reign---Nemesis-Main)
      - [Project New Reign - Nemesis PCEA](https://www.nexusmods.com/skyrimspecialedition/mods/31667?tab=description)
      - [Scaleform Translation Plus Plus](https://www.nexusmods.com/skyrimspecialedition/mods/22603)
      - [SimpleAddItems 2.0 - a zEdit module for leveled lists and containers](https://www.nexusmods.com/skyrimspecialedition/mods/32319?tab=description)
      - [Skyrim Script Extender SKSE64](https://skse.silverlock.org)
      - [UIExtensions](http://nexusmods.com/skyrimspecialedition/mods/17561)

   4. Optional but highly recommended mods(that address issues with the main game that are not really bugs)
      - [Alternate Start - Live Another Life](http://nexusmods.com/skyrimspecialedition/mods/272)
      - [RaceMenu](http://nexusmods.com/skyrimspecialedition/mods/19080)
      - [Finding Susanna Alive - A Blood on the Ice Trigger Revision](https://www.nexusmods.com/skyrimspecialedition/mods/32512) ([Blood on the Ice Redux SE](https://www.nexusmods.com/skyrimspecialedition/mods/6126) users see Note 2. in the [Notes](#notes) section of this readme)
      - [GIST Soul Trap](http://nexusmods.com/skyrimspecialedition/mods/15755)
      - [Gladys the Corgi - A Custom Dog Follower Mod](http://nexusmods.com/skyrimspecialedition/mods/50164)
      - [Loki's Wade In Water](https://www.nexusmods.com/skyrimspecialedition/mods/42854)
      - [No BS AI Projectile Dodge](http://nexusmods.com/skyrimspecialedition/mods/1763)
      - [Notification Log SSE](https://www.nexusmods.com/skyrimspecialedition/mods/27707)
      - [ReCleaned Menu](https://www.nexusmods.com/skyrimspecialedition/mods/26680) (Creation Club users see Note 1. in the [Notes](#notes) section of this readme)
      - [SSE Parallax Shader Fix](http://nexusmods.com/skyrimspecialedition/mods/31963) (See Note 5. in [Notes](#notes).)
      - [StayAtSystemPageSE](http://nexusmods.com/skyrimspecialedition/mods/19832)
      - [Velexia's Animals are not Monsters SE](http://nexusmods.com/skyrimspecialedition/mods/32133)
      - [Wider MCM Menu for SkyUI](https://www.nexusmods.com/skyrimspecialedition/mods/22825)
      - [Whose Quest Is It Anyway](https://www.nexusmods.com/skyrimspecialedition/mods/23581)

---

## INSTALLATION

- To install Skyrim, see [Guide](https://www.reddit.com/r/skyrimmods/wiki/begin2). Read up to the end of the **Install Location** section. 
  - If you want to prepare to add mods yourself, I highly recommend reading the whole thing.
  - You do not need to install ModOrganizer 2 (MO2). SMEFT installs a portable version of MO2 with everything else. If you do have another MO2 installed, use the one SMEFT installs.

- To install SME(FT):
   1. Get the latest [Wabbajack](https://www.wabbajack.org) version.
   2. Select **Browse Modlist**.
   3. From the **Game** list, select **Skyrim Special Edition** and click the check-box for **Show Utility Lists**.
   4. At the bottom of the **SMEFT** window, click the **Download Modlist** icon.
   5. Enter a filepath in the **Installation Location** and **Download Location** fields.
         - The recommended Installation Path is an empty folder at the root of a drive, such as `D:\SMEFT`. The Download Path is updated automatically. You can change it if you want.
   6. Click the blue **Play** button.
         - Wabbajack downloads everything automatically if you have a Premium Nexus Mods account. Normal users are required to click the **Manual Download** button for each mod. Wabbajack highlights the buttons to press.
   7. After the installation completes, click **Close**.
   8. Navigate to `Game Folder Files` in the install folder specified in **Step 5**.
         - Using our previous example, the filepath is: `D:\SMEFT\Game Folder Files`.
   9. Copy the Content of `Game Folder Files` to the game folder located in `..\Steam\steamapps\common\Skyrim Special Edition`.
         - It should be a folder not located in one of the windows protected folders.
   10. Navigate to `..\SMEFT\tools\BethINI (ONLY LAUNCH WITH MO CLOSED)` and run `BethINI.exe`.
         - Make sure the game and MO2 are closed.
   11. In the **Game** list, select **Skyrim Special Edition**.
   12. In **BethINI**, click the `Setup` tab.
   13. Change the **Mod Organizer** field to point to `ModOrganizer.exe`.
   14. Select the SMEFT profile to use from the **INI Path** list.
         - BethINI will restart after applying the profile.
   15. From the **Basic** tab, select a Preset to match your hardware and ENB plans.
   16. When done, click **Save and Exit**.
         - You can come back at any time and change your BethINI settings.
   17. Run `ModOrganizer.exe`.
   18. From the **Profile** list at the top, select a profile to use.
   19. Run Nemesis now.
         1. Press `Update Engine`
         2. Press `Launch` when the engine update is done.
   21. Launch **Synthesis** and click **Run** for the pre-selected patchers. Close it when done.
         - If this step causes issues for you, check if your system has the requirements for it [here](https://github.com/Mutagen-Modding/Synthesis/wiki/Installation).
         - If you have issues on how to use it, check [here](https://github.com/Mutagen-Modding/Synthesis/wiki/Typical-Usage).

- To Launch the game from MO2, select **SKSE** from the drop-down list in the top-right and click **Run**. You can also create MO2 shortcuts to automatically launch linked binaries trough MO2.
  - Your MO2 Setup is now ready to start modding and playing the most barebone PC friendly Skyrim experience.

If you plan to run DynDOLOD, do not forget to grab the resources from the official modpage and if available the dependencies for your weather mods and the likes.

When adding Mods, look out for possible incompatibilities and the [Notes](#notes) sections below.

**Do not try to play the `SME(FT) - Installation` Profile since it is a dummy profile, for me to compile the list.**

---

## UltraWide Fix

[Complete Widescreen Fix](https://www.nexusmods.com/skyrimspecialedition/mods/1778) contains the necessary mods for UltraWide (21:9) monitor users. Download and install these mods using Mod Organizer 2. The first file is found under the `Main Files` section of the mod files page, the rest are under `Optional Files`.

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

## Notes

1. If you want to use Creation Club mods, you must disable `ReCleaned Menu - If you want to use Creation Club mods disable this!!` in your MO for the option to even be available in the main menu. Since there are more people that don't install mods from there anyway, I included this to make their menus cleaner.
2. If you want to use [Blood on the Ice Redux SE](https://www.nexusmods.com/skyrimspecialedition/mods/6126), right-click `Finding Susanna Alive` and select **Reinstall Mod** to let it install with the included patch.
3. If you addded new landscapes or altered existing ones, open and run the included Synthesis patchers.
4. I set the protection of `Essential Favorites` to disabled for disarming since it is incompatible with mods that rely on disarming.
5. Moved this fix in the recommended section due to potential incompatibilities with [Better Dynamic Snow SE](https://www.nexusmods.com/skyrimspecialedition/mods/9121) as indicated [here](https://www.nexusmods.com/skyrimspecialedition/mods/31963?tab=bugs).

---

## Reasoning and Future Plans

People asked why I haven't included mods like [unofficial performance optimized textures AKA (UPOT)](https://www.nexusmods.com/skyrimspecialedition/mods/21166), [Cleaned Skyrim SE Textures](https://www.nexusmods.com/skyrimspecialedition/mods/38775) or [Unofficial High Definition Audio Project](https://www.nexusmods.com/skyrimspecialedition/mods/18115) the short reasoning is size,
since I want this to be a fast to install collection of fixes and tools, and all of the optional mods I included are still smaller than those audio and texture optimizations.
Including a texture and the audio optimizations would triple the installation size. That said, feel free to add them on top if you plan a vanilla playthrough or think you want them.

Future plans:

- I want to update this regularly, while also updating [Tales from the Northern Lands](https://eziothedeadpoet.github.io/Tales-from-the-Northern-Lands/)
- A strong amount further in the future would be [SME(FT) - LL Edition](https://github.com/EzioTheDeadPoet/SME-FT-/issues/11) which I can see as well as very useful as a lot of LE players (active on LL) are slowly moving over to SE as well and could really benefit from this. Sadly I currently have not enough time to get to do it, as seen in the linked [Issue](https://github.com/EzioTheDeadPoet/SME-FT-/issues/11).

---

## Credits and Thanks

- _YOU_ for actually reading the readme. Thanks a ton!!
- Akalonian for making the install instructions clearer.
- Lively and LadyZeefa for encouraging me to make this list.
- ForgottenGlory for making SME(FT) possible due to his early support. 🧡
- trawzified for helping out with updates
- Halgari and everyone the WJ Team - Wabbajack is awesome and so are you.
- ALL the mod authors that made the mods featured in this list.
- Special thanks to all the other people listed [here](https://eziothedeadpoet.github.io/AboutMe/HALLOFFAME.html) that support this and other projects of mine.

## Contact

While I'm always available on the [Wabbajack Discord](https://discord.gg/wabbajack), I recommend checking the [Issues](https://github.com/EzioTheDeadPoet/SME-FT-/issues) (open **and** closed ones) on GitHub first if you have any problems. The same goes for _Enhancements_ or _Feature/Mod Requests_. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS AND I WILL BLOCK YOU**.

**DO NOT CONTACT MOD-AUTHORS WITH ISSUES OR I WILL HAVE TO TAKE ACTIONS THAT WILL RESULT IN YOU BEING BANNED FROM WABBAJACK.**

## Changelog

See [Changelog](CHANGELOG.md).

---
