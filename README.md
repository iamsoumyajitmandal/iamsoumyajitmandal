<div align="center">

<img src="./assets/ascii-art.png" width="620" alt="Soumyajit Mandal ASCII portrait"/>

SOUMYAJIT MANDAL
Analog IC Design Engineer · VLSI · Custom Analog Layout
Transistor-Level CMOS · PLL / VCO / PFD · Circuit Simulation · Physical Verification

<a href="https://soumyajitmandal.onrender.com">
<img src="https://img.shields.io/badge/Portfolio-0B0F14?style=for-the-badge&logo=googlechrome&logoColor=00E5FF" alt="Portfolio">
</a>
<a href="https://linkedin.com/in/soumyajitmandal001/">
<img src="https://img.shields.io/badge/LinkedIn-0B0F14?style=for-the-badge&logo=linkedin&logoColor=0A66C2" alt="LinkedIn">
</a>
<a href="mailto:contact.isoumyajitmandal@gmail.com">
<img src="https://img.shields.io/badge/Email-0B0F14?style=for-the-badge&logo=gmail&logoColor=EA4335" alt="Email">
</a>

</div>

<table>
<tr>
<td width="58%" valign="top">

about.me
I am an Analog & Mixed-Signal IC Design engineer working at the transistor level, with a particular focus on CMOS PLLs, VCOs, PFDs, frequency synthesis and custom analog layout.
My design interest is not limited to the schematic. I am interested in carrying circuit intent through device sizing → simulation → layout → extraction → post-layout verification.
Current technical direction
- Analog / Mixed-Signal IC Design
- PLL, VCO & PFD architectures
- Transistor-level CMOS design
- Custom analog layout & device matching
- DRC / ERC / LVS / PEX
- Parasitic-aware post-layout simulation
- High-frequency clock generation
</td>

<td width="42%" valign="top">

┌─────────────────────────────┐
│      ENGINEERING STACK      │
├─────────────────────────────┤
│                             │
│  DOMAIN                     │
│  Analog IC / VLSI           │
│                             │
│  CIRCUITS                   │
│  PLL · VCO · PFD · CMOS     │
│                             │
│  PRIMARY EDA                │
│  Cadence Virtuoso / Spectre │
│                             │
│  LAYOUT                     │
│  Custom Analog / Matching   │
│                             │
│  SIGN-OFF                   │
│  DRC · ERC · LVS · PEX      │
│                             │
│  TECHNOLOGY                 │
│  45 / 90 / 130 / 180 nm    │
│                             │
└─────────────────────────────┘
</td>
</tr>
</table>

01 · Featured Work
High-Frequency PLL — Enhanced-Stability Architecture
DIAT, DRDO · M.Tech Project · GPDK090 · Cadence Virtuoso / Spectre
A transistor-level CMOS PLL for fine-resolution 2.5–3.8 GHz frequency synthesis, integrating a PFD, charge pump, passive loop filter, source-degenerated current-starved VCRO and feedback divider.
                 REFERENCE
                    │
                    ▼
              ┌───────────┐
              │    PFD    │
              └─────┬─────┘
                    │ UP / DN
                    ▼
              ┌───────────┐
              │   CP      │
              └─────┬─────┘
                    │
                    ▼
              ┌───────────┐
              │ LOOP      │
              │ FILTER    │
              └─────┬─────┘
                    │ VCTRL
                    ▼
              ┌───────────┐
              │ CURRENT-  │
              │ STARVED   │
              │ VCRO      │
              └─────┬─────┘
                    │
                    ▼
                 FOUT
                    │
                    ▼
              ┌───────────┐
              │ DIVIDER   │
              └─────┬─────┘
                    │
                    └──────────► PFD
Design work
- Dead-zone-free PFD with optimized reset timing
- Balanced latch paths and buffered UP/DOWN outputs
- Matched charge pump
- Passive loop filter
- Source-degenerated current-starved VCRO
- Closed-loop frequency and jitter analysis
Reported simulation results
Metric	Result
Technology	GPDK090
Target range	2.5–3.8 GHz
Locked frequency	~2.506 GHz
Frequency ripple	4.013 MHz
Normalized ripple	0.160%
Duty cycle	49.8%
RMS jitter	70.98 fs
Peak-to-peak jitter	1.588 ps


02 · Earlier IC Design Work
PFDs & VCOs for PLL Applications
CGEC · B.Tech Project · 90 nm CMOS · Cadence Virtuoso
Designed and simulated a 5-stage VCRO and PFD architecture for PLL applications.
Parameter	Reported Result
VCRO tuning range	1.25 MHz – 3 GHz
PFD phase noise	−143.71 dBc/Hz @ 1 MHz
Reported lock-in time	~31 ns


Focus: PFD reset-path optimization, dead-zone elimination, transistor-level simulation, stability and power-performance analysis.
Analog IC Design Internship
NIT Sikkim · GPDK090 · Cadence Virtuoso
Worked on analog CMOS building blocks with operating-point, gain, bandwidth and bias-condition analysis.
03 · Design Flow
     SPECIFICATION
           │
           ▼
      ARCHITECTURE
           │
           ▼
   TRANSISTOR SIZING
           │
           ▼
      BIAS + DC OP
           │
           ▼
   ┌─────────────────┐
   │ DC / AC / TRAN  │
   │ NOISE / PVT     │
   └────────┬────────┘
            │
            ▼
      CUSTOM LAYOUT
            │
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
04 · EDA & Engineering Tools
Analog / SPICE
<p>
<img src="https://img.shields.io/badge/Cadence%20Virtuoso-E31837?style=flat-square&logo=cadence&logoColor=white" alt="Cadence Virtuoso">
<img src="https://img.shields.io/badge/Cadence%20Spectre-8B1A2B?style=flat-square&logo=cadence&logoColor=white" alt="Cadence Spectre">
<img src="https://img.shields.io/badge/LTspice-B71C1C?style=flat-square&logo=analogdevices&logoColor=white" alt="LTspice">
<img src="https://img.shields.io/badge/PSpice-C41E3A?style=flat-square&logo=cadence&logoColor=white" alt="PSpice">
</p>

