# Introduction 
In todays' read we will talk about three main topics that are commonly used in the javascript code.

## Operators
The table below will mention the most common operators: 

|Operators | Function | Example
|-----|-----|-----|
| Assignment operators | Assign values to variables |X=6|
|Comparison operators|compare two variables and outputs a boolean answer| X==Z |
|Arithmatic operator|apply a calculation to a variable and outputs a numarical answer|x++ means x=x+1|
|Bitwise Operator|apply bit to bit calculaion and outputs a (0 or 1) in each bit | X & Z |
|Logical operator| used with boolean values| X && Z|
|String operator|add two strings next to each other as a string| console.log('X' + 'Z') |
|Conditional Operator| sets a condition and the result depend on the condition validity|condition ? X : Z|

> For more examples and explainations [Read Here ](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators#relational_operators)


## Loops
loops are used for recurring events until the condition is broken so we can save time in our code writing.

The most common loops used are:
### * For loop
Used when we have a know the count number (number of times we repeat the action).

**Synatax**

for ([initialExpression]; [conditionExpression]; [incrementExpression]) {statement}

**Example**

> for (var i=0 ; i<=5 ; i++){console.log("The count is " + i)}

### * While loop

Used with undefined count number.

**Synatax**

while (condition) {statement}

**Example**

>var i=0 

> while (i<=5){i++} 


### ***Another statement used with loops***
### Labeled statement
A label provides a statement with an identifier that lets you refer to it elsewhere in your program.

**Synatax**

label : statement

### Break statement
Use the break statement to terminate a loop, switch, or in conjunction with a labeled statement.

**Synatax**

break;     **OR**

break [label];

### Continue statement
The continue statement can be used to restart a while, do-while, for, or label statement.

**Synatax**

continue [label];



