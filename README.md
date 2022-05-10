# Pseudo-elements.

### Pseudo-elements don't exist in HTML files, but we can still select and style in CSS.

- An example for pseudo-elements is the first letter or a paragraph of the first line of a paragraph

- Pseudo-elements are selected using two colons

**CODE**:

h1::first-letter {  
font-style: normal;  
}

In the previous code, we selected the first letter of the _h1_ element and set chaged it's font style

**NOTE**: If we set a value of _margin_ or _padding_ to a negative value, then the element will move to the opposite direction
