# Quiz #2

## Instructions

1. Fork this repo
2. Clone your fork
3. Fill in your answers by writing in the appropriate area, or placing an 'x' in
the square brackets (for multiple-choice questions).
4. Add/Commit/Push your changes to Github.
5. Open a pull request.

## JavaScript

### Question #1

**What of the following are JavaScript Data Types?**

Select all that apply:
```
[x] Strings
[x] Booleans
[x] Undefined
[] NaN
[] Integers
[] Arrays
[x] Null
```

## Question #2

Explain what is a REPL, and why is it important for us as developers and help with debugging?

```
A REPL is a method for developers to Read, Evaluate, Print and Loop a piece of code. It's an important process for developers to test a piece of code in an interactive programming environment by only inputing single expressions.
```
### Question #3

**Given the Following Array**

var foods = [ ["apple","banana","strawberry"], ["pizza","fries","hamburger"] ];

Create a For Loop that outputs the following string for each piece of fruit in the console. "I want to eat a [fruit]"

```
var foods = [ ["apple","banana","strawberry"], ["pizza","fries","hamburger"] ];
for (foods = "apple", "bananas", "strawberry";{
  console:log("I want to eat a fruit")};)
```
### Question #4

**Given the Following Array**

var foods = [ ["apple","banana","strawberry"], ["pizza","fries","hamburger"] ];

How would I go about accessing the string "pizza" in the above array?

```
var meal = foods[3];
```

## Scope/Context/Closures

### Question #5

Describe the rules of scope in JavaScript.

Your Answer:
```
Rule #1: a variable created without the var keyword anywhere in the program, is placed in the global scope.
Rule #2: a variable created with the var keyword is created in the local scope.
Rule #3: functions create a new local scope.
Rule #4: the current scope can access all outer scopes, but not the other way around.
```

### Question #6

Define an object and store it in a variable `pizza`. The object should have 2
properties: a temperature (set to 70), and a method called `bake`. When called,
this method should set the pizza's temperature to be 300. Note: you may not use
the variable pizza inside your method.

Your Answer:
```
var pizza = {
  temp: "70",
  bake: function(newTemp){
    console.log("temp has been set to 300");
    pizza.temp = "300";
  }
}
```

### Question #7

Define a global variable instructor and set it equal to your Squad Instructor's Name. Then, define the same as a local variable instead.

Your Answer:
```
var instructor = NickOlds; //global variable

function() {
  var instructor = "NickOlds";
} // local variable


```

## Objects and Functions

### Question #8

What are the differences between calling and referencing a function? Please provide examples of each.

```
You call a function that you want executed now by writing it as someVariable = someFunction (). You reference a function that you want to run upon some other action preceding it by writing it as someVariable = someFunction. This would imply that someVariable is an alias for someFunction. If we call someVariable(), we would get the same result as someFunction().
```
### Question #9

Using the object literal notation, Define an object called student and give it the properties (your attributes) of name, age, and a method sayHello, that outputs "Hi, my name is [your_name]".

Your Answer:
```
var student = {
  name: "Robel",
  age: "37"
}
console.log("Hi, my name is " + student.name);
```

## Callbacks

### Question #10

**What is the difference between synchronous and asynchronous program execution?**

Select all that apply:
```
[] Synchronous code runs at an even pace, asynchronous code runs with uneven pacing.
[] Synchronous code runs all at the same time, asynchronous code runs completely randomly
[x] Synchronous code runs in order (as appears in the source), asynchronous code may run at a later time.
```
