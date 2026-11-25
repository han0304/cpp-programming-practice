# Week 10 – String Manipulation and Bitwise Operations

This week focuses on string manipulation and bitwise operations through LeetCode problems. The exercises introduce alternating string merging, XOR operations, and counting set bits in an integer.

## Exercises

### 1. LeetCode 1768 – Merge Strings Alternately (`week10-1.cpp`)

Implements a function that merges two strings by alternating characters from each string. The first version uses C-style strings and dynamically allocated memory.

**Key Concepts:**
- C-style strings
- String length with `strlen()`
- Dynamic memory allocation with `malloc()`
- Character arrays and indexing

### 2. LeetCode 1768 – Merge Strings Alternately (C++ Version) (`week10-2.cpp`)

Reimplements the alternating string merge problem using C++ `string`. The solution appends characters from both input strings to a result string.

**Key Concepts:**
- C++ `string`
- String length with `length()`
- String concatenation with `+=`
- Comparison between C-style strings and C++ strings

### 3. LeetCode 136 – Single Number (`week10-3.cpp`)

Uses the XOR (`^`) operator to find the number that appears only once in an integer array.

**Key Concepts:**
- Bitwise XOR
- Integer arrays
- Bitwise operations and their properties

### 4. LeetCode 191 – Number of 1 Bits (`week10-4.cpp`)

Implements a function to count the number of set bits (bits equal to 1) in an unsigned integer. The solution repeatedly checks the remainder when dividing by 2 and then reduces the number.

**Key Concepts:**
- Binary representation
- Modulo operator (`%`)
- Integer division
- Counting set bits

## Learning Outcomes

- Understand how to manipulate strings using both C-style strings and C++ `string`.
- Apply dynamic memory allocation to store string results.
- Use bitwise XOR to solve array problems.
- Understand how to examine binary digits and count set bits.
- Practice applying programming concepts to LeetCode problems.
