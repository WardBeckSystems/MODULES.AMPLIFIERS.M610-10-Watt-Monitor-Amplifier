# M610 · Amplifiers

Ward-Beck Systems M610, 1975|8. Wiki page: [M610 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M610.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 26 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 9 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 3 |
| [MANUALS/](MANUALS/) | manuals, manual pages, price lists, brochures, documents | 170 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 9 |
| [SOFTWARE/](SOFTWARE/) | program listings, firmware, the plugin | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 4 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 42 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [2 topics](FORUM.md): what owners and technicians said about it.

## Specifications

From the technical data sheet: [19xx - M610 - 10W Monitor Amp (2).pdf](MANUALS/19xx%20-%20M610%20-%2010W%20Monitor%20Amp%20(2).pdf) page 4 (read by OCR; check against the page). As data: [`Specifications.json`](Specifications.json).

| | |
|---|---|
| **S t** | : a p). Front &quot; a nel vari:able control. |
| **Frequency** | ! 0.2 5d B from 30Hz to 2 0kHz RES?Q NSE: 80dB below lOW TOTAL HARMONIC Less than 0.3 5 ' from 30Hz t o 20 kHz (mea s ured |
| **Distortion** | a t lOW out&quot;ut level). -2 0dB m nominal, OdBm max imUill (60d B g ai nl Od Bm nominal, + l8dBm maximuro (40dB gain). LONGITUDINAL Greater than 5 0dB |
| **Balance** |  |
| &nbsp;&nbsp;Source impedance | 6 00 ohms o r less balanced or unbalanced. |
| **Load impedance** | 8 ohms nominal, 4 or 1 6 o nrn s with app r op r iate power output correction. OUT?UT IMPEDANCE: Less than 0.5 ohms P!!ASI NG: The low terminal n u..:nb e r.o t: the input pair i sin phase with the direct output terminal. POWER REQUI RE-1lSV ec, 6 0Hz, 30VA |
| **MENTS** | AMBIENT TEMPERATURE |
| **Dimensions** | 3.4W X 3.4H X 13.70 inches 4 lbs net. |

## Circuit description

From [19xx - M610 - P003 - 1.jpg](MANUALS/19xx%20-%20M610%20-%20P003%20-%201.jpg) page 1 (read by OCR; check against the pages). As data: [`CircuitDescription.json`](CircuitDescription.json).

<details><summary>Read it</summary>

Tiie balanced input to the amplifier is via module conrecccr F2 Pins 16 and The two operational amplifiers 214 and ZiB operate in che inverting mode The Feedback resistors R7 R8 R13 and R14 set the gain of Z1A _ RLI and R12 set the gain of 213 The cain of these two amplifiers is lowered by 204B when Ehe module connector P2 pins and 14 as well as pins and 15 are strapped together The output of 214 is conneczedto the inverting input of 22 through Rl5 and the output Of Z1B connects EO che non-i inverting input of 22 through Rl6 22 provides differential input to the incoming signal and changes the balanced operation to an unbalanced one Whether che input source is balanced or unbalanced Ene signal level out of 22 will remain constant for the same input signal level. RL3 is the high gain differential balance control and R18 is the low gain differential balance control 22 output is coupled through C12 to Ehe front panel gain control R2 3 This control function can be effectively extended up to approximately 20 feet fron the amplifier by connecting 5K ohn log taper control to connector P2 pins 13 and (high side of control Pin 13 arm pin common pin 12) The signal output from R23 (or the external control) is coupled to the power amplifier input Via C16 23 with its associated components forn the power amplifier driver stage R2 R2 8 R29 R30 C19 and C20 forn 12aB per octave Low pass filter with cut off frequency or approximately 3 OKHz on 23' s input 23' s output is coupled through R37 and biasing diodes CR2 and CR3 to the power output transistors Q3 04 form Ehe upper and Q7, Q8 the lower half of the complimentary power output stage The output signal is taken from the junction of R4 8 and R49 coupled Through Ll and C2 8 appearing at connector Pl pin 1 - Q5 and 06 limit tne output power of the amplifier to safe level should the load impedance become too Low The amplifier operates from nominal voltage of 52 volts rec??lle which 15 derived Erom Tl with bridge er CR4 and filter capacitor C30 02 is decoupling regulator Eo operate 21, 22 and 2 3 01 is current limit controller for decoupler Q2

</details>

<!-- /module data -->

## Photos

_Photographs of the module itself: front, back, inside, racked._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKN3NpdmVkMDJjVDQ/view?resourcekey=0-v9pCzFj5XqvAkzo-dUcb2Q" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKN3NpdmVkMDJjVDQ&resourcekey=0-v9pCzFj5XqvAkzo-dUcb2Q" width="240" alt="19xx - M610 - 002.jpg"></a><br><sub>19xx - M610 - 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZDBHYVJwWDZsUjg/view?resourcekey=0-jrlAm6BBR4JDU-7rzU_rUw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZDBHYVJwWDZsUjg&resourcekey=0-jrlAm6BBR4JDU-7rzU_rUw" width="240" alt="19xx - M610 - file.jpg"></a><br><sub>19xx - M610 - file</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKalh1UWtjZ2M4N28/view?resourcekey=0-lghloFRak7Eis0kblLR2xA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKalh1UWtjZ2M4N28&resourcekey=0-lghloFRak7Eis0kblLR2xA" width="240" alt="19xx - M610 - wbsps - promo - m610 10w amp - 003.jpg"></a><br><sub>19xx - M610 - wbsps - promo - m610 10w amp - 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYmNTdFBlNmtJaXM/view?resourcekey=0-ml4XR-q3eeXnJwv52sfdsg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYmNTdFBlNmtJaXM&resourcekey=0-ml4XR-q3eeXnJwv52sfdsg" width="240" alt="19xx - M610 - wbsps - promo - m610 10w amp - 004.jpg"></a><br><sub>19xx - M610 - wbsps - promo - m610 10w amp - 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKYUtMR29GTk9PS2s/view?resourcekey=0-opQDuMqEOZNyhjeYjThi4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKYUtMR29GTk9PS2s&resourcekey=0-opQDuMqEOZNyhjeYjThi4w" width="240" alt="19xx - M610 - wbsps - promo - m610 10w amp - back.jpg"></a><br><sub>19xx - M610 - wbsps - promo - m610 10w amp - back</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M610 - wbsps - module - m610 10w amp - front_small](https://drive.google.com/file/d/0B0yR0b5T78SKMm8wY25zZmE3UWs/view?resourcekey=0-_9XzEkk-5msKUK86nS2FRw) · [19xx - M610 - wbsps - promo - m610 10w amp - back_small](https://drive.google.com/file/d/0B0yR0b5T78SKVmJFWVpGejM2elU/view?resourcekey=0-CRlzYYJE_BqFFNVNlsbNIA)

Not on Google Drive yet: `19xx - M610 - M610.jpg`

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKVWcyeWQ0djhzOFk/view?resourcekey=0-K2ccuvmzp875OG7j-g4AHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKVWcyeWQ0djhzOFk&resourcekey=0-K2ccuvmzp875OG7j-g4AHg" width="240" alt="19xx - M610 - 610-04-001 - MGIO FIINISH CRA.jpg"></a><br><sub>19xx - M610 - 610-04-001 - MGIO FIINISH CRA · <a href="MECHANICAL/19xx%20-%20M610%20-%20610-04-001%20-%20MGIO%20FIINISH%20CRA%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVFyRmVEZ2VWZDg/view?resourcekey=0-rI3A_LzGdhA2QvLZqXSb1w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVFyRmVEZ2VWZDg&resourcekey=0-rI3A_LzGdhA2QvLZqXSb1w" width="240" alt="19xx - M610 - 610-04-001 - WATT MONITOR AMPLIFIE.jpg"></a><br><sub>19xx - M610 - 610-04-001 - WATT MONITOR AMPLIFIE · <a href="MECHANICAL/19xx%20-%20M610%20-%20610-04-001%20-%20WATT%20MONITOR%20AMPLIFIE%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## 3-D model

[`MECHANICAL/M610.stl`](MECHANICAL/M610.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M610)

- **Size:** 86.36 × 86.36 mm panel, 165 mm deep, 3.2 mm plate (TECHNICAL DATA: 3.4W X 3.4H X 13.70 inches 4 lbs net.)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M610 - front panel.svg`)
- the drawn panel is 0.76 wide to high, the size 1.00: placed by its height
- Made by `tools/module_models.py` (→ `MECHANICAL/M610.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKV0s3UkdtdXR5SUk/view?resourcekey=0-23qukgTbdxXLvMnpj5FknA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKV0s3UkdtdXR5SUk&resourcekey=0-23qukgTbdxXLvMnpj5FknA" width="240" alt="19xx - M610 - 171-06-001 - HEAT SINJK DRONE BGIO.jpg"></a><br><sub>19xx - M610 - 171-06-001 - HEAT SINJK DRONE BGIO · <a href="SCHEMATICS/19xx%20-%20M610%20-%20171-06-001%20-%20HEAT%20SINJK%20DRONE%20BGIO%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2ZIeUhXUlgzSmc/view?resourcekey=0-z4vcwaOoWXi8BLhmbQegGw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2ZIeUhXUlgzSmc&resourcekey=0-z4vcwaOoWXi8BLhmbQegGw" width="240" alt="19xx - M610 - 171-06-001 - WATT AMPLIPIER ASS.jpg"></a><br><sub>19xx - M610 - 171-06-001 - WATT AMPLIPIER ASS · <a href="SCHEMATICS/19xx%20-%20M610%20-%20171-06-001%20-%20WATT%20AMPLIPIER%20ASS%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKUDM5eEFrZjBXNkE/view?resourcekey=0-UO2m8MrqYJTldlwh7EYxAw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKUDM5eEFrZjBXNkE&resourcekey=0-UO2m8MrqYJTldlwh7EYxAw" width="240" alt="19xx - M610 - 610-02-003 - EXTERNAL VOLUME CONTROL VOLUME CONTROL MGIO REMOTE VOLUME.jpg"></a><br><sub>19xx - M610 - 610-02-003 - EXTERNAL VOLUME CONTROL VOLUME CONTROL MGIO REMOTE VOLUME · <a href="SCHEMATICS/19xx%20-%20M610%20-%20610-02-003%20-%20EXTERNAL%20VOLUME%20CONTROL%20VOLUME%20CONTROL%20MGIO%20REMOTE%20VOLUME%20(EXTRACTED).svg">vectors</a></sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQ2NiUmt6b1VPNmM/view?resourcekey=0-97FMm2mcCPCv1GdSETFz4w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQ2NiUmt6b1VPNmM&resourcekey=0-97FMm2mcCPCv1GdSETFz4w" width="240" alt="19xx - M610 - 610-02-004 - MEIO EXT MUTE CONTROL.jpg"></a><br><sub>19xx - M610 - 610-02-004 - MEIO EXT MUTE CONTROL · <a href="SCHEMATICS/19xx%20-%20M610%20-%20610-02-004%20-%20MEIO%20EXT%20MUTE%20CONTROL%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKTnFPY1I2REFxM2M/view?resourcekey=0-bli6S4myv-BUYAPpdzhVPA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKTnFPY1I2REFxM2M&resourcekey=0-bli6S4myv-BUYAPpdzhVPA" width="240" alt="19xx - M610 - P011 - B610-002-001 001.jpg"></a><br><sub>19xx - M610 - P011 - B610-002-001 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMjRILVlUUS1QNUk/view?resourcekey=0-XEeEcOXtrBexbeLiB3rK7w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMjRILVlUUS1QNUk&resourcekey=0-XEeEcOXtrBexbeLiB3rK7w" width="240" alt="19xx - M610 - P011 - B610-002-001 002.jpg"></a><br><sub>19xx - M610 - P011 - B610-002-001 002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKdDR3bGIxMFVnZmc/view?resourcekey=0-bMckZBZzhbGz7D_p8Vf82A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKdDR3bGIxMFVnZmc&resourcekey=0-bMckZBZzhbGz7D_p8Vf82A" width="240" alt="19xx - M610 - P011 - B610-002-001 003.jpg"></a><br><sub>19xx - M610 - P011 - B610-002-001 003</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSnNnMzJHUnJCNzg/view?resourcekey=0-5sW9Bwl9dyMBFyIrZlv4cg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSnNnMzJHUnJCNzg&resourcekey=0-5sW9Bwl9dyMBFyIrZlv4cg" width="240" alt="19xx - M610 - P011 - B610-002-001 004.jpg"></a><br><sub>19xx - M610 - P011 - B610-002-001 004</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWVlHa3gtTHFNLU0/view?resourcekey=0-buaAjZJsOgaV0bPQi0IsZw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWVlHa3gtTHFNLU0&resourcekey=0-buaAjZJsOgaV0bPQi0IsZw" width="240" alt="19xx - M610 - P011 - B610-002-001 005.jpg"></a><br><sub>19xx - M610 - P011 - B610-002-001 005</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMHRCcWlPdF9UQ1k/view?resourcekey=0-yUtit8uEcpwjwiLISLnxHg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMHRCcWlPdF9UQ1k&resourcekey=0-yUtit8uEcpwjwiLISLnxHg" width="240" alt="19xx - M610 - P012 - B610-002-002 001.jpg"></a><br><sub>19xx - M610 - P012 - B610-002-002 001</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKZ0dmX3FZaUh6eW8/view?resourcekey=0-zh5X-bk8t9-w44paU7GojQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKZ0dmX3FZaUh6eW8&resourcekey=0-zh5X-bk8t9-w44paU7GojQ" width="240" alt="19xx - M610 - P012 - B610-002-002 002.jpg"></a><br><sub>19xx - M610 - P012 - B610-002-002 002</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKa0Zjb2IyM3B3Yk0/view?resourcekey=0-urcCMYrkTp1Go-d5idhnfA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKa0Zjb2IyM3B3Yk0&resourcekey=0-urcCMYrkTp1Go-d5idhnfA" width="240" alt="19xx - M610 - P012 - B610-002-002 003.jpg"></a><br><sub>19xx - M610 - P012 - B610-002-002 003</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKT0U3cmJ0Zzl1a0k/view?resourcekey=0-rzJLUXG36FQ1Aq2QyTiw0A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKT0U3cmJ0Zzl1a0k&resourcekey=0-rzJLUXG36FQ1Aq2QyTiw0A" width="240" alt="19xx - M610 - P012 - B610-002-002 004.jpg"></a><br><sub>19xx - M610 - P012 - B610-002-002 004</sub></td></tr>
</table>

## Manuals and documents

_Manuals and manual pages, price lists, RTO-144 connection sheets, brochures, ads and other document scans._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ/view?resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B9I0nu1MPkm6Z2lLNEZYQ3ZoUDQ&resourcekey=0-5DX4cvFxAiR-D4EmHB4zQg" width="240" alt="1975 - M610 - PRICE LIST - PRICE LIST.jpg"></a><br><sub>1975|8 · PRICE LIST - PRICE LIST</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKeV81UGM3NUF3OUk/view?resourcekey=0-NP2wUEwKVpQYPt-PVA3nyw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKeV81UGM3NUF3OUk&resourcekey=0-NP2wUEwKVpQYPt-PVA3nyw" width="240" alt="19xx - M610 - 10W Monitor Amp (2).pdf"></a><br><sub>19xx - M610 - 10W Monitor Amp (2)</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKenpxaTY0MGZ2OTg/view?resourcekey=0-d7EE0WEFURxZr5FMrySC9g" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKenpxaTY0MGZ2OTg&resourcekey=0-d7EE0WEFURxZr5FMrySC9g" width="240" alt="19xx - M610 - 10W Monitor Amp.pdf"></a><br><sub>19xx - M610 - 10W Monitor Amp</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSEwzdkNydVhib2M/view?resourcekey=0-hxZh85g48i2x-0bWlSuTXQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSEwzdkNydVhib2M&resourcekey=0-hxZh85g48i2x-0bWlSuTXQ" width="240" alt="19xx - M610 - AD - wbsps - ad - 600 series.jpg"></a><br><sub>19xx - M610 - AD - wbsps - ad - 600 series</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc2ZWcDZOSS1CRU0/view?resourcekey=0-wOSya4Lz_HGkothFseusSA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc2ZWcDZOSS1CRU0&resourcekey=0-wOSya4Lz_HGkothFseusSA" width="240" alt="19xx - M610 - P001 - Title Page.jpg"></a><br><sub>19xx - M610 - P001 - Title Page</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKRXhxQUxWVDZOQkE/view?resourcekey=0-c-y_wjkT7YvuxcS5wY-YPw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKRXhxQUxWVDZOQkE&resourcekey=0-c-y_wjkT7YvuxcS5wY-YPw" width="240" alt="19xx - M610 - P002.jpg"></a><br><sub>19xx - M610 - P002</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSG8xSng2NFJHcmM/view?resourcekey=0-16HGsZjp6d81JL1Gwp4ciA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSG8xSng2NFJHcmM&resourcekey=0-16HGsZjp6d81JL1Gwp4ciA" width="240" alt="19xx - M610 - P003 - 1.jpg"></a><br><sub>19xx - M610 - P003 - 1</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKSzgyYnNoZlBrdEU/view?resourcekey=0-xpqXTjXDC2kdJU5wQIPBUQ" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKSzgyYnNoZlBrdEU&resourcekey=0-xpqXTjXDC2kdJU5wQIPBUQ" width="240" alt="19xx - M610 - P004 - 2.jpg"></a><br><sub>19xx - M610 - P004 - 2</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKd2hNYnZUc0t3R1k/view?resourcekey=0-bR5t65vbgmJFwts-1Lo7lA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKd2hNYnZUc0t3R1k&resourcekey=0-bR5t65vbgmJFwts-1Lo7lA" width="240" alt="19xx - M610 - P005 - 3.jpg"></a><br><sub>19xx - M610 - P005 - 3</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKc1FMdUNVUmdJc3M/view?resourcekey=0-qwjtdbwjKLI2qtmSWiJJCw" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKc1FMdUNVUmdJc3M&resourcekey=0-qwjtdbwjKLI2qtmSWiJJCw" width="240" alt="19xx - M610 - P006 - 4.jpg"></a><br><sub>19xx - M610 - P006 - 4</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKaC1DOUNNQWV3X0E/view?resourcekey=0-nKPaiLlobWzbrtvBIEHI5w" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKaC1DOUNNQWV3X0E&resourcekey=0-nKPaiLlobWzbrtvBIEHI5w" width="240" alt="19xx - M610 - P007 - 5.jpg"></a><br><sub>19xx - M610 - P007 - 5</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKNzJRdGpvRzFIRHc/view?resourcekey=0-1TVLPVhfRAIA0Zqqny-k-A" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKNzJRdGpvRzFIRHc&resourcekey=0-1TVLPVhfRAIA0Zqqny-k-A" width="240" alt="19xx - M610 - P008 - 6.jpg"></a><br><sub>19xx - M610 - P008 - 6</sub></td></tr>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKWTZ2alJwN0tQbTg/view?resourcekey=0-koxDuF_7PcD4Tc2Mt8eolg" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKWTZ2alJwN0tQbTg&resourcekey=0-koxDuF_7PcD4Tc2Mt8eolg" width="240" alt="19xx - M610 - P009 - 7.jpg"></a><br><sub>19xx - M610 - P009 - 7</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKMXg1SEJBRXU2WjA/view?resourcekey=0-Eqo_7_5wrMBVASkRt3r-vA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKMXg1SEJBRXU2WjA&resourcekey=0-Eqo_7_5wrMBVASkRt3r-vA" width="240" alt="19xx - M610 - P010 - 8.jpg"></a><br><sub>19xx - M610 - P010 - 8</sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/0B0yR0b5T78SKQklyeW9nWkxSWU0/view?resourcekey=0-GnUTM077eAeUcs8RAsXeJA" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=0B0yR0b5T78SKQklyeW9nWkxSWU0&resourcekey=0-GnUTM077eAeUcs8RAsXeJA" width="240" alt="19xx - M610 - wbsps - promo - m610 10w amp - front.jpg"></a><br><sub>19xx - M610 - wbsps - promo - m610 10w amp - front</sub></td></tr>
</table>

Shared privately on Google Drive (opens after sign-in): [19xx - M610 - DOC - wbsps - ad - 600 series](https://drive.google.com/file/d/0B0yR0b5T78SKYV84MnZPdmp4RXM/view?resourcekey=0-BYn5IKGKqKUqwhW73pe0eg) · [19xx - M610 - wbsps - module - m610 10w amp - back](https://drive.google.com/file/d/0B0yR0b5T78SKTnB4VUQwSmVOUkk/view?resourcekey=0-dP5_2X8nyJtYeUggPwRb2Q) · [19xx - M610 - wbsps - module - m610 10w amp - front](https://drive.google.com/file/d/0B0yR0b5T78SKVC1RM1NMeHVkc0U/view?resourcekey=0-88VMldJyGwqoVBmlFfVLmQ)

Not on Google Drive yet: `wbsps - promo - m610 10w amp - 002.jpg`

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [19xx - M610 - 610-02-003 - EXTERNAL VOLUME CONTROL VOLUME CONTROL MGIO REMOTE VOLUME.kicad_sch](KICAD/19xx%20-%20M610%20-%20610-02-003%20-%20EXTERNAL%20VOLUME%20CONTROL%20VOLUME%20CONTROL%20MGIO%20REMOTE%20VOLUME.kicad_sch)
- [19xx - M610 - 610-02-004 - MEIO EXT MUTE CONTROL.kicad_sch](KICAD/19xx%20-%20M610%20-%20610-02-004%20-%20MEIO%20EXT%20MUTE%20CONTROL.kicad_sch)
- [M610.kicad_sym](KICAD/M610.kicad_sym)
- [index.html](KICAD/index.html)

## Software

- [index.html](SOFTWARE/index.html)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
