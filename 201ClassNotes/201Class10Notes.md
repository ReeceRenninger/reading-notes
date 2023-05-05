# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Debugging

[What Went Wrong? Troubleshooting JavaScript](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

1. Syntax errors are spelling errors that cause your code to not RUN at all, or stop working part way through. This will usually provide error messages. Logic errors are where the syntax is correct but the code is not operating as you intended it to.  Much harder to fix and there usually isn't an error message because the code runs but is not working correctly as wanted.
2. I have had errors telling me declarations are needed before initialization or called the wrong variable due to typos have been seen a lot.  I implemented console logs after each new variable to test to make sure my logic was working correctly and I combed through my code to find any typos I might have done.
3. I will continue to use the console to help debug and set breakpoints so I can see what my code is doing at exact lines of code.  I will also ensure that I ensure I utilize my fellow classmates in code review or my instructor until I am more well versed in debugging.  This also makes me want to try and find a JS debugger extension that is approved by my instructor.

[The JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger)

1. The JS debugger allows for coders to see what their code is running upon execution.  Coders can set break points or pause points to allow for the program to halt execution and show what is happening at that specific line to see if it is working how they intended.
2. A break point is a way to pause the execution of code at a SPECIFIC LINE that the coder sets themselves.  This can allow us to find where a loop may be malfunctioning or showing what the system is taking in as it progresses through your code.
3. The Call Stack shows coders what code was executed to get to the current line of code.  This can be important because it can show if the code did not operate as intended to get to the line where the breakpoint was placed.

## Bookmark

[Debugging HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Debugging_HTML)

[Debugging CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/Debugging_CSS)

## Class Notes

- Array Methods
  - Syntax: array.method();

```js
'use strict';

let months = ['Dec', 'Feb', 'Apr', 'June'];

// ********** ADD TO AN ARRAY *****
// .push(); >>>> adds to the end
months.push('July','Aug');
console.log(months);

// .unshift(); >>> adds to the beginning of array
months.unshift('January');
console.log(months);

// ****** REMOVE FROM AN ARRAY ******
//.pop(); >>> removes the last element in the array - takes no arguments, pop returns the popped element
let aug = months.pop();
console.log(months);
console.log(aug);

//.shift(); >>>> removes the first element in the array - takes no arguments; return the shifted element
let jan = months.shift();
console.log(months);
console.log(jan);

// ********* ADD OR REMOVE from ANYWHERE in the array *****
//.splice()
// arguments - what index to start at, # of elements to remove(if any), what to add (if any)

months.splice(2,0,'March'); //start at index 2, remove nothing, add March in at index 2
console.log(months);

// .include() - return a boolean if the argument is in the array
let isItThere = months.includes('Feb');
console.log(isItThere); //true
```

## Things I want to know more about
