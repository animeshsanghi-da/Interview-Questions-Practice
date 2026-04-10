**Q1. What is the purpose of input() in Python?**
It basically takes data from the user while the program is currently running.

**Q2. Why do we use int() with input()?**
Because input() always gives a string by default, so we have to use int() to convert it if we want a number.

**Q3. What type does input() return by default?**
By default it returns the data as a string.

**Q4. How can you take multiple inputs from user?**
You can just write the input() code multiple times and store them in different variables.

**Q5. What happens if user enters text but int() is used?**
The doc mentions we convert to int() specifically for number inputs. So if you enter text, it won't work and will cause an error in the program.

Summary of learnings:
* We use the `input()` function when we want the program to wait for the user to type something.
* The value entered is always stored as a string type.
* To take numbers or decimals, we need to convert them using `int()` or `float()`.