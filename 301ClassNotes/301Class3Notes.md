# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Passing Functions as Props

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. the .map() returns a new array.
2. We can loop through an array in JSX by using {}.
3. Each list item needs a unique key.
4. Keys allow for React to identify which items have changed, are added, or are removed. Keys should be given to elements inside an array to give them a STABLE IDENTITY.

[The spread operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. Spread (...) is used to expand an iterable object into a list of arguments.
2. the spread operator is a way to add items to arrays, combine arrays or objects or spread an array into function arguments, finding the largest number in an array, adding to state in React, copying an array, etc...
3. We could use the spread operator to combine two arrays that have similar data that we want to be stored all together.  The author combined two arrays full of emoticons so they would be condensed to one.
4. You can add to an existing array with the data of an new array by simply using ...arrName inside the new array to grab all the information.
5. We can use the same style of syntax with the ...objName inside of another object to grab the information.

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. The first step to pass functions between components is to create the function wherever the state we want to change is at.
2. The increment function is being passed in the people array and then using map to create a new array with the count being incremented upwards based off the clicks on the button.
3. You can pass a method from a parent component to a child component by creating a prop that references the method you created.
4. The child component can invoke the method it was passed by the parent by invoking it. The video also directed his invoked method to return the name that he was using for the component.

## Bookmarks

[React Tutorial through 'Declaring a Winner'](https://reactjs.org/tutorial/tutorial.html)

[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

## Class Notes

## Things I want to know more about
