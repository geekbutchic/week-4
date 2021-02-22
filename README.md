# What I Learned in Week 4
## Functions 
* A JavaScript function is a block of code designed to perform a particular task. A JavaScript function is executed when "something" invokes it `(calls it)`.
* This week we started with functions building off of creating variables.
* We learned to create functions and invoke them when necessary.  
* Our test functions would pass us in a parameter, depending and what the functions called for we are able to change the parameter and return it.
```javascript 
addToX = (userInput) => {
    x = x + 5;
}
```
* For example this functions is adding 5 to whatever is being passed into the parameter.
## Functions with Parameters 
* A function can take parameters which are just values you supply to the function so that the function can do something utilizing those values.
```javascript 
addToX = (someNumber) => {
    // like saying:
    // let someNumber = whateverTheUserPassedIn
    x = x * someNumber;
}
// These are the parameters being passed into the function
addToX(3);
x;
addToX(5);
x;
```
* These parameters are just like variables except that the values of these variables are defined when we call the function and are not assigned values within the function itself.

## Functions with Return Values
* These parameters are just like variables except that the values of these variables are defined when we call the function and are not assigned values within the function itself.
```javascript 
function add (x, y) {
    return x + y;
}

const num1 = 5;
const num2 = 10;
const sum = add(num1, num2);
sum; //? 15
```
* You use the return statement to send a value back to the calling script or user-defined function.

## Functions Methods 
* In JavaScript, an object is a standalone entity, with properties and type. Compare it with a cup, for example. A cup is an object, with properties. A cup has a color, a design, weight, a material it is made of, etc. The same way, JavaScript objects can have properties, which define their characteristics.
* Below are two examples.
```javascript 
// Converts number to string 
const number = 3;
const str = (3).toString();

// Fixes numbers to designated length
const num = (301.542654).toFixed(2);
num;
```
* These methods helped us return even more complex functions.
## Booleans 
* Booleans are true/false value 
* Booleans are operators and called a comparison operator.
* Booleans are binary operators but returns true or false.
```javascript 
// Logical Operator
// Logical AND - Term for this
// Only if both things are true

const hasMoney = true;
const isHungry = true;
const shouldIGoOutToEat = hasMoney && isHungry;
shouldIGoOutToEat; //? True 

// Either one apply 
// Needs one of them to be true vs && needs both to be true
const isLucky = true;
const isGood = true;
const canIWinToday = isLucky || isGood;
canIWinToday; //? True 
```
* A JavaScript Boolean represents one of two values: true or false.
* It was a busy week and a lot was covered.

![Alt Text](https://devhumor.com/content/uploads/images/August2017/js-strongtyped.png)