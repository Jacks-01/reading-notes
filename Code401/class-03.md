## Reading Notes
## Assignment: Express REST API

Statement: This topic is important because...
___

### Questions:
___
##### [Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

1.  Classes are a template for creating **__**__.
	- creating objects
2.  Can a class declaration be hoisted?
	- No, you must construct it first
3.  How would you describe a constructor and contextual “this” to a non-technical friend?
	- a constructor is like inventing a new item. It is the intialization of the object and the recipe for which each instance of the next object is used. `this` keyword is referring to a specific instance of the object you are using in the expression. It's an indentifier
##### [Using Express Routing](https://expressjs.com/en/guide/routing.html)

1.  Within Express, what does routing refer to?
	- how application endpoints respond to incoming client requests
2.  What is the difference between a route path and a route method?
	- a route path can contain string patterns and regex whereas a method is just the one defined route or string.
3.  When is it appropriate to add `next` as a parameter to a route handler and what must you do if `next` has been passed to your middleware as a parameter?

##### [Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

1.  What is an Express Router?
	- its like a mini express app but with only the routing functionality
2.  By what mean do we initialize `express.Router()` in an express server?
	- it creates an *instance* of express for our file so we can use routes
3.  What do we use route middleware for?
	- allows us to perform other actions before we send a response back to the user such as authentification.




### Things I want to know more about:
___
Routing as a whole, scalability with routing.

### Sources (if any):
___
	x