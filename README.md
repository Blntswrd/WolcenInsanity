# WolcenInsanity

A Mod for the Game "Wolcen", which aims to increase the level caps and item drop values, towards insanity. Currently supporting itemdrops until level 9999, proper mobs and affixes to come. 

Currently only a few select levels are usable from the menu (Currently one more "Ascended" difficulty behind the original one), this should change in the future. Same with the item affixes, those have no progression yet and are totally unbalanced. Items from level 190 and 1337 can drop the same values, high rolls are mostly only the original value times ten. 

Besides that, there are a few modifications listed below under Optional, like the overpowered savegame, item changes or skill changes.

Due to the way mob levels are hardcoded, mobs only have proper values until level 190, above they only have 1HP and do little damage. I did not yet have time to write a script to extend mob levels for all the mob types.


## How to install? 

All folders except "savegames" shall be copied into the "Wolcen\Game" folder, so that you for example have the folder "Wolcen\Game\Umbra".
Those folders are the unpacked and modified equivalent of the respective .pak file. The folders will be read with priority when playing offline. This way the mods will not be overwritten when the game updates. Normally no files should be replaced, unless you are updating the mod or have oder mods already installed.

If this does not work, create, for every folder under "Game" a .zip file and rename it .pak, replacing the original one. (Don't forget the backup, also this way you should never attempt to go online and with every update the mod will be overwritten.)

Also check optional below for files to remove and the optional savegame.

## Optional

### Savegame 

You can copy the savegame folder to "C:\Users\[Your Username]\Saved Games\Wolcen" for ease of play and debugging purposes. 
"playerdata.json" Unlocks every endgame feature and all map difficulties, this will overwrite your existing progress, feel free to skip this if you don't want to. 

Under characters is the Test.json file of the character, after pasting it you will find it in the game to play. This character has very fast movement and attack speed, good area clear and very high damage to make sure every map area of every level is easily playable. Watch out for the Havoc Orb, it will destroy your framerate for a short while, especially on slower machines. This is due to the projectiles modifier on one of the weapons and the skill modifiers.

### Modified item quantity in DifficultyMode

The item quantity is highly increased due to the file "\Umbra\Gameplay\DifficultyMode\normal.xml". If you prefer less drops or it causes too many performance problems feel free to delete the file or change the value. (Rarity chances are unchanged)


### Slightly modified passive tree

The passive tree is currently slightly modified, currently only a projectile number node is changed, if you prefer the original tree you can delete the entire "\Umbra\Skills\Passive" folder. The tree will likely be changed in the future to make it stronger and more exiting to play. 

### All active skill modifiers are free (you can enable all at once)

If you prefer to use the original, more restricted use of the modifiers, you can delete the entire "\Umbra\Skills\Trees\ActiveSkills" folder. 

### Legendaries and Rares have more affixes, Magics have low socket chance

To make items more exiting, most items have now a chance to get more affixes and magic items have a low chance for sockets. 
If you don't like this feel free to alter or delete "\Game\Umbra\Loot\PrefixSuffixParams.xml". 

---
Feel free to contribute and modify :D
