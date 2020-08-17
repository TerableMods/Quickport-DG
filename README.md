## Info:

- Quickly teleports you to a dungeon using a chat command.

---

## Install:

- C_REQUEST_EVENT_MATCHING_TELEPORT

---
- The *definitions* above must have their opcode mapped for your region (if they are not mapped by default):
  - NA patch **97.3** download = [protocol.372754](https://github.com/TerableMods/OP-codez)

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
| Rift's Edge                 | re, ren    |
| RK-9 Kennel                 | rk, rkn    |
| Red Refuge                  | rr, rrn    |
| Commander's Residence       | cr, raid   |
| Velik's Hold                | vh         |
| Velik's Sanctuary           | vs, vsn    |
| Macellarious Catacombs      | mc         |

---

## Info:

- You must meet the ilvl requirements to teleport to a dungeon (must be available in your Vanguard window)
- You may get "your item level is too low" error message, if you have no daily vanguards remaining
- Replicates teleporting using the Vanguard window and is 100% safe
- **Patch 95 introduced a Vanguard bug, so first make sure dungeons are available in your Vanguard window**
  - Teleporting to Ghillieglade entrance then opening your Vanguard window will correct this in game bug (or completing any vanguard)
---

Patch Version: **97.3**

![UI](/ui.png)