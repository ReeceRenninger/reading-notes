# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[useEffect Hook](https://react.dev/reference/react/useEffect#reference)

- The main intended use case for the useEffect hook in React is to handle side effects, such as fetching data, subscribing to events, or manually interacting with the DOM, that need to be performed after the component has rendered or when certain dependencies have changed.
- The effect's logic in the useEffect hook interacts with the component by executing after the DOM has been updated, allowing it to perform tasks or update the DOM. It can also specify dependencies to re-execute the effect when they change and return a cleanup function for performing necessary cleanup before the component is unmounted or when the dependencies change.
- The return value from the effect's logic function in useEffect is important for performing cleanup tasks. It allows you to specify a cleanup function that will be executed before the component is unmounted or when the dependencies change, ensuring proper resource disposal and avoiding memory leaks.

## Bookmark

[Responding to Events](https://react.dev/learn/responding-to-events)

[Conditional Rendering](https://react.dev/learn/conditional-rendering)

[Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)

[Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

## Class Notes

## Things I want to know more about
