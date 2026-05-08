# Foundry BRP StatBlock Converter

A tool to convert Basic Role-Playing (BRP) statblocks into Foundry VTT compatible JSON.

## How to Use

1. Open `brp-converter.html` in any web browser
2. Paste a BRP-style statblock (see example below)
3. Click **Convert to Foundry JSON**
4. Copy the output and import it into Foundry as an NPC

## Example Input Format

```
NAME: Moray Eel
STR 12
CON 14
SIZ 12
DEX 17
INT 4
POW 11
CHA 7
EDU 0
```

## Features
- Uses correct BRP HP formula: (SIZ + CON) × 0.5
- Outputs ready-to-import Foundry JSON
- Simple and fast

## Future Plans
- Better parsing for full statblocks (skills, hit locations, weapons)
- Support for more complex creatures

---

*Originally based on PF1 StatBlock Converter, now adapted for Basic Role-Playing.*