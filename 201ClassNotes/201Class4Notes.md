# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

# Notes: HTML Links, JS Functions, and Intro to CSS Layout

[Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)
[Creating Hyperlinks](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks)

1. To create a basic link we wrap the text in an a element.
2. The href inside the opening a tag contains the url for the link.
3. We can add titles to them to show where the links will take them and possibly give some basic information.  As well as ensuring they will be visible by having good contrast ratio.

[CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout)
[CSS Layout: Normal Flow](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Normal_Flow)
[CSS Layout: Positioning](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Positioning)

1. Normal flow is how elements are laid out with no CSS changes having been made.  The normal flow is set up to allow for good readability for limited browsers with no styling added.
2. Block level elements fill the available inline space of a parent element. The element will grow along the block dimension. Where inline elements is just the size of their content.  They just sit inside the content of the block level elements.
3. STATIC positioning is the default for every HTML element.
4. Absolute positioning can allow for elements to be treated as their own entities and not be affected by surrounding elements.  This can allow for them to be on a layer of their own for creating isolated features. This can allow for creating menus, popup information, or features that can be dragged and dropped anywhere on a page.
5. Fixed and absolute positioning only have ONE key difference. This is where absolute positioning fixes an element in place to its nearest positioned block, fixed positioning *usually* fixes an element in place relate to the visible portion of the viewport.

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
[Functions - Reusable Blocks of Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Functions)

1. A function declaration is the function being created essentially.  Where invoking a function is calling the created function into action to execute the code within it.
2. Parameters are what we pass into a function(parameter) to set what they function can receive.  Arguments are what we pass into the function when invoking for that value to be ran through the function.

[6 Reasons for Pair Programming](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)

1. The top 2 benefits to Pair Programming for me would be work environment readiness and learning from fellow students.  Given that companies do pair-programming for new hires, means I will feel more comfortable when expected to do it and be able to work better in that environment.  Also, being able to learn from each other is vital to me.  I know that I am not the best at every aspect of coding, so being able to learn and work with others will be huge for me.

## Class Notes

- Refer to video if I need a break down on the nesting loops from code review at beginning of day
- CSS fixed and absolute can be interesting to use as I style my page more.

### Functions

- reusable piece of code
- anatomy of a function - function declaration
- function = keyword, sum = function name, a & b = parameters
- 2 step process of declaration/declare and call/invoke.
- HOISTING is very important, first pass it hoists all the variables and functions then on second pass it invokes/calls all the functions.

```js
 'use strict';

function sum(a,b){
   return a + b;
}
sum(); // < -- Calling the function to be activated, can pass arguments into the ().

// function declaration
function greeting(){
  console.log('Hello Class!');
}
greeting();

//function expression
let newGreeting = function(){
  console.log('A new hello to you!')
}
newGreeting();
```

More Examples

```js

function equations(a,b){
  let product = a*b;
  let sum = a+b;
  let difference = a-b;
  //can use array with return to return more than ONE thing
  // returns primarily return one value
  return [product, sum, difference];
}

let myNumbers = equations(5,10);
console.log(myNumbers); //[50,15,-5]
//this calls equations function with 2 arguments BUT then focuses on the product by using [0].
let myProduct = equations(2,10)[0];
console.log(myProduct); // 20
```

## Things I want to know
