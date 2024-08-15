FIFOs are often used to safely pass data from one clock domain to another asynchronous clock domain. Using a FIFO to pass data from one clock domain to another clock domain requires multi-asynchronous clock design techniques. An asynchronous FIFO refers to a FIFO design where data values are written to a FIFO buffer from one clock domain and the data values are read from the same FIFO buffer from another clock domain, where the two clock domains are asynchronous to each other.


Dual n-bit Gray code counter block diagram
![Simulation_waveform](https://github.com/user-attachments/assets/12bc4a04-ea57-4238-8142-977c00f66727)

                                       **Vivado Project** 


image Behavioural Simulation Result for the Testbench attached


Results: ◦ Designed Asynchronous FIFO in Verilog, synthesised & verified the design in Modelsim. ◦ Synchronization of FIFO pointers is accomplished using Gray Code to avoid multi-bit signal transitions. ◦ Implemented 2 Flip-Flop Synchronizer to avoid meta-stability issues in CDC

Reference - Simulation and Synthesis Techniques for Asynchronous FIFO Design ,Clifford E. Cummings, Sunburst Design, Inc.
