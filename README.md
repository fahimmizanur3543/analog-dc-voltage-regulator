# analog-dc-voltage-regulator

**An adjustable analog DC voltage regulator designed and simulated using operational amplifiers in PSpice 9.1.**

## Overview

This project focuses on the design and simulation of an adjustable DC voltage regulator intended for laboratory applications. The entire design and simulation process was carried out exclusively using PSpice 9.1.

The primary objective is to develop a regulated DC power supply for laboratory use that can provide an adjustable and stable output voltage.

The circuit uses an operational amplifier as an error amplifier to compare the reference voltage with the feedback voltage and control a series pass transistor accordingly. This feedback mechanism helps maintain a stable output voltage under varying conditions.

The project emphasizes the practical application of analog electronics, operational amplifiers, voltage references, rectification, filtering, and feedback-based voltage regulation.


# Design Specifications

| Parameter | Design Target |
|---|---|
| AC Input Supply | 220 V, 50 Hz |
| Transformer Secondary | 18 V RMS |
| Rectified DC Voltage | Approximately 23–25 V |
| Adjustable Output Voltage | Approximately 0–15 V DC |
| Initial Current Target | 0.3 A |
| Simulation Software | PSpice 9.1 |

# Major Components and Concepts

- **Operational Amplifier (uA741)** 
- **Zener Diode** 
- **Diode Bridge Rectifier** 
- **Filter Capacitors** 
- **Series Pass Transistor** 
- **Feedback Network and Comparator** 

# Design Approach

1. AC voltage transformation to 18V RMS secondary.
2. Full-wave rectification using a bridge rectifier.
3. DC filtering using a capacitor.
4. Generation of a reference voltage using a Zener diode.
5. Error amplification using an operational amplifier.
6. Output regulation through a series pass transistor.
7. Feedback-based voltage control and simulation in PSpice 9.1.

# Results

The complete circuit schematic was developed and simulated using PSpice 9.1.

The design targets an adjustable DC output voltage ranging from approximately 0–15 V, with a maximum full-load current of 0.3 A.
# Final Circuit Schematic

![Final Circuit Schematic](Final_circuit.png)

*Note: Detailed simulation waveforms and measured output characteristics are available in the project report and presentation.*

# Files
| File | Description |
|---|---|
| `Final_circuit.png` | Final circuit schematic image |
| `Project_Final.sch` | PSpice circuit schematic file |
| `Group_04_EEE208_project_report.pdf` | Complete project report |
| `Group04_EEE208_Project_presentation.pptx` | Project presentation |
| `README.md` | Project documentation |

## Team

**Group 04**

- Member 1: Md. Fahim Mizanr
- Member 2: Md. Sazid Hossain
- Member 3: Rafia Akter
- Member 4: Shoyaib Istiyak Swagoto
- Member 5: Showmik Biswas


## Course / Context

- **Course:** EEE 208-Electronic Circuits II Laboratory
- **Department:** Electrical and Electronic Engineering 
- **University:** Bangladesh University of Engineering and Technology
- **Academic Level:** Level 2, Term II
- **Simulation Software:** PSpice 9.1

---

_*This project was completed as part of the undergraduate Electrical and Electronic Engineering curriculum at BUET.*_
