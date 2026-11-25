# Week 04 – Pointers and Character Frequency

This week introduces pointers in C++, including memory addresses, pointer assignment, and dereferencing. The final exercise applies arrays and character processing to check whether all letters of the English alphabet appear in the input.

## Exercises

### 1. `week04-1.cpp` – Variables and Memory Addresses
- Declares three integer variables (`a`, `b`, and `c`) with values 10, 20, and 30.
- Prints each variable's value and attempts to print its memory address.
- Introduces the relationship between variables and their memory locations.

**Key Concepts:**
- Variable declaration and initialization
- Memory addresses
- Address-of operator (`&`)
- `printf()` output

### 2. `week04-2.cpp` – Pointer Basics
- Declares an integer variable `a` and initializes it to 10.
- Uses a pointer `p` to store the address of `a`.
- Uses the dereference operator (`*`) to access the value stored at the address.

**Key Concepts:**
- Pointer declaration (`int *p`)
- Address-of operator (`&`)
- Dereference operator (`*`)
- Pointer initialization

### 3. `week04-3.cpp` – Pointer Assignment
- Declares two integer variables, `a` and `b`, with values 10 and 20.
- Creates two pointers, `p1` and `p2`, pointing to the respective variables.
- Assigns `p2` to `p1`, making both pointers point to `b`.
- Prints the values accessed through both pointers before and after the assignment.

**Key Concepts:**
- Multiple pointers
- Pointer assignment
- Dereferencing pointers
- Changing the memory location a pointer refers to

### 4. `week04-4.cpp` – Modifying Variables Through Pointers
- Declares two integer variables, `a` and `b`.
- Uses pointer `p1` to modify the value of `a` to 99.
- Assigns `p1` to `p2`, so both pointers refer to the same variable.
- Uses `p2` to change the value of `a` to 77.

**Key Concepts:**
- Modifying values through pointers
- Pointer aliasing
- Pointer assignment
- Dereferencing pointers

### 5. `week04-5.cpp` – Checking Alphabet Coverage
- Uses an integer array `used[26]` to count the occurrences of English letters.
- Reads characters from standard input until EOF.
- Counts uppercase and lowercase letters as the same character.
- Checks whether every letter from A to Z has appeared at least once.
- Prints `Yes` if all 26 letters appear; otherwise, prints `No`.

**Key Concepts:**
- Arrays
- Character processing
- ASCII character ranges
- Case-insensitive counting
- Loops and conditional statements

## Learning Outcomes

After completing these exercises, I practiced:

- Understanding how variables are stored in memory.
- Accessing memory addresses with the address-of operator.
- Declaring and initializing pointers.
- Reading and modifying values through pointers.
- Understanding how multiple pointers can refer to the same variable.
- Using arrays to track character frequencies.
- Processing input until EOF.
- Checking whether all letters of the alphabet are present.
