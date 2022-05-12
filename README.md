# Clearing Floats.

#### The easiest way to clear floats is to add a new empty element after all the floated elements and use the _clear_ property in CSS on that element and set it to _both_, but this is not the best way to fix the problem.

#### It's not a good practice to add unnecessary elements all around the HTML file.

**CODE**:  
{  
 clear: both;  
}

#### A better solution is to add a _pseudo-element_ to the end of the container of the element that contains the problem. And then use the _clear_ property on that _pseudo-element_

**CODE**:  
.clearfix::after {  
content: " ";  
 clear: both;  
 display: block;  
}
