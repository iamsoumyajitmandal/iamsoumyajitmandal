\
<div align="center">

SOUMYAJIT MANDAL
Analog IC Design • Mixed-Signal VLSI • Custom Layout • PLL / VCO / PFD
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2600&pause=700&color=00E5FF&center=true&vCenter=true&width=900&lines=Analog+IC+Design+%7C+Transistor-Level+CMOS;PLL+%7C+VCO+%7C+PFD+%7C+Frequency+Synthesis;Cadence+Virtuoso+%7C+Spectre+%7C+Custom+Layout;DRC+%7C+ERC+%7C+LVS+%7C+PEX+%7C+Post-Layout+Simulation" alt="Typing animation"/>

<a href="https://soumyajitmandal.onrender.com/">
<img src="https://img.shields.io/badge/PORTFOLIO-00E5FF?style=for-the-badge&logo=googlechrome&logoColor=black" alt="Portfolio"/>
</a>
<a href="https://linkedin.com/in/soumyajitmandal001/">
<img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:contact.isoumyajitmandal@gmail.com">
<img src="https://img.shields.io/badge/EMAIL-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>

</div>

> whoami
╔══════════════════════════════════════════════════════════════════════════╗
║                           SOUMYAJIT MANDAL                               ║
╠══════════════════════════════════════════════════════════════════════════╣
║  DOMAIN       : Analog & Mixed-Signal IC Design                         ║
║  SPECIALITY   : CMOS / PLL / VCO / PFD / Custom Analog Layout           ║
║  SIMULATION   : Cadence Virtuoso / Spectre / LTspice / PSpice            ║
║  VERIFICATION : DRC / ERC / LVS / PEX / Post-Layout Simulation            ║
║  TECHNOLOGY   : GPDK45 / GPDK090 / GPDK180 / TSMC130 / SkyWater130       ║
║  EDUCATION    : M.Tech Electronics Engineering — VLSI & Embedded Systems ║
║  INSTITUTION  : DIAT (DU), DRDO                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
Aspiring Analog & Mixed-Signal IC Design and Physical Design Engineer focused on transistor-level CMOS circuits, custom analog layout and silicon-oriented validation. My work centers on device sizing, biasing, matching, connectivity integrity, parasitic-aware analysis and power-performance trade-offs.

My portfolio documents work across PLL, VCO, PFD, analog CMOS building blocks, ASIC implementation and physical verification. citeturn0view0
01 — ENGINEERING FOCUS
<table>
<tr>
<td width="50%">

Analog / Mixed-Signal
- Analog IC Design
- Transistor-Level CMOS
- PLL / VCO / PFD
- Frequency Synthesizers
- Clocking Circuits
- Low-Noise / High-Speed Circuits
- Biasing & Device Sizing
- Power / Performance Trade-offs
</td>
<td width="50%">

Physical / Verification
- Custom Analog Layout
- Device Matching
- Common-Centroid Layout
- DRC / ERC
- LVS / PEX
- Parasitic-Aware Analysis
- Post-Layout Simulation
- ASIC Physical Design Fundamentals
</td>
</tr>
</table>

02 — FEATURED WORK
🔷 Enhanced-Stability High-Frequency PLL Architecture
Defence Institute of Advanced Technology (DIAT), DRDO
August 2025 — May 2026 · GPDK090 · Cadence Virtuoso / Spectre
Designed and verified a CMOS PLL for fine-resolution 2.5–3.8 GHz frequency synthesis.
                  ┌───────────────┐
 Reference ──────►│      PFD      │
                  └───────┬───────┘
                          │ UP / DOWN
                          ▼
                  ┌───────────────┐
                  │ Charge Pump   │
                  └───────┬───────┘
                          │
                          ▼
                  ┌───────────────┐
                  │ Passive Loop  │
                  │    Filter     │
                  └───────┬───────┘
                          │ VCTRL
                          ▼
                  ┌───────────────┐
                  │ Source-       │
                  │ Degenerated   │
                  │ Current-      │
                  │ Starved VCRO  │
                  └───────┬───────┘
                          │
                          ▼
                    High-Speed CLK
                          │
                          ▼
                    Feedback Divider
                          │
                          └──────────────► PFD
