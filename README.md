# 4-Bit CPU Project

## Overview

This project involves the design and implementation of a 4-bit CPU using Logisim. The CPU is capable of performing a variety of arithmetic and logical operations and is built around a finite state machine (FSM) for control. You can scale this to x64, x86 too, and contributions will be greatly appreciated.

![alt text](/images/My_CPU.png)


## Project Details

**Institution:** Namal University Mianwali  
**Department:** Computer Science  
**Course:** Digital Logic Design (DLD) Semester Project (Spring 2022)  
**Author:** Muhammad Wasay Tahir  

## Contents

1. **Project Scope:**
   - Design and implementation of a 4-bit CPU. (Scalable to x64 and x86 architectures too)
   - Development of a finite state machine for automated state transitions.
   
2. **Components:**
   - Program Counter
   - Sub-Counter
   - Finite State Machine (FSM)
   - Control Unit
   - Instruction Memory
   - Data Memory
   - Arithmetic Logic Unit (ALU)
   - Register File
   - Output Unit

3. **Functionality:**
   - The CPU can perform three arithmetic operations (Addition, Subtraction, Multiplication) and three logical operations (Greater Comparator, Equal Comparator, Less Comparator).
   - The FSM manages the state transitions and ensures synchronous operation of the CPU components.
   - Program counter cycles through instructions stored in memory.
   - Sub-counter helps in managing states within each program counter cycle.

4. **Technical Highlights:**
   - **Program Counter:** Generates addresses for instruction memory.
   - **Finite State Machine:** Controls the sequence of operations.
   - **ALU:** Executes arithmetic and logical operations.
   - **Control Unit:** Manages the overall operation of the CPU, including halting and resetting mechanisms.

## Challenges and Solutions

- **Clock Synchronization:** Ensured synchronization across all components to avoid timing issues.
- **State Control:** Developed an FSM to handle state transitions effectively, avoiding misalignment in control signals.

## Limitations and Future Work

- **Current Limitations:**
  - Works with 4-bit data only.
  - Manual loading of instructions into memory.
  - Initial state requires a reset to function correctly.

- **Future Improvements:**
  - Expand to handle 16-bit or 32-bit data.
  - Automate instruction loading.
  - Enhance the CPU to execute multiple instructions per clock cycle.

## Application

This project demonstrates the concepts of CPU design, including state machine implementation, memory management, and control logic. It serves as an educational tool for understanding the inner workings of a CPU and the principles of digital logic design.

---

**Note:** For detailed schematics, timing diagrams, and truth tables, please refer to the full technical report.
