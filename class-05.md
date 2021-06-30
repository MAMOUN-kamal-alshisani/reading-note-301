# reading notes

## How would you break a mock into a component heirarchy?

***1. Break The UI Into A Component Hierarchy. The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names.***
***2. Build A Static Version in React. See the Pen Thinking In React: Step 2 on CodePen. Now that you have your component hierarchy, it’s time to implement your app.***
***3. Identify The Minimal (but complete) Representation Of UI State. To make your UI interactive, you need to be able to trigger changes to your underlying data model.***
***4. Identify Where Your State Should Live.***
***See the Pen Thinking In React: Step 4 on CodePen.***

## What is the single responsibility principle and how does it apply to components?

***a component should only do one thing if it ends up building up it should be breaked down to subcomponents***

## what does it mean to build a static version of your application?

***static version of your app that renders your data model,to build components that reuse other components and pass data using props***

## Once you have a static application, what do you need to add?
***i can use props to pass down propreties but ,i cant use state because it is used to make interactive application

## What are the three questions you can ask to determine if something is state?
***1. is it passed down from the parent if it is its not state but props.***

***2. does it remain unchanged overtime if so it isnt a state***

***3. can you compute it based on aother props or state if so it isnt a state.***

## How can you identify where state needs to live?

***Identify every component that renders something based on that state.***

___Find a common owner component (a single component above all the components that need the state in the hierarchy).__

***- Either the common owner or another component higher up in the hierarchy should own the state.***

***+ If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.***
