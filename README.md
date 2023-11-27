# Not Enough Items Rozmirs Fork

A survival-friendly version of the Not Enough Items mod. Cheat-free when cheats are disabled in a world.

This is a modified version of Not Enough Items GTNH mod v2.0.1.

 

## Modifications to Original Mod:
* Removed Mob Spawners from NEI item panel to fix visual bug when rendering Wither spawner item.

* Removed the bookmarks panel because it was unnecessary.

* Renamed mod and modified neimod.info accordingly.

* Removed update checker.

* Renamed "Supporters:" to "Supporters of Original Mod:" in mod info, to differentiate from the original mod.


* Removed color from "No installed plugins.".

 
## Incompatability with following Mods:
Thaumcraft NEI Plugin - Will crash when auto-fill crafting in Arcane Workbench.

Lesser Issues:
	Optifine    or    Just Another Spawner  -  The light level overlay feature will not work, but all other features still work fine.



## Note for Developers:
When you press "Run Client" for the first time with this project in Eclipse, you will be prompted with a window which says "Select an mcp config dir for the deobfuscator".


When this happens, in the window select the following folder location on your computer (don't include quotation marks):

	~/.gradle/caches/minecraft/net/minecraftforge/forge/<version>/unpacked/conf

(replace ~ with %USERPROFILE% if using a Windows computer).