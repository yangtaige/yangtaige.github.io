+++
date = '2025-09-01'
draft = true
title = 'CS61C: Great Ideas of Computer Architecture'
description = 'University of California, Berkeley'
schools = ["UC Berkeley"]
fields = ["EECS"]
languages = ["C", "RISC-V asm"]
topics = ["RISC-V", "Computer Architecture"]
+++
## Course Overview
An intensive exploration of the hardware-software interface, system-level programming, and modern computer microarchitecture. The coursework ranged from low-level memory management in C and implementing mathematical algorithms in pure RISC-V assembly, to building a pipelined RISC-V processor core from scratch at the digital logic level.

---

## Core Project: Game Logic and Low-Level Memory Management in C
*Developed a complete Snake game engine from scratch in C, focusing on dynamic memory allocation, pointer arithmetic, and the lifecycle management of complex data structures.*

* **Dynamic Memory Management:** Extensively utilized `malloc`, `realloc`, and `free` to dynamically allocate and resize the 2D game board and the array of snake entities. Implemented rigorous memory checking and deallocation logic, leveraging `memcheck` to strictly prevent memory leaks and dangling pointers.
* **Game State Machine & Logic Updates:** Implemented stateless collision detection and movement logic based on coordinate calculations and character parsing. Conducted precise 2D array pointer arithmetic to update grid states (`update_head`, `update_tail`) and handle complex physical boundary conditions.
* **File I/O & State Deserialization:** Engineered robust file stream parsing (`read_line`, `load_board`) to safely load variable-length text files line-by-line into heap memory, perfectly reconstructing the initial state and topology of the game.

### 2. Artificial Neural Network Classifier (RISC-V Assembly)
*Implemented a simple neural network in pure RISC-V assembly (RV32I) capable of performing forward propagation to classify handwritten digits, providing deep insights into instruction set architectures and low-level system execution.*

* **Mathematical Primitives & Matrix Operations:** Hand-wrote and optimized fundamental mathematical primitives in assembly: Absolute Value, ReLU activation, Argmax, and Vector Dot Product. Built upon these to implement general Matrix Multiplication by precisely controlling nested loops and memory stride accesses.
* **Strict Calling Convention:** Strictly managed stack frame allocation and deallocation in the prologue and epilogue of all assembly functions. Precisely differentiated and preserved caller-saved and callee-saved registers to ensure state safety and register consistency during deep nested function calls.
* **System-Level I/O & Execution Flow:** Utilized `ecall` to trap into the OS kernel for dynamic memory allocation and reading/writing matrix parameters. Constructed a complete command-line argument parsing workflow and performed in-depth step-by-step debugging using the Venus simulator and VDB.

### 3. Pipelined RISC-V Processor Architecture (Digital Logic)
*Designed and implemented a RISC-V (RV32I) microprocessor core supporting advanced instructions and pipelining from the hardware ground up using Logisim digital logic gates.*

<img src="/image/projects/CS61C/cpu.png" alt="Pipelined CPU" style="width: 100%; max-width: 600px; border-radius: 8px; margin: 15px 0;">

* **Datapath Component Construction:** Independently designed and wired core datapath components, including Multiplexers, the Arithmetic Logic Unit (ALU), Register File (RegFile), and Immediate Generator. Precisely controlled the core clock cycles for instruction fetching, decoding, execution, memory access, and write-back.
* **Instruction Decoding & Control Logic:** Designed hardwired control logic for the complete integer instruction set (I-type, R-type, B-type, S-type, U-type, J-type). Implemented precise branch condition evaluation and jump address calculation (e.g., return address linking for `jal` and `jalr`). Optimized hardware resources by removing the dedicated branch adder, relying entirely on the single main ALU for all arithmetic and address calculations.
* **Pipelined Architecture Design:** Upgraded the single-cycle CPU to a two-stage pipelined architecture, significantly improving microprocessor clock throughput. Introduced pipeline registers to isolate hardware states across different execution stages, and implemented bypassing and pipeline stalling mechanisms to thoroughly resolve data hazards and control hazards caused by pipeline parallelism.

---

## Technical Stack
* **Languages:** C, RISC-V Assembly (RV32I)
* **Concepts:** Instruction Set Architecture (ISA), Assembly Calling Conventions, Datapath Design, Pipelining, Memory Management.
* **Tools:** Logisim, Venus (RISC-V Simulator), GDB, Valgrind (Memcheck).