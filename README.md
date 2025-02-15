# RISC-V 32-bit Processor (Pipelined & Normal) in GDigital

## Overview
This project implements a 32-bit RISC-V processor using GDigital. It includes both a standard (non-pipelined) version and a pipelined version. The design consists of various components such as registers, ALU, control units, and memory.

## Getting Started
### Requirements
- [GDigital](https://github.com/...) (Download and install GDigital to open the files)

### Opening the Project
1. Open **GDigital**.
2. Navigate to the folder containing all the `.dig` files.
3. Open the main circuit file (`rv32.dig` for the standard version or `rv32pipeline.dig` for the pipelined version).

## Files Included
| File Name                    | Description |
|------------------------------|-------------|
| `boite.dig`                  | A subcomponent used in the design |
| `BR.dig`                     | Branch unit circuit |
| `circuit_controle.dig`       | Control unit for instruction decoding |
| `circuitdecontrolerv32pipeline.dig` | Control unit for the pipelined version |
| `registre8.dig`              | 8-bit register module |
| `rv32.dig`                   | Main RISC-V processor (non-pipelined) |
| `rv32_manuel.dig`            | Manual test circuit for the RISC-V processor |
| `rv32pipeline.dig`           | Pipelined RISC-V processor |
| `ual.dig`                    | ALU circuit |
| `instructions.txt`           | Example instruction set to load into ROM |

## Loading Instructions into ROM
1. Open `instructions.txt`.
2. Modify or add instructions according to the RISC-V ISA.
3. Load the modified instruction set into the ROM component in `rv32.dig` or `rv32pipeline.dig`.

## Contact
Author: **Bilal-66**

If you have any issues or suggestions, feel free to reach out!

