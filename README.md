# 🔍 Equality Check Program (C++)

This C++ program takes **three integer inputs** from the user and checks whether all three values are equal.

---
## 🧠 Objective
To practice conditional statements and logical operators in C++.

---

## 📜 Problem Statement
> Write a C++ program that reads three integers and prints **"Equal"** if all three are the same, otherwise prints **"Not Equal"**.

---

## 💻 Code Overview
The program:
1. Prompts the user to enter three integers (`x`, `y`, `z`).
2. Uses the logical **AND (`&&`)** operator to check equality:
   ```cpp
   if (x == y && y == z)
       cout << "Equal";
   else
       cout << "Not Equal";
