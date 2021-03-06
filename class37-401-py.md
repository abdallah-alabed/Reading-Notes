# ES6 Syntax and Feature Overview

1. declaring:
  - let: which allows for block-scoped variables which cannot be hoisted or redeclared.
  - const: which cannot be redeclared or reassigned, but is not immutable.
  - var: function scope and can be hoisted or redeclared.
2. Arrow functions:
  - syntax:  let func = (a) => {}
3. Template literals
  - syntax: let str = ` ``Release Date: ${date}`` `
4. Implicit returns
  - let func = (a, b, c) => a + b + c
5. Method definition shorthand:
  - let obj = { a(c, d) {},  b(e, f) {}}  
> instead of var obj = {  a: function (c, d) {},  b: function (e, f) {} }
6. Loop Iteration
  - for (let i of arr) {  console.log(i) }
7. Classes/constructor functions 
  -  Func.prototype.getSum = function () {    =>   getSum() {

# React
1. JSX: It is called JSX, and it is a syntax extension to JavaScript. We recommend using it with React to describe what the UI should look like.
> `const element = <h1> Hello, world!</h1>` \
> Specifying Children with JSX:  `Using <div> </div>` \
> JSX Represents Objects: `const element = <h1 className="greeting"> Hello, world!</h1>`

2. Rendering Elements: 
> ReactDOM.render(element, document.getElementById('root'));

3. Components and Props
  - Function and Class Components: function Welcome(props) { \
  - class Welcome extends React.Component { \
  - Rendedring it: const element = <Welcome name="Sara" />;ReactDOM.render(  element,  document.getElementById('root'));
 
4. State and Lifecycle
  - Converting a Function to a Class
    1. Create an ES6 class, with the same name, that extends React.Component.
    2. Add a single empty method to it called render().
    3. Move the body of the function into the render() method.
    4. Replace props with this.props in the render() body.
    5. Delete the remaining empty function declaration.

5. Handling Events
  -` <button onClick={activateLasers}>
  Activate Lasers
</button> `
  - ` <button onClick={(e) => this.deleteRow(id, e)}>Delete Row</button>`
  - `<button onClick={this.deleteRow.bind(this, id)}>Delete Row</button>`

# Tail Wind CSS
Using utility classes to build custom designs without writing CSS \
ex: ` <img class="h-12 w-12" src="/img/logo.svg" alt="ChitChat Logo">`

#### commands
1. padding : p
2. Flexbox: flex
3. max-width: max-w-sm
4. margin utilities: mx-auto
5. background color: bg-white
6. border radius: rounded-xl
7. box-shadow: shadow-lg
8. width and height: w and h
9. space-between: space-x-4
10. font size, text color, and font-weight: text-xl, text-black, font-medium 

#### Maintainability concerns
easily solved by extracting components, EX:

`<button class="btn">  Button </button>
  <style>  .btn {    @apply py-2 px-4 font-semibold rounded-lg shadow-lg;  } </style>`
  
# Next.js
> Next.js: The React Framework

1. Create a Next.js app: npx create-next-app nextjs-blog --use-npm --example "https://github.com/vercel/next-learn/tree/master/basics/learn-starter"
2. Run the development server: cd nextjs-blog
3. npm run dev
4. to use links: import Link from 'next/link'
5. css: <style jsx>{`  ???  `}</style>

