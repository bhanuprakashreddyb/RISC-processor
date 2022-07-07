# RISC-processor
This design is implemented using 5-stage pipelining.
Each instruction is of 32-bit size and these instructions are stored in the memory bank, as shown in the testbench.
Initially, the program counter is made zero and after fetching an instruction, it is incremented by 1.
After the complete execution of an instruction, the result is stored back in a register, which can be accessed using "$display" present in the testbench.
