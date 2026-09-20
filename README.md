<table>
  <tr>
    <td valign="top">
<pre>
                               #[[[[  [                          
                           #[[[[[##[[[[[#[                       
                        @###(##@[[[###([##[[                     
                      @@@##@####[##[#[##[##([[(                  
                     #@@######[((>>>~[@#[###[[##[                
                   @@@@@@#>.           .[@#[####[(               
                  #@@@@#[>~              >###[###[[              
                ##[[#@@#[>.              ~@#####[[(              
                ######@@[+.               +#####[[##[            
               @#####@#[[(((>+.           .#@@####[[[            
              @@@@@@#@@#[[((([[>~ ~>[(>++~~[@@@@@@##[#           
              @@@@@@@@#(+((>~ ~>   .~>>++~+[@@#####[##           
              @@@@#@@@#>.     ~~          .>@@@#@@@#@            
               @@@@@@@#(+.    .~           >#@@@@###             
                @@@@@@#(>.   ~(#(~(       .[[######@             
                @@@@@@@#(+.>([[( [(.      +[@@@##@@              
                @@@@@@@@#(([(>+   .>((  .>#@@@@@@@               
                 @@@@@@@@#[+~~(((+.  ..>[##@@@@@                 
                  @@@@@@@@#[~....    .[###@@@@@                  
                    @@@#[#@@##[((>>+(##>.@@@@@                   
                       +([[#@@@@@@##(~   (#@                     
                   @@@@+>[[[[[##[(+.     [#@                     
              @@@@@@@@#~ ~((((>+.       (######                  
        @#@@#@@@@@@@@@(.   .+>~        ([#########               
      ##@#@#@#@#@@@@@[~   >[>+        [[[[[[#########            
     ##########@#@@@[~  +(@#[#[      [[[[[[[[###########         
    ##########@@@@@#~    .#[#       [[([[[#################      
    ##########@#@@@[      [[[      [[[[[[[[[######[#[[#[##[[[#   
   @@#########@@@@#+     +#[(     ([[[[[[[[[[##[#[[[[[[[[[[####  
   @@#@#######@#@@#     +##((    ([[([[[[[[#[[#[[[[[[[[[[[#####  
   @@#@########@@#[    ~###[(   +[[[[[[[[[#[[[[[[[[[[[[[[###@@#  
</pre>
    </td>
    <td valign="top">
<pre>
soumyajit@mandal
-------------------
Role:........ Analog & Mixed-Signal IC Design Engineer
Location:.... Malda, West Bengal, India
Institution:. Defence Institute of Advanced Technology, DRDO
Focus:....... Transistor-level CMOS, PLL, Physical Design
EDA Tools:... Cadence Virtuoso, Synopsys, Altium, KiCad
Nodes:....... GPDK45, GPDK090, TSMC130, SkyWater130

Languages.Scripting:. Python, MATLAB
Languages.Hardware:.. Verilog, VHDL, SystemVerilog
Languages.Real:...... English, Bengali, Hindi

- Contact -
Email.Personal:...... contact.isoumyajitmandal@gmail.com
LinkedIn:............ soumyajitmandal001
Portfolio:........... soumyajitmandal.onrender.com
</pre>
    </td>
  </tr>
</table>

<br>

## 🔬 About
I work at the transistor level — designing, simulating, and debugging analog and mixed-signal CMOS building blocks in Cadence Virtuoso, with a focus on PLL, VCO, and PFD architectures for high-speed clock generation. My work spans device sizing, biasing, layout matching, connectivity integrity, and parasitic-aware post-layout analysis, evaluated against gain, bandwidth, phase noise, and jitter targets across process nodes from GPDK045 down to TSMC130.

I'm currently pursuing my M.Tech in Electronics Engineering (VLSI & Embedded Systems) at the Defence Institute of Advanced Technology (DU), DRDO, building on a B.Tech in Electronics & Communication Engineering. Alongside circuit-level analog design, I've also run a full RTL-to-GDSII digital physical-design flow — synthesis, floorplanning, CTS, routing, and signoff STA — end to end.

<br>

## 🎯 Engineering Focus

<table>
<tr>
<td width="50%" valign="top">
• Analog & Mixed-Signal IC Design<br>
• ASIC Design Fundamentals<br>
• Transistor-Level CMOS Design<br>
• PLL / VCO / PFD Architectures
</td>
<td width="50%" valign="top">
• Custom Analog Layout & Physical Verification<br>
• Frequency Synthesizers & Clocking Circuits<br>
• PCB & Schematic Design<br>
• Digital Physical Design (RTL-to-GDSII)
</td>
</tr>
</table>

<br>

## 🧰 Technical Arsenal
**IC Design & EDA Suite:** Cadence Virtuoso, Synopsys (Design Compiler, ICC2, VCS, PrimeTime, VERDI/NOVAS)  
**PCB, Schematic & Layout:** Altium Designer, KiCad, LTSpice  
**FPGA, HDL & Scripting:** Xilinx Vivado, Verilog, VHDL, Python, MATLAB  
**Process Technology Nodes:** GPDK45, GPDK090, GPDK180, TSMC130, SkyWater130  
**Layout & Physical Verification:** Custom Analog Layout · Device Matching · DRC · ERC · LVS · PEX · Post-Layout Simulation  

<br>

## 🚀 Featured Projects
*Full write-ups and figures for each project live on my portfolio.*

**1. Enhanced-Stability High-Frequency PLL Architecture**  
*Cadence Virtuoso/Spectre | GPDK090 | DIAT (DU), DRDO · Aug 2025 – May 2026*  
Fine-resolution 2.5–3.8 GHz frequency synthesizer built around a dead-zone-free PFD with balanced latch paths and buffered UP/DOWN outputs, paired with a matched charge pump, passive loop filter, and a source-degenerated current-starved VCRO in a feedback-divided loop.
* **Result:** closed-loop lock around 2.506 GHz with 4.013 MHz ripple (0.160% normalized) and a 49.8% output duty cycle.
* **Result:** 70.98 fs RMS jitter, 1.588 ps peak-to-peak jitter — low timing uncertainty for multi-GHz clock generation.

**2. High-Performance PFDs & VCOs for PLL Applications**  
*Cadence Virtuoso | 90 nm CMOS | TSPC Logic | CGEC · Jul 2023 – Jun 2024*  
Transistor-level design of a 5-stage voltage-controlled ring oscillator and an optimized phase-frequency detector, investigating TSPC-based logic to remove dead-zone behavior and improve linearity.
* **Result:** 1.25 MHz – 3 GHz VCRO tuning range.
* **Result:** −143.71 dBc/Hz PFD phase noise at 1 MHz offset, ~31 ns lock-in time, dead-zone eliminated.

**3. IC Design: RTL-to-GDSII Implementation**  
*Synopsys (VCS, Design Compiler, ICC2, PrimeTime, VERDI/NOVAS) | DIAT (DU), DRDO · Nov 2025*  
End-to-end digital physical-design flow on a 4-bit full adder: RTL design and functional verification, logic synthesis to a timing/area-constrained gate-level netlist, then floorplanning, power-grid creation, placement, Clock Tree Synthesis, and routing in ICC2.
* **Result:** post-route static timing analysis in PrimeTime confirmed timing closure ahead of GDSII signoff.

**4. Vehicle Horn Blow Detection, Recording & Reporting System**  
*Python | IoT Sensors | SMTP | CGEC · Apr 2023 – May 2023*  
Server-based system that logs and tracks vehicle horn activity using frequency-analysis techniques on sensor data to distinguish horn signatures from background traffic noise, with an SMTP-based module that auto-generates and emails activity reports.
* **Result:** real-time architecture for automated data acquisition, processing, and reporting — no manual log review needed.

<br>

## 💼 Experience
**Research Intern — Basic Analog IC Design Using Cadence Virtuoso Platform**  
*National Institute of Technology, Sikkim · Jul 2023 – Aug 2023*
* Designed, simulated, and debugged analog CMOS building blocks (common-source/common-gate amplifiers, current mirrors) using GPDK090 in Cadence Virtuoso.
* Performed transistor-level performance evaluation — operating-point verification, gain, and bandwidth analysis — under varying bias conditions.
* Contributed across the analog IC design flow, from schematic design to performance optimization and technical documentation.

<br>

## 🎓 Education
| Degree | Institution | Duration |
| :--- | :--- | :--- |
| **M.Tech, Electronics Engineering (VLSI & Embedded Systems)** | Defence Institute of Advanced Technology (DU), DRDO | Jul 2024 – Jun 2026 |
| **B.Tech, Electronics & Communication Engineering** | Cooch Behar Government Engineering College | Aug 2020 – Jul 2024 |
| **Higher Secondary (Science — PCMB)** | Malda Zilla School | Apr 2018 – Mar 2020 |

*Relevant coursework: Analog & Mixed-Mode Signal VLSI Design · CAD for VLSI Circuits · RFIC Design and EMI/EMC Design · Digital IC Design · Digital System Design using FPGA*

<br>

## 🏆 Patent & Certifications
**Design Patent — Next-Generation AI Device for Cloud-Integrated Smart Data Intelligence**  
Design No. 496442-001 · Journal No. 23/2026 (05/06/2026) · Design accepted and published.

**Certifications**
* IC Design: RTL to GDSII Implementation — DIAT, DRDO (Nov 2025)
* Advanced Entrepreneurship-Cum-Skill Development Programme (E-SDP) — NIT Sikkim (Mar 2024)
* Basic Analog IC Design Using Cadence Virtuoso Platform — NIT Sikkim (Aug 2023)
* Artificial Intelligence — Remarkskill & IIT Kharagpur (Jan 2023)
* Coder's Python — Homeflic WeGrow (Jun 2021)

<br>

## ⚙️ Currently
* 🔭 Designing a CMOS PLL for 2.5–3.8 GHz frequency synthesis as part of my M.Tech thesis at DIAT, DRDO
* 🧩 Recently ran a full RTL-to-GDSII physical-design flow on the Synopsys toolchain (Nov 2025)
* 💬 Open to conversations on analog/mixed-signal IC design, PLL and clocking circuits, and physical design

<br>

## 📊 GitHub Activity

<!-- Replace YOUR_GITHUB_USERNAME below with your actual GitHub username in all three image URLs -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true" />
  <br>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true" />
</div>

<br>

## 📫 Let's Connect
Open to research collaborations, analog/mixed-signal design discussions, and opportunities in ASIC and physical design.

<div align="center">
<sub>Built at the transistor level. Verified in silicon-ready simulation.</sub>
</div>
