# Arbitrary-Precision-Calculator-APC-
This program implements arbitrary precision calculator that can perform addition, subtraction, multiplication, and division on large integers represented as doubly linked lists. The program takes two operands and operator as command-line arguments, processes the inputs,and  outputs  result while handling edge cases such as negative numbers and leading zeros.
# APC Project – Command Line Calculator in C

This project is a simple command-line calculator developed in C programming language.  
It performs basic arithmetic operations using separate source files for modular programming.

## Features
- Addition
- Subtraction
- Multiplication
- Division
- Argument validation
- Modular code structure
- Compiled using GCC

## Project Structure

├── main.c
├── main.h
├── addition.c
├── subtraction.c
├── multiplication.c
├── division.c
├── function.c


## Compilation

Use GCC compiler to build the project:

```bash
gcc *.c -o apc

Addition
./apc 14590 + 46573
Subtraction
./apc 45900 - 23456
Multiplication
./apc 6578 x 8986432
Division
./apc 67284294 / 478345
Sample Output
Result of 14590 + 46573 is : 61163
Result of 45900 - 23456 is : 22444
Result of 6578 x 8986432 is : 59112749696
Result of 67284294 / 478345 is : 140

Concepts Used
Functions
Header files
Command line arguments
Modular programming
GCC compilation
Basic arithmetic operations


Developed By
Abhijit Randave
