# [Back to Main Page](https://reecerenninger.github.io/reading-notes/)

## Notes: Express REST API

[Review: ES6 Classes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)

- Classes are a template for creating objects.
- Class declarations can be referenced when a class is created but they cannot use the it before it is defined in the code.
- A constructor is a factory for creating objects, which hold information.  A constructor can be set up to create set data based off how you want the information to be created and saved. So, if you wanted to track your favorite sport athletes, you could create a constructor that takes in their name, age, height, point average, or etc.  When utilizing a constructor we can use a keyword of this. This allows us to reference the inputted information that is being used in creating that object that holds the information.  If you wanted to store the height and weight of someone, you could reference those with this.height and this.weight so when the height and weight are inputted JavaScript knows where to refer to to grab that information.

[Using Express Routing](https://expressjs.com/en/guide/routing.html)

- Routing refers to how an applications endpoints (the URls) respond to a client request. An example would be how an app.get() would handle GET requests.
- Route methods are derived from HTTP methods.  Methods support get, post, put and delete. While route paths are a combination of request methods but these can be strings, string patterns or even RegEx. The route path will alter the URl path name with the inputted string elements as part of a GET request.
- It is appropriate to add next as a parameter in a route if you are calling another middleware in a stack that needs to be called immediately following the route being handled.  When utilizing the next as a parameter YOU MUST CALL THE NEXT() WITHIN THE BODY OF THE FUNCTION to pass control the next callback.

[Express Routing](https://scotch.io/tutorials/learn-to-use-the-new-router-in-expressjs-4)

- An express router is like a mini-express application.  It provides the routing APIs like .use, .get, .param. and .route, but it doesn't provide views or settings.
- By using the express.Router() we can create multiple many instances of Express with just the routing capabilities.  This allows for developers to modularize and create flexibility in their applications.  We can use these Routers to create basic routes, authenticated, or even API routes.
- We use route middleware as a way of DOING SOMETHING BEFORE THE REQUEST IS EVEN PROCESSED.  This could include things like verifying a user is authenticated, logging data, or anything that we want completed before the information hits the user. An example of this is below:

``` JavaScript
...

    // we'll create our routes here

    // get an instance of router
    var router = express.Router();

    // route middleware that will happen on every request
    router.use(function(req, res, next) {

        // log each request to the console
        console.log(req.method, req.url);

        // continue doing what we were doing and go to the route
        next();
    });

    // home page route (http://localhost:8080)
    router.get('/', function(req, res) {
        res.send('im the home page!');
    });

    // about page route (http://localhost:8080/about)
    router.get('/about', function(req, res) {
        res.send('im the about page!');
    });

    // apply the routes to our application
    app.use('/', router);

    ...
```

## Reflection

- I want to be comfortable with all of the CRUD functionality while using Express.  We were exposed to the post, get, put, and delete in our previous classes, but I do not feel completely proficient in them. Being able to be comfortable with SQL databases as well will be a big goal in this section.  Creating a SQL cheat sheet for all the different commands will be helpful when trying to navigate through that type of database.

## Class Notes

## Things I want to know more about
