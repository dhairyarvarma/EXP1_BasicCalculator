# C++ Experiment 1: Hello World & Simple Calculator

---

## 🎯 Objective

This experiment demonstrates:
1. A basic C++ program that prints “Hello, World!” to the console.
2. A simple calculator program that performs basic arithmetic using user inputs.

---

## 🛠 Tools Used

- Visual Studio Code (VS Code)

---

## 🎓 Learning Goals

- Familiarize with C++ program structure.
- Use `#include` to bring in standard libraries.
- Practice taking input/output using `cin` and `cout`.
- Perform basic arithmetic operations in C++.
- Understand key C++ syntax elements like `main()`, `return`, data types, and comments.

---

## 📘 Background

C++ is an extension of the C language, offering a mix of procedural and object-oriented programming features. Known for its performance and control over system resources, it is widely used in software, embedded systems, and game development.

### 💡 Why C++ Over C?

- Supports **OOP** (classes, inheritance, etc.) for better modularity and reusability.
- Enables **function and operator overloading**.
- Offers the **Standard Template Library (STL)** with containers and algorithms.
- Provides better **type safety** and **encapsulation**.
- Includes **constructors**, **destructors**, and **namespaces** for better resource handling and code organization.

---

## 🧱 C++ Program Basics

- `#include <iostream>` is used to include standard input-output functionality.
- `using namespace std;` avoids the need to prefix with `std::`.
- The `main()` function is the entry point.
- `cout` displays output; `cin` captures input.
- Control structures (`if`, `else`) allow branching.
- Arithmetic operators (`+`, `-`, `*`, `/`) are used for calculations.
- Use `int`, `float`, `double` depending on the required data precision.
- Comments (`//`) explain logic and improve readability.

---

## 🔍 Program Breakdown

### 🔸 Part 1: Hello World

A minimal C++ program that prints “Hello, World!” to the console — ideal for beginners to understand syntax and structure.

### 🔸 Part 2: Calculator

Takes two numbers from the user and performs:
- Addition
- Subtraction
- Multiplication
- Division (with division-by-zero check)

Displays results after each operation.

---

## 🧠 Key Concepts

- Libraries: `#include <iostream>`
- Namespace usage: `using namespace std;`
- Input/Output: `cin`, `cout`
- Data Types: `float`, `int`, `double`
- Operators: `+`, `-`, `*`, `/`
- Conditional logic: `if`, `else`
- Functions: `main()`, `return 0;`
- Code comments: `//`

---

## 📤 Sample Output

Hello World
Enter num1 : 7.5
Enter num_2 : 2.5
Sum :10
Difference :5
Product :18.75
Division :3


---

## 📝 Notes

- Always validate division to prevent dividing by zero.
- `float` allows decimal numbers; `double` offers higher precision.
- Use consistent indentation and comments to make code cleaner and easier to understand.
- Compilation steps:
  - Compile using: `g++ filename.cpp -o output`
  - Run using: `./output` (Linux/Mac) or `output.exe` (Windows)
- Good commenting is helpful for both learning and collaboration.

---

## ✅ Summary

This experiment helps beginners get hands-on with C++ fundamentals through two simple yet essential programs. It reinforces understanding of input/output, arithmetic operations, control structures, and clean coding practices.
