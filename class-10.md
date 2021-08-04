## Error Handling and debugging
JS handles one line at a time but when we call a function it gets stacked over the current task.

we prepare before we excute the code: create new scope, variables and values before we create functions and excute statements.

> search, use other browser, strip back and explain the code are different methods to help you with debugging.
### Error messages types
- error: generic error
- syntax eerror: syntax wasnt followed
- reference error: variable isnt declared/ within scope
- type error: error cant be coerced
- range error: numbers arent acceptable in range


** errors are solved by **
1. debugging the script to solve the error
- where is the problem.
- what is the problem.
 
2. handle error gracefully (not from the code writer)


** some console methods **
- console.info() (gives general info)
- console.warn() (used for warning)
- console.error() (hold errors)
- console.group() (groups messages together then you can expand them)
> it is closed with console.groupEnd()
- console.table() (objects or arrays)
- console.assert() (check whether a condition is met or not)


### try, catch and finally
- try: to specify the code that might throw an exception
- catch: catches the exception if occured in the try
- finally: will run either way (passed or failed)
