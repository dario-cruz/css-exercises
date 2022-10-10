# The Holy Grail of Layout

In this last flexbox exercise you're going to recreate an incredibly common website layout. It is so common that it is often called the [Holy Grail](https://www.google.com/search?q=holy+grail+layout&tbm=isch&sclient=img) layout... and with flexbox it is actually pretty easy to pull off.

As with the previous exercise, we've left a little more for you to do.

### Hints
- You will need to change the flex-direction to push the footer down.
- You will need to add some divs as containers to get things to line up correctly.
- `flex-wrap` will help get the cards aligned correctly.
-  Make sure you define how much space the cards should take up, in order for `flex-wrap` to work as intended.

## Desired outcome

![desired outcome](./desired-outcome.png)

The number of cards lined up in that section will change based on the width of your screen, so don't stress about getting _exactly_ a 2x3 or 3x2 grid.

On a smaller screen it will look like this:

![smaller](./desired-outcome-smaller.png)

### Self Check
- The header text is size 32px and weight 900.

Adjusted the font-size and font-wieght accordingly. Ye.

- The header text is vertically centered and 16px from the edge of the screen.

Added a align-items ceneter to the header class and then wrapped the header text in a <p> tag and referenced it in the CSS so that I could add a 1em margin. This allowed me to move the text from the side of the screen.

- The footer is pushed to the bottom of the screen (the footer may go _below_ the bottom of the screen if the content of the 'cards' section overflows and/or if your screen is shorter).\

Yes, the footer is push to the bottom of the page. Achieved this by changing the flex-direction to column and creating a div called middle content that contain the page text and side bar. Then placed a min-height on it with a 80vh value to maintain positioning. I think the method that I used was messy but, it got the job done for this project. Will have to revisit and fix this in the future, as my skills progress.

- The footer text is centered horizontally and vertically.
Yes, this was achieve with a align-items center and justify-content center.

- The sidebar and cards take up all available space above the footer.

Yes, due to the sectioning of content and flexbox settings.

- The sidebar is 300px wide (and it doesn't shrink).

Yes, added a property that doesn't allow shrinking aka flex-shrink 0.

- The sidebar links are size 24px, are white, and do not have the underline text decoration.

Yes.

- The sidebar has 16px padding.

Yes.

- There is 32px padding around the 'cards' section.

Yes, padding had been added to all cards. 

- The cards are arranged horizontally, but wrap to multiple lines when they run out of room on the page.

Yes, flex-wrap property was added to the div that contains that cards. The cards wrap to what ever space they have.
