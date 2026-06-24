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
<img width="1446" height="674" alt="Schematic KiCad" src="https://github.com/user-attachments/assets/378a9dd2-7d88-4e29-9a8a-aeff4852b9e2" />
<img width="1133" height="849" alt="Layout KiCad" src="https://github.com/user-attachments/assets/76c8c442-038a-4de7-9c5e-c29042a39ac7" />
<img width="720" height="538" alt="3D Render KiCad" src="https://github.com/user-attachments/assets/6e7bee61-964f-4484-b1b9-3c3af9db51b6" />

---
## 📄 Portfolio Report

A concise engineering portfolio summarizing the complete design workflow, including system specifications, LTspice simulations, control-loop design, PCB implementation, manufacturing, and engineering skills demonstrated throughout the project.

**Report:**

[`Docs/LM5141-Synchronous Buck Converter Report.pdf`](Docs/LM5141-Synchronous%20Buck%20Converter%20Report.pdf)


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

## 🔗 Additional Resources

* 📁 **KiCad Project:** `KiCad/`
* ⚡ **LTspice Simulations:** `LTspice/`
* 🖼️ **Project Images:** `Images/`
* 📦 **Bill of Materials (BOM):** `BOM/`
* 📄 **Portfolio Report:** `Docs/LM5141-Synchronous Buck Converter Report.pdf`


---

## Author

Farhad Ekramitalab

Hardware Engineer | Power Electronics | SMPS | PCB Design | LTspice
