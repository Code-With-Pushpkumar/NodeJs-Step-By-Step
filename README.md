# NodeJs-Step-By-Step
Learn Nodejs - step by step with Example from basics to advanced level. 

Node.js is an open source server environment.
Node.js allows us to run JavaScript on the server.


- ## Node Js Tutorial

  1. Introduction to node.js
  2. File system modules and Express js
  3. Asynchronous Programming
  4. Integration with MongoDB and email server
  5. Rest API and GraphQL
  6. Building node.js application using ES6 [ES2015]
  7. User authentication and security
  8. Dynamic client -server integration with Socket IO
  9. Microservice application
  10. Testing node.js application

  ## Introduction to node.js

  # Node JS

  Node JS is an open-source and cross-platform runtime environment for executing JavaScript code outside a browser. NodeJS is not a framework and it’s not a programming language. Node.js is used to build back-end services like APIs like Web App or Mobile App. It’s used in production by large companies such as Paypal, Uber, Netflix, Walmart, and so on.

          Node.js = Runtime Environment + JavaScript Library

  # How Node works?

  Node accepts the request from the clients and sends the response, while working with the request node.js handles them with a single thread. To operate I/O operations or requests node.js use the concept of threads. Thread is a sequence of instructions that the server needs to perform. It runs parallel on the server to provide the information to multiple clients. Node.js is an event loop single-threaded language. It can handle concurrent requests with a single thread without blocking it for one request.

  # Advantages of Node:

  Easy Scalability: Easily scalable the application in both horizontal and vertical directions.
  Real-time web apps: Node.js is much more preferable because of faster synchronization. Also, the event loop avoids HTTP overloaded for Node.js development.

  Fast Suite: NodeJS acts like a fast suite and all the operations can be done quickly like reading or writing in the database, network connection, or file system

  Easy to learn and code: NodeJS is easy to learn and code because it uses JavaScript.
  Advantage of Caching: It provides the caching of a single module. Whenever there is any request for the first module, it gets cached in the application memory, so you don’t need to re-execute the code.

  # Reason to Choose Node:

  There are other programming languages also which we can use to build back-end services so what makes Node.js different I am going to explain.

  1. It’s easy to get started and can be used for prototyping and agile development
  2. It provides fast and highly scalable services.
  3. It uses JavaScript everywhere, so it’s easy for a JavaScript programmer to build back-end services using Node.js
  4. Large ecosystem for open source library and has asynchronous or non-blocking nature.

  # Download Node.js

  The official Node.js website has installation instructions for Node.js: https://nodejs.org

  # Application of NodeJS:

  NodeJS should be preferred to build Real-Time Chats, Complex Single-Page applications, Real-time collaboration tools, Streaming apps, JSON APIs based application.

  Example: Below is the basic code example of the nodejs server.

  # Getting Started

  Once you have downloaded and installed Node.js on your computer, let's try to display "Hello World" in a web browser.

  # Installing NPM:

  To install NPM, it is required to install Node.js as NPM gets installed with Node.js automatically.

  # Checking and updating npm version:

  Version of npm installed on system can be checked using following syntax:
  Syntax:

  node -v
  npm -v
