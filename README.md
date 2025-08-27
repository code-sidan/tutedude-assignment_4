# Python File Handling - Assignment 4
This repository contains solutions for Module 5: Files, Exceptions, and Errors in Python.  
It includes two tasks:
1. Read a file and handle errors  
2. Write and append data to a file

Task 1: Read a File and Handle Errors

Problem Statement
- Open and read a text file named `sample.txt`.
- Print its content line by line.
- Handle errors gracefully if the file does not exist.

Features
- Uses `try-except` for error handling.
- Displays content line by line.
- Shows a proper error message if the file is missing.

Example Output
If the file exists:
    line 1: This is a sample text file
    line 2: It contains multiple lines
    
If the file does not exist:
    Error: The file 'sample.txt' was not found.

---
Task 2: Write and Append Data to a Fill

Problem Statement
- Take user input and **write it to `output.txt`.
- Append additional data to the same file.
- Read and display the **final content** of the file.

 Features
- First input is written using write mode (`w`).
- Additional text is appended using append mode (`a`).
- Displays the complete file content after all operations.

Example Output

Enter the text to write in the file: hello
Data successfully written to output.txt

Enter additional text to append: world
Data successfully appended

Final content for output.txt:
hello
world

