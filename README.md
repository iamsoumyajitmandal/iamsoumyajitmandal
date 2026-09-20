from pathlib import Path
from textwrap import dedent

readme = dedent(r'''\
# <div align="center">SOUMYAJIT MANDAL</div>

<div align="center">

### Analog & Mixed-Signal IC Design • VLSI • Custom Layout • PLL/VCO/PFD

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=2800&pause=900&color=00D9FF&center=true&vCenter=true&width=850&lines=Analog+IC+Design+%7C+VLSI+%7C+Custom+Layout;PLL+%7C+VCO+%7C+PFD+%7C+Transistor-Level+Design;Cadence+Virtuoso+%7C+Spectre+%7C+Analog+Simulation;Designing+circuits+from+schematic+to+silicon-ready+validation" alt="Typing SVG" />

[![Portfolio](https://img.shields.io/badge/Portfolio-soumyajitmandal.onrender.com-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=white)](https://soumyajitmandal.onrender.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Soumyajit%20Mandal-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/soumyajitmandal001/)
[![Email](https://img.shields.io/badge/Email-contact.isoumyajitmandal%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact.isoumyajitmandal@gmail.com)

</div>

---

## ⚡ About Me

```text
                    ╔══════════════════════════════════════════════════════╗
                    ║                 SOUMYAJIT MANDAL                     ║
                    ╠══════════════════════════════════════════════════════╣
                    ║  Analog IC Design        →  PLL / VCO / PFD         ║
                    ║  Circuit Level           →  CMOS / Transistor Level ║
                    ║  Physical Design         →  Custom Analog Layout    ║
                    ║  Verification            →  DRC / ERC / LVS / PEX  ║
                    ║  Simulation              →  DC / AC / Tran / Noise ║
                    ║  Target                  →  Silicon-Ready Design   ║
                    ╚══════════════════════════════════════════════════════╝
```

> Aspiring **Analog & Mixed-Signal IC Design and Physical Design Engineer** with a strong interest in transistor-level CMOS circuit design, custom layout, and silicon-ready validation. My work focuses on device sizing, biasing, layout matching, connectivity integrity, parasitic-aware post-layout analysis, and power-performance trade-offs.

I completed my **M.Tech in Electronics Engineering (VLSI & Embedded Systems) at Defence Institute of Advanced Technology (DIAT), DRDO**, following a **B.Tech in Electronics & Communication Engineering from Cooch Behar Government Engineering College**.

My core project work includes **PLL, VCO and PFD architectures**, analog CMOS building blocks, transistor-level simulation, custom analog layout, and physical verification.

---

## 🧠 Core Focus

```text
Analog IC Design       ████████████████████████  Transistor-Level CMOS
Mixed-Signal Design    ████████████████████████  PLL / VCO / PFD
Custom Layout          ████████████████████████  Matching / PEX / LVS
Circuit Simulation     ████████████████████████  DC / AC / Transient / Noise
Physical Verification  ████████████████████████  DRC / ERC / LVS
ASIC Flow              ██████████████████░░░░░░  RTL → GDSII
```

- Analog & Mixed-Signal IC Design
- Transistor-Level CMOS Design
- PLL / VCO / PFD Architectures
- Frequency Synthesizers & Clocking Circuits
- Custom Analog Layout & Device Matching
- DRC / ERC / LVS / PEX
- Post-Layout Simulation
- ASIC Design Fundamentals
- Power / Performance / Noise Trade-offs

---

# 🔬 Featured Projects

## 01. Enhanced-Stability High-Frequency PLL Architecture

**Defence Institute of Advanced Technology (DIAT), DRDO**  
`August 2025 – May 2026`

Designed and verified a CMOS PLL for fine-resolution **2.5–3.8 GHz frequency synthesis** using **Cadence Virtuoso / Spectre** in **GPDK090** technology.

### Architecture

```text
 Reference Clock
       │
       ▼
   ┌─────────┐
   │   PFD   │────── UP / DOWN
   └────┬────┘          │
        │               ▼
        │          ┌──────────┐
        │          │ Charge   │
        │          │   Pump   │
        │          └────┬─────┘
        │               │
        │               ▼
        │          ┌──────────┐
        │          │  Loop    │
        │          │  Filter  │
        │          └────┬─────┘
        │               │ VCTRL
        │               ▼
        │          ┌──────────┐
        │          │   VCO    │──────► High-Speed Clock
        │          └────┬─────┘
        │               │
        │               ▼
        └─────────── Divider
```

### Key Work
- Dead-zone-free PFD with balanced latch paths.
- Optimized reset timing and buffered UP/DOWN outputs for small phase errors.
- Matched charge pump and passive loop filter.
- Source-degenerated current-starved VCRO.
- Feedback divider for closed-loop frequency control.
- Transistor-level simulation and PLL lock verification.

### Reported Results

| Metric | Result |
|---|---:|
| Technology | GPDK090 |
| Target frequency range | 2.5–3.8 GHz |
| Closed-loop locking | ~2.506 GHz |
| Frequency ripple | 4.013 MHz |
| Normalized ripple | 0.160% |
| Output duty cycle | 49.8% |
| RMS jitter | 70.98 fs |
| Peak-to-peak jitter | 1.588 ps |

---

## 02. High-Performance PFDs & VCOs for PLL Applications

**Cooch Behar Government Engineering College**  
`July 2023 – June 2024`

Designed and analyzed high-performance **Phase-Frequency Detectors (PFDs)** and **Voltage-Controlled Oscillators (VCOs)** at transistor level.

### Highlights
- Designed a **5-stage VCRO in 90 nm CMOS**.
- Achieved a reported tuning range of **1.25 MHz–3 GHz**.
- Achieved reported PFD phase noise of **−143.71 dBc/Hz at 1 MHz offset**.
- Reduced reported lock-in time to approximately **31 ns**.
- Investigated TSPC-based logic and optimized PFD reset behavior.
- Validated designs through Cadence Virtuoso transistor-level simulations.

---

## 03. Basic Analog IC Design — Research Internship

**National Institute of Technology Sikkim**  
`July 2023 – August 2023`

Worked on fundamental analog CMOS building blocks using **GPDK090** technology and Cadence Virtuoso.

- Common-Source amplifiers
- Common-Gate amplifiers
- High-precision current mirrors
- DC / AC / transient analysis
- Operating-point verification
- Gain and bandwidth analysis
- Bias-condition evaluation
- Analog circuit optimization and documentation

---

## 04. IC Design: RTL to GDSII Implementation

**Defence Institute of Advanced Technology (DIAT), DRDO**  
`November 2025`

Executed a complete RTL-to-GDSII implementation flow for a **4-bit full adder**.

```text
RTL
 │
 ▼
VCS Verification
 │
 ▼
Design Compiler
 │
 ▼
Floorplanning
 │
 ▼
Power Planning
 │
 ▼
Placement
 │
 ▼
CTS
 │
 ▼
Routing
 │
 ▼
PrimeTime STA
 │
 ▼
GDSII Signoff
```

Tools included **Synopsys VCS, VERDI/NOVAS, Design Compiler, ICC2 and PrimeTime**.

---

# 🛠️ Software & EDA Arsenal

### Analog / SPICE / Custom IC Design

<p align="center">
  <img src="https://img.shields.io/badge/Cadence%20Virtuoso-E31837?style=for-the-badge&logo=cadence&logoColor=white" alt="Cadence Virtuoso"/>
  <img src="https://img.shields.io/badge/Spectre-8B0000?style=for-the-badge&logoColor=white" alt="Cadence Spectre"/>
  <img src="https://img.shields.io/badge/LTspice-B71C1C?style=for-the-badge&logo=analogdevices&logoColor=white" alt="LTspice"/>
  <img src="https://img.shields.io/badge/PSpice-CC0000?style=for-the-badge&logo=cadence&logoColor=white" alt="PSpice"/>
</p>

### Synopsys Digital / Physical Design

<p align="center">
  <img src="https://img.shields.io/badge/VCS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Synopsys VCS"/>
  <img src="https://img.shields.io/badge/VERDI%20%2F%20NOVAS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="VERDI NOVAS"/>
  <img src="https://img.shields.io/badge/Design%20Compiler-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Design Compiler"/>
  <img src="https://img.shields.io/badge/ICC2-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="ICC2"/>
  <img src="https://img.shields.io/badge/PrimeTime-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="PrimeTime"/>
</p>

### PCB / Layout / FPGA

<p align="center">
  <img src="https://skillicons.dev/icons?i=altium" height="48" alt="Altium Designer"/>
  <img src="https://skillicons.dev/icons?i=kicad" height="48" alt="KiCad"/>
  <img src="https://skillicons.dev/icons?i=vscode" height="48" alt="VS Code"/>
</p>

**Also:** KLayout • Xilinx Vivado • MATLAB • Python

> **Icon note:** specialized EDA products such as Cadence Virtuoso, PSpice and individual Synopsys tools do not have a consistent open icon set comparable to programming languages. The badges above therefore use brand/logo parameters where available and otherwise retain the product's official name rather than inventing unofficial icons.

---

# 🧩 Technology Nodes

```text
GPDK45       → 45 nm
GPDK090      → 90 nm
GPDK180      → 180 nm
TSMC 130 nm  → 130 nm
SkyWater 130 → 130 nm
```

---

# 📐 Layout & Verification

```text
                    CUSTOM ANALOG LAYOUT
                            │
             ┌──────────────┼──────────────┐
             ▼              ▼              ▼
       Device Matching   Common Centroid   Symmetry
             │              │              │
             └──────────────┼──────────────┘
                            ▼
                         DRC / ERC
                            │
                            ▼
                           LVS
                            │
                            ▼
                           PEX
                            │
                            ▼
                 Post-Layout Simulation
```

**Focus:** Custom Analog Layout • Device Matching • DRC • ERC • LVS • PEX • Parasitic-Aware Simulation

---

# 🎓 Education

| Degree | Institute | Period | Result |
|---|---|---|---:|
| **M.Tech — Electronics Engineering** | DIAT (DU), DRDO | Jul 2024 – Jun 2026 | CGPA 6.62 |
| **B.Tech — Electronics & Communication Engineering** | Cooch Behar Government Engineering College | Aug 2020 – Jul 2024 | CGPA 8.23 |
| **Higher Secondary — Science (PCMB)** | Malda Zilla School | Apr 2018 – Mar 2020 | 80% |

**M.Tech Specialization:** VLSI & Embedded Systems

---

# 🏆 Design Patent

### Next-Generation AI Device for Cloud-Integrated Smart Data Intelligence

`Design No. 496442-001` • `Journal No. 23/2026` • `Journal Date: 05/06/2026`

**Status:** Design Accepted and Published

---

# 📜 Certifications & Training

- **IC Design: RTL to GDSII Implementation** — DIAT, Nov 2025
- **Advanced Entrepreneurship-Cum-Skill Development Programme (E-SDP)** — NIT Sikkim, Mar 2024
- **Basic Analog IC Design Using Cadence Virtuoso Platform** — NIT Sikkim, Aug 2023
- **Artificial Intelligence** — Remarkskill & IIT Kharagpur, Jan 2023
- **Coder's Python** — HOMEFLIC WeGrow, Jun 2021

---

# 📚 Relevant Coursework

- Analog & Mixed Mode Signal VLSI Design
- CAD for VLSI Circuits
- RFIC Design
- EMI/EMC Design
- Digital IC Design
- Digital System Design using FPGA

---

# 🌐 Languages

| Language | Proficiency |
|---|---|
| English | Proficient |
| Bengali | Native |
| Hindi | Fluent |

---

# 📊 GitHub Analytics

> Replace `YOUR_GITHUB_USERNAME` below with your GitHub username. Your portfolio source does not expose a GitHub username, so I have intentionally not guessed it.

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" height="180" alt="GitHub Stats"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true" height="180" alt="Top Languages"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" alt="GitHub Streak"/>
</p>

---

# 🔭 Current Direction

```text
Analog IC Design
      │
      ├── CMOS Transistor-Level Design
      ├── PLL / VCO / PFD
      ├── Frequency Synthesis
      ├── Low-Noise / High-Speed Circuits
      ├── Custom Analog Layout
      ├── DRC / ERC / LVS / PEX
      └── Silicon-Ready Validation
```

I am particularly interested in opportunities involving **Analog IC Design, Mixed-Signal IC Design, Custom Layout, Physical Verification, VLSI Research, and transistor-level circuit development**.

---

# 📫 Let's Connect

<div align="center">

**Interested in Analog IC Design, VLSI, or collaborative research?**

[![Portfolio](https://img.shields.io/badge/🌐%20Portfolio-Soumyajit%20Mandal-00D9FF?style=for-the-badge)](https://soumyajitmandal.onrender.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/soumyajitmandal001/)
[![Email](https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:contact.isoumyajitmandal@gmail.com)

</div>

---

<div align="center">

### `DESIGN • SIMULATE • LAYOUT • VERIFY • INNOVATE`

<sub>© Soumyajit Mandal • Analog IC Design & VLSI</sub>

</div>
''')

out = Path("/mnt/data/README_Soumyajit_Mandal.md")
out.write_text(readme, encoding="utf-8")
print(out)
