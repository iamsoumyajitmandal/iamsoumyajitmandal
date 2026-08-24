# Hi, I'm Soumyajit Mandal 👋

### Analog VLSI | Analog IC Design | PLL & Mixed-Signal Circuit Design

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00BFFF&center=true&vCenter=true&width=700&lines=Analog+VLSI+%7C+Analog+IC+Design;PLL+%7C+VCO+%7C+PFD+%7C+Charge+Pump;Cadence+Virtuoso+%7C+SpectreRF;M.Tech+in+VLSI+%26+Embedded+Systems" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/">
    <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
  </a>
  <a href="https://www.linkedin.com/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white">
  </a>
</p>

---

## 👨‍💻 About Me

I am an **M.Tech student specializing in VLSI & Embedded Systems**, with a strong focus on **Analog VLSI, Analog IC Design, and mixed-signal circuit design**.

My primary interest lies in designing and analyzing transistor-level circuits for high-performance integrated systems, particularly **Phase-Locked Loops (PLLs), Voltage-Controlled Oscillators (VCOs), Phase-Frequency Detectors (PFDs), charge pumps, loop filters, and frequency-divider architectures**.

I enjoy working close to the transistor level — from **circuit architecture and device sizing to simulation, performance analysis, and physical implementation**.

### 🔬 Current Focus

* Analog IC Design
* Analog VLSI
* PLL-based frequency synthesis
* Low-jitter and low-noise VCO design
* High-speed Phase-Frequency Detectors
* Charge Pump and Loop Filter design
* Mixed-Signal Circuit Design
* CMOS transistor-level design
* PVT and corner analysis
* Post-layout verification
* SpectreRF-based RF/analog simulations

---

## 🎓 Education

### M.Tech — Electronics Engineering

**VLSI & Embedded Systems**

**Defence Institute of Advanced Technology (DIAT), Pune**
2024 – 2026

Focused on:

* Analog VLSI
* CMOS Analog Circuit Design
* VLSI Design
* Embedded Systems
* RF/Mixed-Signal Circuit Design
* Semiconductor Device Modeling
* IC Design & Verification

### B.Tech — Electronics & Communication Engineering

**Cooch Behar Government Engineering College (CGEC)**
2019 – 2024

Major academic interests:

* Analog Electronics
* Digital Electronics
* VLSI Design
* Communication Systems
* Microelectronics
* Embedded Systems

---

# 🔬 Research & Thesis

## Enhanced-Stability PLL Architecture for Fine-Resolution Multi-Gigahertz Frequency Synthesis Using Advanced Phase Detection

My current research focuses on the design and simulation of an **analog PLL architecture for multi-gigahertz frequency synthesis** using CMOS technology.

### Target Architecture

```text
                 ┌─────────────────┐
                 │ Reference Clock │
                 │    125 MHz      │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │      PFD        │
                 │ Phase/Frequency │
                 │    Detector     │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │   Charge Pump   │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │   Loop Filter   │
                 │  2nd Order LPF  │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │       VCO       │
                 │ 2.4 – 2.5 GHz   │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Frequency      │
                 │  Divider N = 20 │
                 └────────┬────────┘
                          │
                          └──────────────► PFD
```

### Technology

* **CMOS Technology:** GPDK90
* **Primary EDA:** Cadence Virtuoso
* **Simulator:** Cadence Spectre
* **RF Analysis:** SpectreRF
* **Design Methodology:** Transistor-level analog design
* **Target VCO Frequency:** ~2.4–2.5 GHz
* **Reference Frequency:** 125 MHz
* **Division Ratio:** N = 20

### Key Design Blocks

* TSPC-based Phase-Frequency Detector
* Multi-stage reset architecture
* Dead-zone reduction
* Charge Pump
* Second-order Loop Filter
* Voltage-Controlled Ring Oscillator
* High-speed frequency divider
* Injection-Locked Frequency Divider exploration
* PVT and transient analysis
* Phase-noise and jitter analysis

### Current Research Goals

* Reduce PLL jitter
* Improve phase-noise performance
* Minimize PFD dead zone
* Improve UP/DN current matching
* Improve VCO tuning characteristics
* Improve PLL stability
* Achieve reliable frequency locking
* Analyze PVT variations
* Optimize power-performance trade-offs

---

