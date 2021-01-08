# js-quiz

# JavaScript Fundamentals

1. ## In your own words, describe how JavaScript works.

   Javascript is a high-level object oriented, multi-paradigm, event based, single-threaded programming language that uses it's v8 engine to compile code in the browser.

2. ## In your own words, describe how scope works in JS. What are the three types of scope available to us?

   - Global Scope — variables can be accessed everywhere.
   - Function Scope — variables can be accessed in the boundaries of the function in which they are defined.
   - Block Scope — variables can be accessed in the block in which they are defined.

3. ## What are the main data types in JS? Give a few examples.

   - Numbers(The number data type is used to represent positive or negative numbers)
   - Strings(A string is a sequence of one or more characters that may consist of letters, numbers, or symbols)
   - Booleans (true or false - conditional statements)
   - null (A null value means that there is no value. It is not equivalent to an empty string ("") or 0, it is simply nothing.)
   - undefined (If a variable has been declared, but has not been assigned a value it has the value undefined)

4. ## In your own words, describe the relationship between values and variables in JS.

   A variable is a holder for a representation of a value.
   Also, variables, unlike values, can be updated; that is, the current value of the variable can be replaced by another value.

5. ## What is the difference between var, let, and const?

   - JavaScript variables declared with var and function are hoisted and automatically initialized to undefined.

   - Contrastingly, variables declared with let, const, and class are hoisted but remain uninitialized.Where they differ from other declarations in the hoisting process is in their initialization.

   - var variables can be updated and re-declared within its scope;
     let variables can be updated but not re-declared;
   - const variables can neither be updated nor re-declared.

6. ## What is an IFFE (Immediately Invoked Function)?

   A JavaScript function that runs as soon as it is defined. Immediately invoked functions may be used to prevent variable hoisting, stop pollution of the global env, allow access to methods while retaining local scope.

7. ## What is console.log()? Are there other types of console. methods? If so, name a couple.

   - The Console method log() outputs a message to the web console. The message may be a single string (with optional substitution values), or it may be any one or more JavaScript objects.

   - console.error()
   Outputs an error message. You may use string substitution and additional arguments with this method.
   - console.info()
   Informative logging of information. You may use string substitution and additional arguments with this method.
   - console.warn()
   Outputs a warning message. You may use string substitution and additional arguments with this method.

8. ## What is hoisting?

   Hoisting is JavaScript's default behavior of moving declarations to the top.

9. ## What are the 3 primary ways to define functions in JS? What are the key differences between them?

   - function declaration: Function declarations are used to create named functions. These functions can be called using their declared name.
   - Function expression: Function expressions create functions inside an expression instead of as a function declaration. They can be anonymous and/or assigned to a variable.
   - Anonymous function: Anonymous functions in JavaScript do not have a name property. They can be defined using the function keyword, or as an arrow function

10. ## What is the difference between a parameter and an argument?

    Function parameters are the names listed in the function's definition. Function arguments are the real values passed to the function.

11. ## What is the spread operator? What is a use case?

       The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable (e.g an array) and expands it into individual elements.
       The spread operator is commonly used to make shallow copies of JS objects. Using this operator makes the code concise and enhances its readability. (i.e. concadenation, adding to array)

12. ## What is a callback function?

     A callback funtion is a function passed into another function as an argument.

13. ## What is a higher order function? Describe what filter(), map(), reduce(), sort() do.

    A Higher Order Function is any function that returns a function when executed, takes a function as one or more of its arguments, or both.

    - filter(): Calls a provided callback function once for each element in an array, and constructs a new array of all the values for which callback returns a value that coerces to true
    - map(): Creates a new array with the results of calling a function for every array element
    - reduce(): Method that reduces array to a single value. The return value of the function is stored in an accumulator.
    - sort(): Sorts the elements of an array in place and returns a sorted array.

14. ## What is an event loop?

    JavaScript has a concurrency model based on an event loop, which is responsible for executing the code, collecting and processing events, and executing queued sub-tasks.

