# ZMK Config for KLOR Keyboard

A personal ZMK configuration for the KLOR 42-key split keyboard with rotary encoders.

## Layout

```
╭────────────────────────────┬────────────────────────────╮
│     B   F   L   K   Q      │     P   G   O   U   .      │
│ ESC N   S   H   T   M      │     Y   C   A   E   I  BSPC│
│ ALT X   V   J   D   Z  ENC │ ENC '   W   -   /   ,  INS │
╰───────────╮   R SPC RET    │ TAB WIN SFT DEL ╭─────────╯
            ╰─────────────────┴─────────────────╯
```

## Features

- **42-key split layout** with rotary encoders
- **OLED display** support
- **Mouse emulation** capability
- **Home row mods** (GALS on left, GAES on right)
- **Multiple layers**: Base, QWERTY, Navigation, Numbers, Windows, Function, Mouse
- **Smart behaviors**: Tap-dance, combos, adaptive keys
- **ZMK Studio** compatible

## Layers

1. **Base (0)**: Default layer with optimized layout
2. **QWERTY (1)**: Traditional QWERTY for compatibility
3. **Navigation (2)**: Arrow keys and navigation shortcuts
4. **Numbers (3)**: Number pad and mathematical symbols
5. **Windows (4)**: Window management shortcuts
6. **Function (5)**: F-keys, Bluetooth, and system controls
7. **Mouse (6)**: Mouse emulation and additional functions

## Configuration

- **Sleep timeout**: 30 minutes
- **Encoders**: Enabled with global thread support
- **RGB underglow**: Disabled
- **Bluetooth**: Enhanced with experimental features
- **Power**: Optimized for wireless use

## Building

This configuration uses GitHub Actions for automated building. Firmware files are generated for both left and right halves:

- `klor_left-nice_nano_v2.uf2`
- `klor_right-nice_nano_v2.uf2`

## Installation

1. Download the latest firmware from the releases or actions
2. Put your nice!nano into bootloader mode
3. Copy the appropriate `.uf2` file to the mounted drive
4. Repeat for the second half

## Credits

Special thanks to:

- [**urob**](https://github.com/urob) for [zmk-helpers](https://github.com/urob/zmk-helpers) and [zmk-config](https://github.com/urob/zmk-config) inspiration
- [**Sky Chilstedt**](https://github.com/skychil) for [kombol](https://github.com/skychil/kombol) contributions

## Hardware

- **Board**: nice!nano v2
- **Shield**: KLOR (left/right halves)
- **Features**: Rotary encoders, OLED displays
- **Switches**: Compatible with MX-style switches

## License

This configuration is released under the MIT License.