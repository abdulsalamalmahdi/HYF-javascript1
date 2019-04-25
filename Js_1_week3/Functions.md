Exercises
1

on pytut
parsonized

function f(param_1, param_2, param_3) {
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "y", arg_2 = "x", arg_3 = "z";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "zyx", "1: return_val === " + return_val);

2

on pytut
parsonized

function f(param_1, param_2, param_3) {
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "x", arg_2 = "z", arg_3 = "y";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "return_val === " + return_val);
3

on pytut
parsonized

function f(param_1, param_2, param_3) {
  var _ = param_2;
  param_2 = param_1;
  param_1 = _;
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "z", arg_2 = "x", arg_3 = "y";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "return_val === " + return_val);

4

on pytut
parsonized

function f(param_1, param_2, param_3) {
  var _ = param_2;
  param_2 = param_3;
  param_3 = _;
  var result = param_3 + param_1 + param_2;
  return result;
};

// set values in the args to pass the assert
let arg_1 = "y", arg_2 = "x", arg_3 = "z";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "xyz", "return_val === " + return_val);

5

on pytut
parsonized

function f(param_1, param_2, param_3) {
 var result = param_3 + param_1 + param_2;
 return result;
};

let x = "x", y = "y", z = "z";
let return_val = f(y,z,x);

console.assert(return_val === "xyz", "5: return_val === " + return_val);

6

on pytut
parsonized


function f(param_1, param_2, param_3) {
 var result = param_2 + param_1 + param_3;
 return result;
};

let x = "x", y = "y", z = "z";
let return_val = f(z,x,y);

console.assert(return_val === "xzy", "6: return_val === " + return_val);

7

on pytut

function f(param_1, param_2, param_3) {
 var result =param_3 + param_1 + param_2;
 return result;
};

let arg_1 = "z", arg_2 = "y", arg_3 = "x";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "xzy", "7: return_val === " + return_val);

8

on pytut
parsonized

function f(param_1, param_2, param_3) {
 var result = param_2 + param_3 + param_1;
 return result;
};

let arg_1 = "z", arg_2 = "y", arg_3 = "x";
let return_val = f(arg_1, arg_2, arg_3);

console.assert(return_val === "yxz", "8: return_val === " + return_val);

Turtle Shuffle

Exercises
1

on pytut

function turtle(_1, _2, _3) {
  var result = "";
  var the_start = "tur";
  result = the_start + _1 + _2 + _3;
  return result;
}
const return_val = turtle("t","l","e");
console.assert(return_val === 'turtle', "2: return_val === " + return_val);

on pytut

function turtle(_1, _2) {
  var result = "";
  var the_start = "tu";
  var the_end = "le";
  result = the_start + _1 + _2 + the_end;
  return result;
}
const return_val = turtle("r","t");
console.assert(return_val === 'turtle', "3: return_val === " + return_val);

3

function turtle(_1, _2) {
  var result = "t" + _1 + "r" + _2;
  return result;
}
const return_val = turtle("u","tle");
console.assert(return_val === 'turtle', "4: return_val === " + return_val)

4

function turtle(_1, _2, _3) {
  var result = "t" + _2 + "r" + _1 + _3;
  return result;
}
const return_val_1 = turtle("t","u","le");
console.assert(return_val_1 === 'turtle', "5: return_val_1 === " + return_val_1);

const return_val_2 = turtle("tl","u","e");
console.assert(return_val_2 === 'turtle', "5: return_val_2 === " + return_val_2);

5

function turtle(_1, _2, _3) {
  var result = _1 + _2 + _3;
  return result;
}
const return_val_1 = turtle("tu","rt","le");
console.assert(return_val_1 === 'turtle', "6: return_val_1 === " + return_val_1);

const return_val_2 = turtle("t","urt","le");
console.assert(return_val_2 === 'turtle', "6: return_val_2 === " + return_val_2);

const return_val_3 = turtle("t","ur","tle");
console.assert(return_val_3 === 'turtle', "6: return_val_3 === " + return_val_3);

const return_val_4 = turtle("t","u","rtle");
console.assert(return_val_4 === 'turtle', "6: return_val_4 === " + return_val_4);

const return_val_5 = turtle("turt","l","e");
console.assert(return_val_5 === 'turtle', "6: return_val_5 === " + return_val_5);

const return_val_6 = turtle("t","urtl","e");
console.assert(return_val_6 === 'turtle', "6: return_val_6 === " + return_val_6);

6

function turtle(_1, _2, _3, _4, _5) {
  var result = _4 + _2 + _5 + _4 + _1 + _3;
  return result;
}
const return_val = turtle("l","u","e","t","r");
console.assert(return_val === 'turtle', "7: return_val === " + return_val);

7

function turtle(_1, _2, _3, _4, _5) {
  var result = _2 + _1 + _4 + _2 + "l" + _3;
  return result;
}
const return_val = turtle("u","t","e","r");
console.assert(return_val === 'turtle', "7: return_val === " + return_val);

8

