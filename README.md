# Sum of Two Integers Without Using + or -

This C++ program returns the sum of two integers without using the `+` or `-` operators, utilizing bitwise operations instead.

## 🧠 Problem Statement

Given two integers `a` and `b`, return the sum of the two integers without using the `+` and `-` operators.



## 🛠️ Approach

The solution uses:
- Bitwise XOR (`^`) to calculate the sum without carry
- Bitwise AND (`&`) to calculate the carry
- Left shift (`<<`) to move the carry to the correct position
- A loop until the carry is zero

## ✅ Constraints
-1000 <= a, b <= 1000


## 💻 Prerequisites
- Visual Studio 2022 or any ide of your choice
- C++ compiler (e.g., g++, clang++, MSVC)
- Basic knowledge of compiling and running C++ code via terminal or IDE

## 🚀 How to Run

1. **Clone or download** this repository.
2. Open a terminal in the project directory.
3. Compile the file:

```bash
g++ sum_without_plus_minus.cpp -o sum
