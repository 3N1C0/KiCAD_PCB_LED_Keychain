# LED Keychain PCB

A small two-layer circuit board for an LED keychain, with artwork on the board. The repository holds the manufacturing files that a PCB fab needs.

## Files

| File | What it is |
|---|---|
| `LES Keychain-*.gbr` | Gerber files: copper, solder mask, silkscreen and board edge |
| `LES Keychain-PTH.drl`, `LES Keychain-NPTH.drl` | Drill files for plated and non-plated holes |
| `baby_breath.jpg`, `dragonfly.jpg`, `star.jpg` | Artwork used on the board |

## Layers

- `F_` and `B_`: front and back copper, solder mask and silkscreen
- `Edge_Cuts`: board outline
- `PTH` and `NPTH`: drill files

## Skills demonstrated

- **PCB design:** a two-layer board with copper, solder mask and silkscreen layers.
- **Manufacturing output:** exporting Gerber and drill files that a fabricator can use.
- **Board artwork:** adding images to the silkscreen.

## Use the files

Send the Gerber and drill files to any PCB fabricator. Each file is named after the board and its layer.

## Notes

- The KiCad project files (`.kicad_pcb` and `.kicad_pro`) are not in this repository, so the design can't be edited from here. Adding them would let others change the board.