# 🚀 Featured Projects

## 🔵 PLL Design for Multi-Gigahertz Frequency Synthesis

**Analog VLSI | Cadence Virtuoso | GPDK90**

A transistor-level PLL architecture designed for high-frequency synthesis.

### Main Components

* Phase-Frequency Detector
* Charge Pump
* Loop Filter
* Voltage-Controlled Oscillator
* Frequency Divider
* Feedback Network

### Design Targets

| Parameter           |                Target |
| ------------------- | --------------------: |
| Reference Frequency |               125 MHz |
| VCO Frequency       |         2.4 – 2.5 GHz |
| Divider Ratio       |                    20 |
| Technology          |            90 nm CMOS |
| Design Type         | Analog / Mixed-Signal |

---

## 🔵 High-Performance PFD Design

**Cadence Virtuoso | CMOS | TSPC**

Designed a high-speed Phase-Frequency Detector with emphasis on:

* Dead-zone elimination
* Fast reset operation
* UP/DN pulse generation
* Phase-error detection
* Reduced reset delay
* Improved high-frequency operation

A **multi-stage reset/buffer architecture** was explored to reduce the effective dead zone and improve switching behavior.

---

## 🔵 Voltage-Controlled Ring Oscillator

**Cadence Virtuoso | GPDK90**

Designed and analyzed a multi-stage CMOS ring oscillator for PLL applications.

### Focus Areas

* Oscillation frequency
* Tuning range
* Control-voltage sensitivity
* Power consumption
* Phase noise
* Jitter
* Frequency stability

The VCO was evaluated over multiple control voltages to understand the relationship between tuning voltage and oscillation frequency.

---

## 🔵 PFD & VCO Design for PLL Applications

**B.Tech Final-Year Project**

### Project

**Design of High-Performance Phase Frequency Detectors and Voltage Controlled Oscillators for PLL Applications Using Cadence Virtuoso**

### Technology

* CMOS GPDK45
* Cadence Virtuoso

### Work Included

* PFD architecture design
* Dead-zone reduction
* VCO architecture
* Transistor sizing
* Transient simulation
* Frequency analysis
* Performance comparison
* PLL-oriented circuit optimization

---

## 🔵 Analog IC Design Training

**NIT Sikkim**

Hands-on training in analog integrated circuit design using industry-standard circuit design methodologies.

### Topics Covered

* CMOS transistor fundamentals
* Analog circuit design
* Current mirrors
* Differential amplifiers
* Operational amplifiers
* Frequency response
* Biasing
* Device sizing
* Cadence-based simulation

---

## 🔵 RTL-to-GDSII Digital Design Flow

Although my primary specialization is analog VLSI, I have also worked with the complete digital implementation flow.

### Flow

```text
RTL
 ↓
Synthesis
 ↓
Gate-Level Netlist
 ↓
Floorplanning
 ↓
Placement
 ↓
Clock Tree Synthesis
 ↓
Routing
 ↓
STA
 ↓
GDSII
```

### Tools

* Synopsys VCS
* Verdi
* Design Compiler
* IC Compiler II
* PrimeTime

---

# 🛠️ Technical Skills

## 🔬 Analog / VLSI

* Analog IC Design
* Analog VLSI
* CMOS Circuit Design
* Transistor-Level Design
* Mixed-Signal Circuit Design
* PLL Design
* VCO Design
* PFD Design
* Charge Pump Design
* Loop Filter Design
* Frequency Divider Design
* Current Mirrors
* Differential Amplifiers
* Operational Amplifiers
* CMOS Inverters
* Device Sizing
* Biasing
* PVT Analysis

---

## 🧰 EDA & Simulation Tools

### Cadence

* Cadence Virtuoso
* Virtuoso Schematic Editor
* Virtuoso Layout
* Spectre
* SpectreRF
* PSS
* PNoise
* PXF

### Other Tools

* LTspice
* PSpice
* MATLAB
* Synopsys VCS
* Synopsys Verdi
* Design Compiler
* ICC2
* PrimeTime
* Xilinx Vivado
* Calibre

---

# 💻 Programming & Scripting

```text
Python
MATLAB
Verilog HDL
C
Bash / Linux Shell
HTML
CSS
JavaScript
```

I primarily use programming and scripting for:

