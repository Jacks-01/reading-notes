# Class 9: Functional Programming

## Reading

- What is functional programming?
  - It is a style of structuring elements of code that strictly handles computing and no state management or mutable data.
- What is a pure function and how do we know if something is a pure function?
  - It returns the same result when given the same arguments
  - does not have any unintended side effects
- What are the benefits of a pure function?
  - Its easier to test
  - it is predictable and consistent
- What is immutability?
  - it means that the data cannot be changed
- What is Referential transparency?
  - if a paramater can be replaced with another one of the same value/context
  - ex. sqrt(4) = 2 . The expression of sqrt(4) is the same value of the integer 2.

### Video

- What is a module?
  - A module is a file containing code. You would use it to share variables, functions, etc to another file.
- What does the word ‘require’ do?
  - It is Node.js way of reading an import from another file.
- How do we bring another module into the file the we are working in?
  - `const mongoose = require('mongoose);`
- What do we have to do to make a module available?
  - `export default mongoose;`


