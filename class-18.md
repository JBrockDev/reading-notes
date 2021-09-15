# Class 18 - Reading Notes

## Lists and Keys
1. .map() returns a new array with each index of the array being set by whatever code the callback function performs on the original array at that index.
2. Using curly braces allows the use of variable valuesi n JSX.
3. Each list item needs a unique key.
4. A key is basically used as an id for the elements to be able to determine which have been manipulated, whether added, changed or removed.

## The Spread Operator

1. The spread operator is an modern way of adding items to arrays, combining arrays or objects, and spreading an array into arguments for a function. Spread can be used as a substitute for Array.slice() to create a new array rather than copying the old reference.
2. Four things a spread operator can do: copy an array, concat arrays, use array as arguments for a function, and add to a React state.
3. combinedArray = [...arrayOne, ...arrayTwo];
4. fullArray = ['a', 'b', ...letterArray];
5. civicObject = {...carObject, ...hondaObject, model: "Civic"};

## Passing Functions Between Components

1. Create the function to be passed into the child component from the parent, within the parent component.
2. Increment changes the state of the parent, replacing the old array with a new array where the count is increased by one.
3. You can pass a method from parent to child component via props, just like any variable.
4. The child component would access it just like any prop variable... this.props.propNameFromParent
