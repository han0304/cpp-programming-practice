# Week 05 – Arrays, Pointers, and Integer Algorithms

This week explores the relationship between arrays and pointers, numeric palindrome checking, and removing duplicate elements from a sorted array.

## Exercises

### 1. `week05-1.cpp` – Array and Pointer Access
- Declares an integer array containing values from 1 to 10.
- Creates a pointer `p` that points to the first element of the array.
- Uses array indexing (`a[i]`) and pointer indexing (`p[i]`) to access and print the same elements.
- Demonstrates that array elements can also be accessed through a pointer.

**Key Concepts:**
- Array declaration and initialization
- Pointers and arrays
- Pointer indexing
- Array element access
- `for` loops

### 2. `week05-2.cpp` – Integer Palindrome Checker
- Defines an `isPalindrome()` function to determine whether an integer is a palindrome.
- Returns `false` immediately if the input is negative.
- Reverses the integer by repeatedly extracting its last digit using `% 10`.
- Reconstructs the reversed number using multiplication by 10 and addition.
- Compares the reversed number with the original number.

**Key Concepts:**
- User-defined functions
- Integer arithmetic
- Modulo operator (`%`)
- Integer division (`/`)
- `while` loops
- Boolean return values

### 3. `week05-3.cpp` – Remove Duplicates from a Sorted Array
- Defines a `removeDuplicates()` function that removes duplicate elements from a sorted array.
- Uses two indices to compare consecutive elements and store unique values in the original array.
- Updates the array in place rather than creating another array.
- Returns the number of unique elements.
- Uses the returned length to print the remaining unique elements.

**Key Concepts:**
- Arrays and pointers
- Array modification in place
- Two-index technique
- Duplicate detection
- Function return values
- Working with sorted arrays

## Learning Outcomes

After completing these exercises, I practiced:

- Understanding the relationship between arrays and pointers.
- Accessing array elements through pointer indexing.
- Implementing an integer palindrome checker.
- Using arithmetic operations to reverse an integer.
- Removing duplicate elements from a sorted array.
- Modifying arrays in place.
- Using functions to process arrays and return results.
