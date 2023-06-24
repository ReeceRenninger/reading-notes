# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Context API

[Choosing the State Structure](https://react.dev/learn/choosing-the-state-structure)

    Group related state. If you always update two or more state variables at the same time, consider merging them into a single state variable.

    Avoid contradictions in state. When the state is structured in a way that several pieces of state may contradict and “disagree” with each other, you leave room for mistakes. Try to avoid this.

    Avoid redundant state. If you can calculate some information from the component’s props or its existing state variables during rendering, you should not put that information into that component’s state.

    Avoid duplication in state. When the same data is duplicated between multiple state variables, or within nested objects, it is difficult to keep them in sync. Reduce duplication when you can.

    Avoid deeply nested state. Deeply hierarchical state is not very convenient to update. When possible, prefer to structure state in a flat way.

[Passing State Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)

- Contexts in React aim to solve the problem of prop drilling by providing a mechanism to share data between components without the need for manual prop passing.
- One technique to try before using useContext in React is to utilize component composition and pass down props explicitly through the component hierarchy. You can also try extracting components and pass the JSX down as children props.
- The hook that complements useContext for complex applications in React is the useReducer hook.

## Bookmark

[Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)

[Preserving and Resetting State](https://react.dev/learn/preserving-and-resetting-state)

## Class Notes

## Things I want to know more about
