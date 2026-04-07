# HUDController-CXFR

A KSL mod for **CarX Drift Racing Online** that lets you fully customize the game's UI colors — per scene, with preset support and live preview.

![animiertes-gif-von-online-umwandeln-de (4)](https://github.com/user-attachments/assets/7e5881ee-36b5-43dd-80fd-0c53574d75a7)

## Features

- **Per-scene color profiles** — independent color settings for Menu, Multiplayer, Garage, SelectCar, TimeAttack, Drift, Training, Dynostand
- **10 configurable color slots per scene** — Button background, Button icon, Hover, Hover border, Menu text, Secondary text, Multiplayer text, Top bar glow, Room list background, Screen background
- **Preset system** — save and load unlimited named presets from disk (`kino/mods/HUD_Presets/`)
- **Built-in presets** — Dark, Light, Neon, Matrix, Sunset
- **RGB effect** — animated hue cycling with adjustable speed, toggleable on title
- **UI Theme tab** — customize the mod menu's own window colors
- **Live apply** — colors update in real time without restarting the game
- **Mod toggle** — enable/disable color overrides at runtime, original colors restored cleanly

## Requirements

- [KSL](https://github.com/trbflxr/ksl) and [KSL.CarX](https://github.com/trbflxr/ksl_carx)
- CarX Drift Racing Online Moddable (Steam)

## Installation

1. Download `HUDControllerCXFR_Ksl.dll`
2. Drop it in `CarX Drift Racing Online/kino/mods/`
3. Launch the game — the mod loads automatically

## Usage

Press `Ctrl + H` in-game to open the mod menu.

| Tab | Description |
|---|---|
| Colors | Per-scene color pickers |
| UI Theme | Mod window appearance |
| Presets | Save / load / delete presets |
| Settings | Mod toggle, reset options |
| Effects | RGB animation controls |

Presets are stored as plain text files in `kino/mods/HUD_Presets/` and are fully portable.

## Compatibility

Format is backward-compatible — presets created with older versions (7, 8, 9 or 10 color values) load correctly.

## Author

**SILVER** — v1.1.2
