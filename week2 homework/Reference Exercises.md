Reference Exercises

Swap the Object & the Array
on pytut

let obj = [];
let arr = {};
let _ = null;

// --- swap below here ---
```
_ = obj;

obj = arr;

arr = _;
```

Complete this code


let value_1 = 5;
  let reference_1 = [];

  let value_2 = value_1;
  console.assert(value_2 === value_1);

  let reference_2 = reference_1;
  console.assert(reference_2 === reference_1);

      value_1 = 6; // write this line
  console.assert(value_1 !== value_2);  
    
     reference_1.push(6)
     reference_2.push(9); // write this line
  console.assert(reference_1[0] === reference_2[0]);

  // remove the array from memory
   reference_1 = null; // write this line
   reference_2 = null ; // write this line

TOP
Array Exercises

Complete the Assertions

let a_1 = [];
let a_2 = a_1;
console.assert(a_1  ===  a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 !==  b_2);

// ---

a_1.push(3);
a_2.push(3);
console.assert(a_1  ===  a_2);

b_1.push(5);
b_2.push(5);
console.assert(b_1  !== b_2);

Complete the Assertions
on pytut

let a_1 = [];
let a_2 = a_1;
console.assert(a_1 === a_2);

let b_1 = [];
let b_2 = [];
console.assert(b_1 !== b_2);

// ---

const key = 0;

a_1[key] = 3;
a_2[key] = 3;
console.assert(a_1 === a_2);

b_1[key] = 5;
b_2[key] = 5;
console.assert(b_1 !== b_2);

Fill in the Blanks
on pytut
let arr_1 = []; // write this line
let arr_2 = []; // write this line
console.assert(arr_1 !== arr_2);
console.assert(arr_1[1] === arr_2[1]);

let key = 0;
console.assert(arr_1[key] === arr_2[key]);

  arr_1[0] = arr_2[2]; // write this line
  arr_2[0] = arr_1[2]; // write this line
console.assert(arr_1[arr_2[2]] === arr_2[arr_1[2]]);

    arr_2 = arr_1; // write this line
let arr_3 = []; // write this line
console.assert(arr_1 === arr_2);
console.assert(arr_3 !== arr_1);
console.assert(arr_3 !== arr_2);
console.assert(arr_3[key] === arr_1[0]);

    let obj_3 ={'1':0};
    let obj_2 = {'0':0};// write this line
console.assert(obj_3[1] === obj_2[key]);


TOP
Object Exercises

Complete the Assertions
on pytut

let a_1 = {};
let a_2 = a_1;
console.assert(a_1 === a_2);

let b_1 = {};
let b_2 = {};
console.assert(b_1 !== b_2);

// ---

a_1.x = 3;
a_2.x = 3;
console.assert(a_1 === a_2);

b_1.x = 5;
b_2.x = 5;
console.assert(b_1 !== b_2);

Complete the Assertions
on pytut
 let a_1 = {};
  let a_2 = a_1;
  console.assert(a_1 === a_2);

  let b_1 = {};
  let b_2 = {};
  console.assert(b_1!== b_2);

  // ---
  
  const key = "x";

  a_1[key] = 3;
  a_2[key] = 3;
  console.assert(a_1 === a_2);

  b_1[key] = 5;
  b_2[key] = 5;
  console.assert(b_1 !== b_2);
  
Fill in the Blanks
on pytut
let obj_1 = {}; // write this line
let obj_2 = {}; // write this line
console.assert(obj_1 !== obj_2);
console.assert(obj_1.x === obj_2.x);

let key = "y";
console.assert(obj_1[key] === obj_2[key]);

   obj_1[key] = 4; // write this line
   obj_2[key] = 4; // write this line
console.assert(obj_1[obj_2.y] === obj_2[obj_1.y]);
  console.log((obj_1[obj_2.y] === obj_2[obj_1.y]));
  obj_1 = obj_2; // write this line
    let obj_3= {"y":4}; // write this line
console.assert(obj_1 === obj_2);
console.assert(obj_3 !== obj_1);
console.assert(obj_3 !== obj_2);
console.assert(obj_3[key] === obj_1.y);

   obj_3 = {"x":4} ; // write this line
console.assert(obj_3.x === obj_2[key]);


TOP
Comparison Exercises

Swap 'em
on pytut

const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

_ = obj; // swap the values stored in each structure
obj.prop = arr; //  using dot notation for the object
arr[0] = _; //  using direct access for the array

Swap 'em
on pytut
const obj = {prop: "array"};
const arr = ["object"];
let _ = null;

_ = obj;// swap the values stored in each structure
obj["prop"] = arr;//  using bracket notation for the object
arr[0] = _;//  using variable access for the array
 const obj_key = obj.prop;
 const arr_index = arr[0] ;
 
Relative vs Absolute
on pytut

// array indices are relative
const arr = ["a", "b"];
const index = 0;

const read_arr_1 = arr[index];
arr.shift(0); // removes the first item
const read_arr_2 = arr[index];

console.assert(read_arr_1 !== read_arr_2);

// object keys are absolute
const obj = {x: "a", y: "b"};
const key = "y";

const read_obj_1 = obj[key];
delete obj.x;
const read_obj_2 = obj[key];

console.assert(read_obj_1 ===  read_obj_2);
