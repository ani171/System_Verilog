# Basic SystemVerilog Modules

This repository contains a collection of synthesizable SystemVerilog (.sv) modules along with their corresponding testbenches. The project focuses on implementing fundamental digital building blocks commonly used in digital design and VLSI systems

## Multiplexer ([mux.sv](https://github.com/ani171/System_Verilog/blob/main/mux.sv))
- A combinational circuit that selects one of multiple inputs based on a select signal.
    - Routes selected input to output
    - Commonly used in datapaths and control logic
    - Demonstrates conditional data selection logic
    - Synthesizable and modular implementation
    - Testbench validates selection functionality

## D Flip-Flop ([dff.sv](https://github.com/ani171/System_Verilog/blob/main/dff.sv))
- The D Flip-Flop is a fundamental sequential building block in digital systems.
    - Edge-triggered storage element
    - Captures input D on the clock edge and transfers to output Q
    - Used in registers, counters, pipelines, and state machines
    - Demonstrates sequential logic design principles
    - Testbench verifies clock behavior and data capture

## Encoder ([encoder.sv](https://github.com/ani171/System_Verilog/blob/main/encoder.sv))
- A combinational circuit that converts multiple input lines into a binary-coded output.
    - Converts active input line to binary index
    - Reduces multiple signals into a compact representation
    - Used in interrupt handling and data compression logic
    - Demonstrates combinational logic mapping
    - Testbench verifies encoding correctness

## Priority Encoder ([priority_encoder.sv](https://github.com/ani171/System_Verilog/blob/main/priority_encoder.sv))
- An advanced version of the encoder where inputs are assigned priority
    - Outputs binary code of the highest-priority active input
    - Resolves multiple active inputs deterministically
    - Commonly used in interrupt controllers and arbitration logic
    - Demonstrates conditional prioritization logic
    - Testbench verifies priority resolution behavior

## Barrel Shifter ([barrel_shifter.sv](https://github.com/ani171/System_Verilog/blob/main/barrel_shifter.sv))
- A combinational circuit capable of shifting data by multiple positions in a single clock cycle
    - Performs logical shifts (left/right)
    - Can be parameterized for data width
    - Used in ALUs, processors, and DSP applications
    - Demonstrates scalable and structured combinational design
    - More complex datapath-oriented implementation
    - Testbench verifies shifting across multiple positions
