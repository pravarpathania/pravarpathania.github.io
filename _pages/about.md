---
permalink: /
title: "Pravar Pathania"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

## About Me

I am an undergraduate researcher at IIIT-Delhi pursuing a B.Tech. in Electronics and VLSI, with a strong focus on computer architecture, memory systems, and hardware-software co-design. My work spans intermittent computing, CNN acceleration, and RISC-V system design. I'm particularly interested in developing energy-efficient architectures and exploring ML-guided optimizations for microarchitectural policies.

Currently, I work as a Research Assistant at IIIT-Delhi under Prof. Sujay Deb and Prof. Anuj Grover, where I've developed innovative checkpoint optimization techniques for intermittent computing systems. My work on EASE won **2nd Place (Undergraduate Category)** at the **IEEE/ACM MICRO 2025 Student Research Competition**.

---

## Research Interests

- **Computer Architecture**: Memory systems, prefetching, and data-centric microarchitecture
- **Hardware-Software Co-Design**: RISC-V systems, SoC design, and FPGA prototyping
- **Edge Computing**: CNN accelerators and energy-efficient inference
- **Intermittent Computing**: Checkpoint optimization and energy-harvesting systems
- **ML-Guided Optimization**: Emerging techniques for microarchitectural policy optimization

---

## Publications

<!-- ### **EASE: An Energy-Aware Skip and Execute Mechanism for Efficient Intermittent Computing**
**Submitted to IEEE/ACM Design Automation Conference (DAC) 2026**  
*Pravar Pathania, Namit Gupta, Keshav Goel, Anuj Grover, Sujay Deb*

- Developed an adaptive checkpointing policy integrating energy-awareness and dirty-line tracking
- Designed lightweight Exponential Moving Average (EMA) predictor for checkpoint cost estimation
- Achieved **78% NVM-write reduction** and **22.5% execution-time improvement** over NACHO
- Won **2nd Place (Undergraduate Category)** at IEEE/ACM MICRO 2025 Student Research Competition -->

### **[CoDe-CS: A CNN Accelerator with Co-Designed Compute and Storage for Edge Efficiency](https://ieeexplore.ieee.org/document/11235460)**
**IEEE International System-on-Chip Conference (SoCC) 2025**  
*Pravar Pathania, Namit Gupta, Keshav Goel, Vishal Kumar, Sujay Deb*

- Designed scalable CNN accelerator with parameterized PE arrays (4×4 to 16×16)
- Achieved **9.6 GMAC/s peak throughput** and **23.52 GMAC/s/W power efficiency** on Xilinx Zedboard
- Demonstrated **12× speedup** over Cortex-A9 for MobileNetV1 inference
- Delivered exponential throughput scaling with minimal BRAM increase

---

## Projects

### **Checkpoint Optimization for Intermittent Computing**
*Research Assistant, IIIT-Delhi | June 2025 – Present*  
*Guide: Prof. Sujay Deb and Prof. Anuj Grover*

Developed EASE, an energy-aware checkpoint optimization system for intermittent computing:
- Implemented adaptive checkpointing with dirty-line tracking in ICEmu simulator
- Extended cache controller with hazard-interception logic and sentinel-based energy monitoring
- Achieved **78% NVM-write reduction** and **22.5% execution-time improvement**
- Paper Submitted to DAC 2026 and won 2nd place at MICRO SRC'25


### **Gemmini-Based DNN Training Framework**
*Research Intern, University of Sydney | June 2025 – Sept 2025*  
*Guide: Prof. Sri Parameswaran*

Built DNN training framework in Chipyard with approximate computing support:
- Contributed Chisel/Chipyard changes for dynamic multiplier switching via custom RISC-V instructions
- Evaluated reduced-precision support (FP16/BF16) on Gemmini via ONNX Runtime
- Validated approximate multipliers in simulation with ImageNet models

<!-- ### **Dynamic QoS Policy for Network-on-Chip (NoC)**

Developed framework for dynamic QoS-based bandwidth allocation:
- Implemented 8×8 Mesh XY NoC in Gem5 with runtime QoS adaptation
- Extended router and memory controller modules using multifractal detrended fluctuation analysis
- Validated static QoS prioritization based on core-specific bandwidth demands -->

### **Custom RISC-V SoC Design**
*IIIT-Delhi | Dec 2023 – May 2024*  
*Guide: Prof. Sujay Deb*

Designed modular SoC using Ibex RISC-V core:
- Developed custom peripheral controllers in SystemVerilog
- Prototyped micro weather station on Basys-3 FPGA with sensor integration and wireless transmission

### **Representation Learning: Robustness, Distillation, and Self-Supervision**

Investigated Vision-Language Model robustness and compression:
- Tested CLIP-BLIP adversarial robustness (ε=8/255): 65% alignment reduction, 95% caption flips
- Designed ViT knowledge distillation achieving **83.7% accuracy** with **4.2× speedup**
- Developed self-supervised learning combining rotation prediction and masked autoencoding: **84.3% CIFAR-10 accuracy** (CKA=0.81)

### **Text-to-Image Synthesis using Conditional GANs**

Developed multi-latent Conditional GAN:
- Implemented hybrid training pipeline with hinge loss, gradient penalty, and contrastive loss
- Achieved Inception Score of 2.19 and FID of 184.26
- Built with PyTorch using Conditional BatchNorm and spectral normalization

### **GPU-Centric Characterization of GNNs**

Performed comprehensive GNN performance analysis:
- Conducted roofline analysis on RTX 4090 using NVIDIA Nsight Systems
- Identified aggregation (SpMM) as memory-bound and projection (GEMM) as compute-bound
- Demonstrated CPU-side sampling bottlenecks: high-degree seeds run **3.7×–5.2× slower**

<!-- ### **Design of AOI221 Complex Logic Gate**

VLSI design and optimization:
- Designed and tested AOI221 logic gate layouts for power and area optimization
- Analyzed complexity-performance trade-offs using Cadence Virtuoso and Eldo simulations

--- -->

## Education

**Indraprastha Institute of Information Technology, Delhi**  
*B.Tech. in Electronics and VLSI* | Nov 2022 – May 2026  


---

## Technical Skills

**Architecture & Simulation**: gem5, Chipyard, Spike RISC-V ISA Simulator, ICEmu Simulator  
**Hardware & Design**: SoC Architecture, RTL Design, FPGA Prototyping, RISC-V Systems, Intermittent Computing  
**Software & ML Systems**: ONNX Runtime, PyTorch  
**Programming Languages**: Verilog/SystemVerilog, Chisel, C/C++, Python, Shell Scripting  
**EDA & Tools**: Xilinx Vivado, Vitis HLS, Cadence Virtuoso, Eldo, Git
