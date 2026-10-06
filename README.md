# Bodycam x GTA V Legacy

A single-player GTA V story mode mod that adds a Bodycam mission layer to Los Santos.

## What this project is
This prototype turns GTA V Legacy into a Bodycam-style mission playground. The player stays in the real GTA V world, but the mod adds a short recording HUD, evidence markers, mission triggers, and a simple chase/investigation loop.

## Required game
- GTA V Legacy (story mode only)
- Not GTA Online
- This project is a real game mod that runs from the player's copy of GTA V

## Current status
This is a prototype and design document, not a finished release yet.

## Planned first playable version
- Trigger a mission in GTA V
- Activate Bodycam HUD
- Mark evidence points
- Complete a short objective
- End the mission and return to free-roam

## Safe route
This project follows the same general route already used in the repo for GTA V modding:
- Story mode only
- ScriptHookV + ASI loader
- ReShade overlay path
- No online mode, no anti-cheat bypass

## Project structure
- `src/` - mod source and mission logic
- `assets/` - UI overlays, HUD graphics, evidence markers, screenshots
- `docs/` - design notes and build steps
- `release/` - packaged mod output

## How to use
1. Install GTA V Legacy story mode
2. Install the supported loader setup for this mod
3. Launch GTA V and start the mission from the in-game trigger
4. Use the Bodycam mode in the prototype mission loop

## License
This project is a prototype for personal and modding use. Add your preferred license before publishing.
