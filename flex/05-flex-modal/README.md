# A common 'modal' style
This one is another very common pattern on the web. The solution to this one is _simple_... but it might not be immediately obvious to you. You'll need to edit the HTML a bit to get everything where it needs to be.

### A hint
Depending on how you approach this one, you might need to revisit the `flex-shrink` property to keep a flex item from getting smashed.

## Desired outcome

![desired outcome](./desired-outcome.png)

### Self Check

- The blue icon is aligned to the left.
Yes, it is but, with the code implemintation the circle background is wrapped for some rreason, will have to investigate further to see what the issue is. 

- There is equal space on either side of the icon (the gaps between the icon and the edge of the card, and the icon and the text, are the same).
Yes, there is equal space between the icon.

- There is padding around the edge of the modal.
Yes, padding has been established.

- The header, text, and buttons are aligned with each other.
More or less yes they are. 

- The header is bold and a slightly larger text-size than the text.
Yes, modified the font-weight property so that the text is bold. 

- The close button is vertically aligned with the header, and aligned in the top-right of the card.
Yes, it is. I Used div grouping to accomplish this task.
