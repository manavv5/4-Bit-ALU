# 4-Bit ALU

A basic **4-bit Arithmetic Logic Unit (ALU)** designed and simulated in **Logisim**.

## Features

The ALU supports the following operations:

- Addition
- Subtraction
- Bitwise AND
- Bitwise OR
- Bitwise XOR

It uses a 3-bit operation-select input to choose the required operation and produces a 4-bit result.

## Block Diagram

```text
        A[3:0] ───────────┐
                          │
        B[3:0] ───────────┤
                          ▼
                   ┌─────────────┐
 Operation Select ─►│   4-Bit ALU │──► Result[3:0]
                   └─────────────┘
```

## Implementation

The circuit was built using Logisim components including:

- 4-bit Adder
- NOT gate
- AND gate
- OR gate
- XOR gate
- Multiplexers
- Input/output pins

## Operations

| Operation | Description |
|---|---|
| ADD | A + B |
| SUB | A - B |
| AND | A AND B |
| OR | A OR B |
| XOR | A XOR B |

## How to Run

1. Install Logisim or a compatible Logisim version.
2. Open `logisim/4-bit-ALU.circ`.
3. Set the 4-bit inputs A and B.
4. Select the required operation.
5. Observe the 4-bit output.

## Project Status

**Completed:** Basic 4-bit ALU implementation.

**Future improvements:**
- Add Carry flag
- Add Zero flag
- Add Overflow flag
- Improve circuit hierarchy
- Implement the same ALU in Verilog
- Create a Verilog testbench
- Extend the design to 8-bit/32-bit

## Learning Outcomes

This project helped reinforce:

- Combinational digital logic
- Binary arithmetic
- Logic gates
- Multiplexers
- ALU architecture
- Hardware-oriented problem solving

## Author

Manav Sharma | ECE Undergraduate | Digital Electronics & VLSI enthusiast
