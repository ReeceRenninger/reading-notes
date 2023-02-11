# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes

[Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)

1. Semantics elements are beneficial in HTML because they help us use previous experiences to understand what that element will do. It allows for concise and efficient readability.
2. There are 6 heading levels in HTML
3. Using superscript or subscript element in niche situations such as writing equations or chemical formulations so they will have the correct formatting style.
4. When using the abbreviation element we muse use a title element if we are providing the full expansion of the term.

[How Css is Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)

1. We can apply CSS to HTML in three different ways. We can use an internal style element, inline on the actual element tags, or externally on a separate CSS file.  The external is the primary way.
2. Inline styles take priority over all other style types so they can be used in some situations but still not advised.  They also require you to MANUALLY style each element rather than in clusters.
3. Review Code Block questions
  - The h2 is the selector being represented.
  - At the basic level components in CSS are properties and values.  The properties are the identifiers for the style change, such as color or font-size. Where value is how to style the selected property. 
  - In this example the color and padding are properties while the black and 5px are the values.

[JavaScript Basics : Starting at Comments to Events](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

1. String data types are enclosed in single quote marks or can be enclosed in double quote marks. Maintain consistency in use either in a file but NOT BOTH.
2. 4 simple operators would be addition +, subtraction -, multiplication *, and division /.  There is also the strict equality ===, assignment =, and does not equal ! or !==.
3. I could use a function as an easy way to convert measurements since it is a reusable piece of code. I could also create a function to solve complex math problems that I do not want to hand write out.

[Making Decisions In Your Code - Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

1. An if statement checks a condition and if that condition is truthy it will execute its block of code.
2. An else if allows us to have more if style statements to check multiple different conditions and have different outcomes based on the executing code.
3. Three types of comparison operators are === and !== that tests if a value is IDENTICAL or not identical to another. The < and > test values are less or greater than each other. And the <= or >= test if values are less than or equal to or greater than or equal to.
4. The logical operators consist of &&, ||, !. The && represents and, that ALL EXPRESSIONS to individually evaluate to true for the whole expression to be true.  Where ||, or, allows you to chain multiple expressions so that only ONE or MORE have to evaluate to true for the whole expression to return true. ! represents NOT so it will give you the opposite of whatever you put it in front of.


## Class Notes 2/7/2023

### Javascript

JavaScript is a **loosely type** and **dynamic** language.

-loosely typed: we don't need to know the type of data before declaring a variable.
-dynamic: we can change the type of data after the variable have been declared.

### Data types

1. Strings

- sequence of charactes that will represent text, wrapped in ' or ".

2. Numbers

- numeric data type.
- full numbers, decimals, negatives

3. Boolean

- logical data type
- true or false
- truthy of falsey

  - numbers only contain 0 as a falsey value, all other numbers are truthy

  - strings only have EMPTY(no space or any value ex '') strings equate to falsey value, all other strings are truthy

  - 

4. Undefined

- it hasn't been DEFINDED yet

5. Null

- has been defined but as none
- let dog = null;



## Things I want to know