# 3 bit Arithmatic_Logic_Unit

Objective:

The objective of this lab is to learn the basic logic synthesis steps by synthesizing a 3-bit signed Arithmetic
Logic Unit (ALU) using Verilog.
Lab Description and Specs:

Function:
o Three-bit addition, subtraction, XOR (bitwise between A and B), and 3-bit shift-left (on A; shift in
zero at the least significant bit).
Inputs:
fun_sel0 and fun_sel1: Selects one of the four functions.
ain[2:0] and bin[2:0]: Bus inputs for the two 3-bit numbers or one 3-bit number.
Outputs:
out[2:0]: The three-bit number that is the result of the ALU operation.
HEX0[6:0] HEX1[6:0]: 2 digits 7-segment display control output to show the final result on 7-
segment display.
