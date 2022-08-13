# Python-Processing-Strings-and-Integers
Launch PyCharm and open the WordCount project.

Launch PyCharm.

In the Welcome to PyCharm window, select Open.

The Open File or Project dialog box is shown.

Beneath the 094021Data folder, expand Processing Simple Data Types, and select the WordCount project folder.

Select OK.

The project is loaded and configured to use the Python 3.9 interpreter.

In the Project pane, expand the WordCount folder if necessary, and double-click wordcount.py to show the source code in the editor.

Prompt the user to enter the size of the input file.

Place the insertion point at the end of line 10 and press Enter twice to prepare to enter a new statement.

Write the code as shown to get the size of the input file from the user.

Line 12 creates a variable named size_query and assigns it to the input that the user enters in response to the prompt.
Line 13 converts the user's string input to an integer so math operations can be performed on it.
Line 14 multiplies the user's input to convert it to bytes (assuming one million bytes per megabyte).
Print the user's file size in bytes with string concatenation and interpolation.

Write the code as shown to print the file size in bytes.

Line 15 creates a new response variable which contains a string literal concatenated with the value in size_query, concatenated with another string literal. A { } placeholder value is included in the string.
Line 16 prints the response string, replacing the { } placeholder with the size_in_bytes value.
Why can you concatenate size_query, but must use interpolation for size_in_bytes? Click here for answer.

Run the code to test your conversion operation and print statements.

Right-click the source code window and select Run 'wordcount'.

In the Run wordcount pane, enter any value at the first prompt.

When you're prompted to enter a file size in megabytes, enter 1

Verify that your program converted your file size and formatted your string properly.

In the Run window, close the wordcount tab.

Select Terminate to confirm you want to terminate the program
