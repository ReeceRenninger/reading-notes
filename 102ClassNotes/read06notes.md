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

[How Computers Work - Playlist](https://www.youtube.com/playlist?list=PLzdnOPI1iJNcsRwJhvksEo1tJqjIqWbN-)

## Class Notes