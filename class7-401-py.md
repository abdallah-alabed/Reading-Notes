# Scope in Python
The concept of scope rules how variables and names are looked up in your code and how variables are visibled.
The scope of a name or variable depends on the place in your code where you create that variable.
The Python scope concept is generally presented using a rule known as the LEGB rule.(Local, Enclosing, Global, and Built-in scopes.)

**why scope?**:

Using Python scope will help you avoid or minimize bugs related to name collision as well as bad use of global names across your programs.

**tyoes of scope**:
- Global scope: The names that you define in this scope are available to all your code.
- Local scope: The names that you define in this scope are only available or visible to the code within the scope.

## LEGB Rule for Python Scope
- Local scope: is the code block or body of any Python function or lambda expression. This Python scope contains the names that you define inside the function. 
These names will only be visible from the code of the function. 

- Enclosing scope: is a special scope that only exists for nested functions. If the local scope is an inner or nested function,
then the enclosing scope is the scope of the outer or enclosing function. 
The names in the enclosing scope are visible from the code of the inner and enclosing functions.

- Global scope: is the top-most scope in a Python program, script, or module. This Python scope contains all of the names that you define at the top level of a program or a module.
Names in this Python scope are visible from everywhere in your code.

- Built-in scope: is a special Python scope that’s created or loaded whenever you run a script or open an interactive session. 
This scope contains names such as keywords, functions, exceptions, and other attributes that are built into Python. 
Names in this Python scope are also available from everywhere in your code. It’s automatically loaded by Python when you run a program or script.

**Functions: The Local Scope**:
The local scope or function scope is a Python scope created at function calls. Every time you call a function, you’re also creating a new local scope. 

**Nested Functions: The Enclosing Scope**:
It takes the form of the local scope of any enclosing function’s local scopes.
Names that you define in the enclosing Python scope are commonly known as nonlocal names. 

**Modules: The Global Scope**:
Whenever you assign a value to a name in Python, one of two things can happen:
- You create a new name
- You update an existing name

**Modifying the Behavior of a Python Scope**:
 two keywords to modify the scope are:
- global
- nonlocal








 
