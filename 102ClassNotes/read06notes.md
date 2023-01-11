# Read 06: Dynamic web pages with JavaScript

[Js Intro Paragraph](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

- JS has a multitude of uses from web site based functions to non-browser functions as well.  It is a prototype based, multi paradigm, single threaded, dynamic language that supports obejc oriented, imperative and declarative programming styles.

- [ECMA](https://tc39.es/ecma262/) sets the standards for the JS language and as browsers implement changes they try to update them.

[Introduction to JavaScript - basic output](https://code-maven.com/introduction-to-javascript)

-Traditionally JS was used in browsers where it would be placed into the HTML page so the user would receive it when they visit the site. JS would run in the browser on the "client side" (the visitor) in comparison to on the "server side".

- Now in more recent years JS has been put on the server as well most notably on Node.js or io.js which started as Node.js fork.

- There are 3 major parts of JS.

1. The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.

2. The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.

3. The server API (or just API) provided by Node.js or one of the other server-side systems.

- Can utilize any text editor, you can include the JS directly in the HTML or link the HTML to a JS file.

- There is alert, document.write, console.log as some simple outputs.

[JavaScript input with prompt and confirm](https://code-maven.com/javascript-input-with-prompt-and-confirm)

- There is a prompt function that is rather simple written in the html
- Script tag is how you hold JS in html documents
  script

  var name = prompt ("Your name:","");

  document.write ("Hello", name);

  /script

- Same format style above can be used with other text values as examples show on page.
- You can also use other pop-up style to ask yes or no questions. This can be done by using the confirm function

script

if (confirm("Shall I print Hellow World?)) {

    document.write("Hello World");

} else {

  document.write ("okay, I won't print it!");
}

/script

[Variables](https://code-maven.com/javascript-input-with-prompt-and-confirm)

- var, let, const are variable that can be set to names or numbers and etc in basic form
- always declare variables as const as general rule
- use let if we think the value of the variable can change
- var is a weird one
- == equal to operator
- many variables in one statment ex.
 let person = "John Doe", carName = "Volvo", price = 200;
- $ and _ are treated as letters in JS, not normally used except specific reasonings

[How Computers Work - Playlist](https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-)

1. Video 1: Bill Gates breaks down what videos will look into about computers

2.Video 2: What makes a computer a computer?

- four major components: Take input, store information, process it, and output results.
- Started out as basic calculators.
- camera, typing, clicking, talking, video, are all input types
- computer processor takes information and converts it and then stores it and stages until ready to be output
- computer output varies on the functionality it was designed for

3.Video 3: Binary and Data

- on / off status of being able to represent bits , with more wires, more bits
- Binary allows 0 and 1 to count up to any number we want based off the order of the 0 and 1 combinations
- 8*, 4*, 2*, 1* poisition with binary
- 32 wires can store over 4 billion numbers....
- Text, images, sounds can all be converted into binary to be represented.
- Video, graphics, photos are represented by pixels, and each pixel has a color, and each color is represented by RBG
- Sound are represented as waveform, which is intrepreted into numbers, more bits means higher range of sound quality

4.Video 4: Circuits and Logic

- Every input and ouput is a type of information being represented by on/off or 1/0s
- Circuits are used to modify or combine information.
- Circuit not and Circuit and operate differently based off their inputs
- Adders are needed to allow computers to process multiple flows of information
- Smaller computers are faster because circuits are traveling smaller distance, moving at the speed of light just about
- Circuits turn binary information into what we see on computers

5.Video 5: CPU, Memory, Input & Output

- A single press of a key is hundreds of processes being done by your computer.
- Pretty amazing how compex simple tasks are and how fast they are completed.

6.Video 6: Hardware and Software

- Hardware is the physical components
- Software is everything that we interact with, like games.
- CPU master chip that controls all the other parts of the computer.
- Circuits for math, or sending or receiving information and the CPU controls what it needs based off our input, pretty amazing.
- Binary runs everything essentially.
- OS manages how software uses the hardware of a computer.

## My 3 Favorite things I learned

- The insane amount of information that is processed for a simple keystroke.
- I didn't know that binary is converted even into the pixel images.
- I did not know how circuits really worked, so its crazy to think how many active circuits are firing inside my CPU everday. No wonder that thing needs its own cooling.

## Class Notes
