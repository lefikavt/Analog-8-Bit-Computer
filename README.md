# Analog 8-Bit Computer

## Lefika Tlhabano

**Name:** Lefika Tlhabano |
**Virginia Tech Email:** lefika@vt.edu

## Project Overview

I plan to design and construct a functional 8-bit computer using individual electronic components, including transistors, resistors, capacitors, and diodes. The goal is to understand the fundamental principles of computer architecture and digital electronics by building a processor and its supporting subsystems from the component level. The computer will use binary logic to process, store, and execute instructions. Its architecture will consist of a clock circuit, registers, ALU, RAM, a program counter, an instruction decoder, a control unit, and an output system. These components will communicate through a shared data bus to perform basic arithmetic and logical operations like addition and subtraction.

## What I Hope to Learn
I hope to understand the fundamental principles of computer architecture and digital electronics by building a processor and its supporting subsystems from the component level. I also want to gain hands-on experience with circuit design, digital logic, wiring and breadboards, signal timing, and troubleshooting. Specifically, I want to learn:

- How instructions are fetched, decoded, and executed
- How registers and memory store data
- How binary arithmetic is performed in hardware
- How a control unit coordinates every part of the computer
- How software instructions become electrical control signals


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

### Logic ICs
| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| NPN transistors (2N3904 or 2N2222) | 4 | $3.00 | Link |
| 74LS00 quad NAND gate | 2 | $2.00	 | Link |
| 74LS02 quad NOR gate | 1 | $1.00 | Link |
| 74LS04 hex inverter | 5 | $4.00 | Link |
| 74LS08 quad AND gate | 3 | $3.00 | Link |
| 74LS32 quad OR gate | 1 | $1.00 | Link |
| 74LS86 quad XOR gate (ALU subtraction) | 2 | $2.00 | Link |
| 74LS107 dual JK flip-flop (replaces hard-to-find 74LS76) | 1 | $2.00 | Link |
| 74LS138 3-to-8 line decoder | 1 | $1.00 | Link |
| 74LS139 dual 2-to-4 line decoder | 1 | $1.00 | Link |
| 74LS157 quad 2-to-1 data selector | 4 | $4.00 | Link |
| 74LS161 4-bit counter (program counter, step counter) | 2 | $3.00 | Link |
| 74LS173 4-bit D-type register | 8 | $10.00 | Link |
| 74189 64-bit RAM | 2 | $10.00 | Link |
| 74LS245 octal bus transceiver | 6 | $9.00 | Link |
| 74LS273 octal D flip-flop (output register) | 1 | $2.00 | Link |
| 74LS283 4-bit binary full adder | 2 | $3.00 | Link |
| 28C16 EEPROM (control logic and display decoder) | 3 | $15.00 | Link |

### Passive Components, Switches, and Displays
| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Double-throw toggle switch | 3 | $5.00 | Link |
| 6mm momentary tact switch | 3 | $2.00	 | Link |
| 8-position DIP switch | 1 | $2.00 | Link |
| 4-position DIP switch | 1 | $2.00 | Link |
| Common-cathode 7-segment display | 4 | $6.00 | Link |



### EEPROM Programmer
| Item | Quantity | Estimated Cost | Link |
|---|---:|---:|---|
| Arduino Nano | 1 | $5.00 | Link |
| 74HC595 shift register | 2 | $2.00 | Link |



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

### 2026-11-16

Planned the project scope, architecture, and timeline while looking at reference designs, like Ben Eater's 8-bit breadboard computer. Decided to start with addition, subtraction, and logic operations, and to treat multiplication and division as stretch goals. Upcoming Goal: finalize the block diagram, design the transistor-level logic gates, and order parts.
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
