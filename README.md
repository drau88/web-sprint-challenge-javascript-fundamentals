# Sprint Challenge - JavaScript Fundamentals

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in project. This Sprint explored JavaScript Fundamentals. During this Sprint, you studied array methods, this keyword, prototypes, and class syntax. In your challenge this week, you will demonstrate proficiency by completing a range of JavaScript problems.

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the sprint challenge. 

## Introduction

The index.js file contains all of your challenges. Please review it in full before answering the questions. If you complete the stretch goals please leave them in your file but commented out so that they do not affect the MVP tasks 

In meeting the minimum viable product (MVP) specifications listed below, you should have all tests passing. You can console.log to check your work and ensure you are submitting the correct results 

### Commits

Set up codegrade early and commit your code regularly and meaningfully. 

## Interview Questions
### (please edit this file and write your answer below each question.)
Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read.

1. Explain the differences between `.map`, `.reduce` and `.filter` and describe a use case for each. 

.map, .filter and .reduce are all array methods. .map and .filter return an array while .reduce returns an individual value. .map returns an entirely new array based on the logic of a function being given to it. This is useful for situations in which someone might want to make a new array containing conversions of the data found within the original array, such as converting strings on the original array to upper or lowercase versions of those strings. .filter returns a new array based on specific conditional expressions. When examining the items on the array with .filter, items evaluated as true will be included in the new array, while those evaluating as false will not. .filter is useful for taking a large array and returning a smaller array with items that meet the developer's criteria, making it easier to work with or to evaluate specific subsets of the original data. .reduce has a wide variety of theoretical applications but is perhaps most commonly used for adding or multiplying numbers contained in an array and receiving the sum or product of those values.

2. Explain the difference between a callback and a higher order function.

Callback and higher order functions are closely related ideas. Callback functions are passed into higher order functions as arguments, and higher order functions receive callback functions as parameters.

3. Explain what a closure is.

Closure occurs when a function reaches outside of its own scope for data. Functions can reach outside of themselves for variables found within a parent function or the global scope, but functions cannot reach into functions of smaller scope for their variables.

4. Describe the four principles of the 'this' keyword.

"This" has four principles or bindings that describe to what "this" is actually referring. In window binding, "this" describes the window, a global object with methods available to all other parts of a program by default. "This" can also have implicit binding. Implicit binding is perhaps the most common use-case, where "this" refers to the object containing the method being used. The third binding is explicit binding. With explicit binding, "this" is being instructed to refer to a specific context defined by the use of the methods .call, .apply, or .bind. The last binding context is new binding. In new binding, "this" refers to an object being created through the use of a constructor and the "new" keyword.

5. Why do we need super() in an extended class?

super() is a keyword that is used to call the functions of the parent class to the extended classes so that all instances of the extended class have access to those of the parent class. Super() replaces the .call() and object.create() methods while using class syntax.

You are expected to be able to answer questions in these areas. Your responses contribute to your Sprint Challenge grade. 

## Instructions

### Task 1: Set up Project

Using VSCode and Command Line:


1. Fork the repo
2. Clone your forked version of the repo
3. cd into your repo and create a branch with your first and last name
4. open the terminal in your vs code and type `npm install`
5. next type `npm run test` in your terminal
6. Complete your work making regular commits, once you have all your tests passing and you are ready to submit your work please see canvas for instructions on how to submit

### Testing & Debugging

Open a second terminal inside of your project by clicking on the split terminal icon
![alt text](assets/split_terminal.png "Split Terminal")

Inside of your second terminal type `npm start` 
![alt text](assets/npm_start.png "type npm start")

You will be running your tests in one terminal and debugging in the other. As you work on your code you should make use of `console.log` to check your progress and debug.
![alt text](assets/tests_debug_terminal_final.png "your terminal should look like this")

### Task 2: Project Requirements (MVP)

You must complete all tasks inside of `index.js` and answer the questions above.

In your solutions, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Resources
 
 [Sprint Challenge Study Guide](https://www.notion.so/lambdaschool/Unit-1-Sprint-3-Study-Guide-033a9a00659a4ef98c12eb97e49a6110)

## Submission format

Please submit your project via codegrade by following [these instructions](https://www.notion.so/lambdaschool/Submitting-an-assignment-via-Code-Grade-A-Step-by-Step-Walkthrough-07bd65f5f8364e709ecb5064735ce374)

