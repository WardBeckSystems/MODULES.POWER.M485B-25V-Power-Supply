# M485B 25V Power Supply · Power

Ward-Beck Systems M485B, 1978|11. Wiki page: [M485B on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/WBSps.ca/Github.WardBeckSystems/MODULES.POWER.M485B-25V-Power-Supply/)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 56 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 5 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 92 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 2 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 14 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 31 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [3 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [1982 - M485B - 25V power Supply.pdf](MANUALS/1982%20-%20M485B%20-%2025V%20power%20Supply.pdf) page 2 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **Dc output** | 1/ -25 volts at load currents frorri amperes. |
| **Line regulation** | 0.1% for Line variations from 105 Ta 125 Or from 210 to 250 volts ac respectively |
| **Load regulation** | 0.1% for load variations From zero [0 full load |
| **Ripple and noise** | Less than 500 microvolts RMS for all Line and load conditions specified above. |
| **Internal impedance** | Less than 0. ohm from dc Ta 20 kHz |
| **Stability** | 0.1 volts measured over an after 30 minutes warmiup hour period, |
| **Protection** | Overcurrent and short circuit foldback. Overvoltage crowbar |
| **Ac input** | 110/220 volts aC, nominal 50/60 Hz. Maximum input Power: 525 VA. |
| **Ambient temperature** | to 40 degrees Celsius at rated output. |
| **Dimensions** | 13.5&quot; wide 6.2&quot; high 4.0&quot; deep (340 mm 156 MM 100 mm) |
| **Weight** | 12 Lbs (5.5 kg) |
| **Accessories** | Power cord, AC Fuse and switch. |

## Circuit description

From [1978 - M485B - P05 - 1-117-1-1.jpg](MANUALS/1978%20-%20M485B%20-%20P05%20-%201-117-1-1.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

**1-417 REGULATOR BOARD**

The 1-117 Regulator printed circuit board unit. number WBS Power Supplies and contains the majority circuitry these units. used the 4ctive The +25 regulator consists 21 and booster transistor 01 _ contains internal current limiting and foldback circuits The voltage drop developed across the current sensing resistor R3 on the main chassis fed pin via the voltage divider RZ/R8 _ When the supply current reaches approximately 2.5 amperes: foldback current limiting sets in With the supply output shorted, the current limited approximately 0.75 amperes Feedback sensing the +25 brought back from the main frame via PCB connector pin and coupled pin 21 via the voltage divider consisting R17, R18 and R1S The output 21 controls the basc current Q1 turn, drives the positive series regulator On the main Frame byway edge connector pin The 25 regulator consists 22 and transistors 04 through 06 _ The negative side R15 connected 22 pin By varying R14 the negative output voltage controlled _ Simultaneously via 22, pin and the voltage divider R17, RIB and R1S, the positive output voltage will respond proportionally the operation R14. Thus both positive and negative voltages wili track. R18 serves as differential control. Adjusting Ri8 will increase one voltage while decreasing the other Booster transistors and 05 are operated from the output of 22 (pin and [urn drive the negative series regulator 02 the main frame via pin the edge connector Transistor 06 operated by the voltage developed across the current sensing resistor R4 the min Frame) As the current discs predetermined va Tue 06 will conduct and reduce the drive current from 22, pin 02 will sense the loss either output voltage Norma Iy, 02 saturaled_ resulting 03 being switched off. the event failure either supply voltage, wil become nonconductive and 03 wil saturate, thereby removing the reference currents from and 22 causing buth regulators shut down 1-117-1-1

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSWQ4LWo2N01MRW8/view?resourcekey=0-HONMjFQUNiYS3FNM5KZfNw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSWQ4LWo2N01MRW8&resourcekey=0-HONMjFQUNiYS3FNM5KZfNw" width="240" alt="19xx - M485B - DOC - 1202-04-007 - OSCILLATOR CUE-SOLO RE-ENTRY AND AUX LEVEL SCHEMATIC.jpg"></a><br><sub>19xx - M485B - DOC - 1202-04-007 - OSCILLATOR CUE-SOLO RE-ENTRY AND AUX LEVEL SCHEMATIC · <a href="MECHANICAL/19xx%20-%20M485B%20-%20DOC%20-%201202-04-007%20-%20OSCILLATOR%20CUE-SOLO%20RE-ENTRY%20AND%20AUX%20LEVEL%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M485B.stl`](MECHANICAL/M485B.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M485B)

- **Size:** 340 × 156 mm panel, 100 mm deep, 3.2 mm plate (TECHNICAL DATA: 13.5" wide 6.2" high 4.0" deep (340 mm 156 MM 100 mm))
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M485B - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M485B.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUG52YVNaMXg2cFk/view?resourcekey=0-6A3BkOlZGDq7CVleEZDypA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUG52YVNaMXg2cFk&resourcekey=0-6A3BkOlZGDq7CVleEZDypA" width="240" alt="1978 - M485B - 1-117-02-001 - CIRCUIT ADDED.jpg"></a><br><sub>1978|11 · 1-117-02-001 - CIRCUIT ADDED · <a href="SCHEMATICS/1978%20-%20M485B%20-%201-117-02-001%20-%20CIRCUIT%20ADDED%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRFRVT3BHLU8tSE0/view?resourcekey=0-ws3tgYIcFs6BQ0OydI-sjg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRFRVT3BHLU8tSE0&resourcekey=0-ws3tgYIcFs6BQ0OydI-sjg" width="240" alt="1978 - M485B - 1-117-06-001 - ADOEO KTI.jpg"></a><br><sub>1978|11 · 1-117-06-001 - ADOEO KTI · <a href="SCHEMATICS/1978%20-%20M485B%20-%201-117-06-001%20-%20ADOEO%20KTI%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTUsxbk9ha1A1bHM/view?resourcekey=0-lr5VsepoqvEkZjg_6DJxVg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTUsxbk9ha1A1bHM&resourcekey=0-lr5VsepoqvEkZjg_6DJxVg" width="240" alt="1978 - M485B - 1-117-06-001 - REGULATOR BOARD COMPONENT LAYOUT.jpg"></a><br><sub>1978|11 · 1-117-06-001 - REGULATOR BOARD COMPONENT LAYOUT · <a href="SCHEMATICS/1978%20-%20M485B%20-%201-117-06-001%20-%20REGULATOR%20BOARD%20COMPONENT%20LAYOUT%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTE1FZkhVLVVhVUk/view?resourcekey=0-uPneqxvdrO08BAdZgr4FEg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTE1FZkhVLVVhVUk&resourcekey=0-uPneqxvdrO08BAdZgr4FEg" width="240" alt="1978 - M485B - 485-02-003 - POWER SUPPLY SCHEMATIC.jpg"></a><br><sub>1978|11 · 485-02-003 - POWER SUPPLY SCHEMATIC · <a href="SCHEMATICS/1978%20-%20M485B%20-%20485-02-003%20-%20POWER%20SUPPLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdzlZRmJmOXZtQ0E/view?resourcekey=0-jEZLjm3IRvCBMNo17W-rnA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdzlZRmJmOXZtQ0E&resourcekey=0-jEZLjm3IRvCBMNo17W-rnA" width="240" alt="1978 - M485B - B 485-01-001 - M485B - +-25V POWER SUPPLY - FUNCTIONAL DIAGRAM.jpg"></a><br><sub>1978|11 · B 485-01-001 - M485B - +-25V POWER SUPPLY - FUNCTIONAL DIAGRAM · <a href="SCHEMATICS/1978%20-%20M485B%20-%20B%20485-01-001%20-%20M485B%20-%20%2B-25V%20POWER%20SUPPLY%20-%20FUNCTIONAL%20DIAGRAM%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKbTV6cjBISURldEk/view?resourcekey=0-5ua-VYecQ2cAAPlxx74jYA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKbTV6cjBISURldEk&resourcekey=0-5ua-VYecQ2cAAPlxx74jYA" width="240" alt="1978 - M485B - B 485-02-003 - M485B - +-25V POWER SUPPLY - SCHEMATIC.jpg"></a><br><sub>1978|11 · B 485-02-003 - M485B - +-25V POWER SUPPLY - SCHEMATIC · <a href="SCHEMATICS/1978%20-%20M485B%20-%20B%20485-02-003%20-%20M485B%20-%20%2B-25V%20POWER%20SUPPLY%20-%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSW9DVDFJUjhHNDA/view?resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSW9DVDFJUjhHNDA&resourcekey=0-LsRL7zmoNnMRkR9JkF5V2A" width="240" alt="19xx - M485B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.jpg"></a><br><sub>19xx - M485B - DOC - 1202-02-017 - POSTS CHASSIS GROUND · <a href="SCHEMATICS/19xx%20-%20M485B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1kbyxg7mttqNcz9LD2_GUCDyKuECc15aG/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1kbyxg7mttqNcz9LD2_GUCDyKuECc15aG" width="240" alt="19xx - M485B - DOC - 485-02-003 - POWER SUPPLY SCHEMATIC.jpg"></a><br><sub>19xx - M485B - DOC - 485-02-003 - POWER SUPPLY SCHEMATIC · <a href="SCHEMATICS/19xx%20-%20M485B%20-%20DOC%20-%20485-02-003%20-%20POWER%20SUPPLY%20SCHEMATIC%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## Pinouts

_Pinouts: the RTO-144 edge connector (connection sheets, connector layouts and rear views, strapping), and the pinout / connections drawings made from them. The module root `RTO.json` lists every contact._

## RTO-144 pinout

7 contacts, 2 contacts (J8). Every contact, with where it was read: [`RTO.json`](RTO.json).

| Pin | Signal | Kind | Pair | Confidence |
|---|---|---|---|---|
| 2 |  | unread |  | low |
| 7 | OPERATED FROM THE OUTPUT OF 22 | out |  | medium |

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc1Z5Y3BzYmN5cEk/view?resourcekey=0-gQ5L2qbrtAH9HUb53lAhdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc1Z5Y3BzYmN5cEk&resourcekey=0-gQ5L2qbrtAH9HUb53lAhdg" width="240" alt="1978 - M485B - 25V power Supply.pdf"></a><br><sub>1978|11 · 25V power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM2VodnlLcXRaUEk/view?resourcekey=0-blE4vQc0v9-IG9-ewoFu7Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM2VodnlLcXRaUEk&resourcekey=0-blE4vQc0v9-IG9-ewoFu7Q" width="240" alt="1978 - M485B - P02 - 1-1.jpg"></a><br><sub>1978|11 · P02 - 1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKM1BaVG5NYWhyZjQ/view?resourcekey=0-xfPGlBw5lMHntvL4odBQ2A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKM1BaVG5NYWhyZjQ&resourcekey=0-xfPGlBw5lMHntvL4odBQ2A" width="240" alt="1978 - M485B - P03 - 2-1.jpg"></a><br><sub>1978|11 · P03 - 2-1</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTDFOd3dkcjR4T1E/view?resourcekey=0-k6o1U1T4s9JD8ZxAUCQwCg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTDFOd3dkcjR4T1E&resourcekey=0-k6o1U1T4s9JD8ZxAUCQwCg" width="240" alt="1978 - M485B - P04 - 3-1.jpg"></a><br><sub>1978|11 · P04 - 3-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaHVYN3lGOHdmVFE/view?resourcekey=0-EFD7-K_5SZTvRv8OZNaq5Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaHVYN3lGOHdmVFE&resourcekey=0-EFD7-K_5SZTvRv8OZNaq5Q" width="240" alt="1978 - M485B - P05 - 1-117-1-1.jpg"></a><br><sub>1978|11 · P05 - 1-117-1-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSHRlVTVzdnFxamc/view?resourcekey=0-1JlXzOu8027hM86hFfaZOg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSHRlVTVzdnFxamc&resourcekey=0-1JlXzOu8027hM86hFfaZOg" width="240" alt="1978 - M485B - P06 - 1-117-1-2.jpg"></a><br><sub>1978|11 · P06 - 1-117-1-2</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYXhwblhMT09FbnM/view?resourcekey=0-7pMV4WxPUeMX5VP5CSo9EA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYXhwblhMT09FbnM&resourcekey=0-7pMV4WxPUeMX5VP5CSo9EA" width="240" alt="1978 - M485B - P07 - 1-117-2-1.jpg"></a><br><sub>1978|11 · P07 - 1-117-2-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMVVJR21BVzBfWHM/view?resourcekey=0-X2_QO_UzepaFRCKumryEgQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMVVJR21BVzBfWHM&resourcekey=0-X2_QO_UzepaFRCKumryEgQ" width="240" alt="1978 - M485B - P08 - 1-117-2-2.jpg"></a><br><sub>1978|11 · P08 - 1-117-2-2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKLVloNXE1blBKb2c/view?resourcekey=0-uE2llxbE0yj3HwN2uOIICQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKLVloNXE1blBKb2c&resourcekey=0-uE2llxbE0yj3HwN2uOIICQ" width="240" alt="1978 - M485B - P09 - 1-117-2-3.jpg"></a><br><sub>1978|11 · P09 - 1-117-2-3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUHVwZndET2ZYVnM/view?resourcekey=0-g7hHVu2CcWIo2WkPGPyCdg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUHVwZndET2ZYVnM&resourcekey=0-g7hHVu2CcWIo2WkPGPyCdg" width="240" alt="1978 - M485B - SERIES REG BASE.jpg"></a><br><sub>1978|11 · SERIES REG BASE</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRjl3Q1ZUZFFscjQ/view?resourcekey=0-P3CSDwKEof74DNftaW6GpA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRjl3Q1ZUZFFscjQ&resourcekey=0-P3CSDwKEof74DNftaW6GpA" width="240" alt="1982 - M485B - 25V power Supply.pdf"></a><br><sub>1982|15 · 25V power Supply</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKb0l5cFA4V3RmTms/view?resourcekey=0-wtP9hcJI8K56aem2KrMR0g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKb0l5cFA4V3RmTms&resourcekey=0-wtP9hcJI8K56aem2KrMR0g" width="240" alt="1982 - M485B - P01 - TOC.jpg"></a><br><sub>1982|15 · P01 - TOC</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdFFQX2d0d0tvRDA/view?resourcekey=0-fZBJYJyKwM5zYntvBSm4dQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdFFQX2d0d0tvRDA&resourcekey=0-fZBJYJyKwM5zYntvBSm4dQ" width="240" alt="19xx - M485B - DOC - L1202A - P13 - 11-1.jpg"></a><br><sub>19xx - M485B - DOC - L1202A - P13 - 11-1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRGVVUmx1MlN1ek0/view?resourcekey=0-vJM2sfewluMBwXhSfCFOAg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRGVVUmx1MlN1ek0&resourcekey=0-vJM2sfewluMBwXhSfCFOAg" width="240" alt="19xx - M485B - DOC - L1202A - P25 - IV-1.jpg"></a><br><sub>19xx - M485B - DOC - L1202A - P25 - IV-1</sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1978 - M485B - 1-117-02-001 - CIRCUIT ADDED.kicad_sch](KICAD/1978%20-%20M485B%20-%201-117-02-001%20-%20CIRCUIT%20ADDED.kicad_sch)
- [1978 - M485B - 485-02-003 - POWER SUPPLY SCHEMATIC.kicad_sch](KICAD/1978%20-%20M485B%20-%20485-02-003%20-%20POWER%20SUPPLY%20SCHEMATIC.kicad_sch)
- [1978 - M485B - B 485-01-001 - M485B - +-25V POWER SUPPLY - FUNCTIONAL DIAGRAM.kicad_sch](KICAD/1978%20-%20M485B%20-%20B%20485-01-001%20-%20M485B%20-%20%2B-25V%20POWER%20SUPPLY%20-%20FUNCTIONAL%20DIAGRAM.kicad_sch)
- [1978 - M485B - B 485-02-003 - M485B - +-25V POWER SUPPLY - SCHEMATIC.kicad_sch](KICAD/1978%20-%20M485B%20-%20B%20485-02-003%20-%20M485B%20-%20%2B-25V%20POWER%20SUPPLY%20-%20SCHEMATIC.kicad_sch)
- [1980 - 485-01-001 - +-25V POWER SUPPLY FUNCTIONAL DIAGRAM - DRN P. MAHONEY - ENG MRW - ISS 1 (2).kicad_sch](KICAD/1980%20-%20485-01-001%20-%20%2B-25V%20POWER%20SUPPLY%20FUNCTIONAL%20DIAGRAM%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20MRW%20-%20ISS%201%20(2).kicad_sch)
- [1980 - 485-02-003 - +-25V POWER SUPPLY SCHEMATIC - DRN P. MAHONEY - ENG MRW - ISS 1 (2).kicad_sch](KICAD/1980%20-%20485-02-003%20-%20%2B-25V%20POWER%20SUPPLY%20SCHEMATIC%20-%20DRN%20P.%20MAHONEY%20-%20ENG%20MRW%20-%20ISS%201%20(2).kicad_sch)
- [1980 - 485-02-003 - ±25V POWER SUPPLY SCHEMATIC - DRN P. Mahoney - ENG MRW - ISS 1.kicad_sch](KICAD/1980%20-%20485-02-003%20-%20%C2%B125V%20POWER%20SUPPLY%20SCHEMATIC%20-%20DRN%20P.%20Mahoney%20-%20ENG%20MRW%20-%20ISS%201.kicad_sch)
- [1982 - 1-117-02-001 - 1-117 REGULATOR BOARD SCHEMATIC - DRN MRW - ENG MRW - ISS 8.kicad_sch](KICAD/1982%20-%201-117-02-001%20-%201-117%20REGULATOR%20BOARD%20SCHEMATIC%20-%20DRN%20MRW%20-%20ENG%20MRW%20-%20ISS%208.kicad_sch)
- [1982 - M485B - 25V power Supply p11.kicad_sch](KICAD/1982%20-%20M485B%20-%2025V%20power%20Supply%20p11.kicad_sch)
- [19xx - M485B - DOC - 1202-02-017 - POSTS CHASSIS GROUND.kicad_sch](KICAD/19xx%20-%20M485B%20-%20DOC%20-%201202-02-017%20-%20POSTS%20CHASSIS%20GROUND.kicad_sch)
- [19xx - M485B - DOC - 485-02-003 - POWER SUPPLY SCHEMATIC.kicad_sch](KICAD/19xx%20-%20M485B%20-%20DOC%20-%20485-02-003%20-%20POWER%20SUPPLY%20SCHEMATIC.kicad_sch)
- [M485B - P10 - Functional Diagram.kicad_sch](KICAD/M485B%20-%20P10%20-%20Functional%20Diagram.kicad_sch)
- [M485B - P11 - Schematic.kicad_sch](KICAD/M485B%20-%20P11%20-%20Schematic.kicad_sch)
- [M485B.kicad_sym](KICAD/M485B.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
