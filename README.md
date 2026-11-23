# ESP32-C3 RS-485 Automation Gateway

A compact, modular automation gateway designed around the **Seeed Studio XIAO ESP32-C3**, featuring RS-485 communication and a MikroE mikroBUS-compatible form factor.

This project focuses on developing a practical hardware platform for industrial communication and automation applications through iterative PCB design and prototyping.

## Project Overview

The project consists of three PCB design iterations (V1, V2 and V3), each introducing refinements to the schematic, component selection, power management, PCB layout and overall hardware integration.

The latest design uses the XIAO ESP32-C3 and follows a compact layout intended to fit the CEB-35/CEBV-35 enclosure.

## Hardware Specifications

- **Microcontroller:** Seeed Studio XIAO ESP32-C3
- **Communication:** RS-485
- **Expansion Interface:** MikroE mikroBUS form factor
- **Enclosure Compatibility:** CEB-35 / CEBV-35
- **PCB Design Software:** KiCad

## Design Iterations

### V1 – Initial Prototype
- Initial schematic and PCB development.
- RS-485 communication interface.
- Initial PCB layout and Gerber generation.

### V2 – Hardware Refinement
- Revised schematic and component selection.
- Improvements to power-related circuitry.
- Refinements to the RS-485 interface.
- Updated PCB design.

### V3 – Refined Design
- Integration of the Seeed Studio XIAO ESP32-C3.
- Refined PCB layout and component placement.
- Compact form factor.
- Enclosure-oriented design for CEB-35/CEBV-35.

## Repository Structure

```text
Home_Automation_Bengaluru/
│
├── V1/
│   ├── Schematic/
│   ├── PCB/
│   └── Gerbers/
│
├── V2/
│   ├── Schematic/
│   ├── PCB/
│   └── Manufacturing/
│
├── V3/
│   ├── Schematic/
│   ├── PCB/
│   └── Manufacturing/
│
├── Libraries/
│   └── Custom KiCad footprints and symbols
│
├── Datasheets/
│
└── README.md
```

*Directory names may vary according to the actual repository organization.*

## Software and Tools

- KiCad – Schematic capture and PCB layout.
- ESP32-C3 – Embedded processing platform.
- Git – Version control and project management.

## Getting Started

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Open the desired version's KiCad project.

3. Ensure the required custom footprints and libraries are available.

4. Review the schematic and PCB layout.

5. Refer to the Gerber and manufacturing files for PCB fabrication.

## Project Highlights

- Three generations of PCB development.
- ESP32-C3-based embedded platform.
- RS-485 communication capability.
- Modular mikroBUS-compatible design approach.
- Custom KiCad libraries and footprints.
- Enclosure-oriented PCB development.
- Version-controlled hardware development.


---

**Developed as part of an iterative hardware design and prototyping project.**
