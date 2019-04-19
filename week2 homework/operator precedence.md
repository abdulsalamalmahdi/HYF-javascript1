Exercises
Types and Casting
types & casting 1

parsonized
on pytut

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = false, b = true;

const expected = typeof a === typeof b;

const val_1 = typeof a;

const step_1 = val_1 > b === a;

console.assert(step_1 === expected, "step_1");

const val_2 = (val_1 < b) || a;

const step_2 = val_2 === (val_1 && a);
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 * b / a;

const step_3 = val_2 === Boolean(val_3);
console.assert(step_3 === expected, "step_3");

types & casting 2

parsonized
on pytut

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a =1 , b = -1;

const expected = Boolean(a) !== Boolean(b);

 const val_1 = a + b && b;
const step_1 = val_1 < (a*b) ;
console.assert(step_1 === expected, "step_1");

const val_2 = typeof val_1 === a*(b/step_1);
const step_2 = val_2 ===a;
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 && val_1 || b;
const step_3 = typeof val_3 >= val_2;
console.assert(step_3 === expected, "step_3");

types & casting 3

parsonized
on pytut

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = NaN, b = null;

const expected = Boolean(b) === Boolean(Number(a));

const val_1 = typeof b;
const step_1 = Number(typeof(val_1)) !== b*a;
console.log(b*a);
console.assert(step_1 === expected, "step_1");

const val_2 = a * val_1 && b;
const step_2 = val_2 * a !== val_1 * b;
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 * a !== a;
const step_3 = val_3 === (val_1 !== b);
console.assert(step_3 === expected, "step_3");

const val_4 = val_3 > val_2 === a > b;
const step_4 = val_4 !== val_2;
console.assert(step_4 === expected, "step_4");

TOP
Logical Operators
logical operators 1

parsonized
on pytut

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = 1, b = 0;

const expected = Boolean(b) === Boolean(Number(a));

const val_1 = typeof expected;
const step_1 = val_1 === b;
console.assert(step_1 === expected, "step_1");

const val_2 = typeof val_1 !== b;
const step_2 = val_2 > val_1 && b;
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 && val_1 || a;
const step_3 = val_3 === val_2;
console.assert(step_3 === expected, "step_3");

const val_4 = val_1 !== val_2;
const step_4 = val_4 > val_2*val_1/val_3;
console.assert(step_4 === expected, "step_4");

logical operators 2

parsonized
on pytut


/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = true, b = false;

const expected = !!a || !!b;

const val_1 = !a && !b;
const step_1 = val_1 === !!b && !!a ;
console.assert(step_1 === expected, "step_1");

const val_2 = !val_1 && a || b;
const step_2 = val_2 ;
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 && val_1 || b;
const step_3 = val_3 || val_2;
console.assert(step_3 === expected, "step_3"); 

const val_4 = val_2 || val_1 && val_3;
const step_4 = val_4 && val_2;
console.assert(step_4 === expected, "step_4");

const val_5 = val_3 || val_2 && val_1;
const step_5 = val_5 || val_4;
console.assert(step_5 === expected, "step_5");


logical operators 3

parsonized
on pytut

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = true, b = false, c = 1;

var expected = a || b && c || a;

expected = b && c;

expected = a || b && c;

expected = a || b && c || a;
// break down this expression


ast explorer

TOP
Arithmetic Operators
arithmetic operators 1

parsonized
on pytut

/* values to try
  0, 1, -1, NaN, Infinity, .5, -0.0, 1e3, 1e-3, 999e305, 999e306
*/
const a = 1, b = 0, c = .5 ;

const expected = -(a + b) * c;

const val_1 = (c + b) * a;
const step_1 = val_1 * -(b + a);
console.assert(step_1 === expected, "step_1");

const val_2 =  a * c - b;
const step_2 = -(a *c + b);
console.assert(step_2 === expected, "step_2");

const val_3 = val_2 * (a + b);
const step_3 = a * (step_2);
console.assert(step_3 === expected, "step_3");


scientific notation
arithmetic operators 2

parsonized
on pytut

{
  /* values to try
    0, 1, -1, NaN, Infinity, .5, -0.0, 1e3, 1e-3, 999e305, 999e306
  */
  const a = , b = , c = ;

  const expected = a ** b / +c;

  // break down this expression 
}

arithmetic operators 3

parsonized
on pytut

{
  /* values to try
    0, 1, -1, NaN, Infinity, .5, -0.0, 1e3, 1e-3, 999e305, 999e306
  */
  const a = , b = , c = ;

  const expected = b % c - a ** c / b;

  // break down this expression
}

TOP
All Primitive Operators
all primitive operators 1

parsonized
on pytut
{
/* values to try
  0, 1, -1, NaN, Infinity, .5, -0.0, 1e3, 1e-3, 999e305, 999e306
  0, 3
  1, 3
  2, 3
  3, 3
  4, 3
*/
const a = 1, b = 0;

var expected = a % b || !!a;

expected = a % b;
expected = a % b || !!a;
// break down this expression
}

all primitive operators 2

parsonized
on pytut

{
  * values to try
  0, 1, -1, NaN, Infinity, .5, -0.0, 1e3, 1e-3, 999e305, 999e306
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = true;

var expected = typeof a === 'number' + a;
// break down this expression
typeof a;
 
'number' + a;

typeof a === 'number' + a;

}

all primitive operators 3

parsonized
on pytut

{

/* values to try
  "", " ", true, false, undefined, null, 0, 1, -1, NaN, Infinity
*/
const a = 1;

const expected = !!+a === Boolean(a);
 
 // break down this expression
!!a;
 +a;

}
