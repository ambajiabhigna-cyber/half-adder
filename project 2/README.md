# Half Adder using Verilog

## Project Overview

A Half Adder is a combinational logic circuit that performs the addition of two single-bit binary numbers.

It has:
- Two Inputs: A, B
- Two Outputs:
  - Sum (S)
  - Carry (C)

## Truth Table

| A | B | Sum | Carry |
|---|---|-----|-------|
| 0 | 0 | 0 | 0 |
| 0 | 1 | 1 | 0 |
| 1 | 0 | 1 | 0 |
| 1 | 1 | 0 | 1 |

## Logic Equations

Sum = A XOR B

Carry = A AND B

## Files

- half_adder.v
- half_adder_tb.v
- simulation_output.txt
- waveform.png

## Tools Used

- Verilog HDL
- ModelSim / Vivado / Icarus Verilog
- GTKWave (optional)

## Expected Output

A=0 B=0 Sum=0 Carry=0
A=0 B=1 Sum=1 Carry=0
A=1 B=0 Sum=1 Carry=0
A=1 B=1 Sum=0 Carry=1