Synopsys
<p>
<img src="https://img.shields.io/badge/VCS-111111?style=flat-square&logo=synopsys&logoColor=white" alt="VCS">
<img src="https://img.shields.io/badge/VERDI%20%2F%20NOVAS-111111?style=flat-square&logo=synopsys&logoColor=white" alt="VERDI">
<img src="https://img.shields.io/badge/Design%20Compiler-111111?style=flat-square&logo=synopsys&logoColor=white" alt="Design Compiler">
<img src="https://img.shields.io/badge/ICC2-111111?style=flat-square&logo=synopsys&logoColor=white" alt="ICC2">
<img src="https://img.shields.io/badge/PrimeTime-111111?style=flat-square&logo=synopsys&logoColor=white" alt="PrimeTime">
</p>

Other
<p>
<img src="https://img.shields.io/badge/Altium%20Designer-A5915F?style=flat-square&logo=altiumdesigner&logoColor=white" alt="Altium Designer">
<img src="https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white" alt="KiCad">
<img src="https://img.shields.io/badge/KLayout-333333?style=flat-square" alt="KLayout">
<img src="https://img.shields.io/badge/Vivado-E01F27?style=flat-square&logo=xilinx&logoColor=white" alt="Xilinx Vivado">
<img src="https://img.shields.io/badge/MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white" alt="MATLAB">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
</p>

05 · Technology & Verification
Technology nodes
GPDK45 · GPDK090 · GPDK180 · TSMC 130 nm · SkyWater 130
Layout / verification
Custom Analog Layout · Device Matching · Symmetry · Common-Centroid · DRC · ERC · LVS · PEX
Simulation
DC · AC · Transient · Noise · Operating Point · Post-Layout
06 · Education
Degree	Institute	Period	Result
M.Tech — Electronics Engineering	Defence Institute of Advanced Technology (DU), DRDO	2024–2026	CGPA 6.62
B.Tech — Electronics & Communication Engineering	Cooch Behar Government Engineering College	2020–2024	CGPA 8.23
XII — Science (PCMB)	Malda Zilla School	2018–2020	80%


M.Tech specialization: VLSI & Embedded Systems
07 · RTL → GDSII Exposure
DIAT · November 2025
Worked through the implementation flow using:
VCS → VERDI/NOVAS → Design Compiler → ICC2 → PrimeTime → GDSII
This complements my primary analog focus with an understanding of the broader semiconductor implementation flow.
08 · Patent & Certifications
Design Patent
Next-Generation AI Device for Cloud-Integrated Smart Data Intelligence
Design No. 496442-001 · Journal No. 23/2026 · 05/06/2026
Status: Design Accepted and Published
Certifications
- IC Design: RTL to GDSII Implementation — DIAT, 2025
- Advanced Entrepreneurship-Cum-Skill Development Programme — NIT Sikkim, 2024
- Basic Analog IC Design Using Cadence Virtuoso Platform — NIT Sikkim, 2023
- Artificial Intelligence — Remarkskill × IIT Kharagpur, 2023
- Coder's Python — HOMEFLIC WeGrow, 2021
09 · Research Interests
Analog IC Design
├── CMOS Analog Circuits
├── PLL / VCO / PFD
├── Frequency Synthesizers
├── High-Speed Clocking
├── Low-Noise Circuits
├── Transistor-Level Design
├── Custom Analog Layout
└── Physical Verification
10 · Currently Building
A stronger public portfolio of reproducible IC-design work.
The goal is to turn simulation experience into clearly documented engineering repositories containing:
- circuit architecture
- design equations
- transistor sizing
- simulation methodology
- results
- layout methodology
- verification results
- post-layout comparison
11 · GitHub
<div align="center">

<a href="https://github.com/iamsoumyajitmandal">
<img src="https://github-readme-stats.vercel.app/api?username=iamsoumyajitmandal&show_icons=true&hide_border=true&theme=transparent&title_color=00E5FF&text_color=8B949E&icon_color=00E5FF&rank_icon=github" height="165" alt="GitHub statistics">
</a>

<a href="https://github.com/iamsoumyajitmandal">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=iamsoumyajitmandal&layout=compact&hide_border=true&theme=transparent&title_color=00E5FF&text_color=8B949E" height="165" alt="Top languages">
</a>

</div>

<div align="center">

DESIGN → SIMULATE → LAYOUT → VERIFY

<a href="https://soumyajitmandal.onrender.com">
<img src="https://img.shields.io/badge/🌐%20PORTFOLIO-00E5FF?style=for-the-badge&logoColor=black" alt="Portfolio">
</a>
<a href="https://linkedin.com/in/soumyajitmandal001/">
<img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="mailto:contact.isoumyajitmandal@gmail.com">
<img src="https://img.shields.io/badge/CONTACT-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>




<sub>Soumyajit Mandal · Analog IC Design · VLSI</sub>
</div>
