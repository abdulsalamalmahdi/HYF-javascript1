1- Comment Your JavaScript Code:
```
// This is an in-line comment.

    /* This is a
    multi-line comment */
```
 
 2- Declare JavaScript Variables:
 ```
 var myName;
 ```
3- Storing Values with the Assignment Operator:
```
a = 7;
b = a;
```
4- Initializing Variables with the Assignment Operator:
```
var a = 9;
```
4- Understanding Uninitialized Variables:
```
var a = 5;
var b = 10;
var c = "I am a";
```
5- Understanding Case Sensitivity in Variables:
```
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```
6- Add Two Numbers with JavaScript:
```
var sum = 10 + 10;
```
7- Subtract One Number from Another with JavaScript:
```
var difference = 45 - 33;
```
8- Multiply Two Numbers with JavaScript:
```
var product = 8 * 10;

```
9- Divide One Number by Another with JavaScript:
```
var quotient = 66 / 33;
```
10- Increment a Number with JavaScript:
```
myVar++;
```
11- Decrement a Number with JavaScript:
```
myVar--;
```
12- Create Decimal Numbers with JavaScript:
```
var myDecimal = 3.4;
```
13- Multiply Two Decimals with JavaScript:
```
var product = 2.0 * 2.5;
```
14- Divide One Decimal by Another with JavaScript:
```
var quotient = 4.4 / 2.0; // Fix this line
```
15- Finding a Remainder in JavaScript:
```
var remainder = 11 % 3;
```
16- Compound Assignment With Augmented Addition:
```
var a = 3;
var b = 17;
var c = 12;

// Only modify code below this line

a += 12;
b += 9;
c += 7;
```
17- Compound Assignment With Augmented Subtraction:
```
var a = 11;
var b = 9;
var c = 3;

// Only modify code below this line

a -= 6;
b -= 15;
c -= 1;
```
18- Compound Assignment With Augmented Multiplication:
```
var a = 5;
var b = 12;
var c = 4.6;

// Only modify code below this line

a *= 5;
b *= 3;
c *=  10;
```
19- Compound Assignment With Augmented Division:
```
var a = 48;
var b = 108;
var c = 33;

// Only modify code below this line

a /= 12;
b /= 4;
c /= 11;
```
20- eclare String Variables:
```
// Example
var firstName = "Alan";
var lastName = "Turing";

// Only change code below this line

var myFirstName = "Abdulsalam";
var myLastName  = "Almahdi";
```
21- Escaping Literal Quotes in Strings:
```
r myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line

```
22- Quoting Strings with Single Quotes:
```
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';

```
23- Escape Sequences in Strings:
```
var myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; 
```
24- Concatenating Strings with Plus Operator:
```
var myStr = "This is the start. " + "This is the end.";
```
25- concatenating Strings with the Plus Equals Operator:
```
var myStr =  "This is the first sentence. ";

myStr += "This is the second sentence.";
```
26- Constructing Strings with Variables:
```
var myName = "Abdulsalam";
var myStr = "My name is " + myName + "and I am well!";
```
27-  Appending Variables to Strings:
```
var someAdjective = "learning to communicate with your mind";
var myStr = "Learning to code is ";
 
 myStr += someAdjective;
 ```
 28- Find the Length of a String:
 ```
 var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = lastName.length;
```
29- use Bracket Notation to Find the First Character in a String:
```
// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";

// Only change code below this line
firstLetterOfLastName = lastName[0];

```
30- Understand String Immutability:
```
myStr = "Hello World"; // Fix Me
```
31- Use Bracket Notation to Find the Nth Character in a String:
```
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];

// Setup
var lastName = "Lovelace";

// Only change code below this line.
var thirdLetterOfLastName = lastName[2];

```
32- Use Bracket Notation to Find the Last Character in a String:
```
// Setup
var lastName = "Lovelace";

// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length - 1];
```
33- Use Bracket Notation to Find the Nth-to-Last Character in a String:
```
// Setup
var lastName = "Lovelace";

// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length - 2];

```
34- Word Blanks:
```
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  

  var result =  "";

  result+= "My "+myAdjective+" "+myNoun+" "+myVerb+" very "+myAdverb+".";


  // Your code above this line
  return result;
}
```
35- Store Multiple Values in one Variable using JavaScript Arrays:
```
var myArray = ["Mike", 60];
```
36-  Nest one Array within Another Array:
```
var myArray = [["Harry Potter", 25],["Newet Scamander", 23]];
```
37- Access Array Data with Indexes:
```
var myArray = [50,60,70];

// Only change code below this line.
var myData = myArray[0]; 
```
38- Modify Array Data With Indexes:
```
var myArray = [18,64,99];
myArray[0] = 45;
```
39- access Multi-Dimensional Arrays With Indexes:
```
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];

// Only change code below this line.
var myData = myArray[2][1];
```
40- Manipulate Arrays With push():
```
var myArray = [["John", 23], ["cat", 2]];
myArray.push(["dog", 3]);
```
41- Manipulate Arrays With pop():
```
var removedFromMyArray = myArray.pop();
```
42- Manipulate Arrays With shift():
```
var removedFromMyArray = myArray.shift();
```
43- Manipulate Arrays With unshift():
```
r myArray = [["John", 23], ["dog", 3]];
myArray.shift();

// Only change code below this line.

myArray.unshift(["Paul", 35]);
```
44- Shopping List:
```
var myList = [
    ["Icecream", 20],
    ["Juice", 14],
    ["Bisckuit", 10],
    ["Beer", 5],
    ["Candy", 8]
];
```

