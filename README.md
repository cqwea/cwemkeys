# cwemkeys

A custom, hand-designed Tenkeyless (TKL / 80%) mechanical keyboard built for the [Hack Club KEEB] program.

---

##  Project Overview
`cwemkeys` is a daily-driver TKL mechanical keyboard designed completely from scratch. The project includes custom PCB schematic routing in KiCad, a multi-piece 3D-printed enclosure with heat-set inserts, and custom open-source firmware controlling the switch matrix

---

##  Hardware & Specifications
* **Layout:** Tenkeyless (TKL / 80%)
* **Microcontroller:** Hack Club Orpheus Pico (RP2040)
* **Switches:** MX-Style mechanical switches
* **Keycaps:**  DSA profile keycap set
* **Diodes:** Through-hole 1N4148 diodes
* **Case Hardware:** M3×16mm screws with M3×5×4mm heat-set inserts
* **Firmware:** KMK / QMK

---

##  Repository Structure
* `/pcb` — KiCad schematics, PCB layout files, and Gerber exports
* `/case` — CAD models and 3D print files (STL / STEP) for the split enclosure
* `/firmware` — Keymap layout, matrix routing, and controller code

---

##  Build Process
1. **Schematic & PCB:** Designed in KiCad using the Orpheus Pico footprint, diode matrix, rotary encoder, and OLED display connections.
2. **Case Design:** Interlocking multi-piece enclosure modeled to fit standard 3D printer beds, secured with M3 heat-set inserts.
3. **Firmware:** Configured keymap matrix and flashed to the Orpheus Pico controller.
4. **Assembly:** Soldered 1N4148 diodes, switches and MCU; assembled into the printed chassis.

---

*Built with ❤️ for Hack Club KEEB.*