Circuit-level contribution
- Dead-zone-free PFD using balanced latch paths.
- Optimized reset timing for small phase differences.
- Buffered UP/DOWN outputs.
- Matched charge-pump implementation.
- Passive loop-filter integration.
- Source-degenerated current-starved VCRO.
- Feedback-divider based closed-loop frequency control.
- Transistor-level verification in Cadence Virtuoso / Spectre.
Reported simulation results
Parameter	Reported Result
Technology	GPDK090
Frequency target	2.5–3.8 GHz
Closed-loop frequency	~2.506 GHz
Frequency ripple	4.013 MHz
Normalized ripple	0.160%
Output duty cycle	49.8%
RMS jitter	70.98 fs
Peak-to-peak jitter	1.588 ps


These project details and reported measurements are taken from the supplied CV. fileciteturn0file0L25-L36
🔷 High-Performance PFDs & VCOs for PLL Applications
Cooch Behar Government Engineering College
July 2023 — June 2024 · 90 nm CMOS · Cadence Virtuoso
- Designed a 5-stage Voltage-Controlled Ring Oscillator (VCRO).
- Reported tuning range: 1.25 MHz–3 GHz.
- Reported PFD phase noise: −143.71 dBc/Hz @ 1 MHz offset.
- Reported lock-in time: ~31 ns.
- Investigated PFD reset-path optimization and dead-zone elimination.
- Performed transistor-level simulation and power-performance analysis.
fileciteturn0file0L37-L45
🔷 Basic Analog IC Design — Research Internship
National Institute of Technology Sikkim
July 2023 — August 2023
Designed and simulated fundamental analog CMOS building blocks using GPDK090 + Cadence Virtuoso.
Analog Building Blocks
        │
        ├── Common-Source Amplifier
        ├── Common-Gate Amplifier
        ├── Current Mirrors
        └── Analog CMOS Circuits
                    │
                    ▼
             DC / AC / Tran
                    │
                    ▼
          Gain / Bandwidth /
          Operating-Point Analysis
fileciteturn0file0L17-L24
🔷 IC Design: RTL → GDSII
Defence Institute of Advanced Technology (DIAT), DRDO
November 2025
RTL
 │
 ▼
VCS / VERDI
 │
 ▼
Logic Synthesis
 │
 ▼
Design Compiler
 │
 ▼
Floorplan → Power Grid → Placement
 │
 ▼
CTS → Routing
 │
 ▼
PrimeTime STA
 │
 ▼
GDSII
Tools: Synopsys VCS, VERDI/NOVAS, Design Compiler, ICC2, PrimeTime
fileciteturn0file0L53-L62
03 — EDA / SOFTWARE STACK
🧪 Analog IC & SPICE
<p align="center">
<img src="https://img.shields.io/badge/Cadence%20Virtuoso-E31837?style=for-the-badge&logo=cadence&logoColor=white" alt="Cadence Virtuoso"/>
<img src="https://img.shields.io/badge/Cadence%20Spectre-9B1C31?style=for-the-badge&logo=cadence&logoColor=white" alt="Cadence Spectre"/>
<img src="https://img.shields.io/badge/LTspice-B71C1C?style=for-the-badge&logo=analogdevices&logoColor=white" alt="LTspice"/>
<img src="https://img.shields.io/badge/PSpice-C41E3A?style=for-the-badge&logo=cadence&logoColor=white" alt="PSpice"/>
</p>

⚙️ Synopsys
<p align="center">
<img src="https://img.shields.io/badge/VCS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Synopsys VCS"/>
<img src="https://img.shields.io/badge/VERDI%20%2F%20NOVAS-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="VERDI NOVAS"/>
<img src="https://img.shields.io/badge/Design%20Compiler-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="Design Compiler"/>
<img src="https://img.shields.io/badge/ICC2-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="ICC2"/>
<img src="https://img.shields.io/badge/PrimeTime-111111?style=for-the-badge&logo=synopsys&logoColor=white" alt="PrimeTime"/>
</p>

🧰 Additional Tools
<p align="center">
<img src="https://img.shields.io/badge/Altium%20Designer-A5915F?style=for-the-badge&logo=altiumdesigner&logoColor=white" alt="Altium Designer"/>
<img src="https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white" alt="KiCad"/>
<img src="https://img.shields.io/badge/KLayout-333333?style=for-the-badge" alt="KLayout"/>
<img src="https://img.shields.io/badge/Xilinx%20Vivado-E01F27?style=for-the-badge&logo=xilinx&logoColor=white" alt="Xilinx Vivado"/>
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=for-the-badge&logo=mathworks&logoColor=white" alt="MATLAB"/>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
</p>

