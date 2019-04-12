# Errors

Errors will keep JS from executing your code.  This is not the goal of programming, so here's some errors to practice fixing.


Complete these exercises directly in the browser from your fork of this repo. (We've provided some completed examples for you to get the idea):
1. Paste the broken code into the devtools console and run it
1. Copy-paste the error message into the "error message" space the challenge
1. Classify the error: _Creation or Execution_ and _Syntax or Semantic_
1. Fix the error and paste your fixed code into "the fix" section of the challenge



Practice using the devtools by clicking on the 'VM##:#' link to the right of the error message.  Devtools will automatically open the source code and highlight where the error appears.  With these super simple examples this feature may feel like overkill, but you will appreciate it's help once you move on to the next set of exercises.

### Index:
* [learning objectives](#learning-objectives)
* exercises
    * [malfomed while loop](#malformed-while-loop) (completed example)
    * [missing variable name](#missing-variable-name)
    * [too-far object access](#too-far-object-access)
    * [access property direclty](#access-property-directly)
    * [improper multi-line string](#improper-multi-line-string)
    * [improper end of statement](#improper-end-of-statement)
    * [malformed array](#malformed-array)
    * [missing arguments](#missing-arguments)
    * [improper nested quotes 1](#improper-nested-quotes-1)
    * [improper nested quotes 2](#improper-nested-quotes-2)
    * [reassigning to constant](#reassigning-to-constant)
    * [unassigned const declaration](#unassigned-const-declaration)
    * [is not a function](#is-not-a-function)
* study tools
    * [PythonTutor for JavaScript](http://pythontutor.com/javascript.html#)
    * [the Parsonizer](https://janke-learning.github.io/parsonizer/)
* [resources](https://github.com/janke-learning/errors-and-life-cycle)

---
---

## Learning Objectives


* reading & identifying error messages
* finding and fixing syntax errors
* building a personal error+fix reference
* not logic errors, that's for 'debugging'
* using devtools console
* writing markdown directly from github




---
## Exercises

### malformed while loop

broken code:
```js
let value = 0;
while (value < 9) 
  value++;
};
```
error message:
```
Uncaught SyntaxError: Unexpected token }
```
classification:
* creation phase
* syntax

the fix:
```js
let value = 0;
while (value < 9) {
  value++;
};
```
your notes:

[TOP](#errors)

---

### missing variable name
broken code:
```js
var = 5;
```
error message:
```js
SyntaxError: Unexpected token 
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
var name= 5;
```
your notes:

[TOP](#errors)

---

## too-far object access
broken code:
```js
let a = {b:3};
let b = a.b.3
```
error message:
```js
SyntaxError: Unexpected number
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = {b:3};
let b = a.b;
```
your notes:

[TOP](#errors)

---
## access property directly
broken code:
```js
let x = {b:'e'};
let y = b.e;
```
error message:
```js
pythontutor gives no mistake
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let x = {b:'e'};
let y = x;
```
your notes:

[TOP](#errors)

---
## improper multi-line string
broken code:
```js
let a = 'this is 
two lines';
```
error message:
```js
SyntaxError: Unexpected token ILLEGAL
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = 'this is\n two lines';
```
your notes:

[TOP](#errors)

---
## improper end of statement
broken code:
```js
let a = 1:
```
error message:
```js
SyntaxError: Unexpected token 
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = 1;
```
your notes:

[TOP](#errors)

---
## malformed array
broken code:
```js
let myArray = [1, 2, 3;
```
error message:
```js
SyntaxError: Unexpected token 
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let myArray = [1, 2, 3];
```
your notes:

[TOP](#errors)

---
## missing arguments
broken code:
```js
function getNine {
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
error message:
```js
SyntaxError: Unexpected token
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
function getNine() {
2	  let x = 6;
3	  let y = 3;
4	  return x + y;
5	}
6	let result = getNine();
```
your notes:

[TOP](#errors)

---
## improper nested quotes 1
broken code:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
error message:
```js
SyntaxError: Unexpected token ILLEGAL
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let innerHtml = "<p>Click here to <a href=#Home>return home</a></p>";
```
your notes:

[TOP](#errors)

---
## improper nested quotes 2 
broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```js
SyntaxError: Unexpected string
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let nested_messages = 'remind yourself "i can do this!" at least once a day';
```
your notes:

[TOP](#errors)

---
## reassigning to constant
broken code:
```js
const a = 9;
a = 0;
```
error message:
```js
TypeError: Assignment to constant variable
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let a = 9;
a = 0;
```
your notes:
const value cannot b reassigned
[TOP](#errors)

---
## unassigned const declaration
broken code:
```js
const a;
a = 0;
```
error message:
```
SyntaxError: Missing initializer in const declaration
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
const a = 0;
```
your notes:

[TOP](#errors)

---
## is not a function
broken code:
```js
let array = [];
array.length()
```
error message:
```
TypeError: array.length is not a function
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
let array = [];
array.length;
```
your notes:



[TOP](#errors)



___
___
### <a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>


