# Modulo8Counter-FPGA

## Overview
This is a modulo-8 counter designed using the DE0-Nano FPGA board and Quartus Prime software. 

## Design Process
Initially, a 1-bit adder was designed using a truth table, and then a K-map to simplify and write an appropriate Boolean equation and build the logic circuit. Once this was tested and verified, this was built upon to create a 3-bit adder. 

Finally, the 3-bit adder was connected together with a 3-bit register (based on three D flip-flops). This leads to the modulo-8 counter, which counts up by an amount determined by the switch inputs, shown in the images below. 

// insert image of block diagrams here

To increment the counter by 1, the least significant bit, A0, must be 1, while A1 and A2 are 0. This is shown in the image below where SW0 is turned on. The output of the counter is displayed from least-significant bit on the right, moving to the most-significant bit on the left. The further left LED signifies the carry out of the 3-bit adder.  

//insert image of led lights

Refer to the repository for two videos of the modulo-8 counter. The first counts from 0 to 3, then the reset button is pressed. The second counts all the way from 0 to 7.