The software list follows the supplied CV; the portfolio additionally highlights Cadence Virtuoso, PSpice, LTSpice and Xilinx Vivado. fileciteturn0file0L63-L70 citeturn0view0
Important: GitHub's Markdown cannot guarantee that every proprietary EDA vendor has a public, officially distributable icon. Where an official brand icon is not available through the badge provider, the README uses the product name rather than an unofficial logo.

04 — TECHNOLOGY NODES
┌────────────┬───────────────┬──────────────────────────────┐
│ Node       │ Technology    │ Primary Context              │
├────────────┼───────────────┼──────────────────────────────┤
│ 45 nm      │ GPDK45        │ VLSI / CMOS                  │
│ 90 nm      │ GPDK090       │ Analog IC / PLL / VCO / PFD │
│ 180 nm     │ GPDK180       │ CMOS                         │
│ 130 nm     │ TSMC 130 nm   │ CMOS                         │
│ 130 nm     │ SkyWater 130  │ Open-source CMOS             │
└────────────┴───────────────┴──────────────────────────────┘
05 — LAYOUT & SIGNOFF MINDSET
                 TRANSISTOR-LEVEL SCHEMATIC
                           │
                           ▼
                    Device Sizing
                           │
                           ▼
                  Bias / Matching
                           │
                           ▼
                     CUSTOM LAYOUT
                           │
            ┌──────────────┼──────────────┐
            ▼              ▼              ▼
       Symmetry       Common-Centroid   Guard Rings
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
                POST-LAYOUT SIMULATION
Core layout skills: Custom Analog Layout · Device Matching · DRC · ERC · LVS · PEX · Post-Layout Simulation
fileciteturn0file0L63-L70
06 — EDUCATION
Degree	Institute	Period	Result
M.Tech — Electronics Engineering	Defence Institute of Advanced Technology (DU), DRDO	Jul 2024 – Jun 2026	CGPA 6.62
B.Tech — Electronics & Communication Engineering	Cooch Behar Government Engineering College	Aug 2020 – Jul 2024	CGPA 8.23
XII — Science (PCMB)	Malda Zilla School	Apr 2018 – Mar 2020	80%


M.Tech specialization: VLSI & Embedded Systems
fileciteturn0file0L9-L15
07 — DESIGN PATENT
Next-Generation AI Device for Cloud-Integrated Smart Data Intelligence
Design No.   : 496442-001
Journal No.  : 23/2026
Journal Date : 05/06/2026
Status       : Design Accepted and Published
fileciteturn0file0L71-L73
08 — CERTIFICATIONS
Certification / Training	Organization	Date
IC Design: RTL to GDSII Implementation	DIAT	Nov 2025
Advanced Entrepreneurship-Cum-Skill Development Programme	NIT Sikkim	Mar 2024
Basic Analog IC Design Using Cadence Virtuoso	NIT Sikkim	Aug 2023
Artificial Intelligence	Remarkskill & IIT Kharagpur	Jan 2023
Coder's Python	HOMEFLIC WeGrow	Jun 2021


fileciteturn0file0L74-L79
09 — RESEARCH / COURSEWORK
Relevant Coursework
Analog & Mixed Mode Signal VLSI Design · CAD for VLSI Circuits · RFIC Design · EMI/EMC Design · Digital IC Design · Digital System Design using FPGA
fileciteturn0file0L80-L82
Research Direction
Analog IC Design
       │
       ├── Low-Noise Circuits
       ├── High-Speed Circuits
       ├── PLL / VCO / PFD
       ├── Frequency Synthesis
       ├── Transistor-Level CMOS
       ├── Custom Analog Layout
       └── Physical Verification
10 — GITHUB ANALYTICS
Replace YOUR_GITHUB_USERNAME with your actual GitHub username.
I have intentionally not guessed it because neither the supplied CV nor portfolio identifies it.

<p align="center">
<img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" height="175" alt="GitHub statistics"/>
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" height="175" alt="Top languages"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" alt="GitHub streak"/>
</p>

11 — CONNECT
<div align="center">

Open to Analog IC Design • VLSI • Semiconductor Research • Circuit Design
<a href="https://soumyajitmandal.onrender.com/">
<img src="https://img.shields.io/badge/🌐%20PORTFOLIO-Visit-00E5FF?style=for-the-badge" alt="Portfolio"/>
</a>
<a href="https://linkedin.com/in/soumyajitmandal001/">
<img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:contact.isoumyajitmandal@gmail.com">
<img src="https://img.shields.io/badge/Gmail-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
</a>




DESIGN  →  SIMULATE  →  LAYOUT  →  VERIFY  →  OPTIMIZE
<sub>© Soumyajit Mandal</sub>
</div>
