# 📋 C Programming Interview Preparation Checklist

> **Instructions:** Check off topics as you master them. Click the boxes in VS Code Preview mode (Ctrl+Shift+V) to toggle.

---

## 🎯 Priority Legend
- 🔴 **Critical** - Must know (90% of interviews ask these)
- 🟡 **Important** - Frequently asked
- 🟢 **Good to Know** - Gives you an edge

---

## 🧠 1. Core Basics

### Data Types & Variables
- [ ] 🔴 `int`, `float`, `char`, `double` - sizes and ranges
- [ ] 🔴 Variable declaration and initialization
- [ ] 🟡 Constants (`const` and `#define`)
- [ ] 🟡 Type casting (implicit and explicit)

### Operators
- [ ] 🔴 Arithmetic operators (`+`, `-`, `*`, `/`, `%`)
- [ ] 🔴 Relational operators (`==`, `!=`, `<`, `>`, `<=`, `>=`)
- [ ] 🔴 Logical operators (`&&`, `||`, `!`)
- [ ] 🟡 Bitwise operators (`&`, `|`, `^`, `~`, `<<`, `>>`)
- [ ] 🟡 Ternary operator (`? :`)
- [ ] 🟡 Operator precedence

### Input/Output
- [ ] 🔴 `printf` with format specifiers
- [ ] 🔴 `scanf` with `&` operator
- [ ] 🟡 All format specifiers (`%d`, `%f`, `%c`, `%s`, `%p`, `%x`)

### Control Flow
- [ ] 🔴 `if`, `else if`, `else` statements
- [ ] 🔴 `switch-case` (with `break` importance)
- [ ] 🔴 `for` loop
- [ ] 🔴 `while` loop
- [ ] 🔴 `do-while` loop
- [ ] 🟡 `break` and `continue`
- [ ] 🟡 Nested loops

---

## 🔁 2. Functions

### Basics
- [ ] 🔴 Function declaration vs definition
- [ ] 🔴 Function parameters and return types
- [ ] 🔴 `void` functions

### Parameter Passing
- [ ] 🔴 Call by Value - concept and example
- [ ] 🔴 Call by Reference - using pointers
- [ ] 🔴 Difference between call by value and reference

### Recursion (Very Important!)
- [ ] 🔴 Understand recursion concept
- [ ] 🔴 Base case importance
- [ ] 🔴 Write factorial using recursion
- [ ] 🔴 Write Fibonacci using recursion
- [ ] 🟡 Recursion vs iteration - pros/cons
- [ ] 🟡 Stack overflow in recursion

---

## 📦 3. Arrays

### 1D Arrays
- [ ] 🔴 Declaration and initialization
- [ ] 🔴 Accessing elements (0-based indexing)
- [ ] 🔴 Array traversal using loops
- [ ] 🔴 Passing arrays to functions

### 2D Arrays
- [ ] 🔴 Declaration and initialization
- [ ] 🔴 Accessing elements `arr[i][j]`
- [ ] 🟡 Matrix operations (addition, multiplication)

### Searching
- [ ] 🔴 Linear Search - write code
- [ ] 🔴 Binary Search - write code (sorted array only!)
- [ ] 🟡 Time complexity of both

### Sorting
- [ ] 🔴 Bubble Sort - write code
- [ ] 🟡 Selection Sort - write code
- [ ] 🟡 Insertion Sort - write code
- [ ] 🟢 Time complexity of sorting algorithms

---

## 🔤 4. Strings

### Basics
- [ ] 🔴 Strings are char arrays with `\0`
- [ ] 🔴 String declaration methods
- [ ] 🔴 String input/output (`%s`, `fgets`)

### String Functions
- [ ] 🔴 `strlen()` - get length
- [ ] 🔴 `strcpy()` - copy string
- [ ] 🔴 `strcmp()` - compare strings
- [ ] 🟡 `strcat()` - concatenate
- [ ] 🟡 `strchr()` - find character

### Manual String Operations
- [ ] 🔴 Reverse a string manually
- [ ] 🔴 Check if string is palindrome
- [ ] 🟡 Check if two strings are anagrams
- [ ] 🟡 Remove duplicates from string
- [ ] 🟡 Count vowels/consonants

---

## 📍 5. Pointers (CRITICAL - Master This!)

### Basics
- [ ] 🔴 What is a pointer?
- [ ] 🔴 `&` (address-of) operator
- [ ] 🔴 `*` (dereference) operator
- [ ] 🔴 Pointer declaration and initialization

### Operations
- [ ] 🔴 Pointer arithmetic (`p++`, `p--`, `p+n`)
- [ ] 🔴 Pointers and arrays relationship
- [ ] 🔴 `arr[i]` is same as `*(arr + i)`

### Advanced Pointers
- [ ] 🔴 Difference between `arr` and `&arr`
- [ ] 🔴 Pointer to pointer (`int **pp`)
- [ ] 🟡 Function pointers - declaration and usage
- [ ] 🟡 Array of function pointers

### Common Interview Questions
- [ ] 🔴 Swap two numbers using pointers
- [ ] 🔴 Pass array to function using pointer
- [ ] 🔴 Return multiple values using pointers

---

## 🧱 6. Memory Management

### Stack vs Heap
- [ ] 🔴 Difference between stack and heap
- [ ] 🔴 When to use each

### Dynamic Allocation
- [ ] 🔴 `malloc()` - syntax and usage
- [ ] 🔴 `calloc()` - syntax and usage
- [ ] 🔴 `free()` - importance and usage
- [ ] 🔴 **Difference: `malloc` vs `calloc`**
- [ ] 🟡 `realloc()` - resizing memory

