# AXI4-Lite-Peripheral-Design-Verification
This project implements a custom AXI4-Lite slave peripheral in Verilog, verified with SystemVerilog testbench, and packaged as a Vivado Custom IP. It demonstrates end-to-end flow: RTL design → simulation → IP packaging → SoC integration with MicroBlaze/Zynq → software validation using Vitis SDK.
- Implements AXI4-Lite protocol (read/write channels with handshakes).
- Supports 4 32-bit memory-mapped registers (0x00, 0x04, 0x08, 0x0C).
- Synthesizable RTL design, verified via testbench.
- Compatible with FPGA integration in Xilinx Vivado.
- Modular and extendable for additional peripherals.

🔧 Applications
-FPGA-based SoC designs
-Memory-mapped register interfaces
-Custom IP peripheral development

🎯Learning Outcomes
-Through this project, I gained hands-on experience in:
-AXI4-Lite protocol implementation.
-Writing synthesizable RTL in Verilog.
-Designing a self-checking testbench for verification.
-Debugging and verifying simulation waveforms.
-Packaging a design as a custom Vivado IP core for FPGA use.
