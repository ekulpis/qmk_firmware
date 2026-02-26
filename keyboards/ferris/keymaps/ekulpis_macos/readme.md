# ekulpis_macos

macOS keymap for Ferris Sweep. Designed to be flashed to the **left half**.

## Flashing

```bash
make ferris/sweep:ekulpis_macos:uf2-split-left
```

The `-split-left` suffix writes handedness to EEPROM so the keyboard knows which side it is.

Put the controller into bootloader mode (double-tap reset) and copy the `.uf2` file to the drive.

## Usage

Plug USB into the left half to use macOS keybindings.
