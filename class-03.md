# reading-notes 03

## What does .map() return?
***It is a function to which map passes each element of given iterable***
## If I want to loop through an array and display each value in JSX, how do I do that in React?
***the map() method is the most commonly used function to iterate over an array of data in JSX.***
## Each list item needs a unique key.
## What is the purpose of a key?
 ***“key” is a special string attribute you need to include when creating lists of elements in React. Keys are used to React to identify which items in the list are changed, updated, or deleted. In other words
 , we can say that keys are used to give an identity to the elements in the lists.***
 
## What is the spread operator?
***InJavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.
“When ...arr is used in the function call, it ‘expands’ an iterable object arr into the list of arguments.” — JavaScript.info***
## List 4 things that the spread operator can do. 

* Copying an array
* Concatenating or combining arrays
* Using Math functions
* Using an array as arguments
* Adding an item to a list

Give an example of using the spread operator to combine two arrays.

const myArray = [`🤪`,`🐻`,`🎌`]
const yourArray = [`🙂`,`🤗`,`🤩`]
const ourArray = [...myArray,...yourArray]
console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩

Give an example of using the spread operator to add a new item to an array.

onst fruitStand = ['🍏','🍊','🍌']
const sellFruit = (f1, f2, f3) => { console.log(`Fruits for sale: ${f1}, ${f2}, ${f3}`) }
sellFruit(...fruitStand) // Fruits for sale: 🍏, 🍊, 🍌
fruitStand.pop()
fruitStand.pop()
fruitStand.push('🍉')
fruitStand.push('🍍')
sellFruit(...fruitStand) // Fruits for sale: 🍏, 🍉, 🍍
fruitStand.pop()
fruitStand.pop()
sellFruit(...fruitStand,'🍋') // Fruits for sale: 🍏, 🍋, undefined

Give an example of using the spread operator to combine two objects into one.

onst objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂

**The spread operator is a useful and quick syntax for adding items to arrays,
combining arrays or objects, and spreading an array out into a function’s arguments.***

## In the video, what is the first step that the developer does to pass functions between components?
***create a function where the states are changed***

## In your own words, what does the increment function do?
***as the function loops through the array using map it increases one each time it loops***

## How can you pass a method from a parent component into a child component?
***pass it with props***

## How does the child component invoke a method that was passed to it from a parent component?
***it invokes it using state***

***things i want to learn about***
* react and javascript
* array methods
* components 


