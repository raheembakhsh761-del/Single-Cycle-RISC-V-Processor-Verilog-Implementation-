🧠 Single-Cycle RISC-V Processor (Verilog Implementation)

This project is a Single-Cycle RISC-V Processor implemented in Verilog HDL, based on the concepts presented in Computer Organization and Design RISC-V Edition: The Hardware/Software Interface (2nd Edition) by David A. Patterson and John L. Hennessy.

The design follows the architectural concepts explained in Chapter 4, which focuses on the processor datapath and control for RISC-V instructions.

⚙️ Key Features

Implemented in Verilog HDL

Supports R-type, I-type, S-type, B-type, and J-type instructions

Includes major datapath components:

Program Counter (PC)

Instruction Memory

Register File

ALU and ALU Control Unit

Control Unit

Data Memory

Adders, MUXes, and Logic Components

Designed as a single-cycle processor (all operations complete in one clock cycle)

📘 Reference

Book: Computer Organization and Design RISC-V Edition: The Hardware/Software Interface (2nd Edition)
Authors: David A. Patterson, John L. Hennessy
Chapter: 4 — The Processor

🧩 Tools Used

Language: Verilog HDL

Simulator: ModelSim / Vivado / Quartus (any Verilog-supported tool)

🚀 Future Work

Add pipelined version of the processor

Implement hazard detection and forwarding units

Extend instruction set support
