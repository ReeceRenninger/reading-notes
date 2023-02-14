# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes

[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Domain modeling is creating a concept model in code to solve a specific problem.  The model will describe various entities, their behaviors, attributes as well as any constraints.

[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. HTML tables should be used for tabular data (data normally hosted in a table style). They should not be used in the actually structure of a webpage because they are not automatically responsive as compared to other elements, they can cause code to be harder to write, and they do not work well with screen readers for the visually impaired.
2. A table header a th element, a table row a tr element, and table data a td element are all considered semantic elements.

[Introducing Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. A constructor allows you to create objects by using the new keyword and it will create a new object, bind this to the new object so you can refer to it using your this keyword, run the code within the constructor and return a brand new object.  It allows for objects to be manipulated more easily.
2. This keyword in an object literal will refer to the data that is within the object that is was being used in. Where using the this keyword within a constructor can be bound to the constructor code and then referred back to in your code.

[Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

- NOTE: This is a very common front end developer interview question

1. Prototypes are code that can supply functions, data, or stored input that can then be later utilized through inheritance. The prototype essentially can supply a base behavior to a secondary object.  How that secondary object receives the base behavior is through inheritance.

## BookMarks

[HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)

## Class Notes

-Constructors are a special type of function
  -instantiate/create objects
  -act like a blueprint or 'factory'
  -start with a keyword 'function'
-Why do we use Constructors?
  -keep our code dry
  -helps us to prevent bugs
  -give us a more unified/uniform objects

```js
'use strict';

let personA = {
  name: 'Audrey',
  title: 'Instructor',
  course: '201d97'
};

let personB = {
  name: 'Cameron',
  title: 'Student',
  course: '201d97'
};

let personC = {
  name: 'Laurence',
  title: 'Student',
  course: '201d97'
};

// Constructor function
// Parameters - UNIQUE TO THE OBJECT
// THIS - IN A CONSTRUCTOR refers to the object that will be created

// use capitalization to signify a constructor
function Person(firstName, title){
  this.name = firstName;
  this.title = title;
  this.course = '201d97'
}

// Create Objects using Constructor
let alex = new Person('Alex', 'Student');
let mark = new Person('Mark', 'TA');
let reece = new Person('Reece', 'Student');

console.log(alex); // ouputs Person object with alex as name, student as title, and course as 201d97
console.log(personA);
// PROTOTYPE === INHERTIS
// SPECIAL OBJECT THAT COMES WITH OUR CONSTRUCTOR
// USED TO STORE METHODS

Person.prototype.greeting = function(){
  console.log(`Hello class my name is ${this.name}`);
}

reece.greeting();

Array.prototype.myMethod = function(){
  console.log('I can do this on an array!');
}

let myArr = ['Hello!'];
myArr.myMethod();
```

## Things I want to know more about
