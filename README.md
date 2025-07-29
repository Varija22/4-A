PROGRAM 1
Aim:
To write a C++ program to perform bitwise operations (AND, OR, NOT, XOR, left shift, and right shift) on two integer values.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory:
Bitwise operators in C++ operate on binary representations of integers. These operators are used in low-level programming, embedded systems, and optimization.

The main bitwise operators are:

& (AND): Sets each bit to 1 if both bits are 1

| (OR): Sets each bit to 1 if at least one of the bits is 1

~ (NOT): Inverts all bits

^ (XOR): Sets each bit to 1 only if one of the bits is 1

<< (Left Shift): Shifts bits to the left by a specified number of positions, multiplying the number

>> (Right Shift): Shifts bits to the right, dividing the number

Algorithm:

1.Start the program.

2.Declare two integer variables and initialize them with values.

3.Perform the following operations:

4.Bitwise AND

5.Bitwise OR

6.Bitwise NOT on both numbers

7.Bitwise XOR

8.Left and right shifts on both numbers

9.Display the results using cout.

10.End the program.

Conclusion:
The program was successfully executed to demonstrate the use of bitwise operations in C++. It shows how binary manipulation works using C++ operators and is foundational for learning embedded system-level programming and performance optimization technique


PROGRAM 2
Aim: To write a C++ program that sets and resets a specific bit at a given position in an integer using bitwise operators.

Tools Used:

Programiz (Online C++ compiler)

Visual Studio Code (with C++ extension and GCC compiler)

Theory: Bit manipulation is commonly used in low-level programming, especially in embedded systems. This program demonstrates how to set or reset a particular bit in a number.

To set a bit at a given position: use the bitwise OR | with a mask 1 << position.

To reset a bit at a given position: use the bitwise AND & with the inverse mask ~(1 << position).

Example: If n = 12 (binary 1100)

Setting bit at position 1: changes it to 1110

Resetting bit at position 3: changes it to 0100

Algorithm:

1.Start the program.

2.Initialize an integer with a fixed value (e.g., 12).

3.Take input from the user for the bit position to be set.

4.Use OR operation with a left-shifted 1 to set that bit.

5.Take input from the user for the bit position to be reset.

6.Use AND with the negation of the left-shifted 1 to reset that bit.

7.Display the results.

8.End the program.

Conclusion: The program was successfully written and executed. It demonstrates how to set and reset individual bits in an integer using bitwise operations. This forms the basis for efficient memory-level data manipulation in systems programming and embedded applications.
