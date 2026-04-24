**Q1. What is exception handling?**
It is a technique used to handle runtime errors gracefully so that our program doesn't crash abruptly.

**Q2. What is purpose of try block?**
The try block contains the code that we suspect might cause an error during execution.

**Q3. What does finally do?**
The finally block contains code that will always run at the end, regardless of whether an error occurred or not.

**Q4. How do you handle specific errors?**
We can catch specific errors by defining the error name next to the except keyword, like 'except ValueError:'.

**Q5. What happens if exception is not handled?**
If we do not handle it, the program will crash immediately and display a system error message.

**Summary**:
* Exception handling protects our code from crashing. 
* We test code in the 'try' block, catch issues in the 'except' block, run successful code in 'else', and execute mandatory cleanup in 'finally'.
