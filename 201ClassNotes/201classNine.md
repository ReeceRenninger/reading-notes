# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

[Your first Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)

[How to structure A Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)

1. Forms allow for an easy way to receive input between the user and the website/application.  We can then take that data to be stored or even use it to immediately alter their interface in some way.  
2. Always try to keep it simple and focused.  Ask only the data you absolutely need. You do not want to frustrate users by having a large form that becomes tedious.
3. The form element is how you can begin the creation of a form, label element allows for us to state what is in each section of the form, input element is what allows us to take from the user whether that be text or numerical or etc, textarea element is the input field for the user to use, and button element can be used for submitting the user information.

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

1. An event in coding can be described as when you click a button and your information disappears or you receive an alert it has been submitted in the simples of terms.
2. When adding an addEventListener() we will need to pass in the name of the function and a function to handle the event as arguments. Such as shown below

```js
const btn = document.querySelector('button');

function random(number) {
  return Math.floor(Math.random() * (number+1));
}

btn.addEventListener('click', () => {
  const rndCol = `rgb(${random(255)}, ${random(255)}, ${random(255)})`;
  document.body.style.backgroundColor = rndCol;
});

```

3. The event object can be typed as event,evt or e and it is automatically passed to event handlers to provide extra features or information.  This is useful because it can allow you to target a specific event target like a button.

4. Event bubbling is how the browser handles events targeted at nested elements. This makes it to where the event fires on the innermost element and then works its way outward to the parent elements. Event Capture works in the opposite where the LEAST nested element fires first and then more nested elements follow suit until the target is reached. Capture is DISABLED by default and you have to manually enable it by passing capture into addEventListener().

## BookMark

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event Reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)

## Class Notes

## Things I want to know more about
