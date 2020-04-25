# What the Flexbox?!

Flexbox sure is tricky to learn. Get a grasp on flexbox while learning both the fundamentals and real world applications. Created by Wes Bos (wesbos.com)

Initializes FlexBox inline container
  *display: inline-flex;*

Initializes FlexBox block container
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
Items are packed toward the start of the flex-direction (AKA main axis)
  *justify-content: flex-start;*

Items are packed toward the end of the flex-direction
  *justify-content: flex-end;*

Items are centered along the line
  *justify-content: center;*

Items are evenly distributed in the line; first item is on the start line, last item on the end line
  *justify-content: space-between;*

Items are evenly distributed in the line with equal space around them.
  *justify-content: space-around;*

Items are distributed so that the spacing between any two items
  *justify-content: space-evenly;*

---
Align-items defines the default behavior for how flex items are laid out along the cross axis on the current line. Think of it as the justify-content version for the cross-axis.

Stretch to fill the container (default)
  *align-items: stretch;*

Items are placed at the start of the cross axis.
  *align-items: flex-start*

Items are placed at the end of the cross axis
  *align-items: flex-end;*

Items are centered in the cross-axis
  *align-items: center;*

items are aligned such as their baselines align
  *align-items: baseline;*

---
Align-content aligns a flex container’s lines within when there is extra space in the cross-axis, similar to how justify-content aligns individual items within the main-axis.

Needs flex-wrap: wrap;

flex-start / start: items packed to the start of the container. 

flex-end / end: items packed to the end of the container. 

center: items centered in the container

space-between: items evenly distributed

space-around: items evenly distributed with equal space around each line

space-around: items evenly distributed with equal space around each line

stretch (default): lines stretch to take up the remaining space

---
Align-self

This allows the default alignment (or the one specified by align-items) to be overridden for individual flex items.




Takes width of 1 and evenly distributes it among all items in container
  *flex: 1;*