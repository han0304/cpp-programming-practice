# Week 12 – Bitwise Operations, Sliding Window, and Frequency Sorting

This week focuses on bitwise operations and string-related algorithms through practical exercises and LeetCode problems. The topics include XOR-based swapping, counting vowels within a substring, and sorting characters according to their frequency.

## Exercises

### 1. XOR – Swapping Two Variables (`week12-1.cpp`)

Demonstrates how to swap the values of two integer variables using the XOR (`^=`) operator without using an additional temporary variable.

**Key Concepts:**
- Bitwise XOR
- Compound assignment operator (`^=`)
- Variable swapping
- Bitwise operations

### 2. LeetCode 1456 – Maximum Number of Vowels in a Substring of Given Length (`week12-2.cpp`)

Implements a function that finds the maximum number of vowels in any substring of length `k`. The solution uses a cumulative vowel count array to calculate the number of vowels within each window.

**Key Concepts:**
- C-style strings
- `strlen()` for string length
- Prefix sums
- Sliding window concept
- Character comparison
- Array-based counting

### 3. LeetCode 451 – Sort Characters By Frequency (`week12-3.cpp`)

Implements a function that sorts characters in a string according to their frequency. The solution counts uppercase letters, lowercase letters, and digits using a frequency array, then sorts the frequencies and corresponding characters before rebuilding the string.

**Key Concepts:**
- Character frequency counting
- ASCII character ranges
- Arrays and lookup tables
- Nested loops
- Sorting
- In-place string modification

## Learning Outcomes

- Understand how XOR operations can be used to swap variable values.
- Apply cumulative counting to solve substring problems.
- Understand the sliding window concept for fixed-length substring calculations.
- Count character frequencies using arrays.
- Apply sorting techniques to organize data by frequency.
- Practice solving algorithmic problems using C-style strings and arrays.