15. ## What is a closure? Why is it an important feature in JS?

    A closure is a function inside of another function, allowing access to the scope of the outer function.

16. ## In your own words, describe prototype inheritance in JS?

    Prototype inheritance is the action of inheriting properties from a parent element.

17. ## What is the difference between synchronous and asynchronous programming?

    So to recap, synchronous code is executed in sequence – each statement waits for the previous statement to finish before executing. Asynchronous code doesn't have to wait – your program can continue to run. You do this to keep your site or app responsive, reducing waiting time for the user.

18. ## What is 'this'?

    - 'this' is a keyword, which refers to a    property in the global scope.

19. ## What is a promise? Why do we need promises?
    - The Promise represents the eventual completion or failure of an asynchronous  operation and its resulting value.
    We need promises to execute code, especially when working with APIs

20. ## What is async await & try catch?
    Await is a keyword used before an asynchronous function to wait for the return of promise. Try catch marks a block of statemnets to try and specifies a response should an error be thrown.

21. ## What is NodeJS?

    Node. js is a JavaScript runtime built on Chrome's V8 JavaScript engine. Node. js uses an event-driven, non-blocking I/O model that makes it lightweight and efficient.

22. ## What is ExpressJS?

    Express. js is a Node js web application server framework, which is specifically designed for building single-page, multi-page, and hybrid web applications

23. ## What is middleware? Give examples.
      Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function. ex. const router = express.Router()

24. ## What is method-override? Why do we need it?

      Lets you use HTTP verbs such as PUT or DELETE in places where the client doesn't support it.

25. ## Why did we need EJS? What are some other templating engines?

      We need EJS to execute JS within an HTML view, and to pass values into the view to display. Other templating engines are PUG, React etc.

26. ## What are the restful routes (verbs)? Describe them.

       GET lists everything, POST creates a new  object then redirects, PUT is used to update an object, DELETE deletes a particular object.

27. ## What is req.body? req.params.id?

      Req.body is an object which is returned from a webpage containing properties defined within a form. Req.params.id returns the id variable we defined in a specific route. We use a colon to designate any route variable we wish to access with req.params.

28. ## What is mongooseJS?

      Mongoose is an Object Data Modeling (ODM) library for MongoDB and Node. js. It manages relationships between data, provides schema validation, and is used to translate between objects in code and the representation of those objects in MongoDB. Object Mapping between Node and MongoDB managed via Mongoose.

29. ## What kind of database is MongoDB? What is the other kind? What is an example use case of each?
      Mongo is a NoSQL database, the other kind is SQL. SQL databases are relational, NoSQL are non-relational.

30. ## What is the difference between Authentication and Authorization?

    Authentication confirms that users are who they say they are. Authorization gives those users permission to access a resource.

31. ## What is the difference between Object Oriented Programming and Functional Programming?

      - Functional programming and object-oriented programming uses a different method for storing and manipulating the data.
      - In functional programming, data cannot be stored in objects and it can only be transformed by creating functions.
      - In object-oriented programming, data is stored in objects.
32. ## Describe the following native errors in JS: RangeError, ReferenceError, SyntaxError, TypeError, and InternalError?

       - The RangeError object indicates an error when a value is not in the set or range of allowed values.
       - The ReferenceError object represents an error when a non-existent variable is referenced.
       - SyntaxError indicates that you could have left a bracket unclosed or missing quotations.
       - The TypeError object represents an error  when an operation could not be performed, if you give it a string and it is expecting a number you will get a TypeError.
       - The InternalError object indicates an error that occurred internally in the JavaScript engine.
33. ## What is your favorite feature of JS? Why?

      Arrow functions are a lot prettier and easier to read

34. ## What is the difference between Declarative Programming and Imperative Programming?

      Declarative programming is a programming paradigm … that expresses the logic of a computation without describing its control flow.

    Imperative programming is a programming paradigm that uses statements that change a program’s state.