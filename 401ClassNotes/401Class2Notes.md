# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Express, NPM, TDD, CI/CD

[An introduction to NodeJS and Express](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction)

- Middleware is a communication type that web browsers use to communicate with databases to display information. When you submit information on a form with your computer, you are utilizing middleware to send that information to where it is being stored.
- Express is the most popular Node Web Framework.
- Unopinionated frameworks have fewer restrictions on the best way to put components together to achieve a goal.  Express allows you to insert ALMOST ANY middleware to handle your requests.
- A module is a JavaScript library/file that you can import, Express itself is considered a module. Modularization helps developer make their code more readable by separating the modules into their own elements that interact with each other.  This allows for a much more clear understanding of where modules are living and what they are trying to do.

[What is NPM?](https://docs.npmjs.com/getting-started/what-is-npm)

- I am running v19.8.1 Node on my system.
- To install jshint into my node project, I would run npm install jshint in my terminal.

[What is TDD?](https://www.agilealliance.org/glossary/tdd/)

- Tests that developers use are similar to school testing.  Instead of being given material to study and try to apply it to your test to pass, developers are given an issue to solve by a customer or boss and they implement tests to run their code through to attempt to meet the criteria they are being asked to reach.  So similar to how students study to pass a test, developers generate tests to run their code through to try and pass a certain criteria or achieve a desired result.
- Benefits to testing are that many teams report significant reductions in defect rates at the cost of more effort in the initial development.  The same teams tend to report that the overheads are more than offset by the reduction in effort in the final steps of their projects.  Lastly, veteran practitioners report that TDD leads to better design qualities in code and a higher degree of internal or technical quality.
- Some pitfalls with TDD on the personal and team level can be expected though.  On the personal level, individuals can forget to run tests frequently and they can attempt to write too many tests at the same time.  On the team level, teams can have too little adoption of the testing process meaning that too few developers are using the TDD. Lastly, teams can maintain poor maintenance of the test suite, which can cause long run times when running tests.

[CI/CD](https://www.youtube.com/watch?v=xSv_m3KhUO8)

(Answers were googled due to the above link being broken.)

- 3 major benefits to Continuous Integration is smaller code changes, more test reliability, and leads to higher customer satisfaction.  There are many more advantages, some that can be found here [Benefits of Continous Integration and Delivery](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwjs4KaB3uj-AhUIJUQIHZicAzAQFnoECAwQAw&url=https%3A%2F%2Fkatalon.com%2Fresources-center%2Fblog%2Fbenefits-continuous-integration-delivery&usg=AOvVaw0JKoJ_VIGNKcGWIHEH9qfL)
- Continuous delivery is a practice where the code changes are prepared to be released where Continuous Deployment aims to have code released constantly directly into the production environment.
- GitHub allows for developers to have a remote environment that can allow for either type of integration of code.  We can set up our code to be constantly updating directly into the main set of code for a website or application or we can require the code to go into a staging area before going into a production area.

## Bookmark

[nodeJs docs](https://nodejs.org/en/docs/)

[npm docs](https://docs.npmjs.com/)

[express docs](https://expressjs.com/en/4x/api.html)

[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)

[supertest](https://github.com/visionmedia/supertest)

## Reflection

- I want to be comfortable with how to set up a server and run tests on it with confidence.  I feel more comfortable working in the back end on most projects, however I want to get the muscle memory down of how to set it up with the appropriate required elements.

## Class Notes

## Things I want to know more about
