## The constructor:
property returns a reference to the Object constructor function that created the instance object. Note that the 
value of this property is a reference to the function itself, 
not a string containing the function's name.

display:

function Tree(name) {
  this.name = name
}

let theTree = new Tree('Redwood')
console.log('theTree.constructor is ' + theTree.constructor)

* One can assign the constructor property for any value except null and undefined since those don't have a corresponding constructor 
function (like String, Number, Boolean etc.), but values which are primitives won't keep the change (with no exception thrown). 

let val = null;
val.constructor = 1; //TypeError: var is null

val = 'abc';
val.constructor = Number; //val.constructor === String
