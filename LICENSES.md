# Licences

Numbers for the `Z` field in `FILENAME_X_Y_Z.EXT`. See the [FAQ](FAQ.md).

Leave `Z` out and it is `0`.

## Two rules

1. **Numbers are never reused.** Same rule as identor numbers. If an entry
   is ever withdrawn, its number stays empty for ever.
2. **The list only grows.** A number means today what it meant the day it
   was assigned, so a file tagged years ago still reads correctly.

## The list

| Z | Licence | SPDX |
|---|---|---|
| 0 | Open Love License v1.0 | — see [OLL](https://github.com/micro-FPGA/OLL) |
| 1 | MIT | `MIT` |
| 2 | Apache License 2.0 | `Apache-2.0` |
| 3 | CERN OHL v2 Permissive | `CERN-OHL-P-2.0` |
| 4 | BSD 2-Clause | `BSD-2-Clause` |
| 5 |  |  |
| 6 | GNU GPL v3.0 or later | `GPL-3.0-or-later` |
| 7 | GNU LGPL v3.0 or later | `LGPL-3.0-or-later` |
| 8 | Mozilla Public License 2.0 | `MPL-2.0` |
| 9 | CC0 1.0 — public domain | `CC0-1.0` |
| 10 | Creative Commons BY 4.0 | `CC-BY-4.0` |
| 11 | Creative Commons BY-SA 4.0 | `CC-BY-SA-4.0` |
| 12 | The Unlicense | `Unlicense` |
| 13 | All rights reserved — no license granted | not an SPDX identifier |

## Reading a name

Fields are read from the right-hand end of the name, so underscores earlier
in the name do not matter.
```
fir_tap_delay_1_7_2.vhd   identor #1, year 7 AG, Apache-2.0
led143_1_7.vhd            identor #1, year 7 AG, OLL
```
Fields fill from the left. Only the last one may be left out.

## If the licence you need is not here

Ask, and it is added with the next free number. Or write the SPDX
identifier into the file itself — the number is a convenience, not a
requirement.

## What the tag is not

The tag records an intention. The licence itself still has to be in the
repository.
