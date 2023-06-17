# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Component Based UI

[React Quick Start](https://react.dev/learn)

- The building blocks of a React app are components, which are reusable and independent pieces of UI that encapsulate logic and render a part of the user interface.
- HTML elements represent the structure and content of a web page, React components are reusable, self-contained UI elements that manage their own state and provide dynamic rendering based on props and state changes.
- JSX is a syntax extension for JavaScript used in React that allows us to write HTML-like code in JavaScript, making it easier to write and understand the structure and logic of UI components.
- In JSX, JavaScript expressions can be embedded by using curly braces {} to wrap the expression, allowing dynamic values and computations to be included within the JSX markup.
- React and JSX provide special features for iteration and conditional logic. For iteration, React provides the map() method to iterate over an array and render a list of elements. JSX also allows embedding JavaScript expressions within curly braces to generate content based on conditionals we build out. Additionally, React provides features like useState and useEffect hooks to handle state and lifecycle-related logic.
- React knows how to respond to user's input based on event handling.  Such as utilizing an onClick, onChange, or onSubmit to trigger some type of event that is listening specifically for that.
- The word that indicates that a React component that manages data with a Hook is a useState. This hook is used in React to add state management capabilities to functional components.
- Two React components can share data by lifting the state up to a common parent component and passing the data down to the child components as props.

[Render and Commit](https://react.dev/learn/render-and-commit)

- The three steps of refreshing a React UI are: updating the component state, re-rendering the component tree, and applying the changes to the actual DOM.
- To trigger updates to a component after the initial render, you can use various methods, such as calling the setState function with new state values, using lifecycle methods like componentDidUpdate, or utilizing React Hooks like useEffect to listen for changes and update the component accordingly.
- No, React does not recreate DOM nodes on every rerender. React uses a virtual DOM and a diffing algorithm to efficiently update only the necessary parts of the DOM when a component is rerendered. It compares the previous virtual DOM representation with the new one and applies the minimal set of changes needed to bring the DOM in sync with the new component state.
- The browser needs to re render all the updated elements still.  So, triggering a redeploy with the previous ways in the last question would be the easiest way.

## Bookmark

[Your First Component](https://react.dev/learn/your-first-component)

[Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)

[Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

[sass cheatsheet](https://devhints.io/sass)

[react cheatsheet](https://devhints.io/react)

## Additional Questions

- Intuitive naming is always the best way to go.  Keeping code concise and functional so others could come in and understand what you are doing, even without talking to you.
- Diving deeper into React and what we can do with it.  I got a good amount of information from previous courses, but I know that I can learn a lot more still.
- Getting more comfortable with how to use JSX in front end deployments. I think that will be a big difference for me.

## Class Notes

## Things I want to know more about