* Simulation automation
* Data processing
* Plot generation
* Design calculations
* Hardware description
* Linux-based EDA workflows
* Tool automation

---

# 📊 Design & Analysis

I am particularly interested in understanding circuits through quantitative performance metrics rather than relying only on nominal simulations.

### Important Metrics

* Gain
* Bandwidth
* GBW
* Phase Margin
* Power Consumption
* Slew Rate
* Noise
* Phase Noise
* Jitter
* Lock Time
* Tuning Range
* Current Matching
* PVT Robustness
* Stability
* Frequency Accuracy

---

# 🧠 Areas of Interest

```text
Analog IC Design
      │
      ├── CMOS Analog Circuits
      │
      ├── PLLs
      │    ├── PFD
      │    ├── Charge Pump
      │    ├── Loop Filter
      │    ├── VCO
      │    └── Frequency Divider
      │
      ├── RF / Mixed-Signal ICs
      │
      ├── Low-Noise Circuit Design
      │
      ├── High-Speed Circuit Design
      │
      └── Semiconductor Device & Circuit Modeling
```

---

# 📚 Currently Learning

* Advanced PLL architectures
* Low-jitter PLL design
* Low-phase-noise VCO design
* Injection-Locked Frequency Dividers
* SpectreRF PSS/PNoise analysis
* PVT and Monte Carlo analysis
* Analog layout techniques
* Common-centroid layout
* Matching techniques
* Parasitic-aware circuit design
* Post-layout simulation
* Advanced CMOS analog design methodologies

---

# 🎯 Career Interests

I am particularly interested in opportunities involving:

* **Analog IC Design**
* **Analog VLSI**
* **Mixed-Signal IC Design**
* **PLL / Clocking Circuits**
* **RFIC Design**
* **Memory Circuit Design**
* **Custom IC Design**
* **Circuit Design & Verification**
* **Analog Layout**
* **Semiconductor R&D**

My long-term goal is to work on **high-performance analog and mixed-signal integrated circuits**, with particular interest in clocking, frequency synthesis, RF interfaces, and transistor-level circuit design.

---

# 📈 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=iamsoumyajitmandal&show_icons=true&theme=transparent&hide_border=true&count_private=true" height="165">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iamsoumyajitmandal&layout=compact&theme=transparent&hide_border=true" height="165">
</p>

---

# 🔥 GitHub Streak

<p align="center">
  <img src="https://streak-stats.demolab.com?user=iamsoumyajitmandal&theme=transparent&hide_border=true" />
</p>

---

# 📊 Contribution Graph

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=iamsoumyajitmandal&theme=github-compact&hide_border=true" />
</p>

---

# 📂 What You'll Find Here

My GitHub repositories contain projects, experiments, simulations, and design work related to:

```text
📁 Analog VLSI
📁 CMOS Circuit Design
📁 PLL Design
📁 VCO Design
📁 PFD Design
📁 Cadence Virtuoso
📁 GPDK90 / GPDK45
📁 MATLAB
📁 Verilog HDL
📁 FPGA
📁 Digital VLSI
📁 Linux / EDA Automation
📁 Personal Projects
```

I aim to document my projects with:

* Design objectives
* Circuit architecture
* Schematics
* Simulation setup
* Design equations
* Device sizing
* Results
* Waveforms
* Performance analysis
* Conclusions

---

# 🤝 Let's Connect

I'm open to connecting with:

* Analog IC designers
* VLSI engineers
* Semiconductor researchers
* PhD researchers
* Professors
* Industry professionals
* VLSI students
* Open-source hardware contributors

### 📫 Contact

**LinkedIn:**
https://www.linkedin.com/

**GitHub:**
https://github.com/iamsoumyajitmandal

**Portfolio:**
https://soumyajitmandal.onrender.com/

---

## ⚡ A Little More About Me

> I like understanding circuits from the transistor level up.

Whether it is a single CMOS inverter or a multi-gigahertz PLL, I enjoy breaking the system down into fundamental circuit blocks, understanding the trade-offs, designing the architecture, and validating the result through simulation.

My goal is simple:

**Design circuits that work — understand why they work — and make them better.**

---

<p align="center">
  <b>Thanks for visiting my profile! 🚀</b>
</p>

<p align="center">
  <i>Analog circuits • VLSI • Research • Design • Silicon</i>
</p>
