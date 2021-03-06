~~# reading-note-01~~
## What is a component?
***Components are independent and reusable bits of code. They serve the same purpose as***

## What are the charactistics of a component?

* One-way data binding. ...
* React native. ...
* Declarative UI. ...
* Component-based architecture. ...
* Speed and efficiency. ...
* Flexibility.

## What are the advantages of using component based architecture?
* ***Ease of deployment − As new compatible versions become available, it is easier to replace existing versions with no impact on the other components or the system as a whole.***
* ***Reduced cost − The use of third-party components allows you to spread the cost of development and maintenance.***
## what is react :
***React is a declarative, efficient, and flexible JavaScript library for building user interfaces. It lets you compose complex UIs from small and isolated pieces of code called “components”.
React has a few different kinds of components, but we’ll start with React.Component subclasses:***

***Inspecting the Starter Code***
***If you’re going to work on the tutorial in your browser, open this code in a new tab: Starter Code. If you’re going to work on the tutorial locally, instead open src/index.js in your project folder (you have already touched this file during the setup).***

***This Starter Code is the base of what we’re building. We’ve provided the CSS styling so that you only need to focus on learning React and programming the tic-tac-toe game.***
***By inspecting the code, you’ll notice that we have three React components:***

* Square
* Board
* Game


## What is props short for?
 ***properties. It is a special keyword in React which is used for passing data from one component to another***
# How are props used in React?

***It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It gives a way to pass data from one component to other components. It is similar to function arguments. Props are passed to the component in the same way as arguments passed in a function***
## What is the flow of props?
***data flows in one direction.***
## Passing Data Through Props
***To get our feet wet, let’s try passing some data from our Board component to our Square component.***

***We strongly recommend typing code by hand as you’re working through the tutorial and not using copy/paste. This will help you develop muscle memory and a stronger understanding.***

***In Board’s renderSquare method, change the code to pass a prop called value to the Square:***
  
  ## Why JSX?
***React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display.***

***Instead of artificially separating technologies by putting markup and logic in separate files, React separates concerns with loosely coupled units called “components” that contain both. We will come back to components in a further section, but if you’re not yet comfortable putting markup in JS, this talk might convince you otherwise.***

***React doesn’t require using JSX, but most people find it helpful as a visual aid when working with UI inside the JavaScript code. It also allows React to show more useful error and warning messages.***

## Components and Props
***Components let you split the UI into independent, reusable pieces, and think about each piece in isolation. This page provides an introduction to the idea of components.***

## Function and Class Components
***This function is a valid React component because it accepts a single “props” (which stands for properties) object argument with data and returns a React element. We call such components “function components” because they are literally JavaScript functions.***
