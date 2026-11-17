# Analog 8-Bit Computer

## Lefika Tlhabano

**Name:** Lefika Tlhabano |
**Virginia Tech Email:** lefika@vt.edu

## Project Overview

Design and construct a functional 8-bit computer using individual electronic components, including transistors, resistors, capacitors, and diodes. The goal is to understand the fundamental principles of computer architecture and digital electronics by building a processor and its supporting subsystems from the component level. The computer will use binary logic to process, store, and execute instructions. Its architecture will consist of a clock circuit, registers, ALU, RAM, a program counter, an instruction decoder, a control unit, and an output system. These components will communicate through a shared data bus to perform basic arithmetic and logical operations like addition and subtraction.

## What I Hope to Learn
I hope to understand the fundamental principles of computer architecture and digital electronics by building a processor and its supporting subsystems from the component level. I also want to gain hands on experience with circuit design, digital logic, wiring and breadboards, and troubleshooting. 

## Design and Implementation
The computer follows a simple bus-based architecture, similar to the SAP-1 design used in Ben Eater's breadboard computer. Every module connects to a shared 8-bit bus, and the control unit decides which module writes to the bus and which module reads from it on each clock cycle.

<img width="533" height="243" alt="Screenshot 2026-11-16 120943" src="https://github.com/user-attachments/assets/418c6805-08d6-4ab7-81f0-2c0dc7a7dd80" />


Document the design of your project as it develops.

This may include:
- Block diagrams
- Circuit schematics
- Software architecture
- Hardware selection

Calculations will be documented here as the design develops, including:
- Transistor base resistor values for reliable switching at 5 V
- LED current-limiting resistor values
- Clock frequency (RC timing values for the 555 timer)
- Power consumption and current draw per module
- Testing methods

Explain major design decisions and why you made them.

## Bill of Materials

Document the major components and materials used for the project.

| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| NPN transistors (2N3904 or 2N2222) | 1 | $0.00 | Link |


**Estimated Total Cost:** $250

## Timeline and Milestones

Outline the major stages of the project and update them as work progresses.

| Milestone | Target Date | Status |
|---|---|---|
| Project planning | 11/20/26 | In Progress |
| Initial Design (block diagram, gate schematics, parts ordered) | 12/04/26 | Not Started |
| Logic Gates and Clock Circuit Working | 02/19/26 | Not Started |
| Registers Working | 02/26/27 | Not Started |
| ALU Working | 03/5/27 | Not Started |
| RAM and Program Counter Working | 03/15/27 | Not Started |
| Instruction Register, Decoder, and Control Unit Working | 03/12/27 | Not Started |
| Full Integration (first program runs) | 03/19/27 | Not Started |
| Testing and debugging | 03/26/27 | Not Started |
| Project Completion (documentation and demonstration) | 04/02/27 | Not Started |


## Progress Log

### YYYY-MM-DD

Describe what you worked on, what was completed, any problems you encountered, and what you plan to work on next.

## Project Files

Organize and document important project files in this repository. Depending on the project, this may include:

- Source code
- KiCad files
- Schematics
- PCB layouts
- CAD files
- Datasheets
- Test results
- Documentation

## Useful Links
Refrence #1 (Ben Eater's: Building an 8-bit breadboard computer): https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU

Reference #2: https://arghyabi.in/projects/8bit-computer-with-logic-gates/

Reference #3: https://blog.fponzi.me/2024-10-15-my-8-bit-breadboard-computer.html
