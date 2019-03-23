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
    1. the first: [pytut](https://goo.gl/mk9xd3), [parsons](https://janke-learning.github.io/parsonizer/?snippet=let%20a%20%3D%20%22b%22%2C%20b%20%3D%20%22a%22%3B%0Alet%20_%20%3D%20'%20'%3B%0A%0A_%20%3D%20b%3B%0Ab%20%3D%20a%3B%0Aa%20%3D%20_%3B)
    1. the second: [pytut](https://goo.gl/BWKuGm), [parsons](https://janke-learning.github.io/parsonizer/?snippet=let%20a%20%3D%20%22c%22%2C%20b%20%3D%20%22a%22%2C%20c%20%3D%20%22b%22%3B%0Alet%20_%20%3D%20'%20'%3B%0A%0A_%20%3D%20c%3B%0Ac%20%3D%20a%3B%0Aa%20%3D%20b%3B%0Ab%20%3D%20_%3B%0A)
    1. the third: [pytut](https://goo.gl/jeBHWU), [parsons](https://janke-learning.github.io/parsonizer/?snippet=let%20a%20%3D%20%22d%22%2C%20b%20%3D%20%22a%22%2C%20c%20%3D%20%22b%22%2C%20d%20%3D%20%22c%22%3B%0Alet%20_%20%3D%20'%20'%3B%0A%0A_%20%3D%20a%3B%0Aa%20%3D%20b%3B%0Ab%20%3D%20c%3B%0Ac%20%3D%20d%3B%0Ad%20%3D%20_%3B%0A)
    1. the fourth: [pytut](https://goo.gl/C8t81i), [parsons](https://janke-learning.github.io/parsonizer/?snippet=let%20a%20%3D%20%22z%22%2C%20b%20%3D%20%22y%22%2C%20c%20%3D%20%22x%22%2C%20d%20%3D%20%22w%22%3B%0Alet%20_%20%3D%20'%20'%3B%0A%0A_%20%3D%20a%3B%0Aa%20%3D%20d%3B%0Ad%20%3D%20_%3B%0A_%20%3D%20b%3B%0Ab%20%3D%20c%3B%0Ac%20%3D%20_%3B%0A)
    1. the fifth: [pytut](https://goo.gl/KokxwL), [parsons](https://janke-learning.github.io/parsonizer/?snippet=let%20a%20%3D%20%22z%22%2C%20b%20%3D%20%22y%22%2C%20c%20%3D%20%22x%22%2C%20d%20%3D%20%22w%22%2C%20e%20%3D%20%22v%22%3B%0Alet%20_%20%3D%20'%20'%3B%0A%0A_%20%3D%20a%3B%0Aa%20%3D%20e%3B%0Ae%20%3D%20_%3B%0A_%20%3D%20b%3B%0Ab%20%3D%20d%3B%0Ad%20%3D%20_%3B%0A)


__Sentences__ ask you to reassign variables so that at each step of execution the variables spell out the next word in a sentence.  See how few reassignments you can use per step!
1. without extra holder variables:
    * challenges: 
        1. [the toad reads me](https://goo.gl/imKwgj) 
        1. [eating meat every meal](https://goo.gl/cwZijk)
        1. [many men may melt my mind](https://goo.gl/16C62t)
        1. [if fir trees ever fall](https://goo.gl/8y5Lh2)
    * example solutions: 
        * the toad reads me: [pytut](https://goo.gl/pmpkJZ), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20the%20toad%20reads%20me%0Alet%20_1%20%3D%20%22%20%22%2C%20_2%20%3D%20%22%20%22%2C%20_3%20%3D%20%22%20%22%2C%20_4%20%3D%20%22%20%22%2C%20_5%20%3D%20%22%20%22%3B%0A%2F%2F%20the%0A_1%20%3D%20%22t%22%2C%20_2%20%3D%20%22h%22%2C%20_3%20%3D%20%22e%22%3B%0A%2F%2F%20toad%0A_2%20%3D%20%22o%22%2C%20_3%20%3D%20%22a%22%2C%20_4%20%3D%20%22d%22%3B%0A%2F%2F%20reads%0A_1%20%3D%20%22r%22%2C%20_2%20%3D%20%22e%22%2C%20_5%20%3D%20%22s%22%3B%0A%2F%2F%20me%0A_1%20%3D%20%22m%22%2C%20_3%20%3D%20%22%20%22%2C%20_4%20%3D%20%22%20%22%2C%20_5%20%3D%20%22%20%22%3B)
        * eating meat every meal: [pytut](https://goo.gl/bDVjKL), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20eating%20meat%20every%20meal%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%2C%20_5%20%3D%20'%20'%2C%20_6%3D%20'%20'%3B%0A%2F%2F%20eating%0A_1%20%3D%20%22e%22%2C%20_2%20%3D%20%22a%22%2C%20_3%20%3D%20%22t%22%2C%20_4%20%3D%20%22i%22%2C%20_5%20%3D%20%22n%22%2C%20_6%3D%20%22g%22%3B%0A%2F%2F%20meat%0A_4%20%3D%20_3%2C%20_3%20%3D%20_2%2C%20_2%20%3D%20_1%2C%20_1%20%3D%20%22m%22%2C%20_5%20%3D%20%22%20%22%2C%20_6%20%3D%20%22%20%22%3B%0A%2F%2F%20every%0A_1%20%3D%20_2%2C%20_3%20%3D%20_2%2C%20_2%20%3D%20%22v%22%2C%20_4%20%3D%20%22r%22%2C%20_5%20%3D%20%22y%22%3B%0A%2F%2F%20meal%0A_1%20%3D%20%22m%22%2C%20_2%20%3D%20_3%2C%20_3%20%3D%20%22a%22%2C%20_4%20%3D%20%22l%22%2C%20_5%20%3D%20%22%20%22%3B)
        * many men may melt my mind: [pytut](https://goo.gl/Gh8mCu), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20many%20men%20may%20melt%20my%20mind%0A%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%3B%0A%0A%2F%2F%20many%0A_1%20%3D%20'm'%2C%20_2%20%3D%20'a'%2C%20_3%20%3D%20'n'%2C%20_4%20%3D%20'y'%3B%0A%2F%2F%20men%0A_2%20%3D%20'e'%2C%20_4%20%3D%20'%20'%3B%0A%2F%2F%20may%0A_2%20%3D%20'a'%2C%20_3%20%3D%20'y'%3B%0A%2F%2F%20melt%0A_2%20%3D%20'e'%2C%20_3%20%3D%20'l'%2C%20_4%20%3D%20't'%3B%0A%2F%2F%20my%0A_2%20%3D%20'y'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%3B%0A%2F%2F%20mind%0A_2%20%3D%20'i'%2C%20_3%20%3D%20'n'%2C%20_4%20%3D%20'd'%3B)
        * if fir trees ever fall: [pytut](https://goo.gl/tdJQwW), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20if%20fir%20trees%20ever%20fall%0A%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%2C%20_5%20%3D%20'%20'%3B%0A%0A%2F%2F%20if%0A_1%20%3D%20'i'%2C%20_2%20%3D%20'f'%3B%0A%2F%2F%20fir%0A_1%20%3D%20_2%2C%20_2%20%3D%20'i'%2C%20_3%20%3D%20'r'%3B%0A%2F%2F%20trees%0A_1%20%3D%20't'%2C%20_2%20%3D%20_3%2C%20_3%20%3D%20'e'%2C%20_4%20%3D%20_3%2C%20_5%20%3D%20's'%3B%0A%2F%2F%20ever%0A_1%20%3D%20_3%2C%20_2%20%3D%20'v'%2C%20_4%20%3D%20'r'%2C%20_5%20%3D%20'r'%3B%0A%2F%2F%20fall%0A_1%20%3D%20'f'%2C%20_2%20%3D%20'a'%2C%20_3%20%3D%20'l'%2C%20_4%20%3D%20_3%2C%20_5%20%3D%20'%20'%3B)
2. with extra holder variables:
    * challenges: 
        1. [the toad reads me](https://goo.gl/4eqhLb)
        1. [eating meat every meal](https://goo.gl/F9Njwp)
        1. [many men may melt my mind](https://goo.gl/16C62t)
        1. [if fir trees ever fall](https://goo.gl/BCC6pz)
    * example solutions: 
        1. the toad reads me: [pytut](https://goo.gl/WrWMid), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20the%20toad%20reads%20me%0A%0Alet%20_1%20%3D%20%22%20%22%2C%20_2%20%3D%20%22%20%22%2C%20_3%20%3D%20%22%20%22%2C%20_4%20%3D%20%22%20%22%2C%20_5%20%3D%20%22%20%22%3B%0Alet%20x%20%3D%20'%20'%2C%20y%20%3D%20'%20'%3B%0A%0A%2F%2F%20the%0A_1%20%3D%20%22t%22%2C%20_2%20%3D%20%22h%22%2C%20_3%20%3D%20%22e%22%3B%0A%2F%2F%20toad%0Ax%20%3D%20_3%3B%0A_2%20%3D%20%22o%22%2C%20_3%20%3D%20%22a%22%2C%20_4%20%3D%20%22d%22%3B%0A%2F%2F%20reads%0A_1%20%3D%20%22r%22%2C%20_2%20%3D%20x%2C%20_5%20%3D%20%22s%22%3B%0A%2F%2F%20me%0A_1%20%3D%20%22m%22%2C%20_3%20%3D%20%22%20%22%2C%20_4%20%3D%20%22%20%22%2C%20_5%20%3D%20%22%20%22%3B)
        1. eating meat every meal: [pytut](https://goo.gl/ioTN8v), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20eating%20meat%20every%20meal%0A%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%2C%20_5%20%3D%20'%20'%2C%20_6%3D%20'%20'%3B%0Alet%20x%20%3D%20'%20'%2C%20y%20%3D%20'%20'%3B%0A%0A%2F%2F%20eating%0A_1%20%3D%20%22e%22%2C%20_2%20%3D%20%22a%22%2C%20_3%20%3D%20%22t%22%2C%20_4%20%3D%20%22i%22%2C%20_5%20%3D%20%22n%22%2C%20_6%3D%20%22g%22%3B%0A%2F%2F%20meat%0Ax%20%3D%20_2%3B%0A_4%20%3D%20_3%2C%20_3%20%3D%20_2%2C%20_2%20%3D%20_1%2C%20_1%20%3D%20%22m%22%2C%20_5%20%3D%20%22%20%22%2C%20_6%20%3D%20%22%20%22%3B%0A%2F%2F%20every%0Ay%20%3D%20_1%3B%0A_1%20%3D%20_2%2C%20_3%20%3D%20_2%2C%20_2%20%3D%20%22v%22%2C%20_4%20%3D%20%22r%22%2C%20_5%20%3D%20%22y%22%3B%0A%2F%2F%20meal%0A_1%20%3D%20y%2C%20_2%20%3D%20_3%2C%20_3%20%3D%20x%2C%20_4%20%3D%20%22l%22%2C%20_5%20%3D%20%22%20%22%3B)
        1. many men may melt my mind: [pytut](https://goo.gl/Q8LtiR), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20many%20men%20may%20melt%20my%20mind%0A%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%3B%0Alet%20x%20%3D%20'%20'%2C%20y%20%3D%20'%20'%3B%0A%0A%2F%2F%20many%0A_1%20%3D%20'm'%2C%20%20_2%20%3D%20'a'%2C%20_3%20%3D%20'n'%2C%20_4%20%3D%20'y'%3B%0A%2F%2F%20men%0Ax%20%3D%20_2%2C%20y%20%3D%20_4%3B%0A_2%20%3D%20'e'%2C%20_4%20%3D%20'%20'%3B%0A%2F%2F%20may%0A_3%20%3D%20y%2C%20y%20%3D%20_2%2C%20_2%20%3D%20x%3B%0A%2F%2F%20melt%0Ax%20%3D%20_3%3B%0A_2%20%3D%20y%2C%20_3%20%3D%20'l'%2C%20_4%20%3D%20't'%3B%0A%2F%2F%20my%0A_2%20%3D%20x%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%3B%0A%2F%2F%20mind%0A_2%20%3D%20'i'%2C%20_3%20%3D%20'n'%2C%20_4%20%3D%20'd'%3B)
        1. if fir trees ever fall: [pytut](https://goo.gl/SpjB6t), [parsons](https://janke-learning.github.io/parsonizer/?snippet=%2F%2F%20if%20fir%20trees%20ever%20fall%0A%0Alet%20_1%20%3D%20'%20'%2C%20_2%20%3D%20'%20'%2C%20_3%20%3D%20'%20'%2C%20_4%20%3D%20'%20'%2C%20_5%20%3D%20'%20'%3B%0Alet%20x%20%3D%20'%20'%2C%20y%20%3D%20'%20'%3B%20%2F%2F%20to%20save%20extra%20values%20for%20later%0A%0A%2F%2F%20if%0A_1%20%3D%20'i'%2C%20_2%20%3D%20'f'%3B%0A%2F%2F%20fir%0Ax%20%3D%20_2%3B%0A_2%20%3D%20_1%2C%20_1%20%3D%20x%2C%20_3%20%3D%20'r'%3B%0A%2F%2F%20trees%0A_1%20%3D%20't'%2C%20_2%20%3D%20_3%2C%20_3%20%3D%20'e'%2C%20_4%20%3D%20_3%2C%20_5%20%3D%20's'%3B%0A%2F%2F%20ever%0Ay%20%3D%20_2%3B%0A_1%20%3D%20_3%2C%20_2%20%3D%20'v'%2C%20_4%20%3D%20y%2C%20_5%20%3D%20'%20'%3B%0A%2F%2F%20fall%0A_1%20%3D%20x%2C%20_2%20%3D%20'a'%2C%20_3%20%3D%20'l'%2C%20_4%20%3D%20_3%2C%20_5%20%3D%20'%20'%3B)

[TOP](#variables-&-hoisting)

___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>
