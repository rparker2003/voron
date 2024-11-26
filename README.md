# Voron 2.4 Build Log

This repository tracks the assembly, customization, and ongoing upgrades for my Voron 2.4 3D printer. It includes detailed documentation of installed mods, associated costs, and any modifications made during the build process.

---

## Repository Overview

- **Docs Directory**: Notes, logs, and additional build resources.
- **Costs Directory**: A high-level cost breakdown of the entire build.
- **Mods Directory**: Each mod is included as a submodule in `mods/<mod_name>`. Each mod has:
  - A `BOM.md` file documenting associated costs and required parts.
  - Links to the official repositories for assembly instructions and updates.

---

## Mods Installed / Planned For Install

| Mod Name                                                                  | Description                                                              | Installed? |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------ | ---------- |
| [HULA](https://github.com/thrutheframe/HULA_Voron)                        | Vibration-damping feet to reduce frame stress and improve print quality. | PENDING    |
| [Enraged Rabbit Project](https://github.com/EtteGit/EnragedRabbitProject) | Adds multi-material printing capability via tool-changing mechanisms.    | NO         |

---

## Costs Overview

| Category                     | Description                                                                     | Cost           |
| ---------------------------- | ------------------------------------------------------------------------------- | -------------- |
| **Printer Kit**              | [Formbot 2.4 R2 Pro+ Kit](https://www.aliexpress.us/item/3256807677153373.html) | **$832.39**    |
| **Functional Printed Parts** | [Voron PIF Program](https://pif.voron.dev/) (main in purple, accent in blue)    | **$110 + TBD** |
| **Upgrades**                 |                                                                                 | **$14.02**     |
| - Hotend                     | [TZ V6](https://www.aliexpress.us/item/3256807153308226.html)                   | $14.02         |
| **Mods**                     |                                                                                 | **$3.50**      |
| - HULA                       | Vibration-damping feet                                                          | $3.50          |
| - Enraged Rabbit Project     | Multi-material printing mod                                                     | TBD            |
| **Overall Total**            |                                                                                 | **$959.91**    |

---

## Build Progress

### Completed

- Ordered the Formbot 2.4 R2 Pro+ kit.
- Sourced purple(primary) and blue(accent) ABS parts via the Voron PIF program. (pending)

### Next Steps

1. Begin assembly of the Voron 2.4.
2. Print all parts and install the HULA mod.
3. Print and integrate parts for the Enraged Rabbit Project.

---

## How to Clone This Repository

To clone this repository along with all submodules, use:

```bash
git clone --recurse-submodules https://github.com/rparker2003/voron
```
