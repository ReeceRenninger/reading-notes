# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes

[JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. An object can be imagined as a container that can hold data like a list or numbers, or it could contain a function from JavaScript that could perform a multitude of things.  
2. Object literals allow for flexibility in declaration, it requires less code to be written and simply convenience.
3. Objects can hold mutable information that can be accessed via key value pairs while arrays also hold information that is mutable but can be accessed by their index position.
4. Dot notation (.) is usually preferred over bracket notation, however if a property is held within an object name, you will need to use bracket notation to access that value. Ex. of that would be:

```js
const person = {
  name: ["Bob", "Smith"],
  age: 32,
};

function logProperty(propertyName) {
  console.log(person[propertyName]);
}

logProperty("name");
// ["Bob", "Smith"]
logProperty("age");
// 32

```

5. The this keyword refers to the current object the code is being written inside of, taking that logic the this keyword in the console log should be referred to this.name as 'Spot' and this.age of '2*7'. Meaning Spot is 14 in human years.

``` js
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}

```

[Introduction to DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. DOM is (Document Object Model) is a programming interface for web documents.  It allows for programs to be able to change document structure, style, and content by modifying it with a language like JavaScript.
2. The relationship between DOM and JS is how JS is able to communicate and alter web pages, HTML documents, SVG documents and their component parts.  DOM is a Web API used to to build websites essentially.

## BookMarks

[Understanding the problem with domain is the hardest part of programming](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)
[What's the difference between primitive values and object references in JavasScript?](https://simpleprogrammer.com/solving-problems-breaking-it-down/)

## Class Notes

## Things I want to know more about
