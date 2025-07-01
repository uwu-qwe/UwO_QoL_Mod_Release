# UwO_QoL_Mod_Release
![Image](https://github.com/user-attachments/assets/8e272181-fddc-4203-b641-4445eb445e42)

## Features
• Automatic egg/plant watering.  
  *(Can only be turned on if you're the host)*

• Automatic deletion of player kobolds who have left the lobby. (Has to be actively running to keep check of player kobolds, turning it on/off will just restart it.)  
  *(Can only be turned on if you're the host)*

• Anti-grab - Nobody can grab you when it's activated. (Ideal if you're afk, also has the side effect of preventing you from being spawn-stack grabbed)  
  *(Can be turned on in any lobby)*

• Ragdoll-toggler - Toggle ragdolling on/off.

• Removes the pop-up windows when entering the main menu.  
  *(This is always on.)*

• Chat Window Size Changer - Make your chat window bigger by picking one of the options in the menu. Your selection will be saved in the config file.

• Dick As Inflator - Your dick will be able to inflate anyone's stomach, meaning their stomach capacity will grow as you cum in them when their stomach is full.

• Dick Cum Replacer - Replace your cum with other fluids types! Yep, that's it!  
  *(Can be turned on in a lobby where the host has cheats enabled.)*

• Cursor Unlocker - Instead of using TAB to show the cursor, you can now just press F3.

• ~~Gone are the days when you'd be stuck in an infinite void when joining a server that has a missing mod or mod conflict with your game... Now there's error-handling, meaning if a mod issue is raised when joining a server, you'll be booted back to the main menu with an error message containing the type of error and what mod is causing the issue.~~
*This is now part of base game.*

• Head equipment hiding feature when playing in first person camera. This will now also hide Ember's flames in first person.

• Grab Log window - You can now open a window to check who has been grabbing you! It'll show the player who grabbed you with name, ID, and the time you were grabbed.
*(This is always on, but you can toggle whether or not to show the window.)*

• Camera-based clean up tool. As host of a lobby, you can now look at objects and delete them one at a time. You can't delete players and most of the environment is not deletable.
*(This automatically turns on when you are the host of a lobby.)*

All of these features are toggleable mid-game, with the exception of not being able to toggle anti-grab when actively being grabbed.
The menu window can be dragged around the screen to be somewhere else. The window position will be saved upon closing the game, so it'll be in the same place next time.

## Installation if BepInEx IS NOT installed
1. Unpack the contents of `Bepin QoL.7z` into your KoboldKare game folder (where the .exe is).
2. Run the game and it should work!

## Installation if BepInEx IS installed
1. Ensure you have the Dllstouse folder in your KoboldKare game folder (can be found in `Bepin QoL.7z`).
2. Put the `UwO_QoL_Mod_vX.Y.Z.dll` in the plugins folder (Should be in `KoboldKare\BepInEx\plugins`).
3. Run the game and it should work!

## How to use
Press `F7` (default, can be changed) to show/hide the QoL menu. You can drag it wherever you want on the screen and it'll remember the position for next time you boot up the game.

## Configuration & Default Shortcuts
Cursor Unlocker: `F3`  
Anti-grab shortcut: `LeftAlt + V`  
Water system shortcut: `LeftAlt + B`  
Player clean-up shortcut: `LeftAlt + N`  
Ragdoll-toggling shortcut: `LeftAlt + R`

Select Object: `Insert`  
Deselect Object: `Home`  
Delete Object: `Delete`

These shortcuts can be configured in `\KoboldKare\BepInEx\config\UwO_QoL_Mod.cfg` after running the game once with my plugin.
