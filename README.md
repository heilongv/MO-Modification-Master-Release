# MO Modification Master (MO修改大师)

A lightweight trainer for **Mental Omega 3.3.6** (Red Alert 2: Yuri's Revenge mod) — campaign / single-player skirmish only.

**Author**: Heilongv · **Version**: 1.1.2 · **Free forever**

## Features

- **Resources**: money edit & lock, mission timer edit, power lock / max power
- **Building**: instant build, build anywhere, unlimited build orders & unit caps, tech unlock (unlocks your faction's full tech tree + hidden hero units like Kukov / Reznov)
- **Units**: edit HP & rank of selected units/buildings, capture enemy units/buildings
- **Map**: reveal map + enable minimap radar, shroud reveal (with edge preserved)
- **Anti-detection**: decloak enemies, reveal all disguised units (Mirage Tanks, spies)
- **Superweapons**: charge superweapons, infinite superweapons, add any of 89 superweapons/support powers
- **Assist**: auto-repair, Shift+click turbo, custom hotkeys (16), always-on-top
- **Safety**: write-verify every memory write, auto-restore on exit, integrity check, **single-player only**

## Download

- **MO修改大师.exe** (37 MB, single file, no installation needed, no Python required)
- See the **Releases** tab above.

## Requirements

- Windows 8.1 or later (64-bit)
- Mental Omega 3.3.6 (any version of Yuri's Revenge 1.001)

## Usage

1. Launch the game (Mental Omega campaign or single-player skirmish)
2. Run MO修改大师.exe
3. Click 连接 (Connect), then enable features

Full usage guide is built into the app (说明书 / Manual button).

## Notes

- **Single-player only**: the tool auto-detects multiplayer and disables all features — it won't affect online play or cause desync.
- **FREE**: if you paid for this anywhere, you've been scammed.
- Redistribution or modification of this software for resale is prohibited.

## Changelog

### v1.1.2 (2026-08-17)
- Handle/API declaration hardening, hotkey config validation, disconnect idempotency, action-failure logging
- Core docstrings stripped from compiled pyd (build-only change)

### v1.1.1 (2026-08-16)
- Fixed building capture queue corruption when multiple buildings were captured at once
- Fixed superweapon grant bounds check and remote-memory leak
- Closed multiplayer bypass on Force Win / Map Reveal hotkeys

### v1.1 (2026-08-11)
- Map Reveal now also turns on the minimap radar
- Tech Unlock reworked: unlocks your faction's full tech tree and hidden hero units (Kukov, Reznov, Rashidi); cross-faction units no longer clutter the build menu
- Added an internal CN/EN core sync checker (maintains identical behavior between both language builds)

### v1.0
- Initial public release

## Disclaimer

This is an independent third-party tool, not affiliated with the Mental Omega team or EA. Use at your own risk.
