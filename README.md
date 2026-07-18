# Hi, I'm Gautam Suresh 👋

**Electronics Engineering student -** Specialization in **VLSI Design & Technology** 

I build things at the intersection of hardware and software — from RTL all the way to tape-out, and from backend APIs to AI-powered full-stack apps.

<div align="center">

# Gautam Suresh
### VLSI Design Engineer · FPGA Developer · Verification Engineer

**B.E. Electronics Engineering (VLSI Design & Technology)**  
Chennai, India

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gautam--suresh-0077B5?style=flat&logo=linkedin)](https://www.linkedin.com/in/gautam-suresh-89b637290/)
[![GitHub](https://img.shields.io/badge/GitHub-vsgautam22-181717?style=flat&logo=github)](https://github.com/vsgautam22)
[![Email](https://img.shields.io/badge/Email-vsgautam22@gmail.com-D14836?style=flat&logo=gmail)](mailto:vsgautam22@gmail.com)

</div>

---

## About

I design hardware from RTL to silicon — FPGA-based systems, ASIC physical design flows, and Python-driven verification environments. My work spans the full digital design stack: writing synthesizable HDL, running formal verification, taping out on open-source PDKs, and building coverage-driven testbenches for processor cores.

Currently building hardware + software ideas ahead, targeting VLSI/FPGA/verification roles.

---

## VLSI & Hardware Experience

**Digital Design**
- RTL design in Verilog and VHDL — combinational, sequential, pipelined architectures
- FPGA implementation on Xilinx Spartan-6 (ISE 14.7), Spartan-7, and Zynq (Vivado 2023.1)
- Constraint-driven synthesis and place-and-route; timing closure; UCF/XDC pin mapping
- ASIC physical design: synthesis (Yosys), formal verification (SymbiYosys / Z3), OpenLane GDS tape-out on SKY130A PDK
- Finite state machine design, pipelined datapath architecture, hazard detection and forwarding

**Verification**
- Functional simulation with iverilog, ISim, and ModelSim
- Coverage-driven testbench development using **cocotb** (Python-based) with constrained-random stimulus generation
- Formal property checking with SymbiYosys; waveform analysis in GTKWave

**FPGA Peripheral Integration**
- UART, SPI, I2C protocol implementation in HDL
- LCD interfacing (HD44780 parallel), ADC integration (MCP3208 SPI), relay/GPIO control
- BLE (HC-05) and Wi-Fi (ESP8266) module integration with FPGA via UART
- Red Pitaya SDRLab 122-16 platform (digital lock-in amplifier implementation)
- Advantech PCIE-1761H relay module control via Python

---

## Software & Development Experience

**Languages**: Python · C++ · JavaScript · SQL  
**Full-Stack**: React · Node.js · Express · PostgreSQL · REST APIs  
**AI/ML**: PyTorch 2.6 (CUDA 12.4) · HuggingFace · OpenCV · scikit-learn · NumPy · SciPy  
**RAG / LLM Pipelines**: pgvector · Mistral 7B · Ollama · LangChain patterns  
**DevOps / Tools**: Git · GitHub CLI · Docker · Postman · WSL2 Ubuntu 24.04  
**IDEs**: VS Code · Cursor · Windsurf · Keil µVision5 · Vivado · ISE

---

## Projects

### VLSI / FPGA / Hardware

| Project | Description | Stack |
|---------|-------------|-------|
| [crc-engine](https://github.com/vsgautam22/crc-engine) | Parameterizable CRC engine — 19/19 simulation tests passing, formal verification with SymbiYosys/Z3, Yosys synthesis (596 cells), OpenLane GDS tape-out on SKY130A with 0 DRC violations | Verilog · SymbiYosys · OpenLane · SKY130A |
| [riscv-core](https://github.com/vsgautam22/riscv-core) | 5-stage pipelined RV32I processor — full hazard detection, data forwarding, 8 RTL modules, iverilog verified | Verilog |
| [rv32i-cocotb-verification](https://github.com/vsgautam22/rv32i-cocotb-verification) | Coverage-driven verification testbench for RV32I pipeline — constrained-random instruction generator, ALU/branch/load-store/illegal instruction test suites, JSON + HTML coverage reports | cocotb · iverilog · Python |
| [fpga-smart-home-automation](https://github.com/vsgautam22/fpga-smart-home-automation) | Real-time smart home automation on Spartan-6 — LM35/LDR sensors, relay switching, 16×2 LCD, BLE mobile control, Thingspeak cloud integration | VHDL · ISE 14.7 · IoT |
| [fpga-satellite-downlink-compressor](https://github.com/vsgautam22/fpga-satellite-downlink-compressor) | Hardware RLE compressor for satellite telemetry — pipelined single-cycle architecture, QoS meter (ORG/CMP/LAT), LCD + UART output, ~2.5:1 compression ratio | Verilog · ISE 14.7 |

### Software / Full-Stack / AI

| Project | Description | Stack |
|---------|-------------|-------|
| [StackCheck-Pro](https://github.com/vsgautam22/StackCheck-Pro) | AI-integrated developer environment health checker — scans installed tools, versions, and configs; Claude API for intelligent diagnostics | React · Node.js · Express · PostgreSQL · Anthropic API |
| [arxiv-alpha](https://github.com/vsgautam22/arxiv-alpha) | RAG pipeline for ArXiv paper search and Q&A — vector similarity search, LLM-powered responses | pgvector · Mistral 7B · Python |
| [ooo-pipeline-engine](https://github.com/vsgautam22/ooo-pipeline-engine) | Kronos-32 — Tomasulo out-of-order pipeline engine with register renaming, reservation stations, and ROB | Verilog |

---

## Tools & Technologies

```
HDL         : Verilog  VHDL  SystemVerilog
EDA         : Xilinx Vivado 2023.1  ISE 14.7  AMD Vitis 2025.2
              Yosys  OpenLane  SymbiYosys  KiCad  FOSSEE eSim
Simulation  : iverilog  ModelSim  ISim  GTKWave
Verification: cocotb 1.9.2  SymbiYosys / Z3  Formal methods
FPGA Boards : Xilinx Spartan-6 (EDGE)  Red Pitaya SDRLab 122-16
AI/ML       : PyTorch 2.6+cu124  HuggingFace  OpenCV  spaCy
Dev         : Python 3.13  C++  JavaScript  Git  Docker  WSL2
```

---

## Education

**B.E. Electronics Engineering (VLSI Design & Technology)**  
Chennai Institute of Technology (Autonomous) · Anna University  
2023 – 2027 · Chennai, India

---

## Contact

- **LinkedIn**: [linkedin.com/in/gautam-suresh-89b637290](https://www.linkedin.com/in/gautam-suresh-89b637290/)
- **GitHub**: [github.com/vsgautam22](https://github.com/vsgautam22)
- **Email**: vsgautam22@gmail.com

---

**Chennai, India · Open to internships, opportunities and collaborations in VLSI, FPGA, AI Domain, and Embedded Systems**
