var is like let but "var" the original way of declaring variables in JS so you will see "var" at some point dont be confuse.

if (condition1) {
// block of code to be executed if condition1 is true
} else if (condition2) {
// block of code to be executed if the condition1 is false and condition2 is true
} else {
// block of code to be executed if the condition1 is false and condition2 is false
}

precedence of logical operators is what will be run first

parameters == variable
arguments == value

A parameter is the variable listed inside the parentheses in the function declaration (it’s a declaration time term).
An argument is the value that is passed to the function when it is called (it’s a call time term).

this is how functions work:

function (){ //declare function
do something
return something
}

call function

function names:

showMessage(..) // shows a message
getAge(..) // returns the age (gets it somehow)
calcSum(..) // calculates a sum and returns the result
createForm(..) // creates a form (and usually returns it)
checkPermission(..) // checks a permission, returns true/false

function expressions

// Function Declaration
function sum(a, b) {
return a + b;
}

// Function Expression
let sum = function(a, b) {
return a + b;
};

In most cases when we need to declare a function, a Function Declaration is preferable, because it is visible prior to the declaration itself. That gives us more flexibility in code organization, and is usually more readable.

So we should use a Function Expression only when a Function Declaration is not fit for the task. We’ve seen a couple of examples of that in this chapter, and will see more in the future.