45- Write Reusable JavaScript with Functions:
```
function reusableFunction () {
    console.log("Hi World");
}

reusableFunction();
```
46- Passing Values to Functions with Arguments:
```
function functionWithArgs(a, b){
  console.log(a + b);
}
 
 functionWithArgs(3, 4);
 ```
 47- Global Scope and Functions:
 ```
 var myGlobal = 10;

function fun1() {
  // Assign 5 to oopsGlobal Here
  oopsGlobal = 5;
}

// Only change code above this line
function fun2() {
  var output = "";
  if (typeof myGlobal != "undefined") {
    output += "myGlobal: " + myGlobal;
  }
  if (typeof oopsGlobal != "undefined") {
    output += " oopsGlobal: " + oopsGlobal;
  }
  console.log(output);
}
```
48- ocal Scope and Functions:
```
unction myLocalScope() {
  'use strict'; // you shouldn't need to edit this line
 var myVar;
  console.log(myVar);
}
myLocalScope();

// Run and check the console
console.log();
// myVar is not defined outside of myLocalScope


// Now remove the console log line to pass the test
```
49- Global vs. Local Scope in Functions:
```
var outerWear = "T-Shirt";

function myOutfit() {
  // Only change code below this line
  
  var outerWear = "sweater";
  
  // Only change code above this line
  return outerWear;
}

myOutfit();
```
50- Return a Value from a Function with Return;
```
function timesFive(x){
  return x * 5;
}

console.log(timesFive(10));
```
51- Understanding Undefined Value returned from a Function:
```
var sum = 0;
function addThree() {
  sum = sum + 3;
}

// Only change code below this line

function addFive(){
    
    sum += 5; 
}

// Only change code above this line
var returnedValue = addFive();
```
52- ssignment with a Returned Value:
```
var processed = 0;ssignment with a Returned Value 

function processArg(num) {
  return (num + 3) / 5;
}

// Only change code below this line

 processed = processArg(7);
 ```
 53- Stand in Line:
 ```
 function nextInLine(arr, item) {
  // Your code here
    arr.push(item)
   var removed = arr.shift(0);
  return removed;  // Change this line
}

// Test Setup
var testArr = [1,2,3,4,5];

// Display Code
console.log("Before: " + JSON.stringify(testArr));
console.log(nextInLine(testArr, 6)); // Modify this line to test
console.log("After: " + JSON.stringify(testArr));
 ```
 
 54- Understanding Boolean Values:
 ```
 function welcomeToBooleans() {

// Only change code below this line.

return true; // Change this line

// Only change code above this line.
}
```
55-  Use Conditional Logic with If Statements:
```
function trueOrFalse(wasThatTrue) {

  // Only change code below this line.
  if (wasThatTrue){
      return "Yes, that was true";
  }
  
  return "No, that was false";
  // Only change code above this line.
  
}

// Change this value to test
trueOrFalse(true);
```
 56- Comparison with the Equality Operator:
 ```
 function testEqual(val) {
  if (val == 12) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testEqual(12);
```
57- Comparison with the Strict Equality Operator:
```
function testStrict(val) {
  if (val === 7) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
testStrict(10);
```
58- Practice comparing different values:
```
function compareEquality(a, b) {
  if (a === b) { // Change this line
    return "Equal";
  }
  return "Not Equal";
}

// Change this value to test
compareEquality(10, "10");
```
59- omparison with the Inequality Operator:
```
nction testNotEqual(val) {
  if (val != 99) { // Change this line
    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testNotEqual(10);
```
60- omparison with the Strict Inequality Operator:
```
function testStrictNotEqual(val) {
  // Only Change Code Below this Line
  
  if (val !== 17) {

  // Only Change Code Above this Line

    return "Not Equal";
  }
  return "Equal";
}

// Change this value to test
testStrictNotEqual(10);
```
61- Comparison with the Greater Than Operator:
```
function testGreaterThan(val) {
  if (val > 100) {  // Change this line
    return "Over 100";
  }
  
  if (val > 10) {  // Change this line
    return "Over 10";
  }

  return "10 or Under";
}

// Change this value to test
testGreaterThan(10);
```
62- Comparison with the Greater Than Or Equal To Operator:
```
function testGreaterOrEqual(val) {
  if (val >= 20) {  // Change this line
    return "20 or Over";
  }
  
  if (val >= 10) {  // Change this line
    return "10 or Over";
  }

  return "Less than 10";
}

// Change this value to test
testGreaterOrEqual(10);
```
63- Comparison with the Less Than Operator:
```
unction testLessThan(val) {
  if (val < 25) {  // Change this line
    return "Under 25";
  }
  
  if (val < 55) {  // Change this line
    return "Under 55";
  }

  return "55 or Over";
}

// Change this value to test
testLessThan(10);
```
64- Comparison with the Less Than Or Equal To Operator:
```
function testLessOrEqual(val) {
  if (val <= 12) {  // Change this line
    return "Smaller Than or Equal to 12";
  }
  
  if (val <= 24) {  // Change this line
    return "Smaller Than or Equal to 24";
  }

  return "More Than 24";
}

// Change this value to test
testLessOrEqual(10);

```
65- Comparisons with the Logical And Operator:
````
function testLogicalAnd(val) {
  // Only change code below this line

  
    if (val <= 50 && val >= 25 ) {
      return "Yes";
    }
  

  // Only change code above this line
  return "No";
}

