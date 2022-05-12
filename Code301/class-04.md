# Class 04: React and Forms


1. What is a ‘Controlled Component’?
    - A controlled component is one where the component has its own mutable state by default,  this way the inputs value is always driven by the react state and not its original state.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
   - We should wait until they submit otherwise the state will be written again and change their response.
3. How do we target what the user is entering if we have an event handler on an input field?
   - we use the .bind method to pass the data as an argument to the function in your class.

1. Why would we use a ternary operator?
   - It simplifies an if else statement into oneline of code for readibility.
2. Rewrite the following statement using a ternary statement.
```
  if(x===y){
  console.log(true);
} else {
  console.log(false);
}
```
> With a ternary operator `?`

```
x===y ? console.log('true') : console.log('false');
```