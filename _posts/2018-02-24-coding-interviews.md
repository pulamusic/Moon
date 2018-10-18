---
layout: post
title: "notes for coding interviews"
date: 2018-02-24 13:52:00
excerpt: "Notes from a Udemy tutorial on preparing for coding interviews."
tags: [coding, algorithms]
feature: /../assets/img/algorithm.jpg
comments: true
---
I thought I might as well blog this. These are notes for a Udemy course titled [JavaScript Interview Prep](https://www.udemy.com/javascript-interview-prep/learn/v4/content). The answers below are coded out on the Repl.it and Codepen websites. I have added hyperlinks to each of the code examples.

Also check out the following resources for practice algorithms: [JS: Interview Algorithm](https://thatjsdude.com/interview/js1.html); [Learning Algorithms in Javascript From Scratch](https://www.udemy.com/learning-algorithms-in-javascript-from-scratch/learn/v4/overview); [Coderbyte challenges](https://coderbyte.com/challenges); [Khan Academy JS interview questions](http://khan4019.github.io/front-end-Interview-Questions/sort.html); [Tech Interview Handbook](https://github.com/pulamusic/tech-interview-handbook); etc. Also check out [freeCodeCamp.org](https://www.freecodecamp.org) for a whole bunch of algorithm challenges, or for a [pretty good overview of algorithms in computer science](https://guide.freecodecamp.org/algorithms/).

1. [Triple Add Function](https://repl.it/@jgCarroll/tripleAddFunction): tripleAdd(10)(20)(30) // returns total of all 3 numbers added together
2. [What is an IIFE, and why are they used?](https://repl.it/@jgCarroll/exampleIIFE): Immediately invoked function expression. It declares a function and then calls it immediately. Used to take advantage of the local scope of variables inside the function. Example in Repl.it
3. [Source code guessing](https://codepen.io/pulamusic/pen/YeYvVp?editors=1010): Given some source code, guess what will happen when the various buttons are pushed.
4. [Closures](https://repl.it/@jgCarroll/closures): What is a closure? Code out an example of a closure. *My Answer*: a closure defines a function in a specific scope so that it explicitly has access to that scope. *Instructor's Answer*: A closure is an inner function that has access to the scope of an enclosed function.
5. ['This' keyword](https://repl.it/@jgCarroll/thisKeyword): What is the 'this' keyword in JavaScript, and how is it used? *My Answer*: The 'this' keyword relates to functions that are properties of objects.
6. [Hoisting](https://repl.it/@jgCarroll/hoisting): Describe what variable and function hoisting is and how it works. *Answer*: Variables and functions are hoisted to the top of the scope in which they are declared. Essentially, you can't call or log out a variable or function before it is defined. Also, bear in mind that `let` and `const` are block scoped, not function or global scoped.
7. [Scope and 'self' question](https://repl.it/@jgCarroll/scopeAndSelf): Look at the given code and guess at what is logged out to the console. *NOTE*: The code explains it all.
8. [== vs ===](https://repl.it/@jgCarroll/vs): What is the difference between `==` and `===`? *Answer*: `==` stands for 'equals' and tests for abstract equality (doesn't test for data type), whereas `===` stands for 'strict equals' and tests for strict equality (tests for data type).
9. [Log number function](https://repl.it/@jgCarroll/logNumberFunction): Look at the given source code and determine what will be logged to the console. *Answer*: It logs as undefined, probably because of the keyword `var` being used twice. The second `var` is function scoped, so `var num` is hoisted to the top of the function, but not defined until after the `console.log`.
10. [Use strict](https://repl.it/@jgCarroll/useStrict): What does `use strict` do to code, and what are the benefits of using it? *Answer*: Enforces stricter parsing and error handling in the code. It prevents the use of global variables; enforces that all function parameters must be unique; prevents deleting Object properties that are important. Essentially, `use strict` throws errors when we do bad stuff with our code, informing us early of errors that could throw off our code later.
11. [Curry function](https://repl.it/@jgCarroll/curryFunction): Given some starter code, curry the function. *Answer*: Function with multiple parameters should be re-written as multiple, embedded functions with one parameter each.
12. [Counter function](https://repl.it/@jgCarroll/counterFunction): Write a function that keeps track of how many times it was called and returns the number. *Answer in the code*.
13. [Logging X and Y](https://repl.it/@jgCarroll/loggingXAndY): Looking at the example code, what are the values of `X` and `Y` when they are logged out? *Answer is in the code example*.
14. [Call &amp; apply methods](https://repl.it/@jgCarroll/callAndApplyMethods): Describe the JavaScript `call()` and `apply()` methods. How do they function? What arguments do they take? How are they different? *Answers*: Both are predefined JavaScript methods. The `call()` method can be used to call a function with an object as an argument. The `apply()` method is similar, but it takes an array as an argument.
15. [Determine 'list2'](https://repl.it/@jgCarroll/list2): Look at example code, and determine what `list2` will contain when it is logged to the console. Then, determine how `list2` can refer to `list1` without the extra elements added by the `push()` method.
16. [Singly and doubly invoked functions](https://repl.it/@jgCarroll/singleAndDoubleInvokedFunctions): create a function (see source code) that can be either singly invoked or doubly invoked. *Answer in the code*.
17. [JSON data](https://repl.it/@jgCarroll/JSONdata): Describe what JSON format is. Given source code, delete the data types not permitted in JSON, and replace placeholder text with the corresponding data type, properly formatted as JSON. *Answer in the code*.
18. [Order logged out](https://repl.it/@jgCarroll/orderLoggedOut): Given source code, determine in what order the numbers 1, 2, 3, 4 will be logged. *Answer in the code*.
19. [Making an object](https://repl.it/@jgCarroll/makingAnObject): List and describe three different ways of making an object. *Answer in the code*.
20. [Constructor functions](https://repl.it/@jgCarroll/constructorFunctions): This isn't a separate question, but, rather, a continuation of notes from the last question. Check it out.
21. [Type of data types](https://repl.it/@jgCarroll/typeOfDataTypes): Given some source code, determine what will be logged out for each `console.log` statement. *Answer in the code*.
22. [Bind method](https://repl.it/@jgCarroll/bindMethod): Describe the `bind()` function method. How does it work? What parameters does it take? Code out an example of how it is used. *Answers*: From [MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Function/bind), "The `bind()` method creates a new function that, when called, has its `this` keyword set to the provided value, with a given sequence of arguments preceding any provided when the new function is called." *See code example*.
23. [Two Objects](https://repl.it/@jgCarroll/twoObjects): Given source code, determine what is logged out at the bottom. *Answer in the code*.
24. [Array constructor](https://repl.it/@jgCarroll/arrayConstructor): Given source code, determine what is logged out for each of the constructor statements. *Answer in the code*.
25. [Array indexOf](https://repl.it/@jgCarroll/arrayIndexOf): Given source code which uses the `indexOf()` function, determine what will be logged out to the screen for each `console.log()`. *Answers in the code*.
26. [Equivalent numbers](https://repl.it/@jgCarroll/equivalentNumbers): Given source code, determine what will be logged out to the console. *Answer in the code*.
27. [Objects and strings](https://repl.it/@jgCarroll/objectsAndStrings): Given source code, determine what is logged out. *Answer in the code*.
28. [Strings and arrays](https://repl.it/@jgCarroll/stringsAndArrays): Given source code, determine what will be logged out at the bottom. *Answers in the code*.
29. [Object properties](https://repl.it/@jgCarroll/objectProperties): **Note that this is a very common interview question**. Given source code, determine what will be logged out at the bottom. *Answers in the code*.
30. [X and Y](https://repl.it/@jgCarroll/XandY): Given source code, determine what will be logged out at the bottom. *Answers in the code*.
31. [Withdraw from account](https://repl.it/@jgCarroll/withdrawFromAccount): Given source code, determine what will be logged out at the bottom. *Answers in the code*.
