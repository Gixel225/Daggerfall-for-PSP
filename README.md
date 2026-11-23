Made with Gemini and some minor help by Opus

Copy the folder from the archive to /PSP/GAME.

Controls

HUD Bar Hidden

| Input | Action |
| --- | --- |
| Analog Stick | Move forward/back & strafe left/right (`0.16` radial deadzone); steers climb/pitch angle when Levitating or Swimming |
| D-Pad Left / Right or `□` / `○` | Turn camera left / right |
| D-Pad Up / Down | Look up / look down |
| `✕` | Look down |
| `L` (Hold) | Sprint |
| `R` (Tap) | Attack |
| `L` + `R` | Jump / release wall climb (press); float or swim straight up while Levitating or Swimming (hold) |
| Hold Stick Forward at Wall | Auto wall-climbing; pull Back (or press `L` + `R`) to disengage |
| `START` | Context interact (open/close doors, levers, loot corpses/containers, read shelves, enter/exit dungeons, interact with NPCs & animals) |
| `△` | Open Inventory |
| `L` + `△` | Open Quest Journal & Tutorial Logbook |
| `L` + D-Pad Down | Open Status Info popup (Page 1: Location/Region/Date/Time; press `✕` for Page 2: Health & Active Effects) |
| `SELECT` | Toggle HUD Bar |
| `L` + `SELECT` | Toggle Noclip |

Noclip

| Input | Action |
| --- | --- |
| Analog Stick or D-Pad | Turn & pitch camera |
| `△` / `✕` | Fly forward / backward along camera look direction |
| `R` / `L` | Fly straight up / straight down |
| `L` + `SELECT` | Return to Walk Mode |

HUD Bar opened

| Input | Action |
| --- | --- |
| D-Pad | Highlight one of the 11 HUD slots |
| `✕` | Activate highlighted slot:<br>`[0]` Portrait: Character Sheet • `[1]` OPTION: Options Menu • `[2]` Star: Spellbook • `[3]` Eye/Hand/etc: Execute Interaction Mode • `[4]` Sacks: Inventory • `[5]` Swords: Attack • `[6]` Hand with magic stick: Quest Journal and recast spell • `[7]` Feet: Cycle Movement Mode (Walk / Run / Sneak) • `[8]` Map Scroll: World Travel Map (outside) or 3D Dungeon map (dungeons) • `[9]` Campfire: Rest • `[10]` Compass: Status Info |
| `□` | On `[3]`: cycle Interaction Mode (Steal / Talk / Grab / Info); on `[0]` / `[8]`: open Quest Journal; on `[6]`: recast active spell (camera also pans left slightly) |
| `△` | Open Quest Journal & Tutorial Logbook |
| `○` or `SELECT` | Hide HUD Bar |

Inventory & Character Sheet

| Input | Inventory | Character Sheet |
| --- | --- | --- |
| D-Pad | Navigate |
| `L` / `R` | Cycle tabs (Weapons & Armor / Magic / Clothing / Ingredients) | Cycle highlighted attribute (in Level-Up stat popup, `L`/`R` cycles stats) |
| `✕` | Run middle-strip button or apply mode (Equip / Drink Potion / Read Book / Inspect (`INFO`) / Drop (`REMOVE`) / Cast Enchanted Item (`USE`)) | Open selected Skills popup, `Log`, `History`, `Inventory`, `Spells`, or allocate `+1` Bonus Point (`Right` / `✕` in Level-Up mode) |
| D-Pad Left (Level-Up) | — | Refund `1` allocated Bonus Point |
| `□` | Quick-drop highlighted item to the ground | Inspect highlighted primary attribute |
| `△` | Switch to Character Sheet | Switch back to Inventory (after spending all Bonus Points if leveling up) |
| `○` or `START` | Close Inventory|

World Travel Map (ver. 0.5+ only)

| View | Controls |
| --- | --- |
| Tamriel Overview | Analog / D-Pad: Move pointer; `L` / `R`: Jump prev/next region; `△`: Find Location (all regions); `SELECT`: `I'M AT` (jump to current region); `✕`: Enter hovered region (or click `I'M AT` / `EXIT`); `○` / `START`: Close |
| Region Map | Analog / D-Pad: Move pointer & highlight nearest location; `L` / `R`: Switch map sheet (multi-sheet regions); `□`: Cycle filter (All → Towns → Dungeons → Temples → Homes); `△`: Find Location (region); `SELECT`: `I'M AT`; `✕`: Select location to travel (or click bottom tray `FIND` / `I'M AT` / filter toggles / sheet arrows / `EXIT`); `○`: Back to Overview; `START`: Close |
| Travel Options | D-Pad Up/Down: Select row (Speed, Transport, Stay, Begin, Exit); Left/Right/`✕`: Toggle Cautious/Reckless, Foot-Horse/Ship, Inns/Camp Out; `✕` on `Begin`: Execute fast travel; `○`: Back to Region Map |
| Find OSK & Results | D-Pad: Select character / `_GO_`; `✕`: Type char / submit `_GO_` / select match; `□`: Backspace; `L`: Toggle All Regions vs Current Region; `START`: Submit search; `○`: Cancel |

11/23/26, Version 0.5

Updates:
1. An open world featuring the complete map of TES II, including all regions, climates, RMB (randomly generated building blocks), settlements, skybox backgrounds, citywatch, a day-night cycle, weather, and a fitting soundtrack (with the playlist switching when moving between settlements and the wilderness).
2. Travel map with fast travel and location search
3. Fixed the creation of a custom class
4. You can interact with animals, by pressing the action key (Start), they will make a sound characteristic of their species (this is not present in the original game; it was inspired by a mod for DFU).
5. When traveling through the wilderness, the game will use the same pool of music tracks as it does for dungeon exteriors. This is an intentional design choice, ensuring that high-energy tracks, like "Sunny Day", do not play while you are out exploring. It's yet another feature that doesn't exist in original.

Performance:
1. Dungeons – 30 FPS, with constant loading hitches and FPS drops to 15–20 (or even 10–15 in the worst cases). If the dungeon is relatively small, these loading hitches will be less severe.
2. The open world – a steady 30 FPS (since there’s nothing there but trees).
3. Settlements — I tested only Daggerfall on an actual PSP, and it ran at approximately 25–30 FPS. As you move through a town, different sections load in, which causes stutters and drops in the frame rate to 15–20 FPS for a few seconds. Presumably, these issues would be less noticeable in smaller settlements.

At the moment, there is nothing to do on the world map other than walking around, interacting with animals, and fighting NPCs (whether in the wilderness at night or against guards in towns).

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
