## Info:

- Quickly teleports you to a dungeon using a chat command.

---

## Install:

- C_REQUEST_EVENT_MATCHING_TELEPORT

---
- The *definitions* above must have their opcode mapped for your region (if they are not mapped by default):
  - NA patch **92.3** = [protocol.366221.map](https://github.com/tera-proxy/tera-data/blob/master/map/protocol.366221.map)
  - EU patch **92.3** = [protocol.366222.map](https://github.com/tera-proxy/tera-data/blob/master/map/protocol.366222.map)

- The *.map* file containing your region's opcodes must be placed inside of:
> TeraToolbox\data\opcodes

---

## Commands:

- **dg**
  - to open the Quickport Dungeon Info UI (shows required ilvls, coins, and the available **[tag]** commands)

- **dg [tag]**
  - to teleport to the specified dungeon name  **[tag]**
  - Example: **dg gvn** will teleport you to Gossamer Vault (**gvn** being the **[tag]**)

|        Dungeon Name         |    Tags    |
| ----------------------------|------------|
| Corrupted Skynest (Hard)    | cs, csh    |
| Corrupted Skynest           | cs, csn    |
| Forbidden Arena Challenge   | fa         |
| Bahaar's Sanctum            | bs, bahaar |
| Akalath Quarantine          | aq         |
| Gossamer Vault  (Hard)      | gv, gvh    |
| Antaroth's Abyss (Hard)     | aa, aah    |
| Grotto of Lost Souls (Hard) | gls, glsh  |
| RK-9 Kennel                 | rk, rkn    |
| Red Refuge                  | rr, rrn    |
| Velik's Hold                | vh         |
| Velik's Sanctuary           | vs, vsn    |
| Macellarious Catacombs      | mc         |

---

## Info:

- You must meet the ilvl requirements to teleport to a dungeon
- All teleporting replicates using the Vanguard window and is 100% safe

---

Patch Version: **92.3**

![UI](/ui.png)