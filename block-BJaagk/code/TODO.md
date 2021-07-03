1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here

let totalMarks = function (marks, total) =>{
return (marks \* 100) / total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};
```

let percentage = function (marks, total) {
return (marks \* 100) / total;
};

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};
```

let percentage = (marks, total) => {
return (marks \* 100) / total;
};

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};
```

let percentage = function percentage(marks, total) {
return (marks \* 100) / total;
};

```js
let percentage = (marks, total) => (marks * 100) / total;
```

let percentage = (marks, total) => {
return (marks \* 100) / total;
};

````
 3. Why is a function definition an expression in JavaScript? Give one example of function expression.
```
 we are storing the function defination of a function inside variable like an expresstion so that's
why its is knowa as function expression.
<!-- example -->
let percentage = function percentage(marks, total) {
return (marks \* 100) / total;
};
```
4. Why is a function call an expression in JavaScript?
A function call is an expression containing the function name followed by the function call operator, () . If the function has been defined to receive parameters, the values that are to be sent into the function are listed inside the parentheses of the function call operator.
```

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer => 5
five = add; // Answer//false
five = five(10, 11); // Answer
five = function () {
  return "Hello";
}; // Answer
````

6. What is the difference between function definition and function call? Explain with an example.

So the difference between the function and function call is,

A function is procedure to achieve a particular result while function call is using this function to achive that task.

````

7. What is the similarities between function definition and function call?

Points:
1
A function is a block of code that does a particular operation and returns a result. It usually accepts inputs as parameters and returns a result. The parameters are not mandatory.

E.g:
Function add(a,b)
return a+ b

A function call is the code used to pass control to a function.

E.g.:

b = add(5,6)

Now b will have the value 11.
```
8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log("Hello World!");
}
// valid
`
hello.user = "Sam"; // valid or invalid//invalid
````

9. What is higher order function explain with an example.
   Higher-order functions are functions that take other functions as arguments or return functions as their results. ... For example, the map function on arrays is a higher order function. The map function takes a function as an argument.

```
10. Explain what is callback function. Why you can pass a function inside a function?
A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.
```
