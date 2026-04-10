**Q1. What is a for loop in Python?**
Its used to repeat a block of code when we know exactly how many times we want to run it. This helps us avoid writing the same code agan and again.

**Q2. Explain range() with examples.**
It generates a sequance of numbers, like `range(5)` gives 0,1,2,3,4 because it starts from 0 by default and doesn't include the last value. 

**Q3. Can we iterate over strings using for loop?**
Yes we can definitly loop through strings, and it will return each charecters one by one.

**Q4. Difference between for loop and while loop?**
A for loop is used when you know exactly how many times to repeat something. The notes mainly focus on 'for', but generally 'while' is used when we don't know the exact fixed times to repeat.

**Q5. What are break and continue statements?**
The document mentions that `break` is used to stop the loop immediatly. (Continue isn't in the notes, but it basically skips the current step and moves to the next one).

Summary of learnings:
* A loop is basically used to execute the same block of code multiple times so we don't rewrite it.
* The `for` loop is best when we already know how many times we need to repeat the code.
* The `range()` function generates numbers but it always starts from 0 and skips the last number.
* We can use a step value in range to control the increment or decrement, which is usefull for reverse loops.
* We can use the `break` keyword to stop a loop right away if needed.