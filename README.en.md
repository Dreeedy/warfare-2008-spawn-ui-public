# Warfare (2008) — Spawn UI

[Русский](README.md)

Spawn units near the camera and edit selected player units through an F8 panel. Version **1.1.0**.

The screenshots show an earlier version of the panel.

![Spawn UI panel](images/panel.png)
![Unit catalog](images/units.png)

Compatibility: Steam Warfare 1.0.8.0 for Windows, English localization. Other editions and localizations have not been tested.

## Features

- 200 unit types in USA / NATO, Arab forces and Neutral, organized into seven expandable groups.
- Spawn 1–20 units near the camera. Ground rings preview their placement.
- **Enemy** creates enemy units; **No crew** creates neutral empty vehicles, including helicopters on the ground. Infantry is unaffected by No crew.
- **Skill** selects a level from Recruit to Elite for infantry and vehicle crews.
- **Garrison** assigns newly spawned player units to Garrison. Enemies and empty vehicles are unaffected. Transfer to the next mission still depends on the game's rules.
- **Unit** displays information about a selected player unit and lets you change its skill and assignment.
- **Bugfix** offers an optional fix for units becoming unresponsive after loading a mission or save.

## Installation and update

1. Download `warfare-spawn-ui-1.1.0-windows-x86.zip` from the release. GitHub “Source code” downloads do not contain the mod.
2. Close the game and extract the archive into the Warfare folder, beside `bin` and `basis`.
3. Start the game and load a mission.
4. Run `mods/spawn-ui/spawn-ui-launcher.exe` with the same privileges as the game.
5. Return to the game and press **F8**.

To update, close the game, back up the previous mod files and extract the new archive into the same folder. Keep your `settings.ini` to preserve the Bugfix setting. Restart the game and run the launcher again.

## Controls

**F8** opens or closes the panel; **Esc** or **X** closes it. The panel works only in tactical missions, including pause. Close it to control units.

On **Spawn**, select a category and unit, set Qty and Skill, choose any options you need, then press **SPAWN AT CAMERA CENTER**. Click group headers to expand them and scroll with the mouse wheel. Enemy makes the preview rings red. Enemy, No crew, Garrison and Skill are retained until the next mission, which turns the options off and resets Skill to Recruit.

On **Unit**, select one player unit in the game before opening the panel. A whole infantry squad counts as one unit. Multiple units, partial squads, enemies, neutral or dead units and empty vehicles cannot be edited. Choose **New skill** or **New assignment**, then press **Apply**. Assignments available here are None, Reserve and Garrison. Existing Vanguard is displayed and preserved when changing only skill.

A soldier's skill is shared with its squad, but its assignment changes only for that soldier. Vehicle skill also applies to its crew, excluding passengers. Unchanged skill preserves experience. Closing the panel, switching tabs or changing the selected unit cancels unapplied edits. If Apply reports an error, review the displayed values before trying again.

On **Bugfix**, enable **Fix selection after load** and close the panel. The option is off by default and remembered between launches. It works while the mod is running.

## Notes

Spawn locations may be obstructed. Created units can be included when saving the mission.

To play without the mod, skip the launcher. To uninstall, close the game and delete `mods/spawn-ui`.

[Known issues](KNOWN_ISSUES.en.md) · [Changelog](CHANGELOG.en.md) · [Release notes](RELEASE_NOTES.en.md)
