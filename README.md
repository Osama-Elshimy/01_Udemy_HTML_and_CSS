# Pseudo-classes.

### We can use Pseudo-classes to pick some exact child elements of some parent elements.

For exmaple:

_CODE_:

li:first-child {  
 color: red;  
}

- Here we set the color of the first element of any _li_ element to red.

_CODE_:
li:last-child {  
 color: red;  
}

- Here we set the color of the last element of any _li_ element to red.

_CODE_:
li:nth-child(3) {  
 color: red;  
}

- Here we set the color of the 3rd element of any _li_ element to red.
