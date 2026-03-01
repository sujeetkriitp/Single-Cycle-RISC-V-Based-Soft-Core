# Single-Cycle-RISC-V-Based-Soft-Core
Designed and FPGA-prototyped a single-cycle RV32I RISC- V processor implementing ALU, register file, instruction decode, and memory interface, and verified instruction-level correctness using simulation and hardware validation.
RISC-V is a load-store architecture, in which arithmetic instructions operate only on the registers, and only loads and stores transfer data to and from memory.
RV32I is the base 32-bit integer ISA.
47 instruction(Computational(21), Control Flow(8), memory access(10), System(8))
Six instruction formats
four major formats, R(10), I(25), S(3), and U(2);
And two variants, SB(6) and UJ(1)
<img width="1172" height="406" alt="image" src="https://github.com/user-attachments/assets/71996512-c018-475d-9e1e-03cb0f98c4c9" />
31 general-purpose integer registers x1-x31(x0=0) each 32 bits wide.
PC additional register
<img width="1536" height="1054" alt="image" src="https://github.com/user-attachments/assets/5aaff674-6057-4e87-969d-b10b15441003" />
Micro architecture of single cycle RV32I processor Core
<img width="1272" height="517" alt="image" src="https://github.com/user-attachments/assets/bd5029b0-7922-43eb-84be-7f83d9f0ccbb" />
RTL simulation(Sum of n natural numbers) of the single cycle RV32I Processor Core
<img width="1612" height="911" alt="image" src="https://github.com/user-attachments/assets/3db6d431-9e7e-4f0b-b32f-ebad6eb536d1" />

FPGA Protype and Evaluation results
<img width="1600" height="912" alt="image" src="https://github.com/user-attachments/assets/0e56ff3c-e721-44cf-b4ca-2dd0053cd695" />
