# Week 08 – Vectors and Basic Problem Solving

This week introduces the C++ `vector` container and its dynamic resizing capabilities. It also includes a LeetCode problem involving cumulative sums and a nested-loop exercise for printing a pyramid pattern.

## Exercises

### 1. `week08-1.cpp` – Creating and Accessing a Vector
- Includes the `<vector>` library.
- Declares a vector of integers with an initial size of three.
- Assigns values to individual elements using index notation.
- Uses a `for` loop to print all elements.

**Key Concepts:**
- C++ `vector`
- Vector declaration
- Index-based element access
- `for` loops

### 2. `week08-2.cpp` – Initializing a Vector from an Array
- Declares an integer array containing ten elements.
- Creates a vector using the array's beginning and ending pointer range.
- Uses a `for` loop to print the vector elements.

**Key Concepts:**
- Arrays and vectors
- Vector range constructor
- Pointers and memory ranges
- Element access

### 3. `week08-3.cpp` – Dynamic Vector Resizing with `push_back()`
- Creates a vector with an initial size of two.
- Assigns values to its first two elements.
- Uses `size()` to display the current number of elements.
- Appends additional values using `push_back()`.
- Prints the updated vector and its new size.

**Key Concepts:**
- Dynamic arrays
- `push_back()`
- `size()`
- Vector resizing
- Iterating through containers

### 4. `week08-4.cpp` – LeetCode 1480: Running Sum of 1D Array
- Implements the `runningSum()` function.
- Creates a result vector with the same size as the input vector.
- Sets the first result element equal to the first input element.
- Calculates each subsequent element by adding the current input value to the previous cumulative sum.
- Returns the resulting vector.

**Key Concepts:**
- LeetCode problem solving
- C++ vectors
- Prefix sums
- Array traversal
- Function return values

### 5. `week08-5.cpp` – Printing a Pyramid Pattern
- Reads an integer `n` representing the number of rows.
- Uses nested `for` loops to print spaces and asterisks.
- Calculates the number of spaces as `n - i`.
- Calculates the number of asterisks as `2 * i - 1`.
- Prints a centered pyramid pattern.

**Key Concepts:**
- Nested loops
- Pattern printing
- Loop-based calculations
- Formatted console output

## Learning Outcomes

After completing these exercises, I practiced:

- Creating and accessing C++ vectors.
- Initializing vectors from existing arrays.
- Dynamically expanding vectors with `push_back()`.
- Using `size()` to retrieve the number of elements.
- Solving cumulative sum problems using prefix sums.
- Applying vectors to algorithmic problem solving.
- Using nested loops to generate geometric patterns.
