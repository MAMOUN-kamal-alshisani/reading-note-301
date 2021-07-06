## ~~reading-note-09~~


## What is functional programming?

***Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — 
that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data***

## What is a pure function and how do we know if something is a pure function?

* __It returns the same result if given the same arguments (it is also referred as deterministic)__
* __It does not cause any observable side effects__

## What are the benefits of a pure function?

***The code’s definitely easier to test. We don’t need to mock anything. So we can unit test pure functions with different contexts:***

***Given a parameter A → expect the function to return value B
Given a parameter C → expect the function to return value D***

***A simple example would be a function to receive a collection of numbers and expect it to increment each element of this collection.***

## What is immutability?

***When data is immutable, its state cannot change after it’s created.
If you want to change an immutable object, you can’t. Instead,
you create a new object with the new value.***

## What is Referential transparency?
***Basically, if a function consistently yields the same result for the same input, it is referentially transparent.
pure functions + immutable data = referential transparency***


## What is a module?
 ***collection of new features ,they allow you to import and export stuff***
 
## What does the word ‘require’ do?
***The require function is intended to add separate pieces of code (“modules”) to the current scope,***

## How do we bring another module into the file the we are working in?
***you can export the module to another file***

## What do we have to do to make a module available?
***require and export***
