# Optical and Electrical Simulation of an Ag₂Te Quantum-Dot Photodetector at 1550 nm

> **Status: planned.** This repository will be filled in as the simulations are done.

**Part of:** FMCW LiDAR with a colloidal-QD photodetector (MSc thesis)
**Tools:** Ansys Lumerical FDTD and CHARGE, Python

## Aim

To find how well an Ag₂Te QD photodetector absorbs light at 1550 nm and converts it to current, and to pass the resulting detector parameters to an FMCW LiDAR system model.

## Planned approach

1. **Optical (FDTD):** model the QD active layer using the QD size (≈ 3.8 nm) and material inputs from [Ag2Te-DFT-Simulations](https://github.com/elvinbegen/Ag2Te-DFT-Simulations), and calculate absorption in the active layer at 1550 nm.
2. **Electrical (CHARGE):** use the FDTD generation rate to calculate photocurrent, responsivity, dark current and bandwidth.
3. **Output:** a short parameter set (responsivity, bandwidth, noise) for the FMCW system model.

```text
DFT (QD size, material) ──► FDTD (absorption) ──► CHARGE (photocurrent) ──► FMCW system model
```

## Repository structure

```text
FDTD_Optical_Simulations/       ← optical model of the QD layer (planned)
CHARGE_Electrical_Simulations/  ← electrical model of the device (planned)
```
