Assignment 4 – Task 1
Module 5: Files, Exceptions, and Errors in Python
✅ Task 1: Read a File and Handle Errors

Problem Statement:
    Write a Python program that:
      Opens and reads a text file named sample.txt.
      Prints its content line by line.
      Handles errors gracefully if the file does not exist.
    How the Program Works
      The program first creates a file called sample.txt and writes some sample text into it.
      Then, it reopens the file in read mode and prints the content line by line.
      If the file does not exist, it shows an error message instead of crashing.
    Features Implemented
      File Writing: Adds some sample text into sample.txt.
      File Reading: Reads the file line by line using a loop.
      Error Handling: Uses try-except to handle FileNotFoundError.

Expected Output
If the file exists:
          Reading the file
            line1: this is a sample text file
            line2: it contains multiple lines
            
If the file does not exist:
          Error: The file 'sample.txt' was not found.



Python File Handling - Task 2


📌 Features
  - Takes user input and writes it to a file.
  - Appends more data without overwriting the previous content.
  - Displays the final file content after all operations.
  - Uses proper file handling methods (`with open()`).
  - Ensures data is preserved even after multiple operations.

📜 How It Works
  1. Prompts the user to **enter some text** to write to `output.txt`.
  2. Saves the text in **write mode (`w`)**.
  3. Prompts the user for **additional text** and appends it in **append mode (`a`)**.
  4. Reads and prints the **final content of the file**.

---

## ✅ Example Output
Enter the text to write in the file: hello
Data successfully written to output.txt

Enter additional text to append: world
Data successfully appended

Final content for output.txt:
hello
world
