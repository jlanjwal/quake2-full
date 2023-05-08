
This is the complete source code for Quake 2, version 3.19, buildable with
visual C++ 6.0.  The linux version should be buildable, but we haven't
tested it for the release.

The code is all licensed under the terms of the GPL (gnu public license).  
You should read the entire license, but the gist of it is that you can do 
anything you want with the code, including sell your new version.  The catch 
is that if you distribute new binary versions, you are required to make the 
entire source code available for free to everyone.

The primary intent of this release is for entertainment and educational 
purposes, but the GPL does allow commercial exploitation if you obey the 
full license.  If you want to do something commercial and you just can't bear 
to have your source changes released, we could still negotiate a separate 
license agreement (for $$$), but I would encourage you to just live with the 
GPL.

All of the Q2 data files remain copyrighted and licensed under the 
original terms, so you cannot redistribute data from the original game, but if 
you do a true total conversion, you can create a standalone game based on 
this code.

Thanks to Robert Duffy for doing the grunt work of building this release.

John Carmack
Id Software


Mod Info
This mod is inspired by Fire Emblem

Movement:
The mod is in first person but the direction you face has not impact on the direction
you move. Forward, backward, left, and right are all predetermined directions

Stats:
Normal rpg stat stuff
HP is how much damage you can take before you die.
Attack affects how much damage you can do in a physical class.
Magic affects how much damage you can do in the magical class.
Dexterity affects crit rate. Crits do triple damage.
Speed affects avoid rate. Avoiding lets you take 0 damage.
Defense affects how much damage you take from physical attacks.
Resistance affects how much damage you take from magical attacks.

Classes:
Berserker: High HP and Attack low everything else.
Sniper: High Dex average everything else.
Swordmaster: High Speed average everything else.
Armored Knight: High Defense low Speed and Resistance.
Sorcerer: High Magic and Resistance and low Attack.

Level System:
You gain 30 xp per kill.
Leveling up happens when you have over 100 xp.
Each class has their own growth rates based on their specialty.

Combat:
The combat is turn based.
Monsters cannot move until you attack them.
When you deal damage to a monster you will no longer be able to attack or move.
When a monster hits you, you will be able to move and attack again and they will no longer be able to move.

To Install and play:
Download from GitHub. Build the game on Visual Studio. Make a new folder in the Quake 2 directory.
Put the .dll file that you get from building the game in the new folder.
