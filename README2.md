# Andejakt - CSS Game
By: Ola Nikolai Skjeret and Simen Elvhaug

## The game
We were inspired to make a game like [Duck Hunt](https://en.wikipedia.org/wiki/Duck_Hunt), where the main goal of the game is to hit ducks flying to the sky. The player has to hit them before they fly to far away, or in this case, off the screen. Our website's design is also inspired by this game, with the pixelated text, foreground, background and the main target; ducks.

### Design
Most of the design is made with Adobe Illustrator. The image has layers that are named using BEM, and exported as SVG. Its code is mostly in the html file, though the styling (mostly colors) has been moved to separate css files. This was to keep a nice css architecture and having separation of concern in the SVG implementation.
The colors chosen for this project are similar to the original Duck Hunt game that we are inspired by.

### How it works
The core function of the game consists of checkboxes that are styled as ducks. Most of the magic happens in the css file called [logic](url:_logic.scss). The input boxes are counted in the score when they are checked. This is how we show the score. When all of the checkboxes are checked, a win-screen pops up and congratulates the player.

## About the project
We chose to go for this sort of point-and-click game because it uses no javascript code and is possible to code with only html and css. As avoiding use of javascript, and rather using css to our creative and knowledgable limit, was a big part of the project. We did start out by planning a rock-paper-scissors game, though we found out it would require a lot more experience in css to make that happen without more js code than we were comfortable with delivering in this assignment. 