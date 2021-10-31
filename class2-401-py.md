# Tests in Python
Unit tests are some pieces of code to exercise the input, the output and the behaviour of your code. You can write them anytime you want.
But Test-Driven Development is a strategy to think (and write!) tests first.

#### what you should know:
- The greatest advantage about TDD is to craft the software design first
- Your code will be more reliable: after a change you can run your tests and be in peace


#  __ __name__ __ == “__ __main__ __”
Python interpreter reads source file and if it is running that module (the source file) as the main program,
it sets the special __name__ variable to have a value “__main__”

#### Advantages : 
- Every Python module has it’s __name__ defined and if this is ‘__main__’, 
it implies that the module is being run standalone by the user and we can do corresponding appropriate actions.
- If you import this script as a module in another script, the __name__ is set to the name of the script/module.
- Python files can act as either reusable modules, or as standalone programs.
- if __ __name__ __ == “__ __main__ __”: is used to execute some code only if the file was run directly, and not imported.

# Reccursion
The process in which a function calls itself directly or indirectly is called recursion and the corresponding function is called as recursive function
example on recursive function: f(n) = n + f(n-1)
> Note: If the base case is not reached or not defined, then the stack overflow problem may arise.
