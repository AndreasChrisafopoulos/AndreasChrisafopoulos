# Andreas Chrysafopoulos

Electrical & Computer Engineering student at the **University of Thessaly** (Integrated MEng, expected 2027), focusing on **computer architecture, RTL design and verification, RISC-V processors, FPGA acceleration, and hardware–software co-design**.

I enjoy taking designs from architecture and implementation through verification, FPGA deployment, and measured results.

## Selected Projects

### [Tomasulo-Based Out-of-Order CPU on FPGA](https://github.com/AndreasChrisafopoulos/tomasulo-riscv-cpu-fpga)

**Verilog / SystemVerilog · RISC-V integer subset · Vivado · ZedBoard**

Co-designed a parameterized, single-issue processor with register renaming, reservation stations, reorder-buffer-based in-order commit, and multi-cycle execution units.

- Implemented and verified arithmetic, dependency handling, and load/store behavior using RTL regressions.
- Integrated an AXI4-Lite host-control path and achieved **90 MHz timing closure** on ZedBoard.
- Documented the verified instruction subset, architecture, reproducible tests, design trade-offs, and known limitations.

### Smith–Waterman FPGA Accelerator

**C / C++ · Vitis HLS · ZedBoard**

Developed an FPGA sequence-alignment accelerator with anti-diagonal parallelism and a custom **on-FPGA traceback** architecture that reconstructs the alignment path without transferring the full direction matrix to external DDR memory.

- Verified the implementation on hardware against a software reference.
- Measured approximately **10× speedup** over the fastest tested x86 implementation for the evaluated workload.

### TinyGPT on Vortex RISC-V GPGPU — Ongoing

**C / C++ · OpenCL · FPGA · Hardware–Software Co-design**

Working with a teammate on small-language-model inference using the open-source Vortex GPGPU on an Alveo U250 FPGA. The work includes transformer kernel development, validation, and hardware-configuration evaluation.

Our ongoing work was **accepted for presentation at the Vortex Workshop held with IEEE/ACM MICRO 2026**.

### [C-SPICE Circuit Simulator](https://github.com/AndreasChrisafopoulos/c-spice-simulator)

**C · Numerical Methods · GSL · CSparse**

Built a SPICE-like circuit simulator supporting DC and transient analysis, Modified Nodal Analysis, and dense and sparse numerical solvers. Validated results against large power-grid reference benchmarks.

### [HDMI Pong on FPGA](https://github.com/AndreasChrisafopoulos/fpga-hdmi-pong)

**Verilog · Spartan-7 · Vivado**

Implemented a real-time Pong game with HDMI output, TMDS encoding and serialization, video timing, and self-checking RTL tests. Tested the complete design on a physical FPGA board.

### [UART Communication Subsystem](https://github.com/AndreasChrisafopoulos/fpga-uart-subsystem-verilog)

**Verilog · Spartan-7 · Vivado**

Designed and verified modular UART transmit/receive logic with 16× receiver oversampling, selectable baud rates, parity and framing checks, and FPGA loopback testing.

## Research

I also participate in **faculty-supervised research** at the University of Thessaly, including RISC-V processor design and reliability and a completed research collaboration with a conference manuscript in preparation. Some research work is not publicly released.

## Technical Skills

- **Computer Architecture & RTL:** RISC-V, CPU microarchitecture, Verilog, SystemVerilog, RTL design and verification, self-checking testbenches
- **FPGA & EDA:** Vivado, Vitis HLS, Verilator, Yosys, OpenROAD, HSPICE
- **Programming & Tools:** C, C++, Python, Bash, Tcl, OpenCL, Linux, Git

## Education

**University of Thessaly** — Integrated MEng in Electrical and Computer Engineering (2022–2027)  
**GPA:** 8.59/10

## Contact

[LinkedIn](https://www.linkedin.com/in/andreas-chrisafopoulos/) · [GitHub](https://github.com/AndreasChrisafopoulos) · [achrysafo@gmail.com](mailto:achrysafo@gmail.com)
