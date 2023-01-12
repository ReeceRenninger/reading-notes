# Read 08: Operators and Loops

1.[Expressions and Operators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)

- The precedence of operators determines the order in which they are applied, so think of PEMDAS.
- Both of these result in same output

const x = 1 + 2 * 3;
const y = 2 * 3 + 1;

- x = f() would be an example of an assignment operator
- Destructuring can allow extraction of data from arrays or objects using syntax that mirrors contruction of an array or object literals.

ex. 

const foo = ['one', 'two', 'three'];

// without destructuring
const one   = foo[0];
const two   = foo[1];
const three = foo[2];

// with destructuring
const [one, two, three] = foo;

- Chaining or nesting can be with assignment expressions. You can even make a result be itself and be assigned to another variable, this can be logged or put into an array or object

let x;
const y = (x = f()); // Or equivalently: const y = x = f();
console.log(y); // Logs the return value of the assignment x = f().

console.log(x = f()); // Logs the return value directly.

// An assignment expression can be nested in any place
// where expressions are generally allowed,
// such as array literals' elements or as function calls' arguments.
console.log([ 0, x = f(), 0 ]);
console.log(f(0, x = f(), 0));

- Have to be careful when chaining expressions without parentheses because it will cause them to be grouped RIGHT to LEFT, but they wil be evaluated LEFT to RIGHT.

- Comparison operators compares it operands and returns a logical value based on whether the value comparison is true.  These values can be numerical, string, logical or object.
- === and !== are STRICT comparators, this means they will not alter the values in anyway during the comparison, where == and != are more loose and JS will attempt to convert types during comparison

2.[Loops](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Loops_and_iteration)

- loops repeat an action a given number of times. from 0 to infinity (which can break things...)
- for loops repeat until a specified condition is met, the basic syntax would be
for ([initialExpression]; [conditionExpression]; [incrementExpression])
statement
for (     x=0;                  x<=10;                  x++) 
statement
-Steps in a for loop consist of the initialExpression being executed which then leads into the conditionExpression being evaluated, if this is true then the loop executes otherwise it terminates.  The statement is then executed and then the increement occurs until the condition is met over and over.

- A while statment executes its statements as long as a specified condition evaluates to true. Basic syntax would look like:

while (condition)
  statement

-If the condition becomes false, the loops stops and control passes to the statement after the loop
-This is different than the for loop because the condition test occurs BEFORE statement loop is executed.  If this is true then the condition is tested again, once it returns false, it stops.
 
 ex.

 let n = 0;
let x = 0;
while (n < 3) {
  n++;
  x += n;
}

- This will continue until n is less than (<) 3