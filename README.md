 # 4-bit ALU Design with Memory in Verilog
. *This repository contains the Verilog code for a 4-bit Arithmetic Logic Unit (ALU) with separate memories for storing inputs (A and B) and outputs (R). It supports multiple arithmetic and logical operations based on a 3-bit opcode.*

## Features
. *Arithmetic Operations:*
Addition
Subtraction
. *Logical Operations:*
AND
OR
XOR
NOT
. *Shift Operations:*
Left Shift
Right Shift
. *Memory Implementation:*
Separate memories for input values (A and B)
Result memory to store outputs for each operation
## File Structure
Code Overview
. *1. ALU Module*
The ALU module takes two 4-bit inputs (A and B) and performs operations based on a 3-bit opcode. The output (R) is updated whenever inputs or opcode change.

. *2. Testbench Module*
The Testbench initializes memory for inputs and tests the ALU with predefined values. It stores the results in a separate output memory and displays them during simulation.

# How to Run the Simulation
. *Clone the repository:*
bash
Copy code
git clone https://github.com/[SWATI](https://github.com/sw301)/alu-verilog.git
cd alu-verilog
Open the files in any Verilog-supported IDE or simulator (e.g., ModelSim, Vivado, QuestaSim, etc.).
. *Compile the code:*
bash
Copy code
vlog alu.v alu_testbench.v
. *Simulate the testbench:*
bash
Copy code
vsim work.ALU_Testbench
. *View the simulation waveform or console output:*
bash
Copy code
add wave -position insertpoint sim:/ALU_Testbench/*
run -all
# Sample Output
less
Copy code
A = 0010, B = 0001, R = 0011  // Addition
A = 0100, B = 0011, R = 0111  // Addition
A = 1110, B = 0001, R = 1111  // Addition
A = 1010, B = 0101, R = 1111  // Addition

## Author
. *[SWATI](https://github.com/sw301)*  
(Trainee@Ramaiah Skill academy )






