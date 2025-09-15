# MIPS Vector-Extended Processor Architecture

This project is a **team-designed** implementation of a simple single-cycle processor extended with **vector operations**.  
The design includes a **register file**, **memory unit**, **ALU**, and a **control unit** that together support both scalar and vector instructions.  
It allows parallel read/write of 128-bit data, register-to-register transfers, memory load/store operations, and various ALU operations (add, sub, mul, logical ops) in both scalar (32-bit) and vector (128-bit) modes.

## Features
- **Register File**: Supports both scalar (32-bit) and vector (128-bit) registers with parallel access.  
- **Memory Unit**: 32-bit and 128-bit memory operations with configurable word sizes.  
- **ALU**: Implements scalar and vector arithmetic/logical operations (ADD, SUB, MUL, AND, OR, XOR).  
- **Control Unit**: Handles instruction decoding and control signals for scalar/vector execution.  
- **COP Support**: Special transfer instructions (`TOCOP`, `FROMCOP`) for register/memory data movement.  

## Project Structure
- **Memory Section** – Implements data storage and access logic.  
- **Register Section** – Provides scalar and vector register banks.  
- **ALU Section** – Executes arithmetic and logic operations in parallel.  
- **Control Section** – Manages instruction flow and execution. 
