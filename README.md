Made with Gemini and some help by Opus, GLM and Deepseek.

Copy the folder from the archive to /PSP/GAME. The program looks for the TES II files (the `arena2` and `music` directories) relative to the folder from which it is launched.

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

11/14/26:
At the moment, the game includes only Privateer's Hold. Basic mechanics have been implemented, including dungeon exploration, combat, looting, skill and level progression (though I don’t plan on testing this progression system in any serious capacity yet—it was added primarily to support the loot system), and character death. Upon exiting the dungeon, you are returned to the starting point. 

The full armor specifications are not yet finalized; for now, the pieces of armor differ only in color (though the weapons have been fully developed).

There are some differences compared to the original game. Specifically, once the music in a dungeon ends, it will be replaced by a track chosen at random from a pool of dungeon-themed pieces and the loot here is a bit more random than in the original. An agent implemented this, and I decided to keep it.

Tested on PPSSPP and an actual PSP-3004. Naturally, while PPSSPP delivers a smooth, fast image, the PSP runs at around 20–25 FPS—much like a subpar computer from the era when TES II was first released.

11/15/26, Version 0.2:
Updates:
1. Controls fixed: walking is no longer dependent on the camera's orientation.
2. Game menu, including an introductory video and a character creation system.
3. Quest system (currently featuring an initial quest) with an opening message about a shipwreck, a quest log, and a tutorial.
4. Added books that can be read.
5. Character progression system, including all skills.
6. Adjusted the loot and treasure drop system; also updated NPC sounds.
7. The armor system has been fixed.
