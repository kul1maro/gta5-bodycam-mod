# gta5-bodycam-mod

Bodycam prototype for GTA V Legacy story mode.

## What this project is

This project is a Bodycam-style gameplay layer for GTA V Legacy story mode. The player stays inside the real GTA V world, but the mod adds a short police-style recording experience with a HUD, mission trigger, evidence markers, and a simple investigation loop.

This is a prototype and design project, not a finished commercial release.

## Required game

- GTA V Legacy
- Story mode only
- Not GTA Online

This project is meant to run from the player's own copy of GTA V and changes the game through a mod loader path, not as a standalone game.

## Core idea

The mod adds:
- a Bodycam recording HUD
- a short mission trigger inside Los Santos
- evidence points and markers
- a simple chase or investigation objective
- a clean mission end and return to free roam

## Safe route

This project follows the same general route already used for GTA V story-mode mods:
- Story mode only
- ScriptHookV + ASI loader approach
- ReShade overlay or HUD layer
- No online play
- No anti-cheat bypass
- No multiplayer assumptions

## Current status

This repository is currently a prototype and planning project. It does not yet contain a finished playable build.

## Planned first playable version

The first version will focus on:
1. a mission trigger in GTA V
2. a Bodycam HUD overlay
3. evidence markers
4. one short objective loop
5. mission success/fail state
6. return to free roam

## Goals

- create a working single-player mission prototype
- keep the mod inside GTA V story mode
- stay safe and publishable for Melty
- avoid GTA Online and anti-cheat issues
- document the build and test process clearly

## Project structure

```text
README.md
MODLOG.md
docs/
