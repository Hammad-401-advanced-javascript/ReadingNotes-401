# Readings: Classes, Inheritance, Functional Programming

### Test-driven development (TDD) is a development technique where you must first write a test that fails before you write new functional code.

## 1-Name 3 advantages to Test Driven Development?
* TDD creates a detailed specification.
* TDD reduces time spent on rework.
* You are able to identify the errors and problems quickly.

## 2-In what case would you need to use beforeEach() or afterEach() in a test suite?
**Often while writing tests you have some setup work that needs to happen before tests run, and you have some finishing work that needs to happen after tests run. Jest provides helper functions to handle this.**

## 3-What is one downside of Test Driven Development
* Big time investment
* Additional Complexity
* Design Impacts
* Continuous Tweaking.

## 4-What’s the primary difference between ES6 Classes and Constructor/Prototype Classes?
The most important difference between class- and prototype-based inheritance is that a class defines a type which can be instantiated at runtime, whereas a prototype is itself an object instance.
A child of an ES6 class is another type definition which extends the parent with new properties and methods, which in turn can be instantiated at runtime. A child of a prototype is another object instance which delegates to the parent any properties that aren’t implemented on the child.

## 5-Name a use case for a static method
* to provide class-specific methods for object-oriented programming in Javascript.
* Static methods are called without instantiating their class and are also not callable when the class is instantiated. Static methods are often used to create utility functions for an application
## 6-Write an example of a Higher Order function and describe the use case it solves
The snippet below loops over an array and invokes a function on each item until it has reached the last item. The capability of taking a function that it can invoke is what makes it a higher order function:
function prefixWordWithUnderscore(word) {
  return `_${word}`
}
const words = ['coffee', 'apple', 'orange', 'phone', 'starbucks']
const prefixedWords = words.map(prefixWordWithUnderscore)
// result: ["_coffee", "_apple", "_orange", "_phone", "_starbucks"]


### Functional programming :
**is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data.**
### pure function :
**1-The function always returns the same result if the same arguments are passed in. It does not depend on any state, or data, change during a program’s execution. It must only depend on its input arguments.**
**2-The function does not produce any observable side effects such as network requests, input and output devices, or data mutation.**
### Higher-order functions:
**function that either takes one or more functions as arguments, or returns a function as its result.**
### immutable state :
**Unchanging over time or unable to be changed,When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.**
### The Object :
**represents one of JavaScript's data types. It is used to store various keyed collections and more complex entities. Objects can be created using the Object() constructor or the object initializer / literal syntax.**
### OOP :
**Object-oriented programming (OOP) refers to a type of computer programming (software design) has four basic concepts: encapsulation, abstraction, inheritance and polymorphism.**
### class :
**Classes are in fact "special functions", and just as you can define function expressions and function declarations, the class syntax has two components: class expressions and class declarations. also,class are not hoisted.**
### prototype :
**is an object (called a prototype object) that has a constructor property by default. The constructor property points back to the function on which prototype object is a property. We can access the function’s prototype property using functionName.prototype.**
### Super :
**The super keyword refers to the parent class. It is used to call the constructor of the parent class and to access the parent's properties and methods.**

### Inheritance :
**Inheritance refers to an object's ability to access methods and other properties from another object. Objects can inherit things from other objects. Inheritance in JavaScript works through something called prototypes and this form of inheritance is often called prototypal inheritance.**
### constructor :
**A constructor is a function that creates an instance of a class which is typically called an “object”. In JavaScript, a constructor gets called when you declare an object using the new keyword. The purpose of a constructor is to create an object and set values if there are any object properties present**

### instance :
**An “instance” means a reference to an “object” created by “new” or the equivalent.What's special about JavaScript, and other scripting languages, is that an “instance” is just a regular object; it's not what it is, but how it's made that is different.**

### Context :
**Context is always the value of the this keyword which is a reference to the object that “owns” the currently executing code**
### this :
**keyword refers to the object it belongs to.And It has different values depending on where it is used**
### TDD :
**Test-driven development is a programming methodology with which one can tackle the design, implementation, and testing of units of code, and to some extent the expected functionality of a program.**
### Jest :
**Jest is a JavaScript test runner, that is, a JavaScript library for creating, running, and structuring tests. Jest is distributed as an NPM package, you can install it in any JavaScript project. Jest is one of the most popular test runner these days and the default choice for Create React App.**

### Continuous Integration (CI) :
**practices used by developers all over the world to increase the quality of their software, and decrease the time to market for features and bug fixes.**
### Unit testing :
**Unit testing is the process of testing the implemented code at a module level. Unit testing allows you to ensure that your developed modules are meeting the requirements specified by the business document. These tests are written for every module as they are created. After every new module development, the entire suite of test cases is run to ensure that no existing modules are affected by the developed module.**
