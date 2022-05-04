# Styling Hyberlinks.

### We can use style _Hyberlinks_ by using the _a_ elements.

For exmaple:

_CODE_:

a  
{  
 color: red;  
}

- Here we set the color of _Hyberlink_ to red, **but using this method is not a good practice.**

### A better way of styling _Hyberlinks_ would be to use Pseudo-classes.

For example:

_CODE_:

a:link  
{  
 color: red;  
}

- Here we set the color of the _Hyberlink_ to red.
- This way we make sure that only valid links, links with _href_ elements, will be set to red.

_CODE_:

a:visited  
{  
color: green;  
}

- Here we set the color of the visited _Hyberlink_ to green.

_CODE_:

a:hover  
{  
color: blue;  
}

- Here we set the color of the _Hyberlink_ when we hover over it to blue.

_CODE_:

a:active  
{  
backgroud-color: black;  
}

- Here we set the backgroud-color of any active _Hyberlink_ to black.

### It's important to style the _a_ elements in the following order:

1. _a:link{}_
2. _a:visited{}_
3. _a:hover{}_
4. _a:active{}_
