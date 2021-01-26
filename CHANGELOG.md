---
description: Here you can find a list of changes made during each update.
---
# Changelog

## 21.01.26 Hotfix 1: SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

- fixed ini settings in Engine Fixes

## 21.01.26: SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

- added
  - [Dynamic Distant Objects LOD - DynDOLOD](https://www.nexusmods.com/skyrim/mods/59721)
    - This does **NOT** include the resources found on the same modpage.

- updated
  - [Assorted mesh fixes](https://www.nexusmods.com/skyrimspecialedition/mods/32117)
  - [Engine Fixes](http://nexusmods.com/skyrimspecialedition/mods/17230)
  - [Equip Enchantment Fix](https://www.nexusmods.com/skyrimspecialedition/mods/42839)
  - [hank's gamepad and controller fixes](https://www.nexusmods.com/skyrimspecialedition/mods/42492)

## 21.01.20: SME(FT) - Skyrim Modding Essentials (Fixes & Tools) Same Day Update

I was so eager to push that important update to make the general check for updated mods so I will just push a second update today.

- updated
  - [Assorted mesh fixes](https://www.nexusmods.com/skyrimspecialedition/mods/32117)
  - [BodySlide and Outfit Studio](http://nexusmods.com/skyrimspecialedition/mods/201)

## 21.01.20: SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

- fixed
  - DLL Plugin Loader was setup wrong causing multiple fixes to not load (re-copy all contents from `Game Folder Files` into your game folder.)
    - **If you used SME(FT) as a base your for a modlist you intend to use for Wabbajack, then install this update in a different location and copy the `Game Folder Files` folder into your current setup and the `downloads` of this version into your modlist (this fix needs a dummy file downloaded that would miss during your compile attempts otherwise), so your users get the fix as well!**
    - thanks to the people(or person) repeatedly asking the question why `Custom Skills Framework` wasn't working with this setup, for making me notice this issue.

- changed
  - set the protection of `Essential Favorites` to be disabled for disarming, since it would be incompatible with mods that rely on disarming.
  - moved `SSE Parallax Shader Fix (BETA)` to the recommended section, since it seems to have some incompatibilities with the latest version of [Better Dynamic Snow SE](https://www.nexusmods.com/skyrimspecialedition/mods/9121) as indicated [here](https://www.nexusmods.com/skyrimspecialedition/mods/31963?tab=bugs).

## 21.01.17: SME(FT) - Skyrim Modding Essentials (Fixes & Tools) Same Day Update

- removed
  - [SSE Fixes](https://www.nexusmods.com/skyrimspecialedition/mods/10547) (Covered by engine fixes)
  
## 21.01.17: SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

- changed
  - [hank's gamepad and controller fixes](https://www.nexusmods.com/skyrimspecialedition/mods/42492) (disabled due to some weird camera behavior during conversations while scrolling with the mouse wheel)

- added
  - [Whiterun texture memory usage reduction](https://www.nexusmods.com/skyrim/mods/79995)
  
- updated
  - [Assorted mesh fixes](https://www.nexusmods.com/skyrimspecialedition/mods/32117)
  - [Enhanced Reanimation](https://www.nexusmods.com/skyrimspecialedition/mods/43500)
  - [Synthesis](https://github.com/Mutagen-Modding/Synthesis)

## 20.12.24: SME(FT) - Skyrim Modding Essentials (Fixes & Tools)

- replaced
  - [Protect Your People SE](http://nexusmods.com/skyrimspecialedition/mods/10297) with a Synthesis Patch
  - [Dragon Stalking Fix](http://nexusmods.com/skyrimspecialedition/mods/14060) with [Fixed Dragon Stalking Fix](https://www.nexusmods.com/skyrimspecialedition/mods/37230)
  - [Mator Smash](http://nexusmods.com/skyrim/mods/90987) with [Unofficial Mator Smash Updated](https://www.nexusmods.com/skyrimspecialedition/mods/39378)

- added
  - [Equip Enchantment Fix](https://www.nexusmods.com/skyrimspecialedition/mods/42839)
  - [Enhanced Reanimation](https://www.nexusmods.com/skyrimspecialedition/mods/43500)
  - [Essential Favorites](https://www.nexusmods.com/skyrimspecialedition/mods/42997)
  - [Favorite Misc Items](https://www.nexusmods.com/skyrimspecialedition/mods/42750)
  - [hank's gamepad and controller fixes](https://www.nexusmods.com/skyrimspecialedition/mods/42492)
  - [Logical Outfits and Classes for The Dark Brotherhood Forever](https://www.nexusmods.com/skyrimspecialedition/mods/43483)
  - [Loki's Wade In Water](https://www.nexusmods.com/skyrimspecialedition/mods/42854)

- updated
  - [Alternate Start - Live Another Life](http://nexusmods.com/skyrimspecialedition/mods/272)
  - [deorder's MO2 Plugins](https://github.com/deorder/mo2-plugins)
  - [Dwemer Gates Don't Reset](https://www.nexusmods.com/skyrimspecialedition/mods/26331)
  - [Unofficial Skyrim Special Edition Patch](http://nexusmods.com/skyrimspecialedition/mods/266)
  - [SSE Parallax Shader Fix](http://nexusmods.com/skyrimspecialedition/mods/31963) (Terrain Beta added)

## 20.11.19 h1: SMEF(FT) - Skyrim Modding Essentials (Fixes & Tools)

- cleaned the Dawnguard.esm (I missed some records the 1st time around)

## 20.11.19: SMEF(FT) - Skyrim Modding Essentials (Fixes & Tools)

- initial UI release
