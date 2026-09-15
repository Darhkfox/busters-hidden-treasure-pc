# Buster's Hidden Treasure — PC Runtime

A custom PC port of the Sega Mega Drive / Genesis game **Tiny Toon Adventures: Buster's Hidden Treasure**. The console hardware (68000 CPU, VDP graphics, Z80 + FM/PSG sound) is reproduced in native code, so the game runs directly on Windows — no separate emulator needed — with a few modern extras: **widescreen mode, video filters, save states, fullscreen, and an in-game menu** (cheats, level select, sound test).

This is a personal, non-commercial passion project. It does **not** include the game — you supply your own ROM of a cartridge you own.

## Download

Grab the latest zip from the [**Releases**](../../releases) page, extract it, and run `Buster's Hidden Treasure.exe`.

## Requirements

- **Windows** (64-bit)
- A **good dump of the US (USA) ROM**. Other regions (E / J), bad dumps, and hacks are not supported and are rejected on load. The ROM is loaded at runtime and is never bundled.
- `SDL2.dll` — included in the zip, kept next to the exe.

## Controls (quick reference)

| Action | Keyboard | Gamepad |
| --- | --- | --- |
| Move | Arrows / WASD | D-Pad / Left Stick |
| Jump | K or Space | A |
| Slide / Dash | J | X (or B) |
| Special | H | Y |
| Start / Pause | Enter | Start |
| Open menu | Esc | Back / Select |

**Hotkeys:** `F11` fullscreen · `F10` widescreen · `F9` video filter · `F5` / `F8` save / load state · `1`–`4` save slot.

Full details — the menu, save states, and troubleshooting — are in `readme.txt` inside the zip.

## Legal

Tiny Toon Adventures: Buster's Hidden Treasure and its characters and artwork are copyright their respective owners (Konami / Warner Bros.). This project contains none of that content and requires a ROM dumped from a cartridge you legally own. Personal use only.
