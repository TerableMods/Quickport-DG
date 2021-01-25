## Info:

- Quickly teleports you to a dungeon using a chat command.

---

## Install:

- C_REQUEST_EVENT_MATCHING_TELEPORT.0.def (included file) to:
> TeraToolbox\data\definitions

---
- The *definition* above must have its opcode mapped for your region, download it here:
  - NA patch **102.2** => [protocol.373821.map](https://github.com/TerableMods/OP-codez)

- The *.map* file in the link above, must be placed inside of:
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
| Corrupted Skynest (Hard)    | csh, cshm  |
| Catalepticon (Hard)         | cth, cah   |
| Bahaar's Sanctum            | bs, bahaar |
| Ruinous Manor (Hard)        | rmh, rmhm  |
| Catalepticon                | ct, ctn    |
| Corrupted Skynest           | cs, csn    |
| Forbidden Arena [UW]        | fa, fau    |
| Draakon Arena               | da, dan    |
| Akalath Quarantine          | aq         |
| Ruinous Manor (Easy)        | rm, rmn    |
| Gossamer Vault (Easy)       | gv, gvn    |
| Commander's Residence       | cr, raid   |
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

Patch Version: **102.2**

![UI](/ui.png)