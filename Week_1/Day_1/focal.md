`F`unctions `O`bjects `C`onditionals `A`rrays `L`oops

`ESLint` Refers to linting or cleaning up our code. Eslint can be run from the command line to check a codes style. 

`Command Line Arguments` Are arguments fed into a file from the command line, and are added after the function is called.

``` 
process.argv.slice()
```
Can be used to cut the CLA's into useable bits.

`Template Literals` Are a way of adding code into a string, the syntax is ${} within a string surrounded by backticks ``.

`Objects` Are a data type that is useful in JS. 
  * They contain key value pairs
  * They contain keys which are always strings
  * All keys must be unique

``` 
object.key //or object["key"]
```
Are both valid ways of accessing values in an object.

`For...In` Loops are a special loop in JS that iterats over all enumerable properties of an object. They should be used for objects.

```
for (each element in array) {
  element += 1;
}
//Adds one to each value in an object, or array.
```
`Primitives` Refer to the basic data types available in JS.
  1. Undefined is an undefined value
  2. null is a rarely used datatype
  3. boolean returns a truthy or falsy value
  4. string contains a collection of chars
  5. number contains a number
  6. symbole another rarely used type, contains a symbol.

  `Functions` Are first class objects in JavaScript which means they can be stored in variables and passed around. Functions are also objects. 

  `First Class` refers to an object that can be created, destroyed, passed into a function, or retrieved as a value.