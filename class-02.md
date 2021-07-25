## Most used tags
1. header <h1 .... 
> h1 to h6, the higher the number the smaller and thinner the line is.
2. paragraph <p ...
3. bold <b .... 
4. italic <i ....
5. superscript <sup ... 
6. subscript <sub ....
> ![scripts](https://www.benlcollins.com/wp-content/uploads/2020/11/superscriptInGoogleSheets-1.jpg)
7. breaks <br  / or <hr   /
> used to create a vertical line break or horizontal line break respectively


## Tags used in symmantic markup
1. strong <strong ...
> content has strong importance.
2. emphasis <em ...
> emphasis that subtly changes the meaning of a sentence.
3. quotitaion <q ...
4. Abbreviations and acronyms <acronym title...   <abbr title ...
> to specify the full terms.
5. citation <cite ...
> referencing a piece of work.
6. definition  <dfn ...
> indicate the defining instance of a new term.

## What is a CSS?
adding style and customization to the HTML elements.

![CSS_syntax](https://thewebtext.com/wp-content/uploads/selector.gif)

**can be added to HTML in 3 ways**

1. inline 
2. internal linking
> create a section in the head called style
   
   > where we mention the tags we want to modify and do the mods.

3. external linking
> after creating all the customizations on a separate css file we link it using the following command <link href="css/styles.css" type="text/css" rel="stylesheet" ...>


![css](https://www.bitdegree.org/learn/storage/media/images/8c4493d3-110c-4a95-8b70-7626ce2d2f4e.o.jpg) 

## CSS Selectors
selectors are patterns used to select the element(s) you want to style.

a quick table to sum the selectors
![](https://i.pinimg.com/originals/bc/97/96/bc97965579512f8a6d2303934f599c65.png)
## Why  we use external CSS more frequent?
- use the principle of separation of concerns, this makes both the HTML and CSS easier to read and more organized
- can be used on multiple HTML documents without having to rewrite CSS declarations
- allow global styles to be changed easily, new changes will be applied to the entire HTML document the external CSS is used on

## javascript basics
- statements
> series of instructions that a computer can follow one-by-one.
- comments
> extra data in the code that doesnt appear to the user.
- variables
> stores data can be either boolean, arithmatic or string.




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

