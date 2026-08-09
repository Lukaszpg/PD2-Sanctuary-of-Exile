
# Project Diablo 2: Sanctuary of Exile

Discord: https://discord.gg/CwN2s6AHSZ

## Wiki

Wiki is available on: http://wiki.sanctuaryofexile.com

## Credits

First and foremost, I would like to thank the amazing PD2 team, their work and immense dedication is something that should be admired. Without them this "mod of a mod" would not be possible.

I would also like to thank Derek for his truly awesome models and spells - please check out his website [here](https://www.derekplus.com/).

## Known bugs

- Making corrupted items sacred can sometimes crash the game
    - No know solution for now. Make item's sacred before corrupting
- Using catalyst shard on a map before chiseling it will make map unable to be chiseled
    - Always chisel the map as last step 

## About this mod

This mod is an extension to my another project, [Project Diablo 2: Single Player+](https://github.com/Lukaszpg/PD2-Single-Player-Plus-mod). While Single Player+ contains only single player quality of life features without touching the balance, Sancutary of Exile expands on rich fundamentals od SPP+ and Vanilla PD2 by adding new ways of developing your character.

## Multiplayer

This mod was not made with multiplayer games in mind and was not tested. Most likely will not work properly in TCP/IP.

## Compatibility disclaimer

This mod is NOT compatible with characters from Single Player+ or vanilla Project Diablo 2. You have to: 

* start from scratch - create new character
* remove your shared stash file

Rule of thumb: just make sure that before starting to play Sanctuary of Exile you have empty "Save" folder.

## How to install

**IMPORTANT!** Using PlugY is **NOT RECOMMENDED** as it is out dated and breaks many features of the mod.

There are two ways to install this mod - manual or by using dedicated launched (HIGHLY recommended).
If you would like to use the launcher, head to [launcher repository](https://github.com/Lukaszpg/pd2-sanctuary-of-exile-launcher) and follow the instructions.
Launcher currently is supported only on Windows OS. If you have any other operating system, please follow manual installation istructions below: 

1. Head to [official PD2 site](https://www.projectdiablo2.com/download) and follow instructions (point 6 on that site can be disregarded).
2. Head to "Releases" and download most recent version of this mod. There are modes - Standard and Damnation - differences are described on the [Wiki](https://lukaszpg.github.io/TheArchivistSoE/).
   
   a.  Files you have to download for Standard mode:
   
       - BH.DLL
   
       - ProjectDiablo.DLL
   
       - pd2assets.mpq
   
       - pd2maps.mpq
   
       - pd2data.mpq
   
   b. Files you have to download for Damnation mode:
   
       - BH.DLL
   
       - ProjectDiablo-Damnation.DLL
   
       - pd2assets.mpq
   
       - pd2maps.mpq
   
       - pd2data-Damnation.mpq
   
3. Paste the downloaded files to ProjectD2 folder at your client directory, that you've installed at step 1. If you downloaded the Damnation Mode files, remove the -Damnation from name of `ProjectDiablo-Damnation.DLL` and `pd2data-Damnation.mpq`.
4. **IMPORTANT!** Launch PD2 Launcher through the shortcut created in step 2, head to options and click "Disable Updates". Close options. Click Play.
5. Use the recommended [loot filter by HiimMark](https://github.com/Maaaaaarrk/HiimFilter-PD2-Filter/tree/main/filtergroups/sancofexile) or adjust your personal loot filter, using new items codes on the bottom of this page (loot filter knowledge required):
   
    a. Download the filter you would like to use from the link above (Sancofexile.filter is recommended).
   
    b. Paste it into `<installation_directory\ProjectD2\filters\local`.

    c. Launch official PD2 launcher, go to `Item Filter Profiles -> Select Local Filter -> Select the file you have pasted in subpoint b.`
   
7. Head to Akara and look for a green potion that has "Sanctuary of Exile" in the description. If it's there, mod was installed successfully. In the main menu, the bottom left corner should have information about game version, either `SoE XX.X.Y` for Standard mode and `SoE XX.X.YD` for damnation mode. GLHF!

## Troubleshooting

1. I have launched the mod, but I am getting "Bad Inventory Data" error.

**Solution:** Make sure that you don't have incompatible items in your stash and characters in your save folder. Whenever there is save-breaking change, it WILL be announced long before the patch is released. See: [Compatibility Disclaimer](https://github.com/Lukaszpg/PD2-Sanctuary-of-Exile/?tab=readme-ov-file#compatibility-disclaimer)

2. I have launched the mod, but the game is crashing to desktop with **Diablo II unhandled exception : access_violation (c0000005)**

**Solution:** See point 2. If the character loads but at random you are getting these errors, please make a ticket on Discord.

3. My game crashes whenever I hoover over an item:

**Solution:** Use the recommended loot filter described in installation instructions points 5 & 6. If this does not fix the issue, please make a ticket on Discord.

## Saves compatibility table

In the table below you can check saves from which mod versions are going to work.

How to read the table: 

1. Check the rows for the "Version" column - pick a version you are interested to migrate from.
2. Check the column headers - pick version you are interested to migrate to.
3. Read the intersection cell between the versions. 

 ✅ - means that your save will be compatible if you migrate from this version to the version of your choosing
 
 ❌ - means that your save will NOT be compatible

 〰️ - means you are migrating from same version to same version, save is compatible

Example:

I would like to migrate from version 11.2.1 to 12.0.0. I am looking for the row which says "11.2.1" on the left. Now I am looking at the column header which says "12.0.0". I am checking the intersection table cell between the two. It's ✅, so my save will work. 

Example 2: 

I would like to migrate from version 12.0.6b to 12.1.0. I am looking for the row which says "12.0.6b" on the left. Now I am looking at the column header which says "12.1.0". I am checking the intersection table cell between the two. It's ❌, so my save will NOT work.

| Version 	| 11.0.0 	| 11.0.1 	| 11.0.2 	| 11.0.3 	| 11.1.0 	| 11.2.0 	| 11.2.1 	| 11.2.1a 	| 11.2.1b 	| 11.2.1c 	| 12.0.0 	| 12.0.1 	| 12.0.2 	| 12.0.3 	| 12.0.4 	| 12.0.5 	| 12.0.6 	| 12.0.6b 	| 12.1.0 	| 13.0.0 	| 13.0.1 	| 13.0.2 	|
|---------	|--------	|--------	|--------	|--------	|--------	|--------	|--------	|---------	|---------	|---------	|--------	|--------	|--------	|--------	|--------	|--------	|--------	|---------	|--------	|--------	|--------	|--------	|
| 11.0.0  	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.0.1  	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.0.2  	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.0.3  	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.1.0  	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.2.0  	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.2.1  	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅       	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.2.1a 	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️      	| ✅       	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.2.1b 	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| 〰️      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 11.2.1c 	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ✅       	| 〰️      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.0  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.1  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.2  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.3  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.4  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.5  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅      	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.6  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️     	| ✅       	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.0.6b 	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| ✅      	| 〰️      	| ❌      	| ❌      	| ❌      	| ❌      	|
| 12.1.0  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| 〰️     	| ❌      	| ❌      	| ❌      	|
| 13.0.0  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| 〰️     	| ✅      	| ✅      	|
| 13.0.1  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ✅      	| 〰️     	| ✅      	|
| 13.0.2  	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌       	| ❌       	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌      	| ❌       	| ❌      	| ✅      	| ✅      	| 〰️     	|

## Contents of this GitHub repository

Folder description: 

- Assets - contains ONLY assets that were added or modified in Sanctuary of Exile. To properly build asset MPQ archive, merge these files with vanilla PD2 assets - overwrite if necessary
- Maps - contains ONLY maps that were added or modified in Sanctuary of Exile. To properly build maps MPQ archive, merge these files with vanilla PD2 assets - overwrite if necessary
- Standard-mode/data - contains all .txt files for modified and non-modified data files for Standard Mode
- Damnation-mode/data - contains all .txt files for modified and non-modified data files for Damnation Mode


