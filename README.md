# Single-Cycle RISC-V Processor in Verilog

A modular implementation of a **single-cycle RISC-V processor** developed in Verilog HDL. The project progressively builds the processor from fundamental digital logic blocks to a complete single-cycle CPU, covering datapath design, control logic, ALU implementation, memory interfaces, and processor integration.

The repository demonstrates practical RTL design, processor architecture concepts, and functional verification through simulation.

---

# Features

- RV32I single-cycle processor architecture
- Modular RTL implementation
- Register file
- Arithmetic Logic Unit (ALU)
- Immediate Generator
- Control Unit
- ALU Control
- Program Counter
- Instruction Memory
- Data Memory
- Functional simulation using Verilog testbenches

---

# Processor Organization

The processor consists of reusable RTL modules located in the `rtl/` directory.

Major modules include:

- Program Counter
- Register File
- Control Unit
- ALU Control
- Immediate Generator
- Arithmetic Logic Unit
- Instruction Memory
- Data Memory
- CPU Top Module

---

# Repository Structure

```text
single-cycle-riscv-cpu/

├── rtl/
│   Reusable RTL modules
│
├── labs/
│   Progressive implementation stages
│
├── results/
│   Simulation outputs
│
├── scripts/
│   Utility scripts
│
├── docs/
│   Architecture diagrams and screenshots
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# Progressive Implementation

The processor was developed through successive implementation stages.

| Stage | Focus |
|------|------------------------------|
| Lab 1 | Basic combinational logic |
| Lab 2 | Sequential circuits and FSMs |
| Lab 3 | Instruction encoding |
| Lab 4 | Datapath building blocks |
| Lab 5 | Control logic |
| Lab 6 | Processor integration |
| Lab 7 | Memory subsystem |
| Lab 8 | Complete single-cycle processor |

---

# Directory Overview

## rtl/

Contains reusable RTL modules implementing the processor datapath and control logic.

Examples include:

- ControlUnit
- Register File
- ALU
- Immediate Generator
- Program Counter
- Memory Modules

---

## labs/

Contains the implementation stages, corresponding testbenches, and manuals documenting the evolution of the processor.

---

## results/

Stores generated simulation outputs.

---

## scripts/

Utility scripts for compiling and running simulations.

---

# Future Improvements

Possible extensions include:

- Five-stage pipelined implementation
- Hazard detection
- Forwarding unit
- Branch prediction
- Cache hierarchy
- CSR support
- Performance benchmarking

---

# Tools

- Verilog HDL
- Icarus Verilog
- GTKWave
- Git
- VS Code

---

# License

Released under the MIT License.
