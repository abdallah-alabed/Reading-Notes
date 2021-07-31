### what is an object?
creates a group together a set of variables and functions to create a model of a something you would recognize from the real world'

> in objects variables are called properties and functions are called methods.
> in objects we cant have two keys with the same name.

> keys can be arrays,strings,numbers,boolean or other objects.

### how to create objects?
**using literal notations**
var hotel={
name: 'love'

.....
}
> the object is stored in a variable and its content inside the curly braces.

to access an obect use the following method:
> var hotelname=hotel.name

you can access the object but not its method using square brackets.
> var hotelname=hotel['name']

### document object model
tells the browser how to create a model of an HTML page and how javascript can access and update the page.

#### DOM tree
a cross-platform and language-independent interface that treats an XML or HTML document as a tree structure wherein each node is an object representing a part of the document.

![DOM](https://1.bp.blogspot.com/-c1VhRCxc4ds/X5938GT76GI/AAAAAAAACFU/yzX7a1aIinIR_i4sy7dSIW9z8Q5mgX72QCLcBGAsYHQ/s732/dom1.png)

- document node:represents the entire page.
- element node: describe the structure of an HTML page.
- attribute node: Once you access an element, there are specific JavaScript methods and properties to read or change that element's attributes.
-text node: Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.

#### accessing elements 
- getElementByld('id')
- querySelector( 'css selector')
- getElementsByClassName('class')
- getElementsByTagName('tagname')
- querySelectorAll('css selector')

### adding and removing HTML content
- DOM manipulation

- inner HTML property
