# TCAD Modeling and Characterization of Gate-All-Around (GAA) Nanowire FET


## Overview

As transistor dimensions continue to scale below 5 nm, conventional FinFETs face increasing challenges due to short-channel effects and reduced electrostatic control. Gate-All-Around (GAA) Nanowire FETs address these limitations by surrounding the channel with the gate, enabling superior gate control and improved device performance.

This project presents the design, simulation, and characterization of a **3D sub-5 nm GAA Nanowire MOSFET** using **Synopsys Sentaurus TCAD**. The device geometry was developed based on published IEEE literature, and the simulation framework was configured to investigate nanoscale transistor behavior under various operating conditions.

---

## Objectives

- Build a 3D Gate-All-Around Nanowire FET model
- Implement appropriate carrier transport and mobility models
- Simulate transfer characteristics (ID–VGS)
- Extract important transistor performance metrics

---

## Device Specifications

| Parameter | Value |
|-----------|-------|
| Device Type | Gate-All-Around (GAA) Nanowire MOSFET |
| Technology Node | Sub-5 nm |
| Simulation Type | 3D TCAD |
| Channel Material | Silicon |
| Gate Structure | Gate-All-Around |
| Simulation Tool | Synopsys Sentaurus TCAD |

---
## Physics Models

The following physical models were incorporated during simulation:

- Drift–Diffusion Carrier Transport
- Fermi–Dirac Carrier Statistics
- Ballistic Mobility Model (BalMob)
- Philips Unified Mobility Model (PhuMob)
- Lombardi Surface Mobility Model
- High-Field Saturation Mobility
- Bandgap Narrowing (Old Slotboom)
- Shockley–Read–Hall (SRH) Recombination
- Auger Recombination
- Density Gradient Quantum Potential
- Incomplete Ionization
---

## Results

### Device Structure

- - Cross-sectional View
    <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/8fb8cb30-60c6-4efc-a126-3e571c52f4bd" />

- Device Mesh
  <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/a1b4f03f-183d-4dd9-97cf-3def8967c2ef" />

- Doping Profile
  <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/362a6de9-fffd-4819-a07c-cbd068d39059" />

- Electrostatic Potential
  <img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/fbf6fa3a-5b33-4c34-9614-02ea3553239e" />
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/e8540678-9b2f-4d85-b23f-2977e85aabe1" />


---

### Transfer Characteristics (ID–VGS)

<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/6249b07e-0ad0-4efa-aea8-fbedc314451f" />


The transfer characteristics were used to evaluate the switching behavior of the transistor and extract important electrical parameters.

---

## Extracted Performance Metrics

| Metric | Description |
|---------|-------------|
| Threshold Voltage (VTH) | Gate voltage at which the device turns ON |
| ON Current (ION) | Drain current in the ON state |
| OFF Current (IOFF) | Leakage current in the OFF state |
| ION/IOFF Ratio | Measure of switching performance |
| Peak Transconductance (gm) | Maximum gain of the device |
| Subthreshold Swing (SS) | Switching efficiency in the subthreshold region |

<img width="631" height="470" alt="image" src="https://github.com/user-attachments/assets/2033b6ab-d9ce-448b-a731-b69c3aaecea1" />


| Parameter | Value |
|-----------|-------|
| Threshold Voltage (VTH) | 0.2758 V (Reference Current = 1.0e-07 A) |
| ON Current (ION) | 1.273e-04 A |
| OFF Current (IOFF) | 6.031e-12 A |
| ION/IOFF Ratio |  2.111e+07 |
| Peak Transconductance (gm) | 0.000243 S |
| Subthreshold Swing (SS) | 68.35 mV/dec |

---

## Technologies Used

- Synopsys Sentaurus Structure Editor (SDE)
- Synopsys Sentaurus Device (SDevice)
- Synopsys Sentaurus Visual
- Python (NumPy, Matplotlib) for data analysis and visualization

---

## Key Learning Outcomes

- 3D semiconductor device modeling
- Gate-All-Around transistor architecture
- Nanoscale device electrostatics
- Carrier transport modeling
- Short-channel effects
- Threshold voltage extraction
- Transconductance analysis
- Subthreshold swing characterization
- TCAD simulation workflow

---

## References

1. G. Reddy, J. V, S. M, S. Srivastava and A. Acharya, "Self-Heating Aware Performance Investigation of Vertically and Sideway Stacked GAA Nanowire FETs at Sub-5nm Technology Node," 2026 39th International Conference on VLSI Design & 25th International Conference on Embedded Systems (VLSID), Pune, India, 2026, pp. 341-346

2. Synopsys Sentaurus TCAD Documentation.

**Note:** The device architecture and dimensions were inspired by published IEEE research. The simulation setup, implementation, parameter extraction, and analysis presented in this repository were independently developed for educational and research purposes.

---

