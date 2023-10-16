# Other assorted useful CSS properties

## Position
- static, the elemt is positioned according to the normal flow of the document
- relative - the element is positioned according to the normal flow of the document and then offset relative to itself based on the values of top, right, bottm and left. The offset does not affect the position of any other elements; thus space given for the element in the page layout is the same as if position were static.
- absolute, the element is removed from the normal document flow, and no space is created for the element in the page layout. It is positioned relative to its closest postiioned ancestor, if any; othersie, it is placed relative to the initial containing block. Its final postions is determind by the vaules of top, right, bottom and left.
- fixed, the element is removed from the normal document flow, and no space is created for the element in the page layout. it is positioned relative to the initial containing block established by the viewport, expect when one of its ancestors has a transform, persective or filter property set to something.

## Transform
