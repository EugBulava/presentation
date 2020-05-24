## SLIDE 1

Hello everyone, my name is Eugene, and today I want to tell you about the React library.

## SLIDE 2

Now, we’ll talk a bit about the history of React.
React's story began a long time ago.

## SLIDE 3

In 2010, almost all projects had a programming language like PHP

February 10, 2010 facebook presented XHP. What is XHP?

## SLIDE 4

XHP is Component HTML framework for PHP.
It is a PHP extension that complements the language syntax that improves the responsiveness of html code.


This made it possible to create complex, composite components that were easy to work with,
 since they needed less code to write, they could be inherited from each other, and it was easier to read.

## SLIDE 5

React was first used in the Facebook news feed in 2011, and then used by Instagram in 2012.


React is a very common library. React is used in applications like Netflix, New York Times, WhatsApp, Dropbox and other..

## SLIDE 6

First of all, we must answer 'what is React'?

React is a JavaScript library for building user interfaces.

React is a library and not a framework, it does not restrict code writing.

I think you ask why we use React if we can develop a web project in vanilla JavaScript?

If you are interested in web development, I am sure you know that React allows you to create very fast applications.

Application maked with React libriary have performance higher than native javasript.

Why is that so?


## SLIDE 7

High performance is achieved by a technology called 'Virtual DOM'.

What is it?

## SLIDE 8

okey, first, we need to know what the DOM is.
DOM (аббревиатура от Document Object Model) - in other words,
 it is a way of representing a structural document which using objects.

## SLIDE 9 

(VDOM) is a programming concept in which a “virtual” representation of
 a user interface is stored in memory and synchronized with a “real” DOM using a library such as ReactDOM.
 This process is called reconciliation.
 
How does the virtual DOM work?

## SLIDE 10


Instead of interacting with the DOM directly, we work with lightweight copy of real DOM. 
We can make changes to the copy based on our needs, and then apply the changes to the real DOM.

After that, the DOM tree is compared with its virtual copy,
 the difference is determined and then a redraw our changes.


## SLIDE 11

Another really great benefit is the ability to create web components suitable for reuse.


## SLIDE 12

The easiest way to declare a component is to write a JavaScript function.
This function is a valid React component.
It takes a single props object with data as an argument and returns a React element.
Such components are called “functional” because they are JavaScript functions.


## SLIDE 13

A component can be declared in another way. To do this, use the ES6 class.


## SLIDE 14

Another important advantage of react - it React community.
Nowadays, the react community is very large.
From this we can conclude that most of the problems have already been resolved. 
 This greatly speeds up the development process.


## SLIDE 15

Also good practice is to use react hooks.
React Hooks are a new addition in React 16.8 that let you use state 
 and other React features without writing a class component. 
 In other words, Hooks are functions that let you “hook into” 
 React state and lifecycle features from function components. 


## SLIDE 16

React provides a few built-in Hooks like useState. 
You can also create your own Hooks to reuse stateful behavior between different components. 
The example below shows a counter whose state is managed using the useState() hook. 
Each time you click on the button, we make use of setCount() to update the value of count by 1.


## SLIDE 17, SLIDE 18

This example renders a counter with a value of 0. 
 When you click the button, it increments the value by 1.


## SLIDE 19

The initial value of the component is defined using useState.
As you can see, we set that to be 0. 


## SLIDE 20

 Then we use the onClick() method to call setCount when we want to increment the value.
Before the release of React Hooks, this example would have used more lines of code, 
 as we’d have had to make use of a class component.


## SLIDE 21

To summarize the presentation.
1) React is a library and not a framework, it does not restrict code writing.
2) React allows you to create very fast applications
3) React uses a virtual DOM, which makes the application more productive.
4) Using react we can create web components suitable for reuse.
There ara 2 ways to declare component. Declare a component is to write a JavaScript function/
Declare a component is to write ES6 class.
5) React community is very large. Most of the problems have already been resolved
6) We can use React Hooks, which let you use state 
 and other React features without writing a class component.
