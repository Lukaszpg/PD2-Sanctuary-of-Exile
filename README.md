
# Project Diablo 2: Sanctuary of Exile

Discord: https://discord.gg/CwN2s6AHSZ

Wiki: http://wiki.sanctuaryofexile.com

## Credits

First and foremost, I would like to thank the amazing PD2 team, their work and immense dedication is something that should be admired. Without them this "mod of a mod" would not be possible.

I would also like to thank Derek for his truly awesome models and spells - please check out his website [here](https://www.derekplus.com/).

## Known bugs

- Eternal Coin does not have a name in the inventory
    - No known solution for now
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

Head to [launcher repository](https://github.com/Lukaszpg/pd2-sanctuary-of-exile-launcher) and follow the instructions. This works right now only on Windows OS. If you have other operating system, please follow manual installation istructions below: 

a) With PlugY:

1. Copy your Diablo 2 game with Project Diablo 2 mod installed to a new directory.
2. Install PD2 Plugy for SP by BetweenWalls: https://github.com/BetweenWalls/PD2-PlugY#pd2-plugy. WARNING - The materials tab introduced in S11 tab will not work with Plugy! 2a. If you already have Plugy installed and played previous versions of this mod, please remove the contents of shared stash and create a new character.
3. Head to "Releases" and download most recent version of this mod.
4. Paste the downloaded "pd2data.mpq" file to ProjectD2 folder at your client directory, that you've created at step one.
5. Create a shortcut to "Plugy.exe" from your ProjectD2 folder. Add "-3dfx -plugy" run parameter to your Plugy.exe shortcut.
6. Use the recommended loot filter from "Releases" (just paste the downloaded loot.filter file to your D2 client ProjectD2 folder) or adjust your personal loot filter, using new items codes on the bottom of this page (loot filter knowledge required).
7. Launch the game through the PlugY shortcut created in step 6.
8. Head to Akara and look for an item with Alkor's quest potion graphics. If it's there, mod was installed successfully. GLHF!

b) Without PlugY:

1. Copy your Diablo 2 game with Project Diablo 2 mod installed to a new directory.
2. Create shortcut for PD2 Launcher from the new directory.
3. Head to "Releases" and download most recent version of this mod.
4. Paste the downloaded "pd2data.mpq" file to ProjectD2 folder at your client directory, that you've created at step 1.
5. Use the recommended loot filter from "Releases" (just paste the downloaded loot.filter file to your D2 client ProjectD2 folder) or adjust your personal loot filter, using new items codes on the bottom of this page (loot filter knowledge required).
6. IMPORTANT Launch PD2 Launcher through the shortcut created in step 2, head to options and click "Disable Updates". Close options. Click Play.
7. Head to Akara and look for an item with Alkor's quest potion graphics. If it's there, mod was installed successfully. GLHF!

## Troubleshooting

1. I have launched the mod through PlugY exe, but it's not working with an error pictured below.

![image](https://github.com/user-attachments/assets/5147e3cc-6e4b-49cd-9a65-bee7476d7dfb)

**Solution:** Open PlugY.ini file in your ProjectD2 directory, look for `ActiveShiftClickLimit=1` and change it to `ActiveShiftClickLimit=0`. 

2. I have launched the mod, but I am getting "Bad Inventory Data" error.

**Solution:** Make sure that you don't have incompatible items in your stash and characters in your save folder. Whenever there is save-breaking change, it WILL be announced long before the patch is released. See: [Compatibility Disclaimer](https://github.com/Lukaszpg/PD2-Sanctuary-of-Exile/?tab=readme-ov-file#compatibility-disclaimer)

3. I have launched the mod, but the game is crashing to desktop with **Diablo II unhandled exception : access_violation (c0000005)**

**Solution:** See point 2. If the character loads but at random you are getting these errors, please make a ticket on Discord: https://discord.com/channels/1378780110274035962/1459215364385673377.


