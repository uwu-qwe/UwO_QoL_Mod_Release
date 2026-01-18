# UwO_QoL_Mod_Release
![Image](https://github.com/user-attachments/assets/2f4c49fd-580f-4f4b-8cb3-e15c65b2fb7c)

## Features
• Automatic egg/plant watering.  
  *(Can only be turned on if you're the host)*

• Automatic deletion of player kobolds who have left the lobby. (Has to be actively running to keep check of player kobolds, turning it on/off will just restart it.)  
  *(Can only be turned on if you're the host)*

• Anti-grab - Nobody can grab you when it's activated. Also has the side effect of preventing you from being spawn-stack grabbed. A seperate button is added to prevent people from using the swapping command on you if you have anti-grab turned on.
  *(You're not able to toggle anti-grab when actively being grabbed.)*

• Ragdoll-toggler - Toggle ragdolling on/off.

• Removes the pop-up windows when entering the main menu.  
  *(This is always on.)*

• Chat Window Size Changer - Make your chat window bigger by picking one of the options in the menu. Your selection will be saved in the config file.

• Dick As Inflator - Your dick will be able to inflate anyone's stomach, meaning their stomach capacity will grow as you cum in them when their stomach is full.

• Dick Cum Replacer - Replace your cum with other fluids types! Yep, that's it!  

• Cursor Unlocker - Instead of using TAB to show the cursor, you can now just press F3.

• Head equipment hiding feature when playing in first person camera. This will now also hide Ember's flames in first person.

• Grab Log window - You can now open a window to check who has been grabbing you! It'll show the player who grabbed you with name, ID, and the time you were grabbed.
  *(This is always on, but you can toggle whether or not to show the window.)*

• Camera-based clean up tool. As host of a lobby, you can now look at objects and delete them one at a time. You can't delete players and most of the environment is not deletable.
  *(This automatically turns on when you are the host of a lobby.)*

• Event Log window - As host you can now open a window to check who has been grabbing who, who has been spawning objects and deleting them. This includes yourself in case of grabbing.
  ⚠️ *(This feature is still a bit experimental and can cause instability or even crash, so use at your own risk.)* ⚠️
  *(It is togglable by the square toggles in the window and is off by default.)*

• Automatic chat tag sanitizer that scrubs tags out of names of people who join/leave a lobby. It only applies to the actual join/leave message in chat.

• Automatic self-grab enabler that enables self-grabbing on some maps that have it disabled.

• "Goofs" menu where you can toggle ragdoll anti-gravity, use slightly larger text or smaller text when chatting, or even slow down time.
  ⚠️ *(These were not made with stability in mind, so use at your own risk.)* ⚠️

• Ragdoll tail collision toggle is now a thing. Turning it on will prevent your tail from colliding with the game world.
  *(This does not apply to collision with players. They will still feel your tail pushing them.)*
  *(This feature does not work with the Viper mod.)*

• Drop-down menu scaler. When selecting the menu for changing kobold type (Options --> Kobold) it will now make selection list much larger and easy to scroll down.

• Posing break prevention! There is now an option (turned on by default) that prevents you from grabbing people (it only affects players) who are *not* posed by you (but still posed). This will help prevention breaking other people's poses or putting them into an animation station if they are near one.

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
Anti-gravity ragdoll toggle shortcut: `LeftAlt + B`  
Ragdoll toggle shortcut: `LeftAlt + R`  
Tail collision toggle shortcut: `LeftAlt + N`

*For the camera-based clean up tool:*
Select Object: `Insert`  
Deselect Object: `Home`  
Delete Object: `Delete`

These shortcuts can be configured in `\KoboldKare\BepInEx\config\UwO_QoL_Mod.cfg` after running the game once with my plugin.
