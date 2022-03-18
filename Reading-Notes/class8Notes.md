# Operators and Expressions

Operators in JS let us do arithmetic and logical computing within our functions.

Here are the data types that we can use as operators:

```.js
 Addition
{
5 + 5
// Subtraction
10 - 5
// Multiplication
5 * 10
// Division
10 / 5
// Modulo
10 % 5
}
```

An assignment operator assigns a value to its left operand based on the value of its right operand. Here are some of them:

*   += addition assignment
*  -= subtraction assignment
*   *= multiplication assignment
*   /= division assignment

# Loops

A loop is a programming tool that is used to repeat a set of instructions. Iterate is a generic term that means “to repeat” in the context of loops. A loop will continue to iterate until a specified condition, commonly known as a stopping condition, is met.

The while loop creates a loop that is executed as long as a specified condition evaluates to true. The loop will continue to run until the condition evaluates to false. The condition is specified before the loop, and usually, some variable is incremented or altered in the while loop body to determine when the loop should stop.

Here is a code snippet to demonstrate: 

```.js
 while (condition) {
  // code block to be executed
}
 
let i = 0;
 
while (i < 5) {        
  console.log(i);
  i++;
}
```
A for loop declares looping instructions, with three important pieces of information separated by semicolons ;:

- The initialization defines where to begin the loop by declaring (or referencing) the 
iterator variable

- The stopping condition determines when to stop looping (when the expression evaluates to false)

- The iteration statement updates the iterator each time the loop is completed

[Credit](https://www.codecademy.com/learn/introduction-to-javascript/modules/learn-javascript-loops/cheatsheet)