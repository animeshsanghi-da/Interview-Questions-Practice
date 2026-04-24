**Q1. What is file handling in Python?**
It is the process of working with files in Python, allowing us to read data from them or write new data into them.

**Q2. What is difference between r and w mode?**
The 'r' mode is used strictly to read an existing file, whereas the 'w' mode is used to write data into a file.

**Q3. Why do we use with open()?**
We use the 'with' statement because it ensures that the file is automatically closed after we are done working with it, keeping our code clean and safe.

**Q4. How to read file line by line?**
We can read a file line by line by opening it and using a simple 'for' loop (e.g., for line in f:).

**Q5. What happens if file is not closed?**
If a file is not closed, it can cause memory issues or lead to data not saving correctly. That is why using the 'with' statement is highly recommended to automate the closing process.

**Summary:**
* File handling helps us interact with files using different modes like read ('r'), write ('w'), and append ('a').
* Using the 'with open()' statement is the most efficient way to handle files as it safely closes them automatically once the block of code executes.
