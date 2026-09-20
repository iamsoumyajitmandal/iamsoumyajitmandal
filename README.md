<div align="center">

SOUMYAJIT MANDAL
Analog IC Design · Mixed-Signal VLSI · Custom Analog Layout
<a href="https://soumyajitmandal.onrender.com">
  <img src="https://img.shields.io/badge/Portfolio-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio"/>
</a>
<a href="https://linkedin.com/in/soumyajitmandal001/">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:contact.isoumyajitmandal@gmail.com">
  <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>




<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=18&duration=2600&pause=900&color=00E5FF&center=true&vCenter=true&width=900&lines=Transistor-Level+CMOS+Design;PLL+%7C+VCO+%7C+PFD+%7C+Frequency+Synthesis;Cadence+Virtuoso+%7C+Spectre+%7C+Custom+Layout;DRC+%7C+ERC+%7C+LVS+%7C+PEX;Schematic+%E2%86%92+Layout+%E2%86%92+Extraction+%E2%86%92+Validation" alt="Typing SVG"/>

</div>

<table>
<tr>
<td width="56%" valign="middle">

<p align="center">
  <img src="./assets/ascii-art.png" width="100%" alt="Soumyajit Mandal ASCII art"/>
</p>

</td>

<td width="44%" valign="middle">

SYSTEM PROFILE
┌──────────────────────────────┐
│ ROLE                         │
│ Analog IC Design / VLSI      │
├──────────────────────────────┤
│ SPECIALIZATION               │
│ VLSI & Embedded Systems      │
├──────────────────────────────┤
│ CORE CIRCUITS                │
│ PLL · VCO · PFD · CMOS       │
├──────────────────────────────┤
│ LAYOUT                       │
│ Custom Analog / Matching     │
├──────────────────────────────┤
│ VERIFICATION                 │
│ DRC · ERC · LVS · PEX        │
├──────────────────────────────┤
│ PRIMARY EDA                  │
│ Cadence Virtuoso / Spectre   │
└──────────────────────────────┘
</td>
</tr>
</table>

I design at the transistor level, verify at the circuit level, and think through the layout-to-silicon path.

01 — ABOUT
I am an Analog & Mixed-Signal IC Design / Physical Design engineer with a primary focus on transistor-level CMOS circuit design, PLL/VCO/PFD architectures, custom analog layout, and physical verification.
My engineering workflow is centered around:
SPECIFICATION
     │
     ▼
ARCHITECTURE
     │
     ▼
TRANSISTOR-LEVEL DESIGN
     │
     ▼
BIASING + SIZING
     │
     ▼
CIRCUIT SIMULATION
     │
     ▼
CUSTOM ANALOG LAYOUT
     │
     ▼
DRC / ERC / LVS
     │
     ▼
PEX
     │
     ▼
POST-LAYOUT VALIDATION
Primary Interests
Analog IC Design · Mixed-Signal IC Design · PLL · VCO · PFD · Frequency Synthesis · Clocking Circuits · Custom Analog Layout · Device Matching · DRC/ERC/LVS/PEX
02 — CORE SKILLS
<div align="center">

Analog / Mixed-Signal
<img src="https://img.shields.io/badge/Analog%20CMOS-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Mixed--Signal-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/PLL-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/VCO-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/PFD-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Frequency%20Synthesis-111827?style=for-the-badge" />

Layout / Verification
<img src="https://img.shields.io/badge/Custom%20Analog%20Layout-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/Device%20Matching-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/DRC-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/ERC-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/LVS-111827?style=for-the-badge" />
<img src="https://img.shields.io/badge/PEX-111827?style=for-the-badge" />

</div>

03 — FEATURED PROJECT
Enhanced-Stability High-Frequency PLL Architecture
Defence Institute of Advanced Technology (DIAT), DRDO
August 2025 – May 2026 · GPDK090 · Cadence Virtuoso / Spectre
A transistor-level CMOS PLL designed for fine-resolution 2.5–3.8 GHz frequency synthesis.
Architecture
                         REFERENCE
                            │
                            ▼
                     ┌─────────────┐
                     │     PFD     │
                     └──────┬──────┘
                            │
                       UP / DOWN
                            │
                            ▼
                     ┌─────────────┐
                     │ CHARGE PUMP │
                     └──────┬──────┘
                            │
                            ▼
                     ┌─────────────┐
                     │ LOOP FILTER │
                     └──────┬──────┘
                            │ VCTRL
                            ▼
                     ┌─────────────┐
                     │ CURRENT-    │
                     │ STARVED     │
                     │ VCRO        │
                     └──────┬──────┘
                            │
                            ▼
                       OUTPUT CLOCK
                            │
                            ▼
                     ┌─────────────┐
                     │  DIVIDER    │
                     └──────┬──────┘
                            │
                            └──────────────► PFD
