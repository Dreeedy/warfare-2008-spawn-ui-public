# Warfare (2008) — Spawn UI

[Русский](README.ru.md)

Spawn units near the camera through an F8 panel. Version **1.0.0**. The mod worked correctly at the time of publication.

**Tested only with the Steam edition of Warfare 1.0.8.0 for Windows x86, using the English localization. Other editions and localizations have not been tested.**

## Features

- 200 prototypes in USA / NATO, Arab forces and Neutral; seven expandable groups: Infantry, Crews, Armor, Artillery, Air Defence, Supply & Transport and Aviation.
- Spawn 1–20 units for the current player or enable **Enemy**. The catalog does not determine ownership; enemies are not automatically selected.
- **No crew** creates neutral, empty vehicles, including helicopters on the ground. It overrides Enemy for vehicles; infantry and separate crew squads are unaffected.
- **Skill**: Recruit, Able, Regular, Expert, Veteran, Elite. Applies to infantry and vehicle crews; empty vehicles skip it.
- Ground rings preview placement; exact positions are chosen by the game. Enemy makes rings red, including when No crew is enabled.

## Installation

1. Use `warfare-spawn-ui-1.0.0-windows-x86.zip`; GitHub “Source code” archives contain documents only. Check the ZIP against its `.sha256` file.
2. Extract into the Warfare root, beside `bin` and `basis`: `mods/spawn-ui/spawn-ui-launcher.exe`.
3. Start the game, load a mission, then run the launcher with the same privileges as the game.
4. Return to the game and press **F8**.

## Controls

F8 toggles the panel; Esc or X closes it. Click group headers and units; scroll with the wheel. Use Category arrows, Qty −/+ and Skill arrows, then **SPAWN AT CAMERA CENTER**.

The panel works only in tactical missions, including pause. Close it to control units. Enemy, No crew and Skill persist when closing the panel or switching catalogs; a new mission resets them to off/off/Recruit. Switching catalogs or missions resets the list; the selected catalog persists between missions.

## Limits and troubleshooting

F8 retains the game's **Quick load** binding. Placement does not guarantee clear ground. Spawned units can enter a save if you save the mission.

Fully close the game before replacing files; a new DLL requires a restart. To play without the mod, skip the launcher. To uninstall, close the game and remove `mods/spawn-ui`.

If connection fails, check the game version, file location and process privileges. “DLL loaded” alone does not confirm initialization. See `bridge.log` and `launcher.log` in the mod folder. Report reproduction steps and remove personal paths before sharing logs.

[Known issues](KNOWN_ISSUES.md)
