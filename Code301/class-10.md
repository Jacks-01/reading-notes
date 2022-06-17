# Class 10 : In memory Storage

## Reading


- What is a ‘call’?
  - A call is when a function is invoked.
- How many ‘calls’ can happen at once?
  - Only 1 call can happen at a time.
- What does LIFO mean?
  - Last In First Out
- Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

```js
 function firstFunction(){
  throw new Error('Stack Trace Error');
};

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
```

- What causes a Stack Overflow?
    - a circular dependency, basically an infinite loop until all of your memory is used up.

- What is a ‘reference error’?
  - a reference error means that the program doesn't know what you are referring to, most typically a variable that has not been defined yet (or is scoped improperly).
- What is a ‘syntax error’?
  - A syntax error means you didn't follow the rules of the language. The program will stop if the grammar of your program is wrong, such as a missing curly brace.
- What is a ‘range error’?
  - A range error occurs when you give a function a value that isn't within the specified range.
- What is a ‘type error’?
  - a type error means that the data type of a variable was not compatible with whatever expression was being evaluated. ex `math.floor('hello')`
- What is a breakpoint?
  - A breakpoint is a specified line of code that the interpreter will stop on before proceeding.
- What does the word ‘debugger’ do in your code?
  - Debugger is basically a manual breakpoint that is actually in your code. Used before debuggers were common.
