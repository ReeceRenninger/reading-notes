# Notes

[Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)

- Ordered and Unordered Lists

1. Unordered lists are for grouping items that do not need any type of numerical ordering. So maybe a grocery list or a todo list of chores for the day.
2. The bullet styling is associated with css and you would use list-style-type property to make changes.
3. When the order of items is meaningful you should use an ordered list (ol). So if you you are giving instructions of how to bake a cake you should use an ol because you definitely want to combine all the elements in a specific order before throwing it in the oven.
4. You could nest parts of a list or you could do an ordered list inside of an unordered list to change the numbers.

[Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)

- The Box Model

1. The Box Model is a story of protective layers standing against other elements invading. The first line of defense being the margin that is the outer most line of defense with the padding being the last line of defense on the element's content they protect.
2. The 4 parts of the box model are the:
  Content Box: this is the area where your content is displayed, its size can be changed by using inline-size, block-size, width or height.
  Padding Box: this is the "padding" that exists around your content which is considered white space. You can resize using the padding or related properties.
  Border Box: this warps around the content and the padding. Can be resized with border and related properties.
  Margin Box: this is the outermost layer that wraps around the content and all previous mentioned boxes. This is the white space between this box and other boxes surrounding other elements. Can be resized with margin and related properties.

[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)

- Arrays. Operators and Expressions. Conditionals. Loops.

1. Several different data types can be stored in an array.  They can be strings, objects, numbers or even other arrays.
2. Yes it is a valid array below. It is an array holding values within other arrays. We could access the material within by using hte indexOf() method. This takes an argument based off the position we are trying to retrieve something.

``` javascript
const people = [
  ['pete', 32, 'librarian', null], 
  ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], 
  ['bill', null, 'artist', null]
  ]; 
```

3. 5 shorthand operators:
  Addition: x += f() which results in x = x + f()
  Subtraction: x -= f() which results in x = x - f()
  Assignment: x = f() which is x = f()
  Multiplication: x *= f() which results in x = x * f()
  Division: x /= f() which results in x = x / f()
4. The result would be '10dog' from the last expression below.  10 being added to a string 'dog' would concatanate them into a string together and c being false would add nothing to the expression leaving us with '10dog'.

``` javascript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
```

5. In a reward style system a conditional statement could be used.  If you do something, you receive something as a reward.  A conditional could be used in this type of scenario. If x = chores done, code runs to reward you with running/ get money.
6. Whenever you need to iterate over something multiple times or if you need to do something over and over such as a mathemetical equation.
