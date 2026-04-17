**Q1. What is type conversion in Python?**
It means changing one data type into another, like converting text into a number or a number into a float.

**Q2. What is the difference between implicit and explicit conversion?**
Implicit conversion is done automatically by Python, while explicit conversion is done manually by the programmer using specific functions.

**Q3. Why do we use int() with input()?**
Because the `input()` function always takes data as a string, so we need `int()` to convert that text into a number to perform mathematical calculations.

**Q4. Can we convert string "abc" to int? What happens?**
No, we cannot convert alphabetical characters to an integer. It will throw an error because "abc" does not contain valid numbers.

**Q5. When does Python perform automatic conversion?**
Python performs automatic (implicit) conversion during mathematical operations with mixed types, like adding an integer and a float, resulting in a float to prevent any data loss.

Summary of learnings:
* Type conversion is the process of changing one data type into another to avoid errors during operations.
* Implicit conversion happens automatically by Python, while explicit conversion requires functions like `int()`, `float()`, and `str()`.
* Converting user input is essential when you need to perform mathematical calculations on the received data.