// Change this value to test
testLogicalAnd(40);
```
66- Comparisons with the Logical Or Operator:
```
unction testLogicalOr(val) {
  // Only change code below this line

  if (val > 20 || val < 10) {
    return "Outside";
  
  }

  // Only change code above this line
  return "Inside";
}

// Change this value to test
testLogicalOr(15);
```
67- Introducing Else Statements:
```
function testElse(val) {
  var result = "";
  // Only change code below this line
  
  if (val > 5) {
    result = "Bigger than 5";
  }
  
 else {
    result = "5 or Smaller";
  }
  
  // Only change code above this line
  return result;
}

// Change this value to test
testElse(4);
```
68-  Introducing Else If Statements:
```
nction testElseIf(val) {
  if (val > 10) {
    return "Greater than 10";
  }
  
  else if (val < 5) {
    return "Smaller than 5";
  }
  else{
  
  return "Between 5 and 10";
}

// Change this value to test
testElseIf(7);
}
```
69- Logical Order in If Else Statements:
```
function orderMyLogic(val) 
  if (val < 5) {
    return "Less than 5" ;
  } else if (val < 10) {
    return "Less than 10";
  } else {
    return "Greater than or equal to 10";
  }
}

// Change this value to test
orderMyLogic(7);
```
70- Chaining If Else Statements:
```

unction testSize(num) {
  // Only change code below this line
  if (num < 5){
    return "Tiny";
  }
  else if (num < 10){
     return "Small";
  }
  else if (num < 15){

    return "Medium";
  }
  else if (num < 20){
    return "Large";
  }
  else if (num >= 20){
     return "Huge";
  }
  return "Change Me";
  // Only change code above this line
}

