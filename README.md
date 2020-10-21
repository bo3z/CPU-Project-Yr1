# Year 1 CPU Project
A repo containing the source code and documentation for a general-purpose, ARM-based CPU designed as part of the Electronics Design Project at Imperial College London. This project was created by: Aadi Desai, Benjamin Ramhorst and Kacper Neumann.


### Project description
The main goal of this project was to build a general-purpose CPU, capable of performing a wide range of operations including arithmetic operations such as addition, subtraction and multiplication; logic operations such as bitwise operations and conditionals; memory operations such as load and store. The CPU should be tested with a wide range of mathematical functions and programming algorithms, including but not limited to calculating a Fibonacci number, generating pseudo-random numbers, and traversing a linked list. The CPU is expected to complete these operations efficiently and correctly, using only built-in hardware and instructions.

### Technologies used:
  * Quartus Prime, used for block schematics and testing
  * Verilog HDL, used for multiplication and ALU
  * C++, for writing benchmark tests and automating testing
  
  
### CPU Technical requirements
  1. 16-bit instruction length
  2. The CPU should be able to perform a wide range of arithmetic-logic operations.
  3. Efficient multiplication must be built-into the CPU
  4. Enough memory to store 2K words of instructions and data
  5. The CPU must have a stack, but there are no other hardware requirement on how this is implmented
  6. The CPU must be pipelined to improve performance
  7. The CPU dynamic power consumption should not be above 50 mW
  8. The maximum clock frequency should be at least 100 MHz at 0 degrees Celsius


### CPU Testing:
The CPU should be tested with three algorithms, as described below. It must produce correct results, but also be efficient, both in terms of power and speed. The algorithms used for testing should be:
  1. Calculating the nth Fibonacci number using recursion.
  2. Calculating pseudo-random integers.
  3. Traversing a linked list of integers and searching for a specific element in the list.


