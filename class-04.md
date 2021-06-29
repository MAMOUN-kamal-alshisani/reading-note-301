#  ~~reading-note-04~~


## What is a ‘Controlled Component’?
***Controlled Component is one that takes its current value through props and notifies changes through callbacks like onChange . 
A parent component "controls" it by handling the callback and managing its own state and passing the new values as props to the controlled component***

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
***we should update user responeses as soon as possible because we do not want their to be complications if the user submits another response***

## How do we target what the user is entering if we have an event handler on an input field?
***we use the props to target the input fields***
## Why would we use a ternary operator?
***it shortens time and it is clearer.***

## Rewrite the following statement using a ternary statement :

 ### if(x===y){
 ### console.log(true);
  } else {
### console.log(false);
  }
### x===y ? (console.log(true)):(console.log(false))

## Forms
***The/ <-FormControl-> component renders a form control with Bootstrap styling. The <FormGroup> component wraps a form control with proper spacing, along with support for a label,
 help text, and validation state. To ensure accessibility, set controlId on <-FormGroup>, and use <FormLabel> for the label.***
  
  ## Conditional Rendering
***In React, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.
Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.***
