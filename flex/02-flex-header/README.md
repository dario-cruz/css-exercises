# A Basic Header

Use flexbox rules to create this very common webpage header style. The benefit to using flex here is that everything should be _flexible_. Check out the two screenshots below to get an idea of how it should scale with your screen. Besides flex rules, you'll also want to add some rules for margin and padding. (Hint: `ul`s have some default margin/padding that you will need to deal with.)

## Desired Outcome

narrow:
![narrow](./desired-outcome-narrow.png)

wide: 
![wide](./desired-outcome-wide.png)

### Self Check
- There is space between all items and the edge of the header (specific px amount doesn't matter here).
Yes, the space is present and accounted for. 
- Logo is centered vertically and horizontally.
Yes, made use of the align-self and justify-content values to center the content. 
- list-items are horizontal, and are centered vertically inside the header.
Yes, added an align-self tag for centering. 
- left-links and right-links are pushed all the way to the left and right, and stay at the edge of the header when the page is resized.
Yep, took advantage of the flex-end and flex-start. 
- Your solution does not use floats, inline-block, or absolute positioning.
Nope, just plain old flexbox.