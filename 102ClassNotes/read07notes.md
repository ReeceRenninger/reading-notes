# Read 07: Programming with Javascript

1. [MDN Control Flow](https://developer.mozilla.org/en-US/docs/Glossary/Control_flow)

- Control is th eorder in which the compouter executes the statements within a script
- Can be used to notify a user that a field must be filled in.
ex. 
if (isEmpty(field)) {
  promptUser();
} else {
  submitForm();
}
- Control structures can dictate the complex flows of processing with only a few lines of code.

2.[Functions](https://www.w3schools.com/js/js_functions.asp)

- A JS function is a block of code designed to perform a particular task.
- A function is executed when "something" invokes it or calls it.
- ex of a simple function

// Function to compute the product of p1 and p2
function myFunction(p1, p2) {
  return p1 * p2;
}
    // THE CODE BELOW IS CALLING THE FUNCTION ABOVE //
document.getElementById("demo").innerHTML = myFunction(4, 3);

- Function name () is the basic syntax. Function names can contain letters, digits, underscores and dollar signs, the same rules as variables
- Function parameters are listed in inside the parentheses can be multiple if commas are used, above example uses p1, p2.
- Function arguments are the values received by the function when invoked, the above example is using 4,3 as arguments.
- When JS reaches a return statment the function will STOP executing.

ex.

let x = myFunction(4, 3);   // Function is called, return value will end up in x

function myFunction(a, b) {
  return a * b;            // Function returns the product of a and b (12)
}

- Functions are resuable code such as conversion functions such as Fahrenheint to Celsius.

function toCelsius(fahrenheit) {
  return (5/9) * (fahrenheit-32);
}
document.getElementById("demo").innerHTML = toCelsius(77); 

- ^ using this, the toCelsius refers to the function object, and to Celsius() refers to the function result.

- Variables declared WITHIN a function become LOCAL to the function, so they can only be expressed there.

// code here can NOT use carName

function myFunction() {
  let carName = "Volvo";
  // code here CAN use carName
}

// code here can NOT use carName 

- This can allow for variables when the same name to be used in different functions becuase local variable are created when the function starts and deleted when it is completed.

3.[Operators](https://www.w3schools.com/js/js_operators.asp)

- There are Arthemtic, Assignment, cOmprison, Logical, Conditional, and Type operators
- Arthemtic Operators inclue +, -, *, ** (exponentation), / , % (modulus or division remainder), ++ (increment), -- (decrement)
- Assignment operators can be =, +=, -=, *=, /=, %=, **=. Refer to assignment operators image on local storage for detailed examples.

- Comparison operators 
== equal to
=== equal value and equal type
!= not equal
!== not equal value or not equal type
> greater than
< less than
>= greater than or equal to
<= less than or equal to
? ternary operator

- Logical operators are && (logical and), || (logical or), ! (logical not)
- Type operators type of(returns the type of a variable) and instanceof (returns true if an object is an instance of an object type)
- Bitwise operators work on 32 bits numbers, examples can be found at the link above.

Skim Material
[Expressions and Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
[Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)