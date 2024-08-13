# Not Enough Items Rozmirs Fork

A survival-friendly version of the Not Enough Items mod for 1.7.10. Cheat-free when cheats are disabled in a world.

This project is a modified version of the Not Enough Items GTNH mod v2.0.1 and is licensed under the GNU Lesser General Public License v3.0.

<br>
<br>

## Modifications to Original Mod:
* Removed Mob Spawners from NEI item panel to fix visual bug when rendering Wither spawner item.

* Removed the bookmarks panel because it was unnecessary.

* Renamed mod and modified neimod.info accordingly.

* Removed update checker.

* Renamed "Supporters:" to "Supporters of Original Mod:" in mod info, to differentiate from the original mod.

* Removed color from "No installed plugins.".

<br>
<br>

## Requires the following Mods to work in Minecraft:
**CodeChickenCore-1.7.10-1.0.7.48** (official version) - https://www.curseforge.com/minecraft/mc-mods/codechickencore/files/3293859

**CodeChickenLib-1.7.10-1.1.5.5** (GTNH version) - https://www.curseforge.com/minecraft/mc-mods/codechickenlib-unofficial/files/4192688

<br>
<br>
 
## Incompatability with the following Mods:
**Thaumcraft NEI Plugin** - Will crash when auto-fill crafting in Arcane Workbench.

Lesser Issues: **Optifine**    or    **Just Another Spawner**  -  The light level overlay feature will not work, but all other features still work fine.

<br>
<br>

## Note for Developers:
When you press "Run Client" for the first time with this project in Eclipse, you will be prompted with a window which says "Select an mcp config dir for the deobfuscator".


When this happens, in the window select the following folder location on your computer:

	~/.gradle/caches/minecraft/net/minecraftforge/forge/<version>/unpacked/conf

(Replace ~ with %USERPROFILE% if using a Windows computer.)

<br>
<br>

## Use of anatawa12's Fork of ForgeGradle 1.2 within Project:
The source code of this project uses anatawa12's fork of ForgeGradle 1.2 as a library under the GNU Lesser General Public License v2.1 (https://choosealicense.com/licenses/lgpl-2.1/).

Compiled versions of this mod are permitted under section 5 of the original license, "A program that contains no derivative of any portion of the Library, but is designed to work with the Library by being compiled or linked with it, is called a "work that uses the Library". Such a work...is not a derivative work of the Library"; consequently the conditions of the original license do not apply to the work.

The source code of this mod is permitted under section 6 of the original license, "you may also combine or link a "work that uses the Library" with the Library to produce a work containing portions of the Library, and distribute that work under terms of your choice" provided that:
* Private modifications are allowed.
* Notice is given that the Library is used and a copy of it's original license is provided.
* Access is provided to the source code of the Library.


The source code for anatawa12's fork of ForgeGradle 1.2 can be found here: https://github.com/anatawa12/ForgeGradle-1.2
