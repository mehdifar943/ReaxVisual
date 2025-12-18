<p align="center">
  <img src="https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows" alt="Windows">
  <img src="https://img.shields.io/badge/Version-1.0-green?style=for-the-badge" alt="Version 1.0">
  <img src="https://img.shields.io/badge/License-Academic%20Use-blue?style=for-the-badge" alt="Academic License">
  <img src="https://img.shields.io/badge/ReaxFF-Visualization-orange?style=for-the-badge" alt="ReaxFF Visualization">
</p>

<h1 align="center">⚗️ ReaxVisual</h1>
<p align="center">Transform your ReaxFF molecular dynamics simulations into actionable chemical insights</p>

---

## 📖 Overview

**ReaxVisual** is a cutting-edge desktop application designed for computational chemists and materials scientists. It provides **interactive analysis** of Reactive Force Field (ReaxFF) molecular dynamics simulations, bridging the gap between complex simulation data and intuitive chemical understanding.

> **Direct LAMMPS Integration • Automatic Molecule Recognition • Live Reaction Monitoring**

---

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **🤖 Automatic Molecule Recognition** | Intelligent detection and tracking of chemical species across simulation frames |
| **📊 Complete 3D Structural Analysis** | Multiple rendering modes with bond length, angle, and dihedral measurements |
| **⚡ ReaxFF-Specific Tools** | Direct support for LAMMPS trajectory files (.lammpstrj, .dump) with bond order display |
| **💾 Export Capabilities** | High-resolution image export (PNG, JPG) and data export (CSV, XYZ, PDB) |
| **🎯 Reaction Network Analysis** | Automatic detection of reaction events and network graph generation |

---

## 🚀 Quick Installation

### Download & Install:
1. **Download the latest release** from the [Releases section](https://github.com/mehdifar943/ReaxVisual/releases)
2. **Run `ReaxVisual_1.0.exe`** with administrator privileges
3. **Follow the installation wizard** (default installation takes 2-3 minutes)
4. **Launch** from Start Menu or Desktop shortcut

> The installer includes a bundled Java Runtime Environment for easy setup on Windows systems.

---

## 🔬 Scientific Significance for ReaxFF Simulation

ReaxVisual is not merely a visualization tool; it is a critical analytical platform that fundamentally enhances the study of complex reactive systems. While the ReaxFF method is powerful for simulating bond formation and breaking in large-scale systems (such as combustion, catalysis, or material degradation), the resulting datasets are extraordinarily complex and high-dimensional.

### **The Challenge of Large-Scale ReaxFF Analysis**
Traditional analysis of ReaxFF trajectories for systems containing thousands of atoms involves parsing gigabytes of coordinate and bond order data. Manually identifying transient reaction intermediates, constructing reaction networks, and verifying chemical mechanisms from this numerical output is a slow, error-prone, and often intractable task. Key mechanistic insights are frequently buried in the data.

### **How ReaxVisual Provides the Solution**
This program directly addresses these challenges by transforming abstract data into visual, interactive chemical insight:

*   **From Data to Mechanism**: It automates the tedious process of **molecule recognition and tracking** across thousands of simulation frames, instantly revealing the birth, evolution, and consumption of chemical species. This allows researchers to visually **confirm reaction pathways** and identify rare but crucial catalytic cycles or decomposition routes that might be missed in standard analysis.
*   **Intuitive Validation & Discovery**: By providing a view of the simulation, ReaxVisual serves as an essential **validation tool**. Researchers can immediately see if a simulation is proceeding as expected based on chemical intuition, leading to faster debugging of simulation parameters. Furthermore, the visual format often leads to **unexpected discoveries**—spotting non-obvious intermediates or spatial correlations that are not apparent in graphs or tables.
*   **Scaling Insight with System Size**: The utility of ReaxVisual **increases with the size and complexity of the simulated system**. For studies on polymer aging, catalyst surfaces, or energetic material decomposition—where hundreds of simultaneous reactions may occur—the software's ability to automatically generate and visualize a reaction network is indispensable. It turns an overwhelming dataset into a navigable map of chemical events, making the analysis of large-scale reactive simulations not just possible, but efficient and insightful.

In essence, ReaxVisual closes the critical loop between simulation and understanding, enabling researchers to fully leverage the predictive power of ReaxFF to explore and explain complex chemical phenomena.
