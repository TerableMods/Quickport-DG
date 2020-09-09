## Info:

- Quickly teleports you to a dungeon using a chat command.

---

## Install:

- C_REQUEST_EVENT_MATCHING_TELEPORT.0.def (included file) to:
> TeraToolbox\data\definitions

---
- The *definitions* above must have their opcode mapped for your region (if they are not mapped by default):
  - NA patch **98.2** download = [protocol.373821.map](https://github.com/TerableMods/OP-codez)

- The *.map* file containing your region's opcodes must be placed inside of:
> TeraToolbox\data\opcodes

---

## Commands:

- **dg**
  - to open the Quickport Dungeon Info UI (shows required ilvls, coins, and the available **[tag]** commands)

- **dg [tag]**
  - to teleport to the specified dungeon name  **[tag]**
  - Example: **dg aq** will teleport you to Akalath Quarantine (**aq** being the **[tag]**)

|        Dungeon Name         |    Tags    |
| ----------------------------|------------|
| Corrupted Skynest (Hard)    | cs, csh    |
| Draakon Arena (Hard)        | dah, dahm  |
| Corrupted Skynest           | cs, csn    |
| Forbidden Arena Challenge   | fa         |
| Bahaar's Sanctum            | bs, bahaar |
| Akalath Quarantine          | aq         |
| Draakon Arena               | da, dan    |
| Gossamer Vault (Hard)       | gv, gvh    |
| Antaroth's Abyss (Hard)     | aa, aah    |
| Grotto of Lost Souls (Hard) | gls, glsh  |
| Kezzel's Gorge              | kg         |
| RK-9 Kennel                 | rk, rkn    |
| Red Refuge                  | rr, rrn    |
| Commander's Residence       | cr, raid   |
| Velik's Hold                | vh         |
| Velik's Sanctuary           | vs, vsn    |
| Macellarious Catacombs      | mc         |
| Highwatch                   | hw         |
| Highwatch (no Vanguards)    | hw0        |

---

## Info:

- Module replicates teleporting using the Vanguard window and is 100% safe
- You must meet the ilvl requirements of a dungeon to be able to teleport there (it must be available in your character Vanguard window)
- You may get "your item level is too low" error message, if you have no daily vanguards remaining or the Vanguard window is bugged...
- **Patch 95 introduced a Vanguard window bug, so first make sure the dungeons are available in your Vanguard window**
  - Teleporting to Ghillieglade entrance then opening your Vanguard window will correct this in game bug (or completing any vanguard)

---

Patch Version: **98.2**

![UI](/ui.png)