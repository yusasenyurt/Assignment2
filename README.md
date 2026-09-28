# Assignment 2

## File Organization
I have created one `index.html` file and two CSS files (`styleA.css` and `styleB.css`). The HTML file has a container div and 6 box elements inside it. Currently, it links to `styleA.css`. To see the other design, you just need to change the `<link>` tag in the HTML file to `styleB.css`.

## Challenges Faced
The hardest part was making sure the boxes don't resize or overlap when the window gets smaller. I fixed this by using `flex-shrink: 0` on the boxes. Also, for style B, calculating the exact 100x150px size with the padding and border was tricky, so I used `box-sizing: border-box` to keep the dimensions exactly as required. To keep the last box fixed in the bottom right corner, I used `position: fixed` so it stays there even when scrolling.