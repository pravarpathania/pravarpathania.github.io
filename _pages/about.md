---
permalink: /
title: "Pravar Pathania"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I am an undergraduate researcher at IIIT-Delhi pursuing a B.Tech. in Electronics and VLSI, with a strong focus on computer architecture, memory systems, and hardware-software co-design. My work spans cache replacement policies, intermittent computing, CNN acceleration, and RISC-V system design. I'm particularly interested in developing energy-efficient architectures and exploring ML-guided optimizations for microarchitectural policies.

Currently, I am a Research Intern at IIT Bombay under [Prof. Biswabandan Panda](https://www.cse.iitb.ac.in/~biswa/), working on cache replacement policies for DDR5 memory systems using the ChampSim simulation infrastructure. I also work as a Research Assistant at IIIT-Delhi under Prof. Sujay Deb and Prof. Anuj Grover, where I've developed innovative checkpoint optimization techniques for intermittent computing systems. My work on EASE won **2nd Place (Undergraduate Category)** at the **IEEE/ACM MICRO 2025 Student Research Competition**.

---

## Research Interests

- **Computer Architecture**: Memory systems, prefetching, and data-centric microarchitecture
- **Hardware-Software Co-Design**: RISC-V systems, SoC design, and FPGA prototyping
- **Edge Computing**: CNN accelerators and energy-efficient inference
- **Intermittent Computing**: Checkpoint optimization and energy-harvesting systems
- **ML-Guided Optimization**: Emerging techniques for microarchitectural policy optimization

---

## Publications

### **[CoDe-CS: A CNN Accelerator with Co-Designed Compute and Storage for Edge Efficiency](https://ieeexplore.ieee.org/document/11235460)**
**IEEE International System-on-Chip Conference (SoCC) 2025**  
*Pravar Pathania, Namit Gupta, Keshav Goel, Vishal Kumar, Sujay Deb*

- Designed scalable CNN accelerator with parameterized PE arrays (4×4 to 16×16)
- Achieved **9.6 GMAC/s peak throughput** and **23.52 GMAC/s/W power efficiency** on Xilinx Zedboard
- Demonstrated **12× speedup** over Cortex-A9 for MobileNetV1 inference
- Delivered exponential throughput scaling with minimal BRAM increase

---

## Research Experience

### **Cache Replacement Policy Research**
*IIT Bombay | Jan 2026 – | Guide: Prof. Biswabandan Panda*

Investigating cache replacement policies for DDR5 memory systems:
- Developing and evaluating replacement policies using the ChampSim simulation infrastructure
- Analyzing memory access patterns to guide data-driven cache replacement decisions across memory-intensive workloads on DDR5 platforms

### **Gemmini-Based DNN Training Framework**
*University of Sydney | June 2025 – Sept 2025 | Guide: Prof. Sri Parameswaran*

Built DNN training framework in Chipyard with approximate computing support:
- Contributed Chisel/Chipyard changes for dynamic multiplier switching via custom RISC-V instructions
- Evaluated reduced-precision support (FP16/BF16) on Gemmini via ONNX Runtime
- Validated approximate multipliers in simulation with ImageNet models

### **Checkpoint Optimization for Intermittent Computing (EASE)**
*IIIT-Delhi | June 2025 – Dec 2025 | Guide: Prof. Sujay Deb and Prof. Anuj Grover*

Developed EASE, an energy-aware checkpoint optimization system for intermittent computing:
- Implemented adaptive checkpointing with dirty-line tracking in ICEmu simulator
- Extended cache controller with hazard-interception logic and sentinel-based energy monitoring
- Achieved **78% NVM-write reduction** and **22.5% execution-time improvement**
- Won 2nd place at IEEE/ACM MICRO 2025 Student Research Competition

### **CNN Accelerator Design (CoDe-CS)**
*IIIT-Delhi | Aug 2023 – May 2025 | Guide: Prof. Sujay Deb*

Designed and evaluated a co-optimized CNN accelerator for edge inference:
- Built parameterized PE arrays (4×4 to 16×16) with co-designed compute and storage
- Achieved **9.6 GMAC/s peak throughput** and **23.52 GMAC/s/W power efficiency** on Xilinx Zedboard
- Published at IEEE SoCC 2025

## Education

**Indraprastha Institute of Information Technology, Delhi**  
*B.Tech. in Electronics and VLSI* | Nov 2022 – May 2026  


---

## Technical Skills

- **Simulation**: gem5, ChampSim, Chipyard, Spike RISC-V ISA Simulator, ICEmu
- **HDL & RTL**: Verilog/SystemVerilog, Chisel, FPGA Prototyping
- **EDA Tools**: Xilinx Vivado, Vitis HLS, Cadence Virtuoso, Eldo
- **Programming**: C/C++, Python, Shell Scripting
- **ML Frameworks**: PyTorch, ONNX Runtime

---

## Awards & Honors

- **2nd Prize, Student Research Competition (Undergraduate)** — IEEE/ACM MICRO 2025

---

## Academic Service

- **Artifact Evaluator**, IEEE/ACM HPCA 2026
