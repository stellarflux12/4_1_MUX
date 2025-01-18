# 4_1_MUX
 4:1 Mux Using Domino Logic vs Transmission Gate
 ## Introduction
 This project involves the design and implementation of a 4-1 MUX using both Domino and Transmission gate logic. The objective is to compare the rise time, fall time, area, and power consumption of the two designs. The project includes simulation and analysis of these metrics to provide a comprehensive comparison.
## Feature

1. Takes 4 input data lines and selects 1 output based on 2 select lines.
2. Uses combinational logic for low latency and fast operation.
3. Suitable for digital logic circuits, data routing, and signal selection.
4. Optimized for low power and compact design in hardware.

Inputs:
  - a, b, c, d: 4 data inputs (1-bit each)
  - s: 2-bit select line to choose one of the 4 inputs

Output:
  - y: Selected data output (1-bit)
4:1 Multiplexer Truth Table

| **S1** | **S0** | **Output (Y)** |
|--------|--------|----------------|
|   0    |   0    | I0             |
|   0    |   1    | I1             |
|   1    |   0    | I2             |
|   1    |   1    | I3             |

Notes:
1. S1 and S0 are the select lines.
2. Y is the output determined by the selected input (I0, I1, I2, or I3).
