# 🧮 Arbitrary Precision Calculator (C Language)

## 📌 Overview

This project is a command-line based **Arbitrary Precision Calculator** developed in the C programming language. It performs arithmetic operations on **very large integers** that exceed the limits of standard data types like `int`, `long`, or `long long`.

The application implements big number arithmetic **without using any external libraries**, relying instead on **dynamic data structures** and custom algorithms for complete accuracy.

<p align="center">
  <img src="https://github.com/user-attachments/assets/2e8a58f0-1a8a-40af-86d4-2b6e607320e4" width="100%" />
</p>


## 🎯 Objective

The primary objective of this project is to:

* Understand arbitrary precision arithmetic
* Implement dynamic data structures in C
* Develop custom arithmetic algorithms
* Build a practical calculator for unlimited digit numbers
* Master pointer manipulation and memory management

---

## ✨ Key Features

### ➤ Unlimited Digit Support

* Handles hundreds or thousands of digits
* No upper limit on number size (memory dependent)
* Complete accuracy for all operations

### ➤ Complete Arithmetic Operations

* ➕ **Addition** of large numbers
* ➖ **Subtraction** with borrow handling
* ✖️ **Multiplication** using digit-by-digit method
* ➤ **Division** with remainder calculation

### ➤ Pure C Implementation

* No external big integer libraries
* Custom linked list storage
* Manual algorithm implementation

---

## ⚙️ Working Principle

1. User provides two large numbers and operator as input
2. Numbers are parsed and stored digit-by-digit in dynamic structures
3. Appropriate arithmetic algorithm is selected
4. Custom algorithms perform calculation (like manual methods)
5. Result is reconstructed and displayed with full precision


---

## 🛠️ Technologies Used

* **Programming Language:** C
* **Data Structures:** Linked Lists, Dynamic Arrays
* **Core Concepts:** Pointer Arithmetic, Memory Management
* **Compiler:** GCC
* **Platform:** Linux / Windows / macOS

---

## 📂 Project Structure

Arbitrary_Precision_Calculator/
│
├── main.c # Entry point and command parsing
├── add.c # Addition operation implementation
├── sub.c # Subtraction operation implementation
├── mul.c # Multiplication operation implementation
├── div.c # Division operation implementation
├── apc.h # Header definitions and structures
└── README.md # Documentation


---

## 🚀 How to Run

1. Open terminal in project directory
2. Compile the program:

   ```
   gcc *.c 
   ```

3. Run with operands and operator:

   ```bash
   ./a.out 12345678901234567890 + 98765432109876543210
   
   # Example outputs:
   # Result: 111111111011111111100
   ```

---

## 💡 Applications

* Scientific computing with large numbers
* Cryptography algorithms
* Financial calculations (big decimals)
* Educational tool for algorithm learning
* Embedded systems requiring precise math

---

## ⚠️ Limitations

* Integer arithmetic only (no floating point)
* Single operator per execution
* Performance degrades with very large numbers
* CLI-based interface only

---

## 📌 Conclusion

This project demonstrates how to implement arbitrary precision arithmetic from scratch using pure C. It provides hands-on experience with dynamic memory management, pointer manipulation, and complex algorithm design while solving a practical real-world problem.
