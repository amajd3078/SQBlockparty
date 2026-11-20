# SQBp - Block Party (Vanilla Skript)

A complete **Block Party** minigame written in **100% Vanilla Skript** with no external Skript addons required.

## Features
- **Custom Arenas & Spawns:** Create and manage arenas with custom `pos1` / `pos2` floor bounds, custom game start spawn points, waiting lobbies, and a main hub.
- **Smart Percentage Countdown:**
  - Never starts with only `1` player.
  - `25%+` players: `60s` countdown.
  - `50%+` players: `30s` countdown.
  - `100%` players: `10s` countdown.
- **Progressive Floor Speed:** No round countdown timer—floor speed gradually increases every elapsed minute down to a configurable minimum (`min-round-time`) so it stays playable.
- **Color Callouts:** Shows clean color names (`RED`, `BLUE`, `GREEN`, etc.) and gives the matching wool block in hotbar slot 5.
- **Double Jump:** Configurable cooldown (`double-jump-cooldown`) or set to `0` to lock/disable.
- **Synced Jukebox Music:** Plays a unified random disc across players in the arena when the floor is active, stops it when non-matching blocks drop, and picks a new random disc when the floor regenerates.
- **Live Action Bar:** Displays elapsed match time, player ping, remaining players, and Double Jump status.
- **Win & Lose Effects:** Titles, fireworks/sound effects, and clean arena/hub transitions.

## Commands
### Admin (`sqbp.admin`)
- `/sqbp addarena <name> <max_players>`
- `/sqbp delarena <name>`
- `/sqbp pos1`
- `/sqbp pos2`
- `/sqbp setfloor <name>`
- `/sqbp setspawn <name>`
- `/sqbp setlobby <name>`
- `/sqbp sethub`
- `/sqbp arenalist`

### Players
- `/join <arena_name>`
- `/hub`
