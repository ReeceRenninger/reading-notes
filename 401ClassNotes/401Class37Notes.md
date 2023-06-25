# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[Multiple Reducers Example](https://www.youtube.com/watch?v=gBER4Or86hE)

- Creating multiple reducers allows for better organization and modularization of the application's state management. It allows different parts of the application to handle their own specific data and logic independently, making it easier to maintain and scale the codebase.
- To combine multiple reducers in Redux, we use the combineReducers function provided by Redux. It takes an object as input, where each key represents a slice of the application state and each value represents the corresponding reducer function for that slice. This function merges all the reducers into a single reducer that can be passed to the Redux store.
- Managing state as an immutable object means that once a state is created, it cannot be changed directly. Instead, whenever an update is needed, a new state object is created with the desired changes. This approach ensures data integrity, simplifies debugging, enables efficient change detection, and helps prevent unintended side effects in complex applications.

[Redux Docs: Using Combined Reducers](https://redux.js.org/recipes/structuring-reducers/using-combinereducers/)

- combineReducers is a utility function to simplify the most common use case when writing **Redux reducers**.
- combineReducers assembles the new state tree by creating a new object that combines the output of multiple reducers. Each reducer is responsible for managing a specific slice of state, and combineReducers combines these slices into a single state object.
- In an app using combineReducers, the initial state is defined by specifying the initial state for each individual reducer. Each reducer can define its own initial state, and combineReducers combines them to create the overall initial state of the application.

[Redux Docs: Combined Reducer Syntax](https://redux.js.org/api/combinereducers/)

- As an app becomes more complex, splitting reducing functions allows for better organization, modularity, and scalability, making it easier to manage and maintain the state of different parts of the application independently.
- The **combineReducers** helper function turns an object whos values are different reducing functions into a single reducing function you can pass to **createStore**.
- A popular convention is to name reducers after the state slices they manage, so you can use ES6 property shorthand notation: combineReducers({ counter, todos }). This is equivalent to writing combineReducers({ counter: counter, todos: todos })

## Reflection

[README.md](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-37/)

- Seeing how far we are going to go into reducers, I definitely need to get better at how reducers work in a general way before diving into how combineReducers and such works. 

## Class Notes

## Things I want to know more about
