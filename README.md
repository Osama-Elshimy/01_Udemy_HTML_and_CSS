# CSS Theory#4: Types of Boxes.

## Block-Level Elements:

- Elements are formatted visually as blocks.
- Elements occupy **100% of parent element's width**, No matter the content.
- Elements are **stacked vertically** by default, one after another.
- Box-model applies as shown

**Default Block-Level Elements**: body, main, header, footer, section, nav, aside, div, h1-h6, p, ul, ol, li

**With CSS**: display: block

## Inline Elements:

- Elements occupy only the space **necessary for it's content**
- Cause **no line-breaks** after or before the element
- Box model applies in a different way: **heights and width don't apply**
- Paddings and margins are applied **only horizontally** (left and right)

**Default Inline Elements**: a, img, strong, em, button

**With CSS**: display: inline

## Inline-Block Elements:

- Looks like inline from the **outside**, behaves like block-level on the **inside**
- Occupy only content's space
- Cause no line-breaks
- Box-model applies as shown

**With CSS**: display: inline-block

### NOTE: _img_ elements act like inline-block elements
