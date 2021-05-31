# LAYOUT
Key word to describe and learn about layout.
- Block elements (```<h1><ul><li><p>```)
- In-line elements(```<img><b><i>```)

position elements :
- Normal flow:The element is positioned according to the normal flow of the document. The top, right, bottom, left, and z-index properties have no effect. This is the default value.(MDN)
- Relative :
The element is positioned according to the normal flow of the document, and then offset relative to itself based on the values of top, right, bottom, and left. The offset does not affect the position of any other elements; thus, the space given for the element in the page layout is the same as if position were static.
- Absolute :
The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to its closest positioned ancestor, if any; otherwise, it is placed relative to the initial containing block. Its final position is determined by the values of top, right, bottom, and left.

- fixied:
The element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to the initial containing block .
## z-index properity 
specifies the stack order of an element.

An element with greater stack order is always in front of an element with a lower stack order.

### float properity 
places an element on the left or right side of its container, allowing text and inline elements to wrap around it.
### clear properity
property specifies what elements can float beside the cleared element and on which side.

## LAYOUT :
- fixid width layouts:
Fixed layouts use exact pixel widths which means that the size of the page components will be the same for all resolutions.
- liquid layouts:most of the page components in a Liquid page layout adjust to the user’s screen size by using percentage widths rather than fixed pixel widths. (Fluid layouts )

### Layout Grids
![](https://th.bing.com/th/id/Re550cdf216a4f557ca18e08e7c0c514d?rik=NaitfJnGS5xZ6A&pid=ImgRaw)

