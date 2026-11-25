# Week 06 – File I/O and Sorting Algorithms

This week introduces file input and output operations, followed by different approaches to sorting arrays in C++.

## Exercises

### 1. `week06-1.cpp` – Writing Data to a File
- Uses `fopen()` to open `output.txt` in write mode (`w+`).
- Uses `fprintf()` to write "Hello World" into the file.
- Demonstrates how to redirect formatted output from the console to a file.

**Key Concepts:**
- File pointers (`FILE *`)
- `fopen()`
- File opening modes
- `fprintf()`
- File output

### 2. `week06-2.cpp` – Reading Data from a File
- Opens `output.txt` in read mode (`r`).
- Uses a character array as a buffer to store the input.
- Uses `fscanf()` to read two strings from the file.
- Prints the retrieved strings to the console.

**Key Concepts:**
- File input
- `fopen()`
- `fscanf()`
- Character arrays
- Reading data from files

### 3. `week06-3.cpp` – Bubble Sort
- Initializes an integer array with ten unsorted values.
- Uses nested `for` loops to compare adjacent elements.
- Swaps two elements when they are in the wrong order.
- Repeats the comparison process to sort the array in ascending order.
- Prints the array after each outer loop iteration.

**Key Concepts:**
- Bubble sort
- Nested loops
- Element comparison
- Swapping values
- Array sorting

### 4. `week06-4.cpp` – Sorting with `qsort()`
- Includes `stdlib.h` to use the standard C library sorting function `qsort()`.
- Defines a comparison function that compares two integer values.
- Passes the array, number of elements, element size, and comparison function to `qsort()`.
- Prints the sorted array.

**Key Concepts:**
- `qsort()`
- Comparison functions
- Pointers (`const void *`)
- Type casting
- Standard library functions

### 5. `week06-5.cpp` – Sorting with `std::sort()`
- Includes the C++ `<algorithm>` library.
- Uses `std::sort(a, a + 10)` to sort the first ten elements of an integer array.
- Prints the sorted array in ascending order.

**Key Concepts:**
- `<algorithm>`
- `std::sort()`
- Array iterators and pointer ranges
- Standard C++ library

## Learning Outcomes

After completing these exercises, I practiced:

- Opening and working with files using `fopen()`.
- Writing data to files with `fprintf()`.
- Reading data from files with `fscanf()`.
- Understanding file pointers and file access modes.
- Implementing bubble sort with nested loops.
- Using `qsort()` with a custom comparison function.
- Sorting arrays with C++ `std::sort()`.
- Comparing manual sorting algorithms with standard library functions.
