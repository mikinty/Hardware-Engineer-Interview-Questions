# Digital Questions

## Basics

- What is sequential vs combinational logic?
* Design a circuit that can detect a low to high edge for one clock cycle using only one FF and gates.
* Make an OR gate using 2-1 muxes
* Make a mux using gates
* Types of FSMs:
  * One-hot
  * Output encoded
  * Fully encoded
* Explain the difference between a Mealy and Moore machine
* Design a latch

## Circuits

* Know how to convert an FSM into a digital circuit
* Design an adder

## Timing

* Explain the following:
  * `T_setup`
  * `T_hold`
  * `T_clk2q`
  * `T_prop`
* What is clock skew and what problems can it cause? How do you account for it?
* What is a PLL?
* What are waveform viewers, and why do we use them?

## Applications

* Explain how a USB system works, including:
  * Protocols
  * Bitstuffing
  * NRZI
  * DPDM
  * Difference between USB 2 and 3 (and USB-C!)
* Generally know how to implement memory in digital circuits
* Describe different steps in an ethernet protocol, e.g. packet scrambling, headers, etc.
* Describe how you would implement SHA-256 (or maybe a simpler crypto algorithm)
* Describe how TCP/UDP works

## FPGAs

* What is an FPGA?
  * How is it constructed?
  * Why are FPGAs useful?
  * Why would we use an FPGA over an ASIC or over a computer?

* What are some of the main components that make up an FPGA and why are they useful?
  * LUTs
  * FFs
  * DRAM, BRAM, URAM
  * DSPs
  * PCIe
  * Transcievers

* What is a High-Speed Gigabit Transciever on an FPGA?
  * Why is this necessary or important?
  * How does it interact with PCS/PMA/MAC?

* How does an FPGA implement a function?
  * How do LUTs work?

* What are the different ways to store memory on an FPGA?
  * FFs vs. LUTs vs. RAM

* What are the necessary steps to go from RTL code to FPGA bitstream?

* How might the FPGA interact with host (CPU)?
  * describe DMA and PCIe
  * describe NIC and ethernet packets

* What are Bus Funtional Models (BFMs) and how do they help with FPGA design verification?

* What are the differences between simulation and emulation (on-board/silicon)?

* What are some of the main tools FPGA engineers use today?
  * Simulation
  * Verification
  * Emulation
  * Network Debugging

* Describe CLBs and how they relate to LUTs and FFs on an FPGA

* Describe ways to send stimulus (signals, packets, memory writes, etc) to a simulation RTL for verification purposes
  * Testbenches in SystemVerilog
  * C++ using SystemC library

## System Verilog

* Difference between blocking and nonblocking statements
* What is the difference between `rand` and `randc`

## FSM Design

* Design a traffic light FSM, that takes care of W-E, N-S intersection, with Red, Yellow and Green lights
* Design the FSM for a vending machine that takes nickels, quarters and dimes, dispenses water bottles for $1, and gives change if the amount given is over, but does nothing if the amount of money is not enough.

## Coding

* Code a class for a Queue
* Write a module that computes the Fibonacci numbers

## Resources

* [All you need to know about USB](https://www.beyondlogic.org/usbnutshell/usb1.shtml)