### Memory Issues
- [ ] 🔴 Memory leaks - what and how to prevent
- [ ] 🔴 Dangling pointer - what and how to prevent
- [ ] 🔴 Wild pointer - what and how to prevent
- [ ] 🔴 NULL pointer - proper usage
- [ ] 🔴 Segmentation fault - common causes

---

## 🧩 7. Structures & Unions

### Structures
- [ ] 🔴 `struct` declaration and usage
- [ ] 🔴 Accessing members (`.` operator)
- [ ] 🔴 `typedef` with structures
- [ ] 🟡 Nested structures
- [ ] 🟡 Array of structures
- [ ] 🟡 Pointer to structure (`->` operator)

### Unions
- [ ] 🔴 `union` declaration
- [ ] 🔴 **Difference: `struct` vs `union`**
- [ ] 🟡 Memory sharing in unions

---

## 📂 8. File Handling

- [ ] 🟡 `fopen()` and file modes (`r`, `w`, `a`)
- [ ] 🟡 `fclose()` - always close files
- [ ] 🟡 `fprintf()` and `fscanf()`
- [ ] 🟡 `fgets()` and `fputs()`
- [ ] 🟢 `fread()` and `fwrite()` - binary files

---

## ⚙️ 9. Preprocessor & Macros

- [ ] 🟡 `#include` - system vs user headers
- [ ] 🟡 `#define` - constants and macros
- [ ] 🟡 Macros with parameters
- [ ] 🟡 **Difference: Macros vs Functions**
- [ ] 🟢 Conditional compilation (`#ifdef`, `#ifndef`)

---

## 🔗 10. Storage Classes

- [ ] 🟡 `auto` - default local variable
- [ ] 🔴 `static` - persistent value, limited scope
- [ ] 🟡 `extern` - global variable declaration
- [ ] 🟢 `register` - request CPU register

---

## 🧮 11. Bit Manipulation

- [ ] 🟡 Bitwise AND, OR, XOR, NOT
- [ ] 🔴 Check if number is even/odd using `& 1`
- [ ] 🟡 Swap two numbers without temp (XOR)
- [ ] 🟡 Set, clear, toggle a bit
- [ ] 🟢 Count set bits in a number

---

## 💡 12. Key Differences (Memorize These!)

- [ ] 🔴 `malloc` vs `calloc`
- [ ] 🔴 `struct` vs `union`
- [ ] 🔴 Array vs Pointer
- [ ] 🔴 Call by Value vs Call by Reference
- [ ] 🔴 `++i` vs `i++`
- [ ] 🟡 `while` vs `do-while`
- [ ] 🟡 `break` vs `continue`
- [ ] 🟡 `=` vs `==`
- [ ] 🟡 `#define` vs `const`
- [ ] 🟢 `gets` vs `fgets`

---

## 💻 13. Coding Practice (Must Practice!)

### Basic Programs
- [ ] 🔴 Check if number is prime
- [ ] 🔴 Check if number is palindrome
- [ ] 🔴 Calculate factorial (iterative)
- [ ] 🔴 Calculate factorial (recursive)
- [ ] 🔴 Print Fibonacci series

### Array Programs
- [ ] 🔴 Reverse an array
- [ ] 🔴 Find max/min in array
- [ ] 🔴 Linear search implementation
- [ ] 🔴 Binary search implementation
- [ ] 🟡 Remove duplicates from array

### String Programs
- [ ] 🔴 Reverse a string
- [ ] 🔴 Check palindrome string
- [ ] 🟡 Check anagram
- [ ] 🟡 String compression
- [ ] 🟡 Count word frequency

### Pointer Programs
- [ ] 🔴 Swap using pointers
- [ ] 🔴 Array manipulation with pointers
- [ ] 🟡 Dynamic array creation

### Matrix Programs
- [ ] 🟡 Matrix addition
- [ ] 🟡 Matrix multiplication
- [ ] 🟡 Transpose of matrix

---

## 🔥 14. Advanced Topics (For Top Companies)

- [ ] 🟢 Function pointers with callbacks
- [ ] 🟢 Command-line arguments (`argc`, `argv`)
- [ ] 🟢 Memory alignment and padding
- [ ] 🟢 `volatile` keyword
- [ ] 🟢 `const` pointer vs pointer to `const`

---

## 🎯 15. Interview Day Checklist

### Before Interview
- [ ] Revise pointer concepts
- [ ] Revise key differences
- [ ] Practice 5 coding problems on paper
- [ ] Review common output-based questions

### During Interview
- [ ] Think before coding
- [ ] Handle edge cases
- [ ] Explain your approach
- [ ] Write clean, readable code

---

## 📊 Progress Tracker

| Section | Status |
|---------|--------|
| Core Basics | ⬜ Not Started |
| Functions | ⬜ Not Started |
| Arrays | ⬜ Not Started |
| Strings | ⬜ Not Started |
| Pointers | ⬜ Not Started |
| Memory Management | ⬜ Not Started |
| Structures & Unions | ⬜ Not Started |
| File Handling | ⬜ Not Started |
| Preprocessor | ⬜ Not Started |
| Storage Classes | ⬜ Not Started |
| Bit Manipulation | ⬜ Not Started |
| Key Differences | ⬜ Not Started |
| Coding Practice | ⬜ Not Started |
| Advanced Topics | ⬜ Not Started |

**Legend:** ⬜ Not Started | 🟨 In Progress | ✅ Completed

---

**💪 You've got this! Check off each item as you master it!**

*Tip: Focus on 🔴 Critical items first if you're short on time!*
