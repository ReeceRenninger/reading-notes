# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Redux Asynchronous Actions

[async actions](https://redux.js.org/advanced/asyncactions)

- Redux middleware is used to intercept and modify actions and the state changes before they reach the reducers, enabling additional functionality such as logging, asynchronous operations, and side effects, and enhancing the capabilities of Redux by providing a customizable and extensible layer between the action dispatch and state update.
- In the Redux Async Data Flow, an action is dispatched, which triggers the middleware to intercept it before it reaches the reducers. The middleware can perform asynchronous operations, such as making API requests, and then dispatch additional actions with the fetched data. These dispatched actions flow through the reducers, updating the state and triggering re-rendering of the UI based on the updated data.
- We can accommodate async operations in our Redux app by using middleware, such as Redux Thunk or Redux Saga, which intercept and handle actions with asynchronous logic, allowing us to make API calls, perform side effects, and dispatch additional actions based on the async results, seamlessly integrating async behavior into the Redux flow.

[thunk middleware](https://github.com/reduxjs/redux-thunk)

- We would need the redux-thunk middleware when we want to handle asynchronous actions in Redux, as it allows us to dispatch functions instead of plain objects, enabling us to perform async operations such as API calls, delay actions, and dispatch additional actions based on the async results within our Redux application.
- Redux Thunk middleware allows you to write action creators that return a **function** instead of an action.
- When a thunk function is dispatched, Redux Thunk middleware intercepts it and invokes the function with dispatch and getState as arguments. Any return value from the inner thunk function can be used to perform asynchronous operations, such as making API calls, and the resulting data can be dispatched as regular actions to update the Redux store.

## Reflection

[README.md](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-38/)

- Understanding thunk will be pretty crucial for this module so I will definitely want to try and hone in on that.

## Class Notes

## Things I want to know more about
