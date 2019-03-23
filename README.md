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
* [Exercises](#exercises)
* [js in order](https://github.com/janke-learning/js-in-order)

---

## Learning Objectives

_Program State_: State is the current values of all variables in your program.  Program state is dynamic, it changes over the course of your application's __run-time__. Because variables are frequently modified, state cannot be determined just by reading your source code.  

_Source-Code vs Running Program_: Learning to understand the difference between your source code (simply a text file) and the dynamic runtime of your program is a strange but critical skill to learn.  After you have started your program, you must learn to think of your source code simply as a reference not a full description of your program.  To understand a running program you need to track __program state__ and __which line is next to execute__.



__JavaScript:__
* Variables: var, let, const
  * Assignment by value
  * Reassignment
  * Hoisting behavior
* comma operator 
  * multiple declarations in one step
  * multiple assignments in one step

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
    * [snippet: comma operator](https://goo.gl/ZtxPzU)
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

---

## Exercises

The exercises below are all focused on understanding the [JS notional machine](https://github.com/janke-learning/js-notional-machine), they will push your understanding of JavaScript's runtime behavior.  Each exercise focuses on manipulating _program state_ over the course of execution not on solving programming challenges or producing a final answer.  

__Swaps__ will give you a bunch of variables with the wrong value assigned and a temporary variable you can use for storing values.  Your task is to get the right values to the right variables in as few steps as possible by shuffling around the available values.
* challenges
    1. [the first](https://goo.gl/k9jdZy)
    1. [the second](https://goo.gl/KvayUU)
    1. [the third](https://goo.gl/WXXtV7)
    1. [the fourth](https://goo.gl/nTA1DG)
    1. [the fifth](https://goo.gl/gDaKNi)
* example solutions
    1. the first: [pytut](https://goo.gl/mk9xd3), [parsons](https://janke-learning.github.io/parsonizer/?challenge=108-101-116-32-97-32-61-32-34-98-34-44-32-98-32-61-32-34-97-34-59-10-108-101-116-32-95-32-61-32-39-32-39-59-10-10-95-32-61-32-98-59-10-98-32-61-32-97-59-10-97-32-61-32-95-59)
    1. the second: [pytut](https://goo.gl/BWKuGm), [parsons](https://janke-learning.github.io/parsonizer/?challenge=108-101-116-32-97-32-61-32-34-99-34-44-32-98-32-61-32-34-97-34-44-32-99-32-61-32-34-98-34-59-10-108-101-116-32-95-32-61-32-39-32-39-59-10-10-95-32-61-32-99-59-10-99-32-61-32-97-59-10-97-32-61-32-98-59-10-98-32-61-32-95-59-10)
    1. the third: [pytut](https://goo.gl/jeBHWU), [parsons](https://janke-learning.github.io/parsonizer/?challenge=108-101-116-32-97-32-61-32-34-100-34-44-32-98-32-61-32-34-97-34-44-32-99-32-61-32-34-98-34-44-32-100-32-61-32-34-99-34-59-10-108-101-116-32-95-32-61-32-39-32-39-59-10-10-95-32-61-32-97-59-10-97-32-61-32-98-59-10-98-32-61-32-99-59-10-99-32-61-32-100-59-10-100-32-61-32-95-59-10)
    1. the fourth: [pytut](https://goo.gl/C8t81i), [parsons](https://janke-learning.github.io/parsonizer/?challenge=108-101-116-32-97-32-61-32-34-122-34-44-32-98-32-61-32-34-121-34-44-32-99-32-61-32-34-120-34-44-32-100-32-61-32-34-119-34-59-10-108-101-116-32-95-32-61-32-39-32-39-59-10-10-95-32-61-32-97-59-10-97-32-61-32-100-59-10-100-32-61-32-95-59-10-95-32-61-32-98-59-10-98-32-61-32-99-59-10-99-32-61-32-95-59-10)
    1. the fifth: [pytut](https://goo.gl/KokxwL), [parsons](https://janke-learning.github.io/parsonizer/?challenge=108-101-116-32-97-32-61-32-34-122-34-44-32-98-32-61-32-34-121-34-44-32-99-32-61-32-34-120-34-44-32-100-32-61-32-34-119-34-44-32-101-32-61-32-34-118-34-59-10-108-101-116-32-95-32-61-32-39-32-39-59-10-10-95-32-61-32-97-59-10-97-32-61-32-101-59-10-101-32-61-32-95-59-10-95-32-61-32-98-59-10-98-32-61-32-100-59-10-100-32-61-32-95-59-10)


__Sentences__ ask you to reassign variables so that at each step of execution the variables spell out the next word in a sentence.  See how few reassignments you can use per step!
1. without extra holder variables:
    * challenges: 
        1. [the toad reads me](https://goo.gl/imKwgj) 
        1. [eating meat every meal](https://goo.gl/cwZijk)
        1. [many men may melt my mind](https://goo.gl/16C62t)
        1. [if fir trees ever fall](https://goo.gl/8y5Lh2)
    * example solutions: 
        * the toad reads me: [pytut](https://goo.gl/pmpkJZ), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-116-104-101-32-116-111-97-100-32-114-101-97-100-115-32-109-101-10-108-101-116-32-95-49-32-61-32-34-32-34-44-32-95-50-32-61-32-34-32-34-44-32-95-51-32-61-32-34-32-34-44-32-95-52-32-61-32-34-32-34-44-32-95-53-32-61-32-34-32-34-59-10-47-47-32-116-104-101-10-95-49-32-61-32-34-116-34-44-32-95-50-32-61-32-34-104-34-44-32-95-51-32-61-32-34-101-34-59-10-47-47-32-116-111-97-100-10-95-50-32-61-32-34-111-34-44-32-95-51-32-61-32-34-97-34-44-32-95-52-32-61-32-34-100-34-59-10-47-47-32-114-101-97-100-115-10-95-49-32-61-32-34-114-34-44-32-95-50-32-61-32-34-101-34-44-32-95-53-32-61-32-34-115-34-59-10-47-47-32-109-101-10-95-49-32-61-32-34-109-34-44-32-95-51-32-61-32-34-32-34-44-32-95-52-32-61-32-34-32-34-44-32-95-53-32-61-32-34-32-34-59)
        * eating meat every meal: [pytut](https://goo.gl/bDVjKL), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-101-97-116-105-110-103-32-109-101-97-116-32-101-118-101-114-121-32-109-101-97-108-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-44-32-95-53-32-61-32-39-32-39-44-32-95-54-61-32-39-32-39-59-10-47-47-32-101-97-116-105-110-103-10-95-49-32-61-32-34-101-34-44-32-95-50-32-61-32-34-97-34-44-32-95-51-32-61-32-34-116-34-44-32-95-52-32-61-32-34-105-34-44-32-95-53-32-61-32-34-110-34-44-32-95-54-61-32-34-103-34-59-10-47-47-32-109-101-97-116-10-95-52-32-61-32-95-51-44-32-95-51-32-61-32-95-50-44-32-95-50-32-61-32-95-49-44-32-95-49-32-61-32-34-109-34-44-32-95-53-32-61-32-34-32-34-44-32-95-54-32-61-32-34-32-34-59-10-47-47-32-101-118-101-114-121-10-95-49-32-61-32-95-50-44-32-95-51-32-61-32-95-50-44-32-95-50-32-61-32-34-118-34-44-32-95-52-32-61-32-34-114-34-44-32-95-53-32-61-32-34-121-34-59-10-47-47-32-109-101-97-108-10-95-49-32-61-32-34-109-34-44-32-95-50-32-61-32-95-51-44-32-95-51-32-61-32-34-97-34-44-32-95-52-32-61-32-34-108-34-44-32-95-53-32-61-32-34-32-34-59)
        * many men may melt my mind: [pytut](https://goo.gl/Gh8mCu), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-109-97-110-121-32-109-101-110-32-109-97-121-32-109-101-108-116-32-109-121-32-109-105-110-100-10-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-59-10-10-47-47-32-109-97-110-121-10-95-49-32-61-32-39-109-39-44-32-95-50-32-61-32-39-97-39-44-32-95-51-32-61-32-39-110-39-44-32-95-52-32-61-32-39-121-39-59-10-47-47-32-109-101-110-10-95-50-32-61-32-39-101-39-44-32-95-52-32-61-32-39-32-39-59-10-47-47-32-109-97-121-10-95-50-32-61-32-39-97-39-44-32-95-51-32-61-32-39-121-39-59-10-47-47-32-109-101-108-116-10-95-50-32-61-32-39-101-39-44-32-95-51-32-61-32-39-108-39-44-32-95-52-32-61-32-39-116-39-59-10-47-47-32-109-121-10-95-50-32-61-32-39-121-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-59-10-47-47-32-109-105-110-100-10-95-50-32-61-32-39-105-39-44-32-95-51-32-61-32-39-110-39-44-32-95-52-32-61-32-39-100-39-59)
        * if fir trees ever fall: [pytut](https://goo.gl/tdJQwW), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-105-102-32-102-105-114-32-116-114-101-101-115-32-101-118-101-114-32-102-97-108-108-10-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-44-32-95-53-32-61-32-39-32-39-59-10-10-47-47-32-105-102-10-95-49-32-61-32-39-105-39-44-32-95-50-32-61-32-39-102-39-59-10-47-47-32-102-105-114-10-95-49-32-61-32-95-50-44-32-95-50-32-61-32-39-105-39-44-32-95-51-32-61-32-39-114-39-59-10-47-47-32-116-114-101-101-115-10-95-49-32-61-32-39-116-39-44-32-95-50-32-61-32-95-51-44-32-95-51-32-61-32-39-101-39-44-32-95-52-32-61-32-95-51-44-32-95-53-32-61-32-39-115-39-59-10-47-47-32-101-118-101-114-10-95-49-32-61-32-95-51-44-32-95-50-32-61-32-39-118-39-44-32-95-52-32-61-32-39-114-39-44-32-95-53-32-61-32-39-114-39-59-10-47-47-32-102-97-108-108-10-95-49-32-61-32-39-102-39-44-32-95-50-32-61-32-39-97-39-44-32-95-51-32-61-32-39-108-39-44-32-95-52-32-61-32-95-51-44-32-95-53-32-61-32-39-32-39-59)
2. with extra holder variables:
    * challenges: 
        1. [the toad reads me](https://goo.gl/4eqhLb)
        1. [eating meat every meal](https://goo.gl/F9Njwp)
        1. [many men may melt my mind](https://goo.gl/16C62t)
        1. [if fir trees ever fall](https://goo.gl/BCC6pz)
    * example solutions: 
        1. the toad reads me: [pytut](https://goo.gl/WrWMid), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-116-104-101-32-116-111-97-100-32-114-101-97-100-115-32-109-101-10-10-108-101-116-32-95-49-32-61-32-34-32-34-44-32-95-50-32-61-32-34-32-34-44-32-95-51-32-61-32-34-32-34-44-32-95-52-32-61-32-34-32-34-44-32-95-53-32-61-32-34-32-34-59-10-108-101-116-32-120-32-61-32-39-32-39-44-32-121-32-61-32-39-32-39-59-10-10-47-47-32-116-104-101-10-95-49-32-61-32-34-116-34-44-32-95-50-32-61-32-34-104-34-44-32-95-51-32-61-32-34-101-34-59-10-47-47-32-116-111-97-100-10-120-32-61-32-95-51-59-10-95-50-32-61-32-34-111-34-44-32-95-51-32-61-32-34-97-34-44-32-95-52-32-61-32-34-100-34-59-10-47-47-32-114-101-97-100-115-10-95-49-32-61-32-34-114-34-44-32-95-50-32-61-32-120-44-32-95-53-32-61-32-34-115-34-59-10-47-47-32-109-101-10-95-49-32-61-32-34-109-34-44-32-95-51-32-61-32-34-32-34-44-32-95-52-32-61-32-34-32-34-44-32-95-53-32-61-32-34-32-34-59)
        1. eating meat every meal: [pytut](https://goo.gl/ioTN8v), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-101-97-116-105-110-103-32-109-101-97-116-32-101-118-101-114-121-32-109-101-97-108-10-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-44-32-95-53-32-61-32-39-32-39-44-32-95-54-61-32-39-32-39-59-10-108-101-116-32-120-32-61-32-39-32-39-44-32-121-32-61-32-39-32-39-59-10-10-47-47-32-101-97-116-105-110-103-10-95-49-32-61-32-34-101-34-44-32-95-50-32-61-32-34-97-34-44-32-95-51-32-61-32-34-116-34-44-32-95-52-32-61-32-34-105-34-44-32-95-53-32-61-32-34-110-34-44-32-95-54-61-32-34-103-34-59-10-47-47-32-109-101-97-116-10-120-32-61-32-95-50-59-10-95-52-32-61-32-95-51-44-32-95-51-32-61-32-95-50-44-32-95-50-32-61-32-95-49-44-32-95-49-32-61-32-34-109-34-44-32-95-53-32-61-32-34-32-34-44-32-95-54-32-61-32-34-32-34-59-10-47-47-32-101-118-101-114-121-10-121-32-61-32-95-49-59-10-95-49-32-61-32-95-50-44-32-95-51-32-61-32-95-50-44-32-95-50-32-61-32-34-118-34-44-32-95-52-32-61-32-34-114-34-44-32-95-53-32-61-32-34-121-34-59-10-47-47-32-109-101-97-108-10-95-49-32-61-32-121-44-32-95-50-32-61-32-95-51-44-32-95-51-32-61-32-120-44-32-95-52-32-61-32-34-108-34-44-32-95-53-32-61-32-34-32-34-59)
        1. many men may melt my mind: [pytut](https://goo.gl/Q8LtiR), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-109-97-110-121-32-109-101-110-32-109-97-121-32-109-101-108-116-32-109-121-32-109-105-110-100-10-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-59-10-108-101-116-32-120-32-61-32-39-32-39-44-32-121-32-61-32-39-32-39-59-10-10-47-47-32-109-97-110-121-10-95-49-32-61-32-39-109-39-44-32-32-95-50-32-61-32-39-97-39-44-32-95-51-32-61-32-39-110-39-44-32-95-52-32-61-32-39-121-39-59-10-47-47-32-109-101-110-10-120-32-61-32-95-50-44-32-121-32-61-32-95-52-59-10-95-50-32-61-32-39-101-39-44-32-95-52-32-61-32-39-32-39-59-10-47-47-32-109-97-121-10-95-51-32-61-32-121-44-32-121-32-61-32-95-50-44-32-95-50-32-61-32-120-59-10-47-47-32-109-101-108-116-10-120-32-61-32-95-51-59-10-95-50-32-61-32-121-44-32-95-51-32-61-32-39-108-39-44-32-95-52-32-61-32-39-116-39-59-10-47-47-32-109-121-10-95-50-32-61-32-120-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-59-10-47-47-32-109-105-110-100-10-95-50-32-61-32-39-105-39-44-32-95-51-32-61-32-39-110-39-44-32-95-52-32-61-32-39-100-39-59)
        1. if fir trees ever fall: [pytut](https://goo.gl/SpjB6t), [parsons](https://janke-learning.github.io/parsonizer/?challenge=47-47-32-105-102-32-102-105-114-32-116-114-101-101-115-32-101-118-101-114-32-102-97-108-108-10-10-108-101-116-32-95-49-32-61-32-39-32-39-44-32-95-50-32-61-32-39-32-39-44-32-95-51-32-61-32-39-32-39-44-32-95-52-32-61-32-39-32-39-44-32-95-53-32-61-32-39-32-39-59-10-108-101-116-32-120-32-61-32-39-32-39-44-32-121-32-61-32-39-32-39-59-32-47-47-32-116-111-32-115-97-118-101-32-101-120-116-114-97-32-118-97-108-117-101-115-32-102-111-114-32-108-97-116-101-114-10-10-47-47-32-105-102-10-95-49-32-61-32-39-105-39-44-32-95-50-32-61-32-39-102-39-59-10-47-47-32-102-105-114-10-120-32-61-32-95-50-59-10-95-50-32-61-32-95-49-44-32-95-49-32-61-32-120-44-32-95-51-32-61-32-39-114-39-59-10-47-47-32-116-114-101-101-115-10-95-49-32-61-32-39-116-39-44-32-95-50-32-61-32-95-51-44-32-95-51-32-61-32-39-101-39-44-32-95-52-32-61-32-95-51-44-32-95-53-32-61-32-39-115-39-59-10-47-47-32-101-118-101-114-10-121-32-61-32-95-50-59-10-95-49-32-61-32-95-51-44-32-95-50-32-61-32-39-118-39-44-32-95-52-32-61-32-121-44-32-95-53-32-61-32-39-32-39-59-10-47-47-32-102-97-108-108-10-95-49-32-61-32-120-44-32-95-50-32-61-32-39-97-39-44-32-95-51-32-61-32-39-108-39-44-32-95-52-32-61-32-95-51-44-32-95-53-32-61-32-39-32-39-59)

[TOP](#variables-&-hoisting)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
