# Microprocessordesign
32bit RISC Microprocessor Design With Pipeline


## Abstract

* The Project involves the design of a 32-bit Microprocessor with RISC architecture based on the pipeline depth being four. The four-stage pipeline reciprocates “Instruction fetch”, “Read register / Address generation”, “Fetch operand / Execute” and “Write back”. The microprocessor interfaces the pseudo memory and the registers by means of Memory Interface Unit (MIU) and Register Interface Unit (RIU). The design also covers the avoidance of certain structural Hazards and Data hazards by using the Stall, Flush and Data Forwarding control logic making the design fully functional.

* Certain considerations that have been included in the project on our convenience are as follows.

* The format used for data read and write is “Little Endian”.
 
* For the increment and decrement of the stack pointer we have used the standard method of how a stack works, that is 

* “pre-decrement” which is SP-4 in case of PUSH instruction and “post-increment” which is SP+4 in case of POP instruction.
