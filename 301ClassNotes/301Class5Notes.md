# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Putting it all together

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1. The single responsibility principle is that a component should only do ONE THING. If it ends up growing in usage, it should be broken down into smaller subcomponents.
2. Building a static version means you'll build components that reuse other components by passing data using props.  We would NOT USE STATE in this because it is static and data should not be changing over time since static builds do not have interactibility.
3. We need to add our root render to populate onto your page, this will allow for data to be change if we need to change the underlying data model to update the UI.
4.

- We can ask is it passed in from a parent via props. If so, it probably IS NOT STATE.

- We can ask does it remain unchanged over time? if so, it probably IS NOT STATE.

- We can ask can it compute is based on any other state or props in your component? if so, IS NOT STATE.

5. We need to find a common component above all the components that NEED the state to OWN the state. If we can't find a common component above the components that need the state, we should create a component purely to house the state to be passed down.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. A function that operates on other functions, either by taking them as arguments or by returning them are called higher-order functions. These allow us to abstract over actions, not just values.
2. Line two of the greaterThan function is a return statement setting the element to m in an arrow function and the conditional of if m > n;
3. Map would transform an array by applying a function to all of its elements and building a new array from the returned values. The new array should have the same length as the input array but the content will have been mapped to a new form by the function being applied to each element.

## Class Notes

## Things I want to know more about
