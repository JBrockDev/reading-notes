# Class 17 - Reading Notes

## State and Props

React Lifecycle
1. Render occurs before componentDidmount.
2. Calling the constructor is the first thing in the lifecycle of a component.
3. Constructor, render, React updates, componentDidMount, componentWillUnmount are the order of things happening in the lifecycle.
4. ComponentDidMount allows you to run network requests or initialize the DOM as well as setState, though setState shouldn't be regularly used here due to performance issues when it causes a rerender.

React State
1. Props can pass down anything that can be stored in a javascript variable.
2. Props are passed into components, state is handled inside components.
4. Anytime some value changes, a re-render occurs.
5. State can store things being used within the component, a form, contents of a form, etc. 
