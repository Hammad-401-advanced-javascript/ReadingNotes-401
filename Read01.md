# Node Ecosystem, TDD, CI/CD

## 1-Why would you want to run JavaScript code outside of a browser?
**Running JavaScript without/outside a browser means you are using node.js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.**

## 2-What is the difference between a module and a package?
**Node.js has a simple module loading system. In Node.js, files and modules are in one-to-one correspondence.**
**A package is one or more modules (libraries) grouped (or packaged) together. These are commonly used by other packages or a project of your own**

## 3-What does the node package manager do?
**Node Package Manager (NPM) is a command line tool that installs, updates or uninstalls Node.js packages in your application. It is also an online repository for open-source Node.js packages. The node community around the world creates useful modules and publishes them as packages in this repository.**

## 4-Provide code snippets showing 3 different ways to export a function from a node module:

**1- Exporting Literals:**
app.js(export literal): module.exports="Helloo Hammad";

index.js(import the file app.js to print the exported literal to the console.):

const name = require("./app");
console.log(company);

**2-Exporting Object:**

app.js :  module.exports = { 
name: 'GeeksforGeeks', 
website: 'https://geeksforgeeks.org'
} 

index.js : const company = require('./app'); 
console.log(company.name); 
console.log(company.website); 

3-Exporting Function:

app.js: module.exports = function (a, b) { 
console.log(a + b); 
} 
index.js : const sum = require('./app'); 
sum(2, 5); 




## Ecosystem: 
**ecosystem: "a collection of software projects, which are developed and co-evolve in the same environment”**

## Node.js:
**is an open-source, cross-platform, JavaScript runtime environment that executes JavaScript code outside of a web browser.**

## V8 JavaScript engine: 
**is an open source JavaScript and WebAssembly engine that compiles JavaScript to optimized machine code before
execution.**

## A module
**is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.
To be loaded by the Node.js require() function, a module must be one of the following:
A folder with a package.json file containing a "main" field.
A folder with an index.js file in it.
A JavaScript file.**

## A package:
**is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be published
to the npm registry.**

## npm :
**is the package manager for the Node JavaScript platform. It puts modules in place so that node can find them, and manages
dependency conflicts intelligently. It is extremely configurable to support a wide variety of use cases. Most commonly, it is used
to publish, discover, install, and develop node programs.**

## A Node.js server:
**provides the mechanisms for connecting to a service and sending/receiving data. This is done through TCP or UDP 
connections. This allows developers to create their own servers using these protocols or the protocols built upon them (like HTTP).**

## NODE_ENV :
**is an environment variable made popular by the express webserver framework. When a node application is run, it can check the
value of the environment variable and do different things based on the value. NODE_ENV specifically is used (by convention) to state
whether a particular environment is a production or a development environment. A common use-case is running additional debugging or
logging code if running in a development environment.**

## JS-Interpreter :
**is a sandboxed JavaScript interpreter written in JavaScript. It allows for execution of arbitrary JavaScript code line
by line. Execution is completely isolated from the main JavaScript environment. Multiple instances of the JS-Interpreter allow for
multi-threaded concurrent JavaScript without the use of Web Workers.**

## A compiler
**is a software that converts a high-level code scripted by developers to a low-level binary code in machine language which 
can be easily understood and executed by the processor and this process is called compilation or code compilation.**

![image](https://www.erasmuslifebudapest.com/wp-content/uploads/2018/11/node-js-main.jpg)