function turtle(_1, _2, _3, _4, _5) {
  _4 = _2;
  _1 = _3;
  var result = _4 + "u" + _1 + _4 + _5 + "e";
  return result;
}
const return_val = turtle("","t","r","t","l");
console.assert(return_val === 'turtle', "9: return_val === " + return_val);

9

function turtle(_1, _2, _3, _4, _5) {
  var _ = _4;
  _4 = _2;
  _1 = _3;
  _3 = _;
  var result = _4 + "u" + _1 + _4 + _3 + "e";
  return result;
}
const return_val = turtle("","t","r","l","");
console.assert(return_val === 'turtle', "9: return_val === " + return_val);

Sentences

warmup
2 
function a_word(_1, _2, _3, _4) { 
  
  function tour(_a, _b, _c, _d) {
    return _c + _a + _d + _b;
  }
  var word = tour(_4,_3,_2,_1);

  var result = word;
  return result;
}
const return_val = a_word("u","t","r","o");
console.assert(return_val === 'tour', "wu-2: return_val === " + return_val);

Exercises
1

function sentence(_1, _2, _3) { 
  
  function eat(_x, _y, _z) {
    return _x + _y + _z;
  }
  var word_1 = eat(_2,_1,_3);

  function ate(_x, _y, _z) {
    return _x + _y + _z;
  }
  var word_2 = ate(_1, _3, _2);

  function tea(_x, _y, _z) {
    
   var _= _x;
    _x= _3;
    _3= _;
    return _x + _y + _3;
  }
  var word_3 = tea(_1,_2,_3);

  var result = word_1 + " " + word_2 + " " + word_3;
  return result;
}
const return_val = sentence("a", "e", "t");
console.assert(return_val === 'eat ate tea', "1: return_val === " + return_val);

2

function sentence(_1, _2, _3) { 
  
  function eat(_x, _y, _z) {
    return _z + _y + _x;
  }
  var word_1 = eat(_3,_1,_2);

  function ate(_x, _y, _z) {
    return _y + _x + _z;
  }
  var word_2 = ate(_3,_1,_2);

  function tea(_x, _y, _z) {
    return _x + _z + _y;
  }
  var word_3 = tea(_3,_2,_1);

  var result = word_1 + " " + word_2 + " " + word_3;
  return result;
}
const return_val = sentence("a", "e", "t");
console.assert(return_val === 'eat ate tea', "2: return_val === " + return_val);

3

function sentence(_1, _2, _3, _4, _5) { 

  function space(_v, _w, _x, _y, _z) {
    return _v + _w + _x + _y + _z;
  }
  var word_1 = space(_1,_2,_3,_4,_5);

  function capes(_v, _w, _x, _y, _z) {
    return _v + _w + _x + _y + _z;
  }
  var word_2 = capes(_4, _3, _2, _5, _1);

  var result = word_1 + " " + word_2;
  return result;
}
const return_val = sentence("s","p","a","c","e");
console.assert(return_val === 'space capes', "3: return_val === " + return_val);

4




5

on pytut

{ // 5 -> cruel ulcer
  function sentence(_1, _2, _3, _4, _5) { 

    function cruel(_v, _w, _x, _y, _z) {
      return _v + _w + _x + _y + _z;
    }
    var word_1 = cruel(_3, _1, _4, _5, _2);

    function ulcer(_v, _w, _x, _y, _z) {
      return _v + _w + _x + _y + _z;
    }
    var word_2 = ulcer(/* fill this in */);

    var result = word_1 + " " + word_2;
    return result;
  }
  const return_val = sentence(/* fill this in */);
  console.assert(return_val === 'cruel ulcer', "5: return_val === " + return_val);
};

6

on pytut

{ // 6 -> cruel ulcer
  function sentence(_1, _2, _3, _4, _5) { 

    function cruel(_v, _w, _x, _y, _z) {
      return _v + _w + _x + _y + _z;
    }
    var word_1 = cruel(/* fill this in */);

    function ulcer(_v, _w, _x, _y, _z) {
      return _v + _w + _x + _y + _z;
    }
    var word_2 = ulcer(/* fill this in */);

    var result = word_1 + " " + word_2;
    return result;
  }
  const return_val = sentence("e", "l", "u", "c", "r");
  console.assert(return_val === 'cruel ulcer', "6: return_val === " + return_val);
};

7

on pytut

{ // 7 -> cruel ulcer
  function sentence(_1, _2, _3, _4, _5) { 

    function cruel(_v, _w, _x, _y, _z) {
      return _x + _z + _w + _v + _y;
    }
    var word_1 = cruel(/* fill this in */);

    function ulcer(_v, _w, _x, _y, _z) {
      return _z + _w + _y + _x + _v;
    }
    var word_2 = ulcer(/* fill this in */);

    var result = word_1 + " " + word_2;
    return result;
  }
  const return_val = sentence("e", "l", "u", "c", "r");
  console.assert(return_val === 'cruel ulcer', "7: return_val === " + return_val);
};
