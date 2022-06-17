# An entire page!

Flexbox is useful for laying out entire pages as well as the smaller components we've already been working with. For this exercise, we're leaving you with a little more work to do, with some things you may not have encountered yet. It's perfectly acceptable to google things you're unsure of!

### Hints
- You may want to search something like `CSS remove list bullets`.  We've done this for you in previous examples, but not here. Yay learning.
- Finding out how to style links in CSS might help you get rid of that pesky underline decoration...
- We've added `height: 100vh` to the `body`... this makes the body exactly the same height as the viewport. To stick the footer to the bottom you will need to use flex and change the direction to column.

## Desired Outcome
![desired outcome](./desired-outcome.png)

### Self Check

- The header is at the top of the page, the footer is at the bottom, and they stay in place if you resize your screen.
- The header and footer have padding.
Did not make use of padding for the header and footer. Actually had to remove global margin and padding in the CSS file to achieve the desired effect for the header and footer. Both the header and footer have margin added to them for spacing. Links in the header and footer also have gap applied to achieve the needed spacing.

- The links in the header and footer are pushed to either side.
Yes, the links on each side of the page in the header and footer had justify properties applied to them. 

- There is space between the links in the header and footer.
Yes, applied a gap to the links in the header and footer to achieve the desired effect.

- The footer has a light gray background (`#eeeeee`).
Yes, the background property is applied to the footer of the page.

- The logo, input and buttons are centered in the screen.
Yep, made the the content class display as flex in column mode and then applied an align-items and justify-content with center to get the needed effect.

- The buttons have an appropriate amount of padding.
Yes, padding is applied to the buttons.

- There is space between the logo, input and buttons.
Yes, there is spacing between all of them.
