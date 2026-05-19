# 32-Bit Pipelined MIPS Processor

## Project Overview
This project implements a 32-bit pipelined MIPS processor using SystemVerilog. The processor follows a modular design approach and is organized around the standard five pipeline stages: instruction fetch, instruction decode, execute, memory, and write back.

The design supports arithmetic, logic, memory, branch, and jump operations. Each module was developed and tested individually before being integrated into the full processor design.

## Team Project Notice
This project was completed as a group project for a Computer Engineering course at the University of the Pacific.

Team members:
- Matthew Bernardino
- Minh Dinh
- Shaan Lele

My main contributions were focused on the SystemVerilog modules included in this repository, including decode, execute, control, ALU, immediate handling, register file, and pipeline register components. The full processor was completed through team collaboration, integration, simulation, and debugging.

## Features
- 32-bit MIPS processor design
- Five-stage pipelined architecture
- Instruction Fetch, Decode, Execute, Memory, and Write Back stages
- Modular SystemVerilog implementation
- ALU and ALU control logic
- Register file
- Immediate handling for sign and zero extension
- Pipeline registers
- Hazard and forwarding support in the full project
- Functional verification using testbenches and simulation waveforms

## Tools Used
- SystemVerilog
- AMD/Xilinx Vivado
- Vivado Simulator

## Repository Structure
- `Design Files/` contains SystemVerilog source modules
- `Simulation Files/` contains testbench files used for module and top-level verification
- `docs/` contains the project report and presentation

## Modules Personally Contributed
- `alu.sv`
- `alu_control.sv`
- `control_unit.sv`
- `decode_ex.sv`
- `ex_mem_reg.sv`
- `id_ex_reg.sv`
- `imm_handle.sv`
- `reg_file.sv`

## Verification
Testbenches were used to verify individual modules before merging them into the full processor. Simulation waveforms were used to confirm expected behavior and debug logic issues during integration.

## What I Learned
This project strengthened my understanding of computer architecture, pipelined processor design, RTL development, and SystemVerilog verification. It also gave me experience working in a team-based hardware design environment where each module had to function correctly before full-system integration.
