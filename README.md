# 🔀 Shuffle cards
Press random and see how it moves. <br />
The cards are placed randomly, and they never leave the screen.

#### ✔️ Things to remember
```
let windowHeight, windowWidth

const RESIZE = () => {
  windowWidth = window.innerWidth;
  windowHeight = window.innerHeight;
  CARD_RESET()
}
```
* The main purpose of this function is to update the width (windowWidth) and height (windowHeight) of the browser window. <br />
 `window.innerWidth` is a property that represents the width of the current browser window, <br />
 and `window.innerHeight` is a property that represents the height of the current browser window. <br />
These two values are updated whenever the browser window is resized.
