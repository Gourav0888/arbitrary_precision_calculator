# Arbitrary Precision Calculator

A C-based calculator that performs mathematical operations on extremely large numbers using **doubly linked lists**. Designed to handle numbers beyond standard data type limits.

## Overview

This project demonstrates **arbitrary-precision arithmetic** (also known as big-number arithmetic) by storing each digit of large numbers in a linked list. It supports:

- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

## Features

- Handles numbers of any size (limited only by memory)
- Works with positive integers as well negative integers
- Command-line interface
- Implemented using **Doubly Linked Lists** as Abstract Data Type (ADT)

## Technologies Used

- **Language**: C  
- **Concepts**:  
  - Data Structures (Doubly Linked List)  
  - Dynamic Memory Allocation  
  - Operator Simulation  
  - Manual Carry/Borrow Handling  

## Usage

1. Compile using `make`.
2. Then `./res.exe <operand1> <operator> <operand2>`.
3. Can provide any big number.

## Applications

- Cryptography (handling large keys)
- Scientific Computation
- Mathematical Constants (e.g., Pi to millions of digits)
   
