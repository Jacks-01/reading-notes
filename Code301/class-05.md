## Class 05: Putting it all together

# Thinking in React

1. What is the single responsibility principle and how does it apply to components?
   - It is a best practice where you separate your components in a way where each component only has one primary task, the more you can break them down the better usually.
2. What does it mean to build a ‘static’ version of your application?
   - It means that you build a barebones version of your react app that is not dynamic. You don't want to use state when building a static app.
3. Once you have a static application, what do you need to add?
    - You need to add a mockup or a framework so that you can work topdown and sort your components into their responsibilities. Try to have very few mutable elements so that you aren't depending on state.
4. What are the three questions you can ask to determine if something is state?
    1. Is it passed in from a parent via props? If so, it probably isn’t state.
    2. Does it remain unchanged over time? If so, it probably isn’t state.
    3. Can you compute it based on any other state or props in your component? If so, it isn’t state.
5. How can you identify where state needs to live?
    1. Identify every component that renders something based on that state.
    2. Find a common parent component. The highest call is the best component to include state in.
    3. If you can't find a good place, make a new component to manage the state.

## Higher Order Functions
1. They are functions that operate on other functions, usually by taking them in as an argument.