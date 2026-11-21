Made with Gemini and some minor help by Opus

Copy the folder from the archive to /PSP/GAME.

Control version 0.2, dated 11/15/26:
CONTROLS (WITH THE HUD HIDDEN)

Analog stick – move forward/backward and strafe left/right

D-Pad Left/Right – rotate camera (also Square/Circle)

D-Pad Up/Down – tilt camera up/down (down also X)

R – attack

L – run (hold)

L + R – jump

Start – action: open door, pull lever, search corpse

Triangle – open inventory (press again while in the menu to open the character sheet)

L + Triangle – open quest log and tutorial

Select – show/hide HUD

L + Select – noclip

CONTROLS (WITH THE HUD VISIBLE)

Use the D-Pad to select icons

X — select

Portrait — character sheet (press the square button to open quest log)

Options — settings menu

Star — spellbook

Hand/eye/etc — environment interaction mode (cycle options using Square)

Sacks — inventory

Swords — attack

Hand with magic stick — Quest log (press the square button to repeat a spell)

Feet — movement mode (Walk/Run/Sneak)

Scroll — 3D dungeon map (press the square button to open quest log)

Campfire — rest

INVENTORY

Navigate using the D-Pad

X — select

Triangle — move weapon to the other hand

Square — quick-drop an item

Circle or Start — close the inventory

11/21/26, Version 0.4.1:

Updates:
The same ver. 0.4 but with fixed dungeon code (it turns out that a lot of dungeons were generated with slightly wrong geometry) and fixed performance issues on the physical PSP. Game works at 30 FPS (or even higher), and it still will slow down to 15-20 FPS if dungeon is too large (bigger than Privateer's Hold-tier, so not really big amount of such dungeons).

This release will be last "dungeon-only" version.

11/20/26, Version 0.4 (Won't work on PSP-1000, experimental version):

Updates:
A number of relatively minor changes, such as gold/inventory weight limits, immobility when overencumbered, fatigue exhaustion, death (instead of respawn you will thrown into main menu), fixed accessory equipment slot mapping (amulets, rings, bracers, marks, torcs), mechanisms in dungeons (moving bridges, platforms, teleports, traps, etc), finished spells and special features of NPC, ambient sounds in dungeons, etc...

Known problems:
While tests on PPSSPP went well, issues arose on actual PSP due to changes in the dungeon-loading code. Memory-related problems—such as glitches in combat animations, missing inventory icons, and the loss of collision detection, were resolved on the PSP-3000 by rebuilding the EBOOT with the `PSP_LARGE_MEMORY = 1` parameter. However, purely CPU-related issues, specifically unresponsive controls and a drop in framerate to 15–20 FPS in areas containing more than one NPC, will be addressed in version 0.5.  

Consider version 0.4 an experimental release; if you want a stable gaming experience, go with version 0.3, it works well, at least on the PSP-3000, and even in its less finished state, version 0.3 is already an unique dungeon crawler with no equivalent on the PSP.

11/19/26, Version 0.3:
Updates:
1. In addition to Privateer's Hold, it is now possible to travel to random dungeons from anywhere in the game. An "extra start" option is available in the menu, which places a random character in a random dungeon. Furthermore, exiting any dungeon (including one in Privateer's Hold) will now trigger a transition to a random dungeon; the game will suggest [dungeon] located in [region]. You may decline this offer, and the next time you trigger the transition, you will be presented with a different random dungeon.
2. You can now view weapon stats in your inventory without needing to pick up each item; a gear degradation system has also been introduced.
3. Improved AI for NPCs.
4. Other minor additions such as dungeon water level parsing, animated water surfaces, swim speed and encumbrance sinking, underwater breath, Water Breathing magic, wall climbing (with skill/race checks and climbing out of water), Steal-mode Lockpicking and door bashing, Open/Climbing/Jumping/Water Breathing/Comprehend Languages spells, monster metal immunities, fixed voice for female player, disease/poison/paralysis mechanics, sprinting drains stamina, etc...
5. Reducing NPC activity at distances greater than 15 meters from the player has increased the FPS on the PSP to 25–30.

11/15/26, Version 0.2:
Updates:
1. Controls fixed: walking is no longer dependent on the camera's orientation.
2. Game menu, including an introductory video and a character creation system.
3. Quest system (currently featuring an initial quest) with an opening message about a shipwreck, a quest log, and a tutorial.
4. Added books that can be read.
5. Character progression system, including all skills.
6. Adjusted the loot and treasure drop system; also updated NPC sounds.
7. The armor system has been fixed.

11/14/26:
At the moment, the game includes only Privateer's Hold. Basic mechanics have been implemented, including dungeon exploration, combat, looting, skill and level progression (though I don’t plan on testing this progression system in any serious capacity yet—it was added primarily to support the loot system), and character death. Upon exiting the dungeon, you are returned to the starting point. 

The full armor specifications are not yet finalized; for now, the pieces of armor differ only in color (though the weapons have been fully developed).

There are some differences compared to the original game. Specifically, once the music in a dungeon ends, it will be replaced by a track chosen at random from a pool of dungeon-themed pieces and the loot here is a bit more random than in the original. An agent implemented this, and I decided to keep it.

Tested on PPSSPP and an actual PSP-3000. Naturally, while PPSSPP delivers a smooth, fast image, the PSP runs at around 20–25 FPS—much like a subpar computer from the era when TES II was first released.












- [GitHub Repository](https://github.com/Gixel225/Daggerfall-for-PSP)
- [Download Releases](https://github.com/Gixel225/Daggerfall-for-PSP/releases)
