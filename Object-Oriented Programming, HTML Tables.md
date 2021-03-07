## basic Table structur:
1. The <table> element is used to create a table. The contents of the table are written out row by row.
2. You indicate the start of each row using the opening <tr> tag. (The tr stands for table row.)
3. Each cell of a table is represented using a <td>element. (The td stands for table data.)
4. The <th> element is used just like the  <td> element but its purpose is to represent the heading for either a column or a row. (The th stands for table heading.)
5. thead:The headings of the table should sit inside the <thead> element. 
6. tbody :The body should sit inside the <tbody> element. 
7. tfoot:The footer belongs inside the <tfoot> element.

## Object.prototype.constructor:
he constructor property returns a reference to the Object constructor function that created the instance object. Note that the value of this property is a reference to the function itself, not a string containing the function's name.

All objects (with the exception of objects created with Object.create(null)) will have a constructor property. Objects created without the explicit use of a constructor function (such as object- and array-literals) will have a constructor property that points to the Fundamental Object constructor type for that object.

## changing the constructor of an object:

One can assign the constructor property for any value except null and undefined since those don't have a corresponding constructor function (like String, Number, Boolean etc.), but values which are primitives won't keep the change (with no exception thrown). This is due to the same mechanism, which allows one to set any property on primitive values (except null and undefined) with no effect. namely wherenever one uses such a primitive as an object an instance of the corresponding constructor is created and discarded right after the statement was executed.

## Domain Modeling:
Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

# This is object-oriented programming in JavaScript at its most fundamental level.

* The new keyword instantiates (i.e. creates) an object.
* The constructor function initializes properties inside that object using the this variable.
* The object is stored in a variable for later use.
