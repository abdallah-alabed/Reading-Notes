## Tables
a set of data represented in a grid format.

**the syntax with example**

![example](https://slideplayer.com/13283077/79/images/slide_1.jpg)
- *tr* indicates the start of each row

- *td* indicates the start of a cell

- *th* indicates the table heading

*we can make a coloumn/row span using **colspan=** , **rowspan=** *

**For long tables**
- thead : table headings
- tbody : data inside it 
- tfoot : display data in the end (summation, etc..)

**other properties we can alter in our tables**
- background
- border
- width
- spacing


## DOM
#### creating an object
syntax:  var object name= {properties : values}

**editing property**
> change value

objectname.property = 'new value';

> delete property

delete objectname.property;

>clear value

objectname.property='';

> when we are inside the object we dont use the object name we use ***this***

##### Array is a special type of objects!
> each index is a property and its value is a value.

### built-in objects
1. BROWSER OBJECT MODEL: creates a model of the browser tab or window.
>example: window. open ()
2. DOCUMENT OBJECT MODEL: creates a model of the current web page. 
> example: document . getElementByld()
3. GLOBAL JAVASCRIPT OBJECTS: doesnt for models just a group of individual objects. 
> example: toUpperCase()

### data types
- string 
- boolean
- number
- undefined
- null
- object (arrays, functions)

### some object types
- math objects
- date objects
