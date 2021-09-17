
# Class 20 - Reading Notes

## Thinking in React

1. Single Responsibility principle, according to the reading material today is a component that should ideally do one thing. I know of Single Responsibility as the S in the object oriented principles SOLID, where essentially a method should have only one reason to ever be changed.
2. A static version of the application is one without state, using only the data that comes in initially without user interactivity.
3. After building the static application, then it is time to add in the state and user interactiveness.
4.  Three questions to determine if something is state.
    - Is it passed in from a parent via props? If so, it probably isn’t state.
    - Does it remain unchanged over time? If so, it probably isn’t state.
    - Can you compute it based on any other state or props in your component? If so, it isn’t state.

## Higher Order Functions

1. A higher order function is a function that takes in another function as an argument or returns it.
2. In the greaterThan function, line 2 is returning the arrow function m => m > n; reference when called.
3. Reduce returns the values of an array into a new array based on the expression provided, similar to greaterThan, where items are pushed or not pushed based on truthy evaluation.
