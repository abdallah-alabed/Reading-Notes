# HTML and Javascript
### What is HTML?
A language used to create webpages using tags and elemnts to identify the content type for the browser to properly display it for the user.

> we will be using HTML version 5.

### How can we view the webpage?
We need a web browser (google chrome for example) to connect you with the webserver (te place where webpages are stored) to display its content to you.

 > we can create a small analogy

  |User | Web browser | Web server|
  |-----|-----| -----|
  |you| Server in a resturant | food |

 ### Where is HTML used?
  in small and large website with the help of CSS and Javascrip to add an interactive and decorative manner.


### How does the internet (web) work?
1. The user connect to the web using an internet service provider, you type web address like "apple.com".
2. The computer contacts network of servers called domain name system (DNS) that will provide the IP address for the requested website.
3. The web server then sends the page you requested back to your web browser and display it.


### HTML structure
- opening HTML tag 
> Must be added, anything between the closing and ending tag must be written in HTML language.
- the body  
> Usually divided into header, main and footer , the main elements of the code is written in here.
- the head
>include the title tag in it which will display any written information in the browser window.


### What is a Tag?
tags are elemnts to specify the content type for the web browser

there is two types for tags:
- Normal tags
> require both opening and closing tag ex: 
![Normal tags](https://clearlydecoded.com/assets/images/posts/2017-09-04-anatomy-of-html-tag/simple-p-tag.png)

- self-closing tags
> Doesn't require a closing tag ex: 
![self closing tag](https://www.easytolearning.com/webroot/ck_files/files/html-image-tag.png)
  
While we mentioned the tags we must talk about the attributes.
#### Attributes 
an attriburte will give us extra information about the element's content.

### extra markups and skills in HTML
- !doctype : declare the HTML version for the web
- writting comments : comments will stay in the code and won't appear on the website. 

  >the tag used <!- the comment goes here ->
- IDs and Classes : both are used to identify elements which will make it easier to alternate objects while using CSS and JS with HTML, the difference is an ID cant be used more than once.
> ID tag ex: <p id='ID goes here' ... 

 > Class tag ex: <p class='Class goes here' ...

-  Elements: the position that the item will appear on the browser window
> block elements starts on the beginning of each line. (some tags like DIV groups elements in a block element form).

 > Inline elements starts at the end of the previous element.(some tags like SPAN groups elements in an Inline element form).

- Iframes: creates an area in the webpage to display other websites with the set specs.
> check ![This Link](https://www.w3schools.com/html/html_iframe.asp) for extra information.
- The <meta> tag allows you to supply all kinds of information about your web page. 
> (doesnt appear for the user).

### HTML5 layout
1. Header and footer
2. Navigation
3. Articles
4. Aside 
5. Sections
6. Heading groups
7. Divide 

### Things to take in consideration when creating a website
- The Audience
- Why people visit my website
- What Your Visitors are Trying to Achieve
- What Information Your Visitors Need
- How Of ten People Will Visit Your Site
- Site Maps
> ex: ![Site map](https://www.connectinternetsolutions.com/wp-content/uploads/2016/03/html-sitemap.png)
- Wireframes
> ex: ![Wireframe](https://www.comentum.com/images/wireframes-sample/ecommerce/home.png)

### The design 
when we start designing our webpage we need to pay attention for:
- organizing priorities
- similarity for equal items
- grouping 
- sizes, colors and style are key factors for attraction !
- brief, clear, consistent and decisive 
- clear context 
- interactive (links, videos, iframes etc...)

> example for a properly sorted website
 > ![webpage](https://images.websitebuilderexpert.com/wp-content/uploads/2015/12/effective-page-layout-design1.jpg) 





 ## What is Javascript?
 makes the pages more interactive! by modifing content, create rules to control the output and react to events done by the user.
 
 ### Steps to follow when writing a javascript script
 1. define what you want to achieve.
 2. divide into tasks 
 3. Code one-by-one
> ex: ![flowchart](https://jquery-plugins.net/image/plugin/flowchartjs-svg-flow-chart-diagrams-with-javascript.png)

### How does a browser see a webpage?
1. RECEIVE A PAGE (each page is a different document written in HTML)
2. CREATE A MODEL OF THE PAGE 
3. USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN (links CSS and JS to HTML in the code so everything appears and works as designed).

> models are objects represents physical things, where the objects can have a properties to tell us about the object itself, methods to perform tasks trigger events depend on user inputs. 


### Connecting JS and CSS to HTML externally
after creating the files for our css and js codes we link them using the following two tags respectively:

link rel="stylesheet" href="style.css">

script src="pop.js"> /script>