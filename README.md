<p align="center">
  <img src="https://img.shields.io/badge/SystemVerilog-6B2B44?style=for-the-badge&logo=systemverilog&logoColor=white" />
  <img src="https://img.shields.io/badge/Verilog-AA1745?style=for-the-badge&logo=verilog&logoColor=white" />
  <img src="https://img.shields.io/badge/UVM-FF6A21?style=for-the-badge&logo=uvm&logoColor=white" />
  <img src="https://img.shields.io/badge/SVA-5A47FF?style=for-the-badge&logo=sva&logoColor=white" />
  <img src="https://img.shields.io/badge/Makefiles-3B36E9?style=for-the-badge&logo=gnu&logoColor=white" />
</p>

<h1 align="center" style="color:#6B2B44;">🔎 UVM & SVA-Based 6-bit ALU Verification Project (with Reset Agent) 🔎</h1>

<p align="center">
  <b>Comprehensive UVM-class verification of a 6-bit SystemVerilog ALU, with formal SVA checks, a modular reset agent, and clear documentation.</b>
</p>

---

## 🎨 Overview

This repository demonstrates the design and in-depth verification of a configurable 6-bit ALU (Arithmetic Logic Unit) using:
- <span style="color:#6B2B44"><b>SystemVerilog</b></span> for RTL
- <span style="color:#FF6A21"><b>UVM</b></span> for a modular, reusable testbench
- <span style="color:#5A47FF"><b>SystemVerilog Assertions (SVA)</b></span> for property and formal verification
- <span style="color:#AA1745"><b>Dedicated Reset Agent</b></span> for robust reset scenario testing

Illustrations, block diagrams, and waveforms are provided for easy understanding.

---

## 📁 Repository Structure

```
.
├── rtl/             # ALU RTL design (SystemVerilog)
├── dv/              # UVM-based testbench & verification env
├── illustrations/   # Diagrams, block diagrams, docs, waveforms
```

- <span style="color:#6B2B44"><b>/rtl</b></span>: ALU main RTL sources
- <span style="color:#FF6A21"><b>/dv</b></span>: UVM testbench, reset agent, assertions, coverage
- <span style="color:#5A47FF"><b>/illustrations</b></span>: Block diagrams, waveforms, documentation

---

## ✨ Features

- <img src="https://img.shields.io/badge/6--bit%20ALU-6B2B44?style=flat-square" height="18"/> Configurable, arithmetic & logic operations
- <img src="https://img.shields.io/badge/UVM%20Testbench-FF6A21?style=flat-square" height="18"/> Modular, reusable, and class-based
- <img src="https://img.shields.io/badge/SVA%20Assertions-5A47FF?style=flat-square" height="18"/> Property checks for correctness
- <img src="https://img.shields.io/badge/Reset%20Agent-AA1745?style=flat-square" height="18"/> Dedicated, verifies all reset logic
- <img src="https://img.shields.io/badge/Constrained%20Random-ED254E?style=flat-square" height="18"/> Stimulus and functional coverage
- <img src="https://img.shields.io/badge/Illustrations-3B36E9?style=flat-square" height="18"/> Block diagrams & waveforms

---

## 🚀 Getting Started

1. **Clone the repository**
   ```sh
   git clone https://github.com/AbdelrahmanYassien11/6bit-ALU-UVM-SVA-Verification.git
   cd 6bit-ALU-UVM-SVA-Verification
   ```

2. **Explore the folders**
   - RTL: <span style="color:#6B2B44">`/rtl`</span>
   - UVM env & testbench: <span style="color:#FF6A21">`/dv`</span>
   - Diagrams/docs: <span style="color:#5A47FF">`/illustrations`</span>

3. **Run Simulations**
   - Supported on QuestaSim, ModelSim, VCS (Makefile provided)
   ```sh
   cd dv
   make run
   ```

---

## 📖 Documentation

- **ALU Features & Operations:** `/rtl` and `/illustrations`
- **Verification Plan & Test Strategy:** `/dv` and `/illustrations`
- **Reset Agent Details:** `/dv/agents/reset_agent/` (if present)

---

## 🤝 Contributors

Worked on this project alongside my friend & colleague  
<a href="https://github.com/YoussefNasser11/YoussefNasser11" style="color:#FF6A21;"><b>Youssef Nasser</b></a>  
Show him some love!

Future contributions, issues, and PRs are welcome. For significant changes, please open an issue to discuss them first.

---

## 📫 Contact

- <img src="https://img.shields.io/badge/GitHub-AbdelrahmanYassien11-6B2B44?style=flat-square&logo=github&logoColor=white" height="18"/> [AbdelrahmanYassien11](https://github.com/AbdelrahmanYassien11)
- <img src="https://img.shields.io/badge/LinkedIn-Abdelrahman%20Mohamad%20Yassien-AA1745?style=flat-square&logo=linkedin&logoColor=white" height="18"/> [LinkedIn](https://www.linkedin.com/in/abdelrahman-mohamad-yassien)

---

<p align="center" style="color:#ED254E; font-size:1.1em;">
  <b>🌟 Star this repo if you found it useful or inspiring!</b>
</p>