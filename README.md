# Low Power DSP Module Using Approximate Circuits

This project explores the design and implementation of **low-power Digital Signal Processing (DSP) modules** using **approximate computing techniques**. It is aimed at achieving energy-efficient computation for signal processing tasks without significantly compromising output accuracy — a trade-off acceptable in many DSP applications like image/audio processing, edge computing, and IoT systems.

---

## 🧠 Project Objective

To develop and evaluate **low-power MAC (Multiply-Accumulate)** and other DSP modules using **approximate arithmetic units** such as:
- Approximate Adders (e.g., LOA, ETA, Hybrid Adders)
- Approximate Multipliers
- Hybrid Approximate-Exact Designs

---

## 📁 Repository Structure

Low_power_DSP_module_using_approximate_circuits/
│
├── RTL/
│ ├── mac_with_loa.v # MAC using Lower-part OR Adder (LOA)
│ ├── mac_with_exact.v # MAC using traditional adders
│ └── loa_adder16.v # 16-bit LOA adder module
│
├── Testbenches/
│ ├── tb_mac_with_loa.v # Testbench for approximate MAC
│ └── tb_mac_with_exact.v # Testbench for exact MAC
│
├── Reports/
│ ├── area_power_report.pdf # Genus synthesis results (90nm library)
│ └── accuracy_analysis.xlsx # Error metrics comparison
│
├── Docs/
│ └── project_presentation.pptx # Final PPT for academic/demo use
│
└── README.md # Project documentation
