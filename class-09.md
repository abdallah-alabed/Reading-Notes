## forms
im HTML forms are elements that allow you to collect information from visitors to your site.
> famous example of forms are google search bar.

**we can conotrol forms by:**
- adding texts (text, password, text input area).
> <input type='text' ...>
- creating choices (checkbox, dropdown box, radio button).
> <input type='radio' ...>
- submitting forms (submit button, image buttons).
> <input type='submit' ...>
- uploading files. 
> <input type='file' ...>


> multiple select box: ![boxes](https://i.stack.imgur.com/8Sigc.jpg)


**Syntax**

form action=''   method=''

/form
  
  > action: the URL of the page that will recieve the form information.
  
  > method: get (send to the URL in action)/ post (sent in HTTP Headers).


## styling
- bullet point styles (life-style-type in css).
- images for bullets (life-style-type: url('')).
- marker position (life-style-position)
- table properties (width, padding, text transform, letter spacing, :hover)
- borderempty cells (empty-cells:show)
- cell gaps: (border-collapse: collapse;)
- cursor style: (cursor:text)


## Events
how to create events:
1. select elements
2. specify the event
3. call the code


#### DOM event handlers
**syntax**: element.onevent= functionname

### DOM event listeners (deal with one or more functions)
**syntax**: element.addEventlistener('event', functionName [, Boolean]) ;

### changing default behavior of an element
- preventDefault(): stop the default action.
- stopPropagation(): stops the event.

### event types
- W3C DOM EVENTS
- HTM LS EVENTS (submit, input, change)
- SOM EVENTS (Touchend, orientationchange)

### FOCUS & BLUR EVENTS
- focus: When an element gains focus, the focus event fires for that DOM node. 
- blur: When an element loses focus, the b 1 ur event fires for that DOM node. 
- focus-in: Same as focus (see above but not supported in Firefox at time of writing) 
- focusout: Same as b 1 ur (see above but not supported in Firefox at time of writing) 

### where do events occur?
- screen
- page
- client
