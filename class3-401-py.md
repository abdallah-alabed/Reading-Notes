## Reading and Writing Files in Python
**What is a file**:set of bytes used to store data. 

Files are composed of three main parts:
- Header
- Data
- End of file (EOF)

**What is a file path**:a string that represents the location of a file.

Path is broken into three major parts:
- Folder Path
- File Name
- Extension

**Character Encodings**:a translation from byte data to human readable characters. (ASCII)

**Opening and closing files** is done using the commands:
- open(FILENAME) // with open(FILENAME,r) as reader:
- clode(FILENAME)

Character	Meaning:
- 'r'	Open for reading (default)
- 'w'	Open for writing, truncating (overwriting) the file first
- 'rb' or 'wb'	Open in binary mode (read/write using byte data) (buffer reader)

**Reading and Writing Opened Files**:
- .read(size=-1)	This reads from the file based on the number of size bytes. If no argument is passed or None or -1 is passed, then the entire file is read.
- .readline(size=-1)	This reads at most size number of characters from the line. This continues to the end of the line and then wraps back around. If no argument is passed or None or -1 is passed, then the entire line (or rest of the line) is read.
- .readlines()	This reads the remaining lines from the file object and returns them as a list.



## Exceptions versus Syntax Errors
- Syntax errors occur when the parser detects an incorrect statement
- exception error occurs whenever syntactically correct Python code results in an error.

> We can use raise to throw an exception if a condition occurs. The statement can be complemented with a custom exception.

**The AssertionError Exception**
**The try and except Block: Handling Exceptions**

- raise allows you to throw an exception at any time.
- assert enables you to verify if a certain condition is met and throw an exception if it isn’t.
- In the try clause, all statements are executed until an exception is encountered.
- except is used to catch and handle the exception(s) that are encountered in the try clause.
- else lets you code sections that should run only when no exceptions are encountered in the try clause.
- finally enables you to execute sections of code that should always run, with or without any previously encountered exceptions.