// Change this value to test
testSize(7);
```
71-  Golf Code:
```
names = ["Hole-in-one!", "Eagle", "Birdie", "Par", "Bogey", "Double Bogey", "Go Home!"];
function golfScore(par, strokes) {
  // Only change code below this line
  
  
  return "Change Me";
  // Only change code above this line
}

// Change these values:
to test
golfScore(5, 4);
```
-72: electing from Many Options with Switch Statements:
```
function caseInSwitch(val) {
  var answer = "";
  // Only change code below this line
     switch(val){
          case 1: 
          answer = "alpha";
          break;
          case 2: 
          answer =  "beta";
          break;
          case 3: 
          answer =  "gamma";
          break;
          case 4: 
          answer =  "delta";
          break;

     }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
caseInSwitch(2);
```
73- Adding a Default Option in Switch Statements:
```
function switchOfStuff(val) {
  var answer = "";
  // Only change code below this line
  switch(val){

    case "a":
    answer = "apple";
    break;

    case "b":
    answer = "bird";
    break;

    case "c":
    answer = "cat";
    break;

    default:
    answer = "stuff";
    break;
  }
  
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
switchOfStuff('c');
```
74- Multiple Identical Options in Switch Statements:
```
function sequentialSizes(val) {
  var answer = "";
  // Only change code below this line
  switch(val){

    case 1:
    case 2:
    case 3:
    answer = "Low";
    break;
    case 4:
    case 5:
    case 6:
    answer = "Mid";
    break;
    case 7:
    case 8:
    case 9:
    answer = "High";
    break;
  }
  
  
  // Only change code above this line  
  return answer;  
}
// Change this value to test
sequentialSizes(10);
```

75- Replacing If Else Chains with Switch:
```
function chainToSwitch(val) {
  var answer = "";
  // Only change code below this line
  switch (val){
   
   case "bob":
    answer = "Marley";
    break;

   case 42:
    answer = "The Answer";
    break;

  case  1:
    answer = "There is no #1";
    break;

  case 99: 
    answer = "Missed me by this much!";
    break;

  case 7:
    answer = "Ate Nine";
    break;
  }
  
  // Only change code above this line  
  return answer;  
}

// Change this value to test
chainToSwitch(7);
```
76- Returning Boolean Values from Functions:
function isLess(a, b) {
  // Fix this code
    return a < b;
  
  }


// Change these values to test
isLess(10, 15);
```
77- Return Early Pattern for Functions:
function abTest(a, b) {
  // Only change code below this line
  
  if (a < 0 || b < 0){
    
    return;
  }
  
  // Only change code above this line

  return Math.round(Math.pow(Math.sqrt(a) + Math.sqrt(b), 2));
}

// Change values below to test your code
abTest(2,-1);

78- Counting Cards:
```
var count = 0;

function cc(card){
      // Only change code below this line
      switch(card){
        case 2:
        case 3:
        case 4:
        case 5:
        case 6:
          count++;
          break;
        case 10:
        case "J":
        case "Q":
        case "K":
        case "A":
          count--;
          break;
      }
      if (count > 0){
        return count + " Bet";
      } else {
        return count + " Hold";
      }
      // Only change code above this line
    }

// Add/remove calls to test your function.
// Note: Only the last will display
cc(2); cc(3); cc(7); cc('K'); cc('A');
```
80- Build JavaScript Objects:
```

var myDog = {
  "name" : "popy",
  "legs" : 1,
  "tails" :2,
  "friends" : ["mac", "bob", "al"] 
};
```
81-  Accessing Object Properties with Dot Notation:
```
var testObj = {
  "hat": "ballcap",
  "shirt": "jersey",
  "shoes": "cleats"
};

// Only change code below this line

var hatValue = testObj.hat;      // Change this line
var shirtValue = testObj.shirt;    // Change this line
```
82- Accessing Object Properties with Bracket Notation:
```
var testObj = {
  "an entree": "hamburger",
  "my side": "veggies",
  "the drink": "water"
};

// Only change code below this line

var entreeValue = testObj ["an entree"];   // Change this line
var drinkValue = testObj ["the drink"];    // Change this line
````
83-  Accessing Object Properties with Variables:
```
var testObj = {
  12: "Namath",
  16: "Montana",
  19: "Unitas"
};

// Only change code below this line;

var playerNumber = 16 ;       // Change this Line
var player = testObj[playerNumber];   // Change this Line
```
