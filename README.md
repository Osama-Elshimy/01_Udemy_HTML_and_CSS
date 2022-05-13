# Box Sizing: Border-box

### The default box model:

- **With CSS**:  
  box-sizing: content-box;
- **Final element width** = right border + right padding + width + left padding + left border
- **Final element height** = top border + top padding + height + bottom padding + bottom border

---

### The box model with box sizing: border-box:

- **With CSS**:  
  box-sizing: border-box;
- **Final element width** = width of the element
- **Final element height** = height of the element
- When we add padding to the element, that padding will be substracted from the area of the content.

**_For example_**:  
If we set the width of the element to 300px, and the padding right to 50px and the padding left to 50px, then the width of the content area will be 200px (the width of the element - the padding right - the padding left)

---

**NOTE**:  
The box-sizing property does not get inherited, therefore if we want apply the box-sizing property to the whole page, we should use it in the universal selector and **NOT** in the body tag.
