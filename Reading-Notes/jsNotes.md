# JavaScript Notes

Javascript is able to help us create dynamic websites. Dynamic meaning that it is able to update things continuously and in real-time. When you write your html and css code, the browser loads it in one snap of your fingers, and nothing you click (other than tags connecting pages) will change the display. With JavaScript we are able to add our own bits of code to play when another action is taken.

## Control Flow
 
 Control flow is the term used to describe the order in which our code executes. In JS, code is read in a logical manner from left to right, then down.

## The essentials

In JavaScript there are a few core concepts that lay the ground work for what a line of code does.

* Methods
  - Methods return information about an object, and are called by appending an instance with a period ., the method name, and parentheses. ex. `console.log`

* Variables 
  - Variables are used whenever there’s a need to store a piece of data. A variable contains data that can be used in the program elsewhere. Using variables also ensures code re-usability since it can be used to replace the same value in multiple places. 
    - We define variables with `let` (can be changed) and `const` (cannot be changed). 
  
* Functions
  - Functions are one of the fundamental building blocks in JavaScript. A function is a reusable set of statements to perform a task or calculate a value. Functions can be passed one or more values and can return a value at the end of their execution. In order to use a function, you must define it somewhere in the scope where you wish to call it. 
  
```.js
Defining the function:
function sum(num1, num2) {
  return num1 + num2;
}
 
// Calling the function:
sum(3, 6); // 9

```

[Credit](https://www.codecademy.com/learn/introduction-to-javascript/modules/learn-javascript-functions/cheatsheet)

 