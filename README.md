# LM5141-Q1 Synchronous Buck Converter

## Project Overview

Design and implementation of a 12 V to 3.3 V, 5 A synchronous buck converter using the Texas Instruments LM5141-Q1 peak-current-mode controller.

This project covers the complete development flow:

- Power-stage design
- LTspice simulation
- Control-loop design
- Compensation design
- KiCad schematic capture
- 4-layer PCB layout
- Manufacturing preparation
- Hardware validation (in progress)

---

## Specifications

| Parameter | Value |
|------------|------------|
| Input Voltage | 8 V – 16 V |
| Nominal Input Voltage | 12 V |
| Output Voltage | 3.3 V |
| Output Current | 5 A |
| Switching Frequency | 440 kHz |
| Topology | Synchronous Buck |
| Controller | LM5141-Q1 |
| Control Method | Peak Current Mode |

---

## Design Highlights

- Peak current mode control
- Type-II compensation network
- Loop crossover frequency ≈ 37 kHz
- Phase margin ≈ 83°
- 4-layer PCB implementation
- Kelvin current sensing
- AGND / PGND separation
- Optimized switching-node layout

---

## Current Status

- [x] Power stage design completed
- [x] LTspice simulation completed
- [x] Compensation design completed
- [x] KiCad schematic completed
- [x] PCB layout completed
- [x] PCB ordered
- [ ] Assembly
- [ ] Hardware validation
- [ ] Efficiency characterization
- [ ] Thermal characterization
---

## Tools Used

- LTspice
- KiCad 9
- TI WEBENCH
- Oscilloscope (planned validation)

---

## Repository Structure

```

Docs/
LTspice/
KiCad/
Images/
Measurements/
BOM/

```

---

## Author

Farhad Ekramitalab

Hardware Engineer | Power Electronics | SMPS | PCB Design | LTspice
