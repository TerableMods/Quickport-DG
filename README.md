## Info:

- Quickly teleports you to a dungeon using a chat command.

---

## Install:

- C_REQUEST_EVENT_MATCHING_TELEPORT

---
- The *definitions* above must have their opcode mapped for your region (if they are not mapped by default):
  - NA patch **91.4** = [protocol.365097.map](https://github.com/tera-proxy/tera-data/blob/master/map/protocol.365097.map)
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

|         Dungeon Name         |        Tags       |
| -----------------------------|-------------------|
| Forbidden Arena Challenge    | fa                |
| Corrupted Skynest (NM/HM)    | cs, csn, csh      |
| Akalath Quarantine           | aq                |
| Bahaar's Sanctum             | bs, bahaar        |
| Gossamer Vault  (NM/HM)      | gv, gvn, gvh      |
| Demokron Factory (NM/HM)     | df, dfn, dfh      |
| Grotto of Lost Souls (NM/HM) | gls, glsn, glsh   |
| Antaroth's Abyss (NM/HM)     | aa, aan,  aah     |
| RK-9 Kennel (NM/HM)          | rk, rkn, rkh, rke |
| Ruinous Manor (NM/HM)        | rm, rmn, rmh      |
| Velik's Sanctuary (NM/HM)    | vs, vsn, vsh      |
| Macellarious Catacombs       | mc                |
| Shadow Sanguinary            | ss, ssn           |
| Dark Reach Citadel           | dr, drc, drcn     |
| Red Refuge                   | rr, rrn           |
| Lilith's Keep                | lk, lkn           |
| Velik's Hold                 | vh                |
| Thaumetal Refinery           | tr, trn           |
| Ravenous Gorge               | rg                |
| Channelworks                 | cw                |

---

## Info:

- You must meet the ilvl requirements to teleport to a dungeon
- All teleporting replicates using the Vanguard window and is 100% safe

---

Patch Version: **91.4**

![UI](/ui.png)