Circuit Contributions
- Dead-zone-free PFD using balanced latch paths.
- Optimized reset timing.
- Buffered UP/DOWN outputs for small phase differences.
- Matched charge-pump implementation.
- Passive loop-filter integration.
- Source-degenerated current-starved VCRO.
- Feedback divider for closed-loop frequency control.
- Transistor-level simulation and lock verification.
Reported Results
Parameter	Result
Technology	GPDK090
Target frequency	2.5–3.8 GHz
Closed-loop locking	~2.506 GHz
Frequency ripple	4.013 MHz
Normalized ripple	0.160%
Output duty cycle	49.8%
RMS jitter	70.98 fs
Peak-to-peak jitter	1.588 ps


04 — PLL BUILDING BLOCKS
                    PLL SUBSYSTEM
                         │
        ┌────────────────┼────────────────┐
        │                │                │
        ▼                ▼                ▼
       PFD         CHARGE PUMP       LOOP FILTER
        │                │                │
        └────────────────┼────────────────┘
                         │
                         ▼
                        VCO
                         │
                         ▼
                      DIVIDER
                         │
                         └──────────► FEEDBACK
PFD
- Phase and frequency comparison
- UP/DOWN pulse generation
- Reset-path optimization
- Dead-zone reduction
- Small phase-error detection
Charge Pump
- UP/DOWN controlled current paths
- Current matching
- Control-voltage generation
- Interaction with passive loop filter
Loop Filter
- Control-voltage smoothing
- Loop dynamics
- Ripple suppression
- VCO control
VCO / VCRO
- Voltage-controlled oscillation
- Current-starved topology
- Source degeneration
- Kvco and tuning behavior
- Frequency stability
Divider
- Feedback frequency generation
- Closed-loop frequency control
- VCO-to-reference frequency relationship
05 — PFD & VCO PROJECT
High-Performance PFDs & VCOs for PLL Applications
Cooch Behar Government Engineering College
July 2023 – June 2024 · 90 nm CMOS · Cadence Virtuoso
Designed and analyzed PFD and VCO circuits at transistor level for PLL applications.
┌────────────────────────────────────────────────┐
│              5-STAGE VCRO                      │
├────────────────────────────────────────────────┤
│ Technology       : 90 nm CMOS                  │
│ Tuning Range     : 1.25 MHz – 3 GHz            │
│                                                 │
│ PFD Phase Noise  : -143.71 dBc/Hz              │
│ Offset           : 1 MHz                       │
│                                                 │
│ Reported Lock-In : ~31 ns                      │
└────────────────────────────────────────────────┘
Work Included
- 5-stage VCRO design.
- PFD architecture and reset-path optimization.
- Dead-zone elimination.
- Transistor-level simulation.
- Stability analysis.
- Power-performance analysis.
06 — ANALOG IC DESIGN INTERNSHIP
Basic Analog IC Design Using Cadence Virtuoso
National Institute of Technology Sikkim
July 2023 – August 2023
Worked with GPDK090 technology and Cadence Virtuoso on analog CMOS building blocks.
SCHEMATIC
    │
    ├── Device sizing
    ├── Biasing
    └── Operating-point verification
             │
             ▼
       DC / AC / TRANSIENT
             │
       ┌─────┼─────┐
       ▼     ▼     ▼
      GAIN  BW   WAVEFORM
       │     │     │
       └─────┼─────┘
             ▼
        OPTIMIZATION
Focus:
- Basic analog CMOS building blocks
- Operating-point verification
- Gain analysis
- Bandwidth analysis
- Bias-condition analysis
- Transistor-level performance evaluation
- Circuit optimization and documentation
07 — EDA TOOLCHAIN
Analog IC Design
<p align="center">
  <img height="52" src="https://cdn.simpleicons.org/cadence" alt="Cadence"/>
  <img height="52" src="https://img.shields.io/badge/Virtuoso-E31837?style=for-the-badge&logo=cadence&logoColor=white" alt="Cadence Virtuoso"/>
  <img height="52" src="https://img.shields.io/badge/Spectre-8B1A2B?style=for-the-badge" alt="Cadence Spectre"/>
  <img height="52" src="https://img.shields.io/badge/LTspice-B71C1C?style=for-the-badge&logo=analogdevices&logoColor=white" alt="LTspice"/>
  <img height="52" src="https://img.shields.io/badge/PSpice-C41E3A?style=for-the-badge&logo=cadence&logoColor=white" alt="PSpice"/>
