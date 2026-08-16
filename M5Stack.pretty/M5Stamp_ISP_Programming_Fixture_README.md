# M5Stamp ISP S006 programming-fixture footprint

## Orientation and pad map

Top view, USB-C connector at the bottom:

| Pad | Signal | Position |
|---:|---|---|
| 1 | 5V | bottom-left outer |
| 2 | GND | bottom-left inner |
| 3 | D+ | bottom-right inner |
| 4 | D- | bottom-right outer |
| 5 | 3V3 | top-right outer |
| 6 | RXD | top-right inner |
| 7 | TXD | top-center right |
| 8 | EN | top-center left |
| 9 | BOOT | top-left inner |
| 10 | GND | top-left outer |

The numbering follows J1 in the official Stamp ISP schematic and continues counter-clockwise around the module.

## Fixture geometry

- Nominal module PCB outline: 20.0 x 20.0 mm.
- Castellations: R0.425 mm, 2.54 mm pitch.
- Electrical contact hole: plated 0.50 mm drill with 1.20 mm copper land.
- Locating slot: non-plated 1.50 x 0.50 mm.
- Slot penetrates 0.150 mm beyond the bottom of each R0.425 castellation, matching the corrected M5Stamp Pico fixture.
- PTH-to-NPTH center distance: 2.800 mm.
- USB-C connector overhang is shown on F.Fab, Dwgs.User, and F.SilkS.

Verify the signal orientation against the physical module and make one low-cost fit-check PCB before production.
