# TCAD Modeling and Characterization of Gate-All-Around (GAA) Nanowire FET

> **3D modeling and electrical characterization of a sub-5 nm Gate-All-Around (GAA) Nanowire Field-Effect Transistor (FET) using Synopsys Sentaurus TCAD.**

---

## Overview

As transistor dimensions continue to scale below 5 nm, conventional FinFETs face increasing challenges due to short-channel effects and reduced electrostatic control. Gate-All-Around (GAA) Nanowire FETs address these limitations by surrounding the channel with the gate, enabling superior gate control and improved device performance.

This project presents the design, simulation, and characterization of a **3D sub-5 nm GAA Nanowire MOSFET** using **Synopsys Sentaurus TCAD**. The device geometry was developed based on published IEEE literature, and the simulation framework was configured to investigate nanoscale transistor behavior under various operating conditions.

---

## Objectives

- Build a 3D Gate-All-Around Nanowire FET model
- Implement appropriate carrier transport and mobility models
- Simulate transfer characteristics (ID–VGS)
- Evaluate short-channel effects
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

- Drift-Diffusion Carrier Transport
- Fermi-Dirac Statistics
- Doping-Dependent Mobility
- High-Field Saturation
- Shockley-Read-Hall (SRH) Recombination
- Bandgap Narrowing
- Electrostatic Modeling

---

## Simulation Workflow

```
Device Geometry
      │
      ▼
Mesh Generation
      │
      ▼
Material Definition
      │
      ▼
Physics Model Setup
      │
      ▼
Bias Conditions
      │
      ▼
Transfer Characteristics (ID–VGS)
      │
      ▼
Parameter Extraction
      │
      ▼
Performance Analysis
```

---

## Results

### Device Structure

> Add screenshots of the following:

- 3D Device Structure
- Cross-sectional View
- Device Mesh
- Doping Profile
- Electrostatic Potential (optional)
- Electron Concentration (optional)

---

### Transfer Characteristics (ID–VGS)

*Insert your ID–VGS plot here.*

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

> Replace the table below with your measured values.

| Parameter | Value |
|-----------|-------|
| Threshold Voltage (VTH) | XX V |
| ON Current (ION) | XX A |
| OFF Current (IOFF) | XX A |
| ION/IOFF Ratio | XX |
| Peak Transconductance (gm) | XX S |
| Subthreshold Swing (SS) | XX mV/dec |

---

## Repository Structure

```
.
├── README.md
├── tcad/
│   ├── structure/
│   ├── simulation/
│   └── project_files/
├── scripts/
├── figures/
├── results/
└── docs/
```

---

## Technologies Used

- Synopsys Sentaurus TCAD
- Semiconductor Device Modeling
- Nanowire MOSFET Simulation
- Silicon Device Physics
- Python (for data visualization and analysis)

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

## Future Improvements

- Simulate output characteristics (ID–VDS)
- Perform AC analysis for gate capacitance extraction
- Compare simulation results with additional published GAA FET designs
- Investigate the impact of channel dimensions and oxide thickness on device performance

---

## References

1. Published IEEE literature on Gate-All-Around (GAA) Nanowire FET architectures.
2. Synopsys Sentaurus TCAD Documentation.

> **Note:** The device architecture and dimensions were inspired by published IEEE research. The simulation setup, implementation, parameter extraction, and analysis presented in this repository were independently developed for educational and research purposes.

---

## License

This project is intended for educational and research purposes.
