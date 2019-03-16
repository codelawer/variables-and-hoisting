# Variables & Hoisting

The most basic unit of JavaScript is the __variable__. Variables are a way for you the programmer to understand, talk about, and manipulate what is happening in program memory.   This repo covers the life-cycle of variables in JS and provides you with the study skills necessary to explore them on your own using whatever examples or tutorials you prefer. 

Variables are not a very complicated topic, but they are tricky and crucial to understanding the relationships between:
  * the code you write
  * the javascript notional machine / program execution phase
  * and program state

The most important take-aways from this page are:
1. Using PythonTutor.com to visualize how JavaScript handles declaration, assignment & hoisting.
3. Becoming JavaScript. Learning to execute simple variable-based scripts in your mind.

You will know you have mastered these skills when you can describe every change that will take place in PythonTutor before clicking the 'forward' button.  These skills aren't very glamorous and will take plenty of work to master, but mastering them now will ensure your success when you encounter more challenging code later on. 

Not taking the time to learn these skills now may feel harmless and probably won't stop you from making progres at first, but you will soon reach a point where lacking these skills keeps you from progressing.  By then it's too late, you'll have some unlearning to do. 


### Index
* [Learning Objectives](#learning-objectives)
* [Resources](#resources)
* [js in order](https://github.com/janke-learning/js-in-order)

---

## Learning Objectives

_Program State_: State is the current values of all variables in your program.  Program state is dynamic, it changes over the course of your application's __run-time__. Because variables are frequently modified, state cannot be determined just by reading your source code.  

_Source-Code vs Running Program_: Learning to understand the difference between your source code (simply a text file) and the dynamic runtime of your program is a strange but critical skill to learn.  After you have started your program, you must learn to think of your source code simply as a reference not a full description of your program.  To understand a running program you need to track __program state__ and __which line is next to execute__.



__JavaScript:__
* Variables: var, let, const
  * Declaration
  * Assigning values
  * Reassignment
  * Hoisting 

__Programming Skillzz:__
* Code life-cycle:
  * Source-time: The code that's written
  * Build-time: JavaScript creation phase (hoisting happens here)
  * Run-time: When JS executes lines one at a time
* Tracing variables:
  * Hoisting (build-time)
  * Declaration
  * Assignment & reassignment
* Descriptive variable names




[TOP](#variables-&-hoisting)

---

## Resources


__study tools__:
* [PythonTutor for JavaScript](http://pythontutor.com/javascript.html#)
* [the Parsonizer](https://janke-learning.github.io/parsonizer/)

__links__:
* on pytut: 
    * [snippet: Declaration](https://goo.gl/dGfhNj) - declaration tells JavaScript to create a new variable that can be used to store values later on, but does not assign it a value. 
    * [snippet: Assignment](https://goo.gl/14s6vU) - assignment tells JS to set a new value to a variable. if no value is assigned, the variable will default to _undefined_
    * [snippet: Hoisting](https://goo.gl/Ruc4gB) - JS declares (but not defines) "var" variables during the _creation phase_ of a program.
    * [video: variables & values of primitive types](https://www.youtube.com/watch?v=pHt_tKYUgbo&index=2&list=PLzV58Zm8FuBJFfQN5il3ujx6FDAY8Ds3u)
* snippet studies:
    * [the Value Swap](https://github.com/janke-learning/value-swap) - a good and simple way to check your understanding of variables
    * [let vs. var](https://github.com/janke-learning/hoisting-variables)
* on variables
    * [flaviocopes](https://flaviocopes.com/javascript-variables/)
    * [javascript.info](http://javascript.info/variables) 
    * [practical js](https://shawnr.gitbooks.io/practical-introduction-to-javascript/content/basic-syntax/45-variables.html)
    * [undeclared variables](https://github.com/janke-learning/undeclared-variables)
    * [learnteachcode](https://github.com/LearnTeachCode/intro-javascript-class/blob/july-aug-2018/week-1/1-8-memory-variables.md)
* free code camp:
    * [declaring variables](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/declare-javascript-variables/)
    * [initializing with assignment](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/initializing-variables-with-the-assignment-operator/)
    * [storing values with assignment](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/storing-values-with-the-assignment-operator/)
    * [variables are case-sensitive](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/basic-javascript/understanding-case-sensitivity-in-variables/)
    * [constant variables](https://learn.freecodecamp.org/javascript-algorithms-and-data-structures/es6/declare-a-read-only-variable-with-the-const-keyword/)
    


[TOP](#variables-&-hoisting)


___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
