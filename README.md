# Differential Folded Cascode Amplifier

An LTspice implementation of an amplifier designed for a Sharif University project.

## 📋 Project Overview

This project involves the design and simulation of a high-performance differential folded cascode amplifier in LTspice. The circuit is designed to drive a **100 Ω load** and meets strict performance specifications for gain, output swing, and distortion.

## 🛠️ Circuit Architecture

*   **Topology:** Folded Cascode
*   **Input Stage:** Differential Pair
*   **Load:** Current Mirror Active Loads
*   **Output Stage:** Buffer

## ⚙️ Key Design Features

*   **Current Mirror Biasing:** Implemented for stable and consistent biasing, superior to a simple current source.
*   **Folded Cascode Topology:** Chosen for its excellent combination of:
    *   High Voltage Gain
    *   Wide Output Voltage Swing
    *   Improved Input-Output Isolation
    *   Enhanced Frequency Response and Stability

## ✅ Achieved Performance

The design successfully meets the following project requirements:

| Parameter | Spec |
| :--- | :--- |
| **Voltage Gain** | 2 |
| **Output Swing** | > 16.6 V (peak-to-peak) |
| **Total Harmonic Distortion (THD)** | < 0.05% (@ 16.4 V swing) |
| **Quiescent Power Consumption** | 50 mW |

## 📁 Repository Contents

*   `Folded_Cascode_Amplifier.asc` - Main LTspice schematic
*   `Simulation_Results.pdf` - Plots and analysis of performance metrics
*   `README.md` - This file

## 🔬 How to Use

1.  Open the `Folded_Cascode_Amplifier.asc` file in LTspice.
2.  Run the simulation to verify the operating point and transient response.
3.  Use the .step commands (if any) to perform parametric analyses.

## 👨‍🎓 Contributors

This project was developed as part of an academic course at Sharif University.
