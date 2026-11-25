# Week 03 – Palindromes and Mirrored Strings

This week focuses on checking whether a string is a palindrome or a mirrored string. The exercises gradually introduce string comparison, character mapping, and functions to classify different types of strings.

## Exercises

### 1. `week03-1.cpp` – Basic String Output
- Reads strings from standard input until EOF.
- Prints each input string followed by a message stating that it is not a palindrome.
- Introduces basic string input and output.

**Key Concepts:**
- Character arrays
- `scanf()` and `printf()`
- Reading input until EOF

### 2. `week03-2.cpp` – Palindrome Checker
- Reads a string and calculates its length using `strlen()`.
- Compares characters from opposite ends of the string.
- Determines whether the string is a palindrome.

**Key Concepts:**
- String length with `strlen()`
- Character comparison
- `for` loops
- Conditional statements

### 3. `week03-3.cpp` – Mirrored Character Mapping
- Defines a `mirrored_char()` function.
- Uses conditional statements to map individual characters to their mirrored equivalents.
- Returns a space for characters without a defined mirrored equivalent.
- The `main()` function is currently empty.

**Key Concepts:**
- User-defined functions
- Character mapping
- `if-else` statements
- Return values

### 4. `week03-4.cpp` – Mirrored String Checker
- Defines a `mirrored_char()` function using two character arrays as a mapping table.
- Compares each character with the mirrored equivalent of the character at the opposite end of the string.
- Determines whether the input is a mirrored string.

**Key Concepts:**
- Character mapping with arrays
- String traversal
- Character comparison
- Functions

### 5. `week03-5.cpp` – Palindrome and Mirrored String Classification
- Implements separate functions to check whether a string is a palindrome and a mirrored string.
- Combines both results to classify the input into four categories:
  - Not a palindrome
  - Regular palindrome
  - Mirrored string
  - Mirrored palindrome
- Processes multiple input strings until EOF.

**Key Concepts:**
- Function decomposition
- String manipulation
- Combining multiple conditions
- Boolean-style return values
- Input processing until EOF

## Learning Outcomes

After completing these exercises, I practiced:

- Reading and processing strings in C++.
- Using `strlen()` to determine string length.
- Checking palindromes through character comparisons.
- Implementing character-mapping functions.
- Using arrays to represent character relationships.
- Breaking a problem into reusable functions.
- Combining multiple checks to classify strings.
