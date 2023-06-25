# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes:

[Dan Abramov Redux Tutorials](https://egghead.io/courses/getting-started-with-redux)

- The first principle of Redux is dependent on the size of the application.  The state of the application is stored in an object tree within a single store.  The only way to change the state tree is to emit an action, an object describing what happened.  To specify how the actions transform the state tree, you write pure reducers.
- A store in Redux is a JavaScript object that holds the application state. It serves as a centralized repository for all the data, and we use reducers to update the store by defining pure functions that specify how the state should change in response to dispatched actions.
- Three Redux store methods provided by createStore are:

    getState(): This method returns the current state of the store. It allows you to access the data stored in the Redux store.

    dispatch(action): This method is used to dispatch an action, triggering the state update in the store. It sends the action object to the reducers, which specify how the state should be updated based on the action type.

    subscribe(listener): This method allows you to register a listener function that will be called whenever the state in the store is updated. It provides a way to respond to state changes and update the UI or perform other side effects.
- combineReducers() is a Redux function that combines multiple reducer functions into a single reducer. It is useful because it allows managing different parts of the application state separately, making the code more organized and maintainable. A reducer is like a recipe that takes in ingredients (actions) and cooks them together with the existing dish (state) to create a new version of the dish. It helps in updating and managing the application's data by applying changes based on the actions received.

## Bookmark

[worlds easiest guide to redux](https://medium.freecodecamp.org/understanding-redux-the-worlds-easiest-guide-to-beginning-redux-c695f45546f6)

[testing reducers](https://medium.com/@netxm/testing-redux-reducers-with-jest-6653abbfe3e1)

[Redux docs](https://redux.js.org/)

## Additional Questions

[course schedule](https://codefellows.github.io/code-401-javascript-guide/curriculum/#module-8)

- Looking ahead I think I will enjoy learning Redux because it seems that it will allow for an easier way to manage state and data.

[class README.md](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-36/)

- Really drilling down and understanding the "store" and how it works will be important to understand Redux. I think if I can nail down the store and how it works, the rest of Redux will be easier to understand.

## Class Notes

## Things I want to know more about
