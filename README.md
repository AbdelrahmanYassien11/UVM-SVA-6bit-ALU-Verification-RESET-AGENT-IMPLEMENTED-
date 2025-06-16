# 6-bit ALU Verification with UVM & SVA (Reset Agent Included)

This project demonstrates the design and comprehensive verification of a 6-bit Arithmetic Logic Unit (ALU) using Universal Verification Methodology (UVM) and SystemVerilog Assertions (SVA). A dedicated reset agent is implemented for robust reset sequence verification.

## 📁 Repository Structure

- `/rtl` — ALU RTL design sources (SystemVerilog)
- `/dv` — UVM-based testbench and verification environment
- `/illustrations` — Diagrams and documentation assets

## ✨ Features

- 6-bit Configurable Arithmetic Logic Unit
- UVM Testbench: Modular and reusable verification environment
- SystemVerilog Assertions (SVA): Property-based and formal checks
- Dedicated Reset Agent: Isolates and tests reset logic and scenarios
- Constrained Random Stimulus & Functional Coverage
- Illustrations: Block diagrams and waveforms for easier understanding

## 🚀 Getting Started

1. Clone the repository
   ```bash
   git clone https://github.com/AbdelrahmanYassien11/6bit-ALU-UVM-SVA-Verification.git
   ```

2. Explore the folders
   - RTL design in `/rtl`
   - UVM testbench in `/dv`
   - Diagrams in `/illustrations`

3. Run Simulations
   - Use your preferred simulator (e.g., QuestaSim, ModelSim, VCS)
   - Example (using Makefile if provided):
     ```bash
     cd dv
     make run
     ```

## 📝 Documentation

- ALU Features & Operations: See `/rtl` and `/illustrations`
- Verification Plan & Test Strategy: See `/dv` and `/illustrations`
- Reset Agent Details: `/dv/agents/reset_agent/` (if present)

## 🤝 Contributions

Contributions, issues, and PRs are welcome! For major changes, please open an issue first to discuss what you would like to change.

## 📫 Contact

- GitHub: [AbdelrahmanYassien11](https://github.com/AbdelrahmanYassien11)
- LinkedIn: [Abdelrahman Mohamad Yassien](https://www.linkedin.com/in/abdelrahman-mohamad-yassien)
