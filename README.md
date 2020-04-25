# What the Flexbox?!

Flexbox sure is tricky to learn. Get a grasp on flexbox while learning both the fundamentals and real world applications. Created by Wes Bos (wesbos.com)

Initializes FlexBox inline container.
*display: inline-flex;*

Initializes FlexBox block container.
*display: flex;*

Children inherit display flex from container

### Flex Direction
Vertical rows (Default setting)         |||
Main axis   ->  X axis (Left to Right)
Cross axis  ->  Y axis (Top to Bottom)
  *flex-direction: row;*

Stacks columns vertically               ===
Main axis   ->  Y axis (Top to Bottom)
Cross axis   ->  X axis (Left to Right)
  *flex-direction: column* 

Vertical rows reversed                  |||
Main axis   ->  X axis (Right to Left)
Cross axis  ->  Y axis (Top to Bottom)
  *flex-direction: row-reverse;*

Stacks columns vertically reversed      ===
Main axis   ->  Y axis (Bottom to Top)
Cross axis   ->  X axis (Left to Right)
  *flex-direction: column-reverse* 

### Flex Wrap
Wraps all items across container from Left to right and Top to bottom
  *flex-wrap: wrap*
Wraps all items across container from Right to left and Bottom to top
  *flex-wrap: wrap-reverse*
Default
  *flex-wrap: nowrap*

Flex Ordering
Creates an order ranking for this item
Default for all items is order: 0
  *order: 1*

### Alignment and centering
Items are packed toward the start of the flex-direction
  *justify-content: flex-start;*

Items are packed toward the end of the flex-direction
  *justify-content: flex-end;*

Items are centered along the line
  *justify-content: center;*

Items are evenly distributed in the line; first item is on the start line, last item on the end line
  *justify-content: space-between;*

Items are evenly distributed in the line with equal space around them.
  *justify-content: space-around;*


Takes width of 1 and evenly distributes it among all items in container
  *flex: 1;*