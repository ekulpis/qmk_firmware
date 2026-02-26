# ekulpis_linux

Linux keymap for Ferris Sweep. Designed to be flashed to the **right half**.

## Flashing

```bash
make ferris/sweep:ekulpis_linux:uf2-split-right
```

The `-split-right` suffix writes handedness to EEPROM so the keyboard knows which side it is.

Put the controller into bootloader mode (double-tap reset) and copy the `.uf2` file to the drive.

## Usage

Plug USB into the right half to use Linux keybindings.