</p>

Synopsys / ASIC
<p align="center">
  <img height="52" src="https://cdn.simpleicons.org/synopsys" alt="Synopsys"/>
  <img height="52" src="https://img.shields.io/badge/VCS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Synopsys VCS"/>
  <img height="52" src="https://img.shields.io/badge/VERDI%20%2F%20NOVAS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="VERDI NOVAS"/>
  <img height="52" src="https://img.shields.io/badge/Design%20Compiler-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Design Compiler"/>
  <img height="52" src="https://img.shields.io/badge/ICC2-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="ICC2"/>
  <img height="52" src="https://img.shields.io/badge/PrimeTime-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="PrimeTime"/>
</p>

Additional Tools
<p align="center">
  <img src="https://skillicons.dev/icons?i=python,matlab,git,github,vscode&perline=5" alt="Python MATLAB Git GitHub VS Code"/>
</p>

Altium Designer · KiCad · KLayout · Xilinx Vivado
Brand icons above use Simple Icons where an icon is available; product-specific tools are represented by labeled badges where a suitable maintained brand icon is not available. Simple Icons documents its CDN usage and supported icon library. 

08 — TECHNOLOGY NODES
        ┌─────────────────────────────────────┐
        │          CMOS TECHNOLOGIES          │
        ├─────────────────────────────────────┤
        │                                     │
        │  GPDK45       → 45 nm               │
        │  GPDK090      → 90 nm               │
        │  GPDK180      → 180 nm              │
        │  TSMC 130 nm  → 130 nm              │
        │  SkyWater 130 → 130 nm              │
        │                                     │
        └─────────────────────────────────────┘
09 — CUSTOM ANALOG LAYOUT
                 CIRCUIT SPECIFICATION
                          │
                          ▼
                 TRANSISTOR SIZING
                          │
                          ▼
                       BIASING
                          │
                          ▼
                   CUSTOM LAYOUT
                          │
             ┌────────────┼────────────┐
             ▼            ▼            ▼
          Matching     Symmetry    Common-Centroid
             │            │            │
             └────────────┼────────────┘
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
                POST-LAYOUT SIMULATION
Layout Focus
Custom Analog Layout · Device Matching · Symmetry · Common-Centroid · DRC · ERC · LVS · PEX
10 — RTL TO GDSII EXPOSURE
IC Design: RTL to GDSII Implementation
Defence Institute of Advanced Technology
November 2025
Although my primary focus is analog IC design, I have also worked through a complete introductory digital implementation flow.
RTL
 │
 ▼
VCS
 │
 ▼
VERDI / NOVAS
 │
 ▼
DESIGN COMPILER
 │
 ▼
FLOORPLAN
 │
 ▼
POWER GRID
 │
 ▼
PLACEMENT
 │
 ▼
CTS
 │
 ▼
ROUTING
 │
 ▼
PRIMETIME
 │
 ▼
GDSII
Tools
Synopsys VCS · VERDI/NOVAS · Design Compiler · ICC2 · PrimeTime
11 — EDUCATION
Degree	Institute	Period	Result
M.Tech — Electronics Engineering	Defence Institute of Advanced Technology (DU), DRDO	Jul 2024 – Jun 2026	CGPA 6.62
B.Tech — Electronics & Communication Engineering	Cooch Behar Government Engineering College	Aug 2020 – Jul 2024	CGPA 8.23
XII — Science (PCMB)	Malda Zilla School	Apr 2018 – Mar 2020	80%


M.Tech Specialization: VLSI & Embedded Systems
12 — DESIGN PATENT
Next-Generation AI Device for Cloud-Integrated Smart Data Intelligence
Design No.     : 496442-001
Journal No.    : 23/2026
Journal Date   : 05/06/2026
Status         : Design Accepted and Published
13 — CERTIFICATIONS
Year	Certification / Training	Organization
2025	IC Design: RTL to GDSII Implementation	DIAT
2024	Advanced Entrepreneurship-Cum-Skill Development Programme	NIT Sikkim
2023	Basic Analog IC Design Using Cadence Virtuoso Platform	NIT Sikkim
2023	Artificial Intelligence	Remarkskill × IIT Kharagpur
2021	Coder's Python	HOMEFLIC WeGrow


14 — COURSEWORK
Analog & Mixed Mode Signal VLSI Design
CAD for VLSI Circuits
RFIC Design
EMI / EMC Design
Digital IC Design
Digital System Design using FPGA
