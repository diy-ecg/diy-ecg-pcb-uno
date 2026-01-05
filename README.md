# diy-ecg-pcb-uno

# DIY ECG Amplifier Board (Arduino Uno Shield)

This repository contains the KiCad design files for a **DIY ECG (Electrocardiogram) amplifier board**.
The board is designed as an **Arduino Uno–compatible shield** and is intended for **educational, experimental, and research use**.

## Overview
- Analog front-end for ECG signal acquisition
- Designed for **Einthoven Lead I** measurements
- Uses a **MCP6004** quad operational amplifier
- Includes:
  - Differential ECG amplification
  - Biasing to a virtual ground (mid-supply)
  - Common-mode / body reference feedback (DRL-like concept)

The design is optimized for **low-cost components** and **didactic clarity**, making it suitable for
university courses, lab exercises, and DIY learning projects.

## Files
The repository intentionally contains only the essential KiCad files:
- `.kicad_sch` – schematic
- `.kicad_pcb` – PCB layout
- `.kicad_pro` – project file

These files are sufficient to inspect, modify, and manufacture the board.

## Intended Use
This board is **not a medical device** and must **not** be used for diagnostic or clinical purposes.
It is intended exclusively for:
- Education and teaching
- Private experimentation
- Research and prototyping

## License
This hardware design is licensed under the  
**CERN Open Hardware Licence Version 2 – Non-Commercial (CERN-OHL-NC v2)**.

You are free to study, modify, and manufacture the design for **private, educational, and research purposes**.
**Commercial use, sale, or mass production is not permitted** without explicit permission.

If you are interested in a **commercial license**, please contact the author.

## Author
Jens Bongartz - info@diy-ecg.org
