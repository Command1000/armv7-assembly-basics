# ARM v7 Assembly Basics

This repository contains foundational practice files for learning ARM v7 Assembly language. The primary focus is on understanding hardware-software interaction at the instruction level, particularly memory manipulation and register allocation.

## Repository Contents

The current examples cover the following fundamental concepts:

- **Load/Store Architecture:** Usage of `LDR` and `STR` instructions to move data between registers and memory.
- **Addressing Modes:**
  - Immediate offset
  - Pre-indexed addressing (e.g., `[R0, #4]!`)
  - Post-indexed addressing (e.g., `[R0], #4`)
- **Data Directives:** Memory allocation using directives such as `.data` and `.word`.
- **Program Entry Point:** Standard `.global _start` declaration for execution.

## Build and Run Instructions

The source code uses standard GNU Assembler (GAS) syntax. You can build and run it using your preferred ARM toolchain or simulator.

### General Steps:
1. **Assemble:** Use an ARM assembler (e.g., `arm-none-eabi-as` or `arm-linux-gnueabihf-as`) to compile the `.s` file into an object file.
2. **Link:** Use a linker to generate the executable.
3. **Execute:** Run on a native ARM environment or use an emulator like QEMU.
