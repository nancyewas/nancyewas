<!-- ========= HEADER ========= -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A7EA4,100:6C3BD1&height=210&section=header&text=Hi%2C%20I'm%20Nancy&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=From%20C%20driver%20to%20logic%20gate%2C%20I%20own%20the%20whole%20stack&descSize=18&descAlignY=58" alt="Nancy header banner" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1100&color=0A7EA4&center=true&vCenter=true&width=700&height=45&lines=SoC+Integration+Engineer;RTL+Verification+Engineer;Hardware-Software+Co-Design;Digital+IC+Design;Reading+waveforms+so+you+don't+have+to" alt="Typing animation of my focus areas" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nancy--ewas-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nancy-ewas)
![RISC-V](https://img.shields.io/badge/RISC--V-SoC%20Integration-283272?style=for-the-badge&logo=riscv&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-RTL%20%26%20Verification-6C3BD1?style=for-the-badge)
![Location](https://img.shields.io/badge/Cairo-Egypt-E4002B?style=for-the-badge&logo=googlemaps&logoColor=white)
![Profile views](https://komarev.com/ghpvc/?username=nancyewas&style=for-the-badge&color=0A7EA4&label=PROFILE+VIEWS)

</div>

---

## 👩‍💻 About me

I'm a Communication and Information Engineering graduate (Capital University, formerly Helwan University, class of 2026) based in Cairo, Egypt. I work as an **SoC Integration Engineer** and **RTL Verification Engineer**, and I was **technical lead** of my graduation project, RISCyLUT, sponsored by Si-Vision.

**What I work on**

- 🔗 Hardware-software co-design
- ✅ RTL verification
- 🧩 Digital IC design and SoC integration

**Current focus:** SoC integration, and exploring the world of digital verification.

**Looking for:** full-time roles in RTL design, ASIC / digital IC design, SoC integration, or hardware accelerator architecture, ideally at a company building next-generation silicon for compute or AI.

> 💬 **Engineering philosophy:** I'd rather spend an extra hour reading a waveform than guess at a fix. Correctness, traceability, and clear documentation matter as much as a working design.

---

## 🚀 Featured project: RISCyLUT

**A custom LUT-based Deep Learning Accelerator (LUT-DLA) integrated into a RISC-V SoC (PULPissimo).** I was the **technical lead** and worked as **SoC Integration Engineer** and **RTL Verification Engineer**. The project covers the full stack, from architecture and RTL design to driver development and ASIC synthesis.

![Si-Vision sponsored](https://img.shields.io/badge/Sponsor-Si--Vision-0A7EA4?style=flat-square)
![Evaluation](https://img.shields.io/badge/Team%20evaluation-Excellent-2EA043?style=flat-square)
![Grade](https://img.shields.io/badge/Graduation%20project-96%2F100%20(A)-6C3BD1?style=flat-square)

```mermaid
flowchart LR
    subgraph SW["Software"]
        C["C code"] --> HAL["HAL-style C drivers"]
    end
    subgraph SOC["RISC-V SoC (PULPissimo)"]
        CORE["RISC-V core"] <--> BUS["AMBA interconnect<br/>APB / AHB / AXI"]
    end
    subgraph ACC["LUT-DLA"]
        CTRL["Control plane"]
        DATA["Data plane"]
    end
    HAL --> CORE
    BUS <--> CTRL
    BUS <--> DATA
```

<details>
<summary><b>🔬 What I worked on (click to expand)</b></summary>
<br/>

- Integrating the accelerator into the SoC with a suitable choice of interconnects (AHB / APB / AXI)
- Control/data-plane separation for the accelerator interface
- HAL-style C drivers, with hardware/software interaction verified through waveform-level debugging
- A verification environment for the design
- RTL through gate-level synthesis using industry-standard EDA flows

</details>

---

## 🛠️ Tech stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,py,java,bash,linux,git,github&theme=dark" alt="Languages and tools icons" />

</div>

| Area | What I use |
|---|---|
| 🧩 **RTL design** | Parameterized synthesizable Verilog / SystemVerilog, FSM design, memory-mapped register files, custom APB/AXI peripherals |
| ✅ **Verification** | Module-based and class-based testbenches, UVM concepts, assertions, waveform debug in QuestaSim |
| 🔌 **SoC design** | RISC-V SoC integration (PULPissimo / RI5CY), AMBA APB / AHB / AXI4, bus matrix and interconnect architecture |
| 🏭 **Physical design flow** | Pre-place-and-route synthesis, gate-level netlists and timing reports, SAED32 standard-cell library, constraints, Synopsys Design Compiler |
| 🧪 **DFT** | Scan-friendly RTL coding, testbench-driven design validation |
| 💻 **Embedded** | HAL-style C drivers, RISC-V cross-compilation toolchains |
| 📜 **Scripting & OS** | Bash, TCL, Makefile, Python, Linux / WSL, Git / GitHub |

---


## 📊 GitHub stats

<div align="center">

<img height="175" src="https://github-readme-stats.vercel.app/api?username=nancyewas&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub stats" />
<img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=nancyewas&layout=compact&theme=tokyonight&hide_border=true&border_radius=10" alt="Top languages" />

<img src="https://streak-stats.demolab.com/?user=nancyewas&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=nancyewas&theme=tokyo-night&hide_border=true&area=true" alt="Contribution activity graph" />

</div>

---

<div align="center">

### 🤝 Let's connect

[![LinkedIn](https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nancy-ewas)

*Open to full-time opportunities in digital design, verification, and SoC integration.*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6C3BD1,100:0A7EA4&height=110&section=footer" alt="footer wave" />

</div>

<!--
OTHER PROJECTS (hidden until you confirm they are yours; delete the comment markers to show them).
These came from the attached file, which is headed "Mohammed Hussein". No links were provided, so none are added.

### Other projects
- **RTL-to-GDS Implementation of a Low-Power Configurable Multi-Clock Digital System**: UART receiver commands drive register file read/write and ALU processing, with results sent to a UART transmitter through an asynchronous FIFO for clock-domain crossing. Stack: SystemVerilog, C, QuestaSim, Synopsys DC, Cadence SoC Encounter, Formality
- **Single-Cycle MIPS CPU**: from-scratch SystemVerilog implementation of a single-cycle MIPS processor.
- **SPI Slave with Single Port RAM**: synthesizable SPI slave with a self-checking testbench.
-->
