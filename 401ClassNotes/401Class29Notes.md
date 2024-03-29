# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[Extracting State Logic into a Reducer](https://react.dev/learn/extracting-state-logic-into-a-reducer)

- The motivation for adding a reducer in React is to manage complex state and state transitions in a more organized and predictable manner. It helps in centralizing state logic, handling actions, and updating the state based on those actions, resulting in cleaner and more maintainable code.
- In the context of a reducer, actions are plain JavaScript objects that describe a state change. They typically have a type property that specifies the type of action and may also contain additional data relevant to the state update. Actions are different from setting state directly because they provide a standardized way to describe state changes and can be processed by the reducer function to update the state in a controlled and predictable manner. By dispatching actions to the reducer, it becomes easier to track and manage state transitions, implement complex logic, and maintain a clear separation between state management and component code.
- The useReduce hook is named after the common list operation called "reduce" or "fold." This operation is used to aggregate or accumulate values from a list into a single value by applying a combining function to each element of the list.
- You should switch from useState to useReducer when the state management in your component becomes more complex and involves multiple related state transitions or when you need to pass down state update logic to child components. useReducer is particularly useful when you have a complex state that may have multiple actions that modify it or when the next state depends on the previous state.

## Bookmark

[useReducer hook](https://react.dev/reference/react/useReducer)

[Keeping Components Pure](https://react.dev/learn/keeping-components-pure)

[Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)

## Class Notes

- Just getting better at state seems to be the major goal.  The state seems to ramp up even more on this module and I feel the weakest there with React.

## Things I want to know more about
