# Node.js Interview Questions

## Table of Contents

- [JavaScript](#javascript)
  - [1. What is JavaScript?](#1-what-is-javascript)
  - [2. What are the different data types in JavaScript?](#2-what-are-the-different-data-types-in-javascript)
  - [3. What is the difference between == and ===?](#3-what-is-the-difference-between--and-)
  - [4. What are JavaScript functions?](#4-what-are-javascript-functions)
  - [5. What are closures in JavaScript?](#5-what-are-closures-in-javascript)
  - [6. What is the difference between let, const, and var?](#6-what-is-the-difference-between-let-const-and-var)
  - [7. What is the difference between undefined and null?](#7-what-is-the-difference-between-undefined-and-null)
  - [8. What are operators in JavaScript?](#8-what-are-operators-in-javascript)
  - [9. What are events in JavaScript?](#9-what-are-events-in-javascript)
  - [10. What are the Array in JavaScript?](#10-what-are-the-array-in-javascript)
  - [11. What is callback in JavaScript?](#11-what-is-callback-in-javascript)
  - [12. What is promises in JavaScript?](#12-what-is-promises-in-javascript)
  - [13. What is async/await in JavaScript?](#13-what-is-asyncawait-in-javascript)
  - [14. What is DOM?](#14-what-is-dom)
  - [15. What is JSON?](#15-what-is-json)
  - [16. What is arrow function in JavaScript?](#16-what-is-arrow-function-in-javascript)
  - [17. What is Spread operator and Rest parameter in JavaScript?](#17-what-is-spread-operator-and-rest-parameter-in-javascript)
  - [18. What is purpose of try, catch and finally block in JavaScript?](#18-what-is-purpose-of-try-catch-and-finally-block-in-javascript)
  - [19. Difference between function expression and function declaration in JavaScript?](#19-difference-between-function-expression-and-function-declaration-in-javascript)
  - [20. What is difference between map() and forEach() in JavaScript?](#20-what-is-difference-between-map-and-foreach-in-javascript)
  - [21. What is callback hell and how it avoided?](#21-what-is-callback-hell-and-how-it-avoided)
  - [22. What is Deep copy and Shallow copy in JavaScript?](#22-what-is-deep-copy-and-shallow-copy-in-javascript)
  - [23. What is Synchronous and Asynchronous in JavaScript?](#23-what-is-synchronous-and-asynchronous-in-javascript)
  - [24. What is difference between While and doWhile?](#24-what-is-difference-between-while-and-dowhile)
  - [25. What is Currying in JavaScript?](#25-what-is-currying-in-javascript)
  - [26. Call By Value & Call By Ref](#26-call-by-value--call-by-ref)

- [Node.js](#nodejs)
  - [1. What is Node.js?](#1-what-is-nodejs)
  - [2. Why Node.js?](#2-why-nodejs)
  - [3. What is Event-Loop?](#3-what-is-event-loop)
  - [4. What is Event-Driven?](#4-what-is-event-driven)
  - [5. What is Non-blocking I/O?](#5-what-is-non-blocking-io)
  - [6. What are callbacks in Node.js?](#6-what-are-callbacks-in-nodejs)
  - [7. What is the difference between require() and import in Node.js?](#7-what-is-the-difference-between-require-and-import-in-nodejs)
  - [8. What is middleware?](#8-what-is-middleware)
  - [9. What is Buffer in Node.js?](#9-what-is-buffer-in-nodejs)
  - [10. What is Stream in Node.js?](#10-what-is-stream-in-nodejs)
  - [ 11. What is Cluster in Node.js?](#11-what-is-cluster-in-nodejs)
  - [12. What is Thread Pool in Node.js?](#12-what-is-thread-pool-in-nodejs)
  - [13. What is Worker Thread in Node.js?](#13-what-is-worker-thread-in-nodejs)
  - [14. What is Child Process in Node.js?](#14-what-is-child-process-in-nodejs)
  - [15. What is a module in Node.js?](#15-what-is-a-module-in-nodejs)
  - [16. Is Node.js single-threaded?](#16-is-nodejs-single-threaded)
  - [17. What is npm and its advantages?](#17-what-is-npm-and-its-advantages)
  - [18. What is package.json in Node.js?](#18-what-is-packagejson-in-nodejs)
  - [19. What is body-parser in Node.js?](#19-what-is-body-parser-in-nodejs)
  - [20. What is CORS in Node.js?](#20-what-is-cors-in-nodejs)
  - [21. What is libuv library?](#21-what-is-libuv-library)
  - [22. What is REPL in Node.js?](#22-what-is-repl-in-nodejs)
  - [23. Authentication & Authorization?](#23-authentication--authorization)
  - [24. EventEmitter in Node.js?](#24-eventemitter-in-nodejs)
  - [25. setTimeout & setImmediate?](#25-settimeout--setimmediate)
  - [26. How do you handle errors in Node.js?](#26-how-do-you-handle-errors-in-nodejs)
  - [27. What is the role of the global object in Node.js?](#27-what-is-the-role-of-the-global-object-in-nodejs)
  - [28. What is process.nextTick() in Node.js?](#28-what-is-processnexttick-in-nodejs)

- [Express](#express)
  - [1. What is Express.js?](#1-what-is-expressjs)
  - [2. What is the difference between app.use() and app.all() in Express?](#2-what-is-the-difference-between-appuse-and-appall-in-express)
  - [3. What is the difference between res.send() and res.json() in Express?](#3-what-is-the-difference-between-ressend-and-resjson-in-express)
  - [4. What is Express Router?](#4-what-is-express-router)
  - [5. How do you handle errors in Express.js?](#5-how-do-you-handle-errors-in-expressjs)
  - [6. What is the purpose of req.body in Express.js?](#6-what-is-the-purpose-of-reqbody-in-expressjs)
  - [7. What is the purpose of app.listen() in Express.js?](#7-what-is-the-purpose-of-applisten-in-expressjs)
  - [8. What is the purpose of app.use() in Express.js?](#8-what-is-the-purpose-of-appuse-in-expressjs)

- [MongoDB](#mongodb)
  - [1. What is MongoDB?](#1-what-is-mongodb)
  - [2. What is the difference between SQL and NoSQL databases?](#2-what-is-the-difference-between-sql-and-nosql-databases)
  - [3. What are collections and documents in MongoDB?](#3-what-are-collections-and-documents-in-mongodb)
  - [4. What is BSON in MongoDB?](#4-what-is-bson-in-mongodb)
  - [5. What is the difference between find() and findOne() in MongoDB?](#5-what-is-the-difference-between-find-and-findone-in-mongodb)
  - [6. What is an ObjectId in MongoDB?](#6-what-is-an-objectid-in-mongodb)
  - [7. What is indexing in MongoDB?](#7-what-is-indexing-in-mongodb)
  - [8. Replication in MongoDB?](#8-replication-in-mongodb)
  - [9. Sharding in MongoDB?](#9-sharding-in-mongodb)
  - [10. Replica Set in MongoDB?](#10-replica-set-in-mongodb)
  - [11. What is .pretty() in MongoDB?](#11-what-is-pretty-in-mongodb)
  - [12. Scaling in MongoDB?](#12 -scaling-in-mongodb)
  - [13. What is Aggregation?](#13-what-is-aggregation)

## JavaScript

### 1. What is JavaScript?
Answer: JavaScript is a scripting language used for creating dynamic web content. It is dependent, single-threaded, and synchronous by default but supports asynchronous behavior.

### 2. What are the different data types in JavaScript?
Answer: Primitive types: String, Number, Boolean, Null, Undefined, Symbol, BigInt. Non-primitive types: Object, Arrays, and Date.

### 3. What is the difference between `==` and `===`?
Answer: `==` tries to convert the value to the same data type, while `===` strictly checks both the value and the data type.

### 4. What are JavaScript functions?
Answer: A function is a block of reusable code designed to perform a particular task.

### 5. What are closures in JavaScript?
Answer: A closure has access to its outer scope variables even after the outer function has executed.

### 6. What is the difference between let, const, and var?
Answer: Var is global level scope; it can be redeclared and re-assigned. Let and const are ES6 features with block-level scope; let cannot be redeclared but can be re-assigned, while const cannot be redeclared or re-assigned.

### 7. What is the difference between undefined and null?
Answer: Undefined means a variable has been declared but not assigned a value, while null means a variable has been assigned the value null.

### 8. What are operators in JavaScript?
Answer: There are three types of operators: Assignment, Logical, and Arithmetical.

### 9. What are events in JavaScript?
Answer: JavaScript events are actions or occurrences that happen in the browser, triggered by user interaction or the browser itself.

### 10. What are Arrays in JavaScript?
Answer: Arrays are used to store multiple data in a single variable.

### 11. What is a callback in JavaScript?
Answer: A callback is a function that is passed as an argument to another function.

### 12. What are promises in JavaScript?
Answer: Promises are objects in JavaScript that take a function with resolve and reject as arguments. They provide a way to handle asynchronous operations and enable better control flow.

### 13. What is async/await in JavaScript?
Answer: These are keywords used to handle asynchronous operations more easily. `async` makes a function asynchronous, and `await` pauses the execution until the asynchronous operation is resolved.

### 14. What is DOM?
Answer: DOM stands for Document Object Model. It is a programming interface that provides a way to access, manipulate, and interact with the structure of a web document.

### 15. What is JSON?
Answer: JSON stands for JavaScript Object Notation. It is a lightweight format for storing and transporting data.

### 16. What is an arrow function in JavaScript?
Answer: An arrow function is a shorter way to write a function.

### 17. What is the Spread operator and Rest parameter in JavaScript?
Answer: The spread operator allows you to expand or unpack items into arrays or objects, while the rest parameter allows a function to take any number of arguments and puts them into an array.

### 18. What is the purpose of try, catch, and finally blocks in JavaScript?
Answer: The try block contains code that might throw an exception. If an exception occurs, it is caught by the catch block, which contains error handling logic. The finally block, if present, is executed regardless of whether an exception is thrown.

### 19. What is the difference between function expression and function declaration in JavaScript?
Answer: The difference lies in syntax and hoisting. A function declaration is defined with the function keyword and is hoisted, while a function expression is defined by assigning a function to a variable and is not hoisted.

### 20. What is the difference between map() and forEach() in JavaScript?
Answer: The map() function creates a new array by transforming each element in an existing array, while forEach() executes a function for each element but doesn't return anything.

### 21. What is callback hell and how is it avoided?
Answer: Callback hell occurs when multiple callback functions are nested, making the code harder to read. It can be avoided using Promises, async/await, and try/catch blocks.

### 22. What is Deep copy and Shallow copy in JavaScript?
Answer: A shallow copy creates a new object with references to the same memory location as the original object, while a deep copy creates a new object with new memory locations for all properties and nested arrays or objects.

### 23. What is Synchronous and Asynchronous in JavaScript?
 Answer: Asynchronous is a non-blocking architecture where the execution of one task does not depend on another task, while synchronous is a blocking architecture where the execution of each operation depends on completing the one before it.

### 24. What is the difference between While and doWhile?
Answer: The while loop checks the condition before executing the loop body, whereas the do...while loop executes the loop body at least once before checking the condition.

### 25. What is Currying in JavaScript?
Answer: Currying is a functional programming concept where a function is transformed into a sequence of functions, each taking a single argument. Instead of taking all its arguments at once, a curried function takes one argument and returns a new function that takes the next argument.

### 26. Call By Value & Call By Ref:
Answer: 
- **Call By Value**: A copy of the value is passed to the function; changes inside the function do not affect the original value. It uses primitive data types like number and string.
- **Call By Ref**: A reference (memory address) to the value is passed; changes inside the function affect the original value. It uses non-primitive data types like object and array.

## Node.js

### 1. What is Node.js?
Answer: Node.js is a runtime environment that allows you to run JavaScript outside of a web browser. It is used for building fast, scalable, and efficient server-side applications using JavaScript.

### 2. Why Node.js?
Answer: Node.js offers significant advantages such as fast and efficient performance, high scalability, and asynchronous, non-blocking I/O.

### 3. What is Event-Loop?
Answer: The event loop is a mechanism that handles asynchronous operations, allowing Node.js to perform non-blocking I/O operations in a single-threaded manner.

### 4. What is Event-Driven?
Answer: Event-driven programming in Node.js uses an event loop to manage multiple events asynchronously, ensuring that tasks don't wait for each other to finish.

### 5. What is Non-blocking I/O?
Answer: The non-blocking model ensures that tasks don't wait for each other to finish.

### 6. What are callbacks in Node.js?
Answer: A callback is a function that is passed as an argument to another function.

### 7. What is the difference between require() and import in Node.js?
Answer: require() is used to include modules in Node.js (CommonJS style), while import is part of ES6 module syntax.

### 8. What is middleware?
Answer: Middleware functions sit between the request and response cycle, performing tasks like logging, authentication, and data processing.

### 9. What is Buffer in Node.js?
Answer: A buffer is a temporary storage space for binary data, allowing Node.js to handle raw data directly, such as files and images.

### 10. What is Stream in Node.js?
Answer: A stream is a way to handle data that is too large to process all at once by breaking it into smaller chunks, allowing reading or writing data piece by piece instead of loading everything into memory at once.

### 11. What is Cluster in Node.js?
Answer: The Cluster module is used to run multiple instances of Node.js that can distribute workloads among their application processes, enabling the creation of child processes (called workers) that run simultaneously.

### 12. What is Thread Pool in Node.js?
Answer: A thread pool is a collection of worker threads that manage heavy tasks, such as API fetching and network-related operations.

### 13. What is Worker Thread in Node.js?
Answer: In Node.js, Worker Threads provide a way to execute JavaScript code in parallel across multiple threads.

### 14. What is Child Process in Node.js?
Answer: In Node.js, a child process is a separate process created by a Node.js application to perform tasks in parallel.

### 15. What is a module in Node.js?
Answer: A module in Node.js is a block of code that provides specific functionality, which can be reused across different parts of an application.

### 16. Is Node.js single-threaded?
Answer: Yes, Node.js is single-threaded but uses event-driven architecture and non-blocking I/O to handle multiple requests efficiently.

### 17. What is npm and its advantages?
Answer: npm is the default package manager for Node.js, offering benefits like dependency management, version control, and a centralized repository.

### 18. What is package.json in Node.js?
Answer: package.json is a metadata file in Node.js that contains information about the project, such as dependencies, scripts, and version.

### 19. What is body-parser in Node.js?
Answer: Body-parser is middleware that parses incoming request bodies in a middleware before handling it in Node.js applications.

### 20. What is CORS in Node.js?
Answer: CORS stands for Cross-Origin Resource Sharing, allowing restricted resources on a web page to be requested from another domain.

### 21. What is libuv library?
Answer: Libuv is a powerful library written in C that gives Node.js its ability to handle asynchronous operations and non-blocking I/O.

### 22. What is REPL in Node.js?
Answer: REPL stands for Read, Evaluate, Print, and Loop; it's an interactive environment for executing Node.js code and debugging. 
- **Read**: Takes user input and parses it into a JavaScript expression.
- **Eval**: Evaluates the parsed JavaScript code.
- **Print**: Displays the result of the evaluated code to the user.
- **Loop**: Repeats the process for the next input.

### 23. Authentication & Authorization?
Answer: Authentication is the process of verifying the identity of a user. Authorization is the process of determining what that person is allowed to do or access after they’ve been authenticated.

### 24. EventEmitter in Node.js?
Answer: EventEmitter is a class in Node.js used to handle events. It allows objects to emit events (e.g., "data" or "error") and listen for them to perform actions when they occur.

### 25. setTimeout & setImmediate?
Answer: setTimeout() delays the execution of a function by a specified time, while setImmediate() schedules a function to run after the current event loop cycle.

### 26. How do you handle errors in Node.js?
Answer: There are several ways to handle errors in Node.js, including Promises, async/await, and try/catch blocks.

### 27. What is the role of the global object in Node.js?
Answer: The global object in Node.js provides global variables and functions that can be accessed anywhere in your application. It’s similar to the window object in browsers.

### 28. What is process.nextTick() in Node.js?
Answer: process.nextTick() is used to execute a function after the current operation completes, but before any I/O tasks. It ensures that a callback is executed as soon as possible.

## Express

### 1. What is Express.js?
Answer: Express.js is a minimal and flexible Node.js web application framework that provides a set of features for building web and mobile applications. It simplifies the process of handling HTTP requests, routing, middleware, and managing views. Express is widely used for creating RESTful APIs and web applications.

### 2. What is the difference between app.use() and app.all() in Express?
Answer: app.use() is used to apply middleware functions to routes, while app.all() is used to define handlers for all HTTP methods (GET, POST, etc.) for a specific route.

### 3. What is the difference between res.send() and res.json() in Express?
Answer: res.send() is used to send a response of any type (text, HTML, etc.), while res.json() is specifically used to send a JSON response.

### 4. What is Express Router?
Answer: Express Router is a feature that allows you to create modular route handlers.

### 5. How do you handle errors in Express.js?
Answer: Errors in Express.js are handled using middleware functions with four parameters: err, req, res, next.

### 6. What is the purpose of req.body in Express.js?
Answer: req.body contains data sent in the body of the HTTP request, typically used in POST or PUT requests to handle form data or JSON payload.

### 7. What is the purpose of app.listen() in Express.js?
Answer: app.listen() is used to bind and listen for incoming HTTP requests on a specific port.

### 8. What is the purpose of app.use() in Express.js?
Answer: app.use() is used to apply middleware functions to specific routes or all routes in an Express application.

## MongoDB

### 1. What is MongoDB?
Answer: MongoDB is a NoSQL database that stores data in a flexible, JSON-like format called BSON (Binary JSON). It allows you to store and query large amounts of unstructured data.

### 2. What is the difference between SQL and NoSQL databases?
Answer: SQL databases store data in tables with a fixed schema (e.g., MySQL), while NoSQL databases like MongoDB store data in collections with a flexible schema (e.g., documents).

### 3. What are collections and documents in MongoDB?
Answer: A collection is a group of MongoDB documents, similar to a table in SQL. A document is a set of key-value pairs, similar to a row in SQL.

### 4. What is BSON in MongoDB?
Answer: BSON (Binary JSON) is a binary format that MongoDB uses to store data.

### 5. What is the difference between find() and findOne() in Mongo DB?
Answer: find() returns an array of documents that match the query, while findOne() returns only the first document that matches the query.

### 6. What is an ObjectId in MongoDB?
Answer: ObjectId is a unique identifier automatically assigned to documents when they are created.

### 7. What is indexing in MongoDB?
Answer: Indexing in MongoDB is a way to improve query performance.

### 8. Replication in MongoDB?
Answer: Replication is the process of creating and maintaining multiple copies of data across different servers.

### 9. Sharding in MongoDB?
Answer: Sharding is a method in MongoDB for distributing data across multiple servers. It helps in horizontal scaling by breaking up a large collection into smaller, manageable parts called shards.

### 10. Replica Set in MongoDB?
Answer: A replica set is a group of MongoDB servers that maintain the same data set, providing redundancy and high availability.

### 11. What is .pretty() in MongoDB?
Answer: The .pretty() method in MongoDB is used to format the output of a query in a more readable and human-friendly way.

### 12. Scaling in MongoDB?
Answer: In MongoDB, scaling is a strategy used to handle increased data loads and expand the database's capacity.
- **Horizontal Scaling**: Expands capacity by adding multiple servers and distributing data across them.
- **Vertical Scaling**: Adding more resources (CPU, RAM, or storage) to a single server.
Horizontal scaling is better for handling large datasets and high traffic, while vertical scaling is simpler but limited by the server's hardware capacity.

### 13. What is Aggregation?
Answer: Aggregation is the process that groups data from multiple documents into a single document based on specified expressions. The aggregation pipeline consists of several stages, each transforming the data in some way. A pipeline is an array of different operations.
