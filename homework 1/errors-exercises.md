
### missing variable name
broken code:
```js
var a = 5;
```
error message:
```js
SyntaxError: missing variable name
```
classification:
* creation phase.
* syntax.

the fix:
```js
var x = 5;
```
your notes:
declare variable name after var

[TOP](#errors)

## too-far object access
broken code:
```js
let a = {b:3};
let b = a.b.3;
```
error message:
```
SyntaxError: Unexpected number
```
classification:
* creation phase.
* syntax.

the fix:
```js
let a = {b:3};
let b = a.b;
```
your notes:
access the value only by its prop name.
[TOP](#errors)

## access property directly
broken code:
```js
let x = {b:'e'};
let y = b.e;
```
error message:
```
ReferenceError: b is not defined 
```
classification:
* creation phase.
* syntax.

the fix:
```js
let x = {b:'e'};
let y = x.b;
```
your notes:
use object.prop to acess its value
[TOP](#errors)

---
## improper multi-line string
broken code:
```js
let a = 'this is 
two lines';
```
error message:
```
SyntaxError: Unexpected token ILLEGAL.
```
classification:
* creation phase.
* syntax.

the fix:
```js
let a = 'this is two lines';
```
your notes:
strings can not be broken.
[TOP](#errors)

---
## improper end of statement
broken code:
```js
let a = 1:
```
error message:
```
SyntaxError: Unexpected token :
```
classification:
* creation phase 
* syntax.

the fix:
```js
let a = 1;
```
your notes:
always close statments with a semicolon.
[TOP](#errors)

---
## malformed array
broken code:
```js
let myArray = [1, 2, 3;
```
error message:
```
SyntaxError: Unexpected token ;
```
classification:
* creation phase.
* syntax.

the fix:
```js
let myArray = [1, 2, 3];
```
your notes:
an array should be enclosed inside two square prackets.
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
```
SyntaxError: Unexpected token {
```
classification:
* creation phase or execution phase ?
* syntax or semanitc ?

the fix:
```js
function getNine (){
  let x = 6;
  let y = 3;
  return x + y;
}
let result = getNine();
```
your notes:
always create brackets immediately after the function name.
[TOP](#errors)

---
## improper nested quotes 1
broken code:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
error message:
```
SyntaxError: Unexpected token ILLEGAL
```
classification:
* creation phase.
* syntax.

the fix:
```js
let innerHtml = "<p>Click here to <a href="#Home">return home</a></p>";
```
your notes:
use single quotes to contain nested qoutes.
[TOP](#errors)

---
## improper nested quotes 2 
broken code:
```js
let nested_messages = 'remind yourself ''i can do this!'' at least once a day';
```
error message:
```
SyntaxError: Unexpected string
```
classification:
* creation phase.
* syntax.

the fix:
```js
let nested_messages = 'remind yourself "i can do this!" at least once a day';
```
your notes:
use the same type of qoutes for external quoring but use different type for nested.
[TOP](#errors)

---
## reassigning to constant
broken code:
```js
const a = 9;
a = 0;
```
error message:
```
TypeError: Assignment to constant variable.
```
classification:
* execution phase.
* syntax.

the fix:
```js
let a = 9;
a = 0;
```
your notes:
you can not reassign const.
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
* creation phase.
* syntax.

the fix:
```js
let a;
a = 0;
```
your notes:
when declaring const it most be initialized to a value.
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
* creation phase.
* syntax.

the fix:
```js
let array = [];
array.length;
```
your notes:
do not use brackets after length because it is a property not a method.


[TOP](#errors)



___
___
### [a link](<a href="http://janke-learning.org" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/50098409-22575780-021c-11e9-99e1-962787adaded.png" width="40" height="40"></img> Janke Learning</a>)

