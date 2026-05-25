<!-- Parent: ../AGENTS.md -->
<!-- Generated: 2026-05-24 | Updated: 2026-05-24 -->

# image

## Purpose
Game image assets organized by category. Contains 1500+ images referenced by filename in game data JSON and component code. All images are served as static files.

## Subdirectories

| Directory | Purpose |
|-----------|---------|
| `_ui/` | UI chrome images — buttons, bars, Korean text overlays, UI decorations (240+ files) |
| `buff/` | Buff and status effect icons (100+ files) |
| `gameob/` | In-game object effect shadows (2 files) |
| `item/` | Item icons — weapons, armor, food, materials, consumables (800+ files) |
| `monsterskill/` | Monster ability/skill icons (30+ files) |
| `object/` | Game world object images (currently empty) |
| `skill/` | Player skill and ability icons (20+ files) |
| `spell/` | Spell and magic effect icons (40+ files) |
| `totem/` | Totem and relic images in multiple color variants and sizes (100+ files) |
| `wmap/` | World map images (3 files) |

## For AI Agents

### Working In This Directory
- Filenames are directly referenced in JSON data (`src/lib/assets/json_extracted/`) — renaming breaks data lookups
- Images are referenced in components via `/image/<category>/<filename>` URL paths
- Do not reorganize subdirectory structure without updating all JSON references

<!-- MANUAL: -->
