# reading-note-01

## what is react :
***React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.
React has a few different kinds of components, but we’ll start with React.Component subclasses:***

***Inspecting the Starter Code***
***If you’re going to work on the tutorial in your browser, open this code in a new tab: Starter Code. If you’re going to work on the tutorial locally, instead open src/index.js in your project folder (you have already touched this file during the setup).***

***This Starter Code is the base of what we’re building. We’ve provided the CSS styling so that you only need to focus on learning React and programming the tic-tac-toe game.***
***By inspecting the code, you’ll notice that we have three React components:***

Square
Board
Game
***The Square component renders a single <button> and the Board renders 9 squares. The Game component renders a board with placeholder values which we’ll modify later. There are currently no interactive components.***

***Passing Data Through Props***
***To get our feet wet, let’s try passing some data from our Board component to our Square component.***

***We strongly recommend typing code by hand as you’re working through the tutorial and not using copy/paste. This will help you develop muscle memory and a stronger understanding.***

***In Board’s renderSquare method, change the code to pass a prop called value to the Square:***
  
  ***Why JSX?**
React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.

Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.

React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.

With that out of the way, let’s get started!

Embedding Expressions in JSX
In the example below, we declare a variable called name and then use it inside JSX by wrapping it in curly braces
