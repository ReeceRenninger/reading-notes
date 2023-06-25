# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Redux Additional Topics

[Redux Toolkit(RTK)](https://redux-toolkit.js.org/introduction/getting-started)

- Redux Toolkit addresses several concerns related to Redux development, including reducing boilerplate code, simplifying store setup, providing a standard approach for defining reducers and actions, enabling immutability by default, and supporting the use of Redux middleware.
- The configureStore() function is a utility provided by Redux Toolkit that simplifies the setup of a Redux store by combining several steps into a single function call. It automatically configures the store with sensible defaults, including the use of the Redux DevTools Extension for debugging, and allows for easy customization of middleware and other store options.
- To use createSlice() from Redux Toolkit, you would define a slice of your Redux state by specifying an initial state and an object containing reducers. It automatically generates action creators and action types based on the provided reducers, allowing you to easily create and handle actions for that specific slice of state.

[MobX](https://mobx.js.org/getting-started.html)

- Mobx is a state management library for JavaScript applications, including React, Angular, and Vue. It enables developers to create observable data structures that automatically update the user interface whenever the underlying data changes. Mobx follows the principle of "observable programming," where any changes made to the observed data are automatically tracked and propagated to the relevant components, simplifying the process of managing and synchronizing state in applications.
- Mobx achieves consistency in state by leveraging the concept of observable data and reactive updates. Whenever a piece of data marked as observable changes, Mobx automatically triggers the necessary reactions to update any dependent components or computations. This reactive nature ensures that the state and UI are always in sync, eliminating the possibility of inconsistent or out-of-date data. Additionally, Mobx provides mechanisms like computed values and actions, which enforce proper data manipulation and encapsulation, further preventing inconsistencies in the state.
- To build a reactive user interface, we can use a reactive programming library like Mobx or RxJS. By defining observable data and reactive computations, we establish a relationship between the data and the UI, allowing the UI to automatically update whenever the data changes, creating a seamless and reactive user experience.

## Tutorial:

[Tutorial](https://redux-toolkit.js.org/tutorials/intermediate-tutorial)

- There are a few different tutorials with getting started with redux toolkit or even on how to migrate vanilla redux to redux toolkit. I just read through the Quick Start Tutorial. Tutorial was pretty straight forward on how to bring it in and how to provide the store to React. Definitely a bookmark for the future once we get into this material.

## Bookmark

[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)

[HookState](https://hookstate.js.org/)

## Reflection

[README.md](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-39/)

- I am not sure how the Redux toolkit will feel to use in practice, but it seems like it will be extremely useful once I can get the hang of it. I am excited to see how it works in development.

## Class Notes

## Things I want to know more about
