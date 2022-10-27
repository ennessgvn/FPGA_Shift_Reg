# FPGA_Shift_Register

A shift register is a type of digital circuit using a cascade of flip-flops where the output of one flip-flop is connected to the input of the next. They share a single clock signal, which causes the data stored in the system to shift from one location to the next. By connecting the last flip-flop back to the first, the data can cycle within the shifters for extended periods, and in this form they were used as a form of computer memory. In this role they are very similar to the earlier delay-line memory systems and were widely used in the late 1960s and early 1970s to replace that form of memory.

In most cases, several parallel shift registers would be used to build a larger memory pool known as a "bit array". Data was stored into the array and read back out in parallel, often as a computer word, while each bit was stored serially in the shift registers. There is an inherent trade-off in the design of bit arrays; putting more flip-flops in a row allows a single shifter to store more bits, but requires more clock cycles to push the data through all of the shifters before the data can be read back out again.
