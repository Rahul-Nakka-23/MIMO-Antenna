# Multi-Port Fractal MIMO Antenna: A Mini Project Report

This repository contains the mini-project report on the design, simulation, and analysis of a **multi-port fractal MIMO antenna** tailored for ultra-wideband (UWB) applications. The project focuses on creating a compact and efficient antenna system with inherent self-decoupling properties, eliminating the need for complex external isolation structures.

---

## 📄 Project Overview

This project addresses the growing demand for compact, high-performance UWB MIMO antennas in modern wireless communication systems. By using a novel circular fractal geometry and a Coplanar Waveguide (CPW) feeding mechanism, the antenna achieves excellent performance metrics, making it suitable for applications like 5G, Wi-Fi 6, radar imaging, and wireless sensor networks.

The antenna is a quad-port system designed to operate over a wide frequency range of **3.15 GHz to 20 GHz**. A key feature is its **self-decoupling architecture**, which relies on symmetrical geometric placement rather than additional isolation components, simplifying fabrication and reducing cost.

---

## ✨ Key Features

- **Wide Impedance Bandwidth**: The antenna operates seamlessly across the 3.15-20 GHz frequency range, with a return loss ($S_{11}$) of less than -10 dB.
- **High Isolation**: Achieves inter-element isolation greater than **15 dB** without any external decoupling structures.
- **High Efficiency**: Maintains a radiation efficiency exceeding **85%** throughout the UWB band, with a peak gain of **6.13 dBi**.
- **Excellent MIMO Performance**:
  - **Envelope Correlation Coefficient (ECC)**: Less than 0.008, indicating low signal correlation.
  - **Channel Capacity Loss (CCL)**: Below 0.25 bps/Hz, ensuring minimal degradation.
  - **Mean Effective Gain (MEG)**: Less than -3 dB, confirming uniform signal reception.
- **Compact Design**: The antenna's small size (≤ 50 x 50 mm) makes it ideal for integration into portable and space-constrained devices.
- **Simplified Fabrication**: The use of a CPW-fed design allows for single-layer fabrication, reducing production complexity and cost.

---

## 🛠️ Methodology

The project followed a systematic methodology for design and analysis:

1.  **Requirement Definition**: Defined target specifications based on IEEE 802.15 UWB standards, including frequency range, size, gain, and isolation targets.
2.  **Antenna Geometry Design**: Conceptualized a quad-port configuration using a circular fractal radiating patch on an FR4 or Rogers substrate.
3.  **Feeding Mechanism**: Implemented a **Coplanar Waveguide (CPW)** feed for its wideband matching, low-loss, and single-layer fabrication benefits.
4.  **Simulation & Analysis**: Modeled and simulated the antenna using full-wave electromagnetic simulation tools like **ANSYS HFSS** and **CST Microwave Studio**. Performance parameters such as S-parameters, ECC, and radiation patterns were rigorously analyzed.
5.  **Optimization**: Iteratively tuned key parameters like slot width, fractal ring gap, and element spacing to achieve optimal performance.

---

## ⚙️ Simulation Environment

-   **Software**: ANSYS HFSS 2023, CST Microwave Studio 2022
-   **Frequency Sweep**: 2 GHz to 12 GHz
-   **Boundary Conditions**: Radiation boundary at λ/4, Wave port excitation with 50 Ω impedance.
-   **Substrate**: FR4 Epoxy or Rogers RT/Duroid

---

## 📊 Results and Analysis

The simulation results confirmed the antenna’s superior performance. The `S11` plot shows a return loss below -10 dB across the UWB band, while the `S21` plot demonstrates isolation greater than 15 dB. The radiation patterns are stable, and key MIMO metrics like ECC and CCL are well within acceptable limits, validating the design's effectiveness for modern communication systems.

<p align="center">
  <img width="737" height="578" alt="image" src="https://github.com/user-attachments/assets/08c6ec03-e0ad-441c-8749-e80df6138cda" />

</p>

---

## 📚 References

The project's design and analysis were informed by various academic papers and journals, which are detailed in the `REFERENCES` section of the report. The foundational concepts and comparative analysis drew from a rich body of work on UWB and MIMO antenna design.

---

