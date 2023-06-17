# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: useState() Hook

[Thinking in React](https://react.dev/learn/thinking-in-react)

  Break the UI into a component hierarchy: Identify the different parts of the user interface and organize them into a tree-like structure of      components.

  Build a static version of the UI: Create a static version of the UI using React components but without any interactivity or state management. This helps in visualizing the overall structure and layout of the UI.

  Identify the minimal (but complete) representation of UI state: Determine the minimal set of state that is required to represent the UI and make it interactive. This involves identifying the data that will change over time and affect the UI.

  Identify where the state should live: Determine which component or components should own and manage the identified state. This involves finding the common parent component that can store and distribute the state to its child components.

  Add inverse data flow: Establish the flow of data and events in the application by adding callbacks and event handlers to update the state and trigger re-rendering of components. This ensures that changes in the UI are reflected in the state and vice versa, enabling interactivity and dynamic updates.

[State: A Component's Memory](https://react.dev/learn/state-a-components-memory)

- One reason a local variable isn't sufficient for managing a React component is that local variables are not preserved between component renders.
- The argument to the useState hook in React is the initial state value. The useState hook returns an array with two elements: the current state value and a function to update the state.
- To allow Component A to access the state from Component B in React, you need to lift the state up to a common ancestor component that both Component A and Component B share. This lets the parent component in the hierarchy to have access to both shared via props.

## Bookmark

[Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)

[Rendering Lists](https://react.dev/learn/rendering-lists)

[State as Snapshot](https://react.dev/learn/state-as-a-snapshot)

[useState hook](https://react.dev/reference/react/useState)

## Reflection

- Understanding hooks will be my biggest goal. State in general was a hard concept for me to work around in 301 so hopefully its better this time around.

## Class Notes

## Things I want to know more about
