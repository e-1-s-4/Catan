# Catan — Single-File Web Edition

Play here: https://qeuph.github.io/Catan/

This project is a polished, browser-based Catan adaptation built in a **single `index.html` file** (no build step required).

## What’s Improved

Recent improvements focused on reliability and smooth gameplay:

- **Auto-save system**
  - The game now auto-saves every 30 seconds during active play.
  - A final silent save is attempted on tab close / refresh.
- **Better keyboard controls**
  - `R` = Roll dice
  - `E` = End turn
  - `1` = Open build menu
  - `2` = Open trade menu
  - `3` = Open development card menu
  - `4` = Buy development card
  - `M` = Toggle music on/off
  - `Ctrl/Cmd + S` = Save game now
  - `Esc` = Cancel current placement/action
- **Safer game lifecycle handling**
  - Auto-save starts on new game and loaded games.
  - Auto-save is stopped when quitting the game.
  - Manual save still exists for explicit snapshots.

## How to Run

### Local (recommended)
1. Clone the repository.
2. Open `index.html` in any modern desktop browser (Chrome, Edge, Firefox, Safari).

That’s it—no install, no bundler, no dependencies.

## Game Overview

Catan is a strategy board game where players race to **10 victory points** by collecting resources and building:
- Roads
- Settlements
- Cities

### Win condition
First player to 10 VP wins.

## Features

- Full randomized 19-hex island setup
- Resource production by dice roll
- Robber movement and stealing
- Building roads / settlements / cities
- Development cards (Knight, Road Building, Monopoly, Year of Plenty, VP)
- Largest Army and Longest Road awards
- Human + AI players
- In-game statistics and achievements
- Save/load support via local storage

## Controls Quick Reference

### Mouse / UI
- Use bottom action buttons for rolling and ending turn.
- Use side actions for building, trading, dev cards, and menu actions.

### Keyboard
- `R`, `E`, `1`, `2`, `3`, `4`, `M`, `Esc`, `Ctrl/Cmd + S`

## Notes

- Save data and settings are stored in browser local storage.
- “Continue” on the main menu appears when a save exists.
- For best experience, use a desktop browser with audio enabled.
