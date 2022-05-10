# Combining Selectors

We can combine selectors together if we want to use one style property for all of them.

For example, we used the same _font-family_ for all of the text elements. This is repetitive. A better way of doing this is to combine the selectors together and use the same _font-famliy_ for all of them.

_CODE_:

h1, h2, h3, h4, p, li  
{  
font-family: sans-serif;  
}

We can combine selectors in another way.

_CODE_:

footer p  
{  
 fon-size: 26px;  
}

That way we select only the _p_ element that is inside the _footer_ element.

Although this worked just fine, it's not a good practice to use this way of combining selectors.
A better practice would be to use _IDs_ and _Classes_.
