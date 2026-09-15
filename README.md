# Haptic Glove PCB

A wrist-mounted PCB for a haptic feedback glove, developed as part of my Research Assistantship at the Tactile Laboratory, Nazarbayev University.

## Overview
The board mounts on the wrist and drives 5 vibromotors, one per fingertip, delivering independent tactile feedback to each finger. It is designed to sit inside a glove, secured to the wrist via velcro straps threaded through slots in the board.

## Design Details
- **Board size:** 65mm x 50mm
- **Actuators:** 5x vibromotors (one per fingertip), each with a dedicated 3.3V power channel and signal channel
- **Driver components:** Capacitors and diodes placed near the board edge for each motor driver channel
- **Wrist-to-fingertip connection:** Discrete flexible wire harness (evaluated flex PCB / FPC, but chose a wire harness for flexibility and cost)
- **Mounting:** Component side faces outward (away from skin); board sits on the palm/volar side of the wrist inside the glove
- **Hand coverage:** Single-hand design

## Files
- `/schematic` — Schematic source files
- `/pcb` — PCB layout files
- `/gerbers` — Fabrication-ready Gerber files
- `/images` — Board renders and assembled photos
- `BOM.csv` — Bill of materials

## Tools
- [Your EDA tool — e.g. KiCad / Altium / Eagle]

## Status
[In progress / Fabricated & tested / etc. — update with current status]
