1. What does thread of execution means in JavaScript?

```js
ans- thread of execution means in JavaScript ,javascript execute code ;ine by line abd give the output.

// const num = 3;
// function addOne(x) {
//   const result = x + 1;
//   return result;
// }
// const output = addOne(num);
// When our JavaScript is executed, the code is being stepped through line by line (single-threaded), so in our code above the first line is:

// const num = 3;
// then we move onto the next line:

// function addOne(x) {
// It’s important to note that we are declaring a function here and not executing one. Therefore, we store the function name with the value of the entire function.
```

```js
2. Where the JavaScript code gets executed?

   JavaScript can execute not only in the browser, but also on the server, or actually on any device that has a special program called the JavaScript engine. The browser has an embedded engine sometimes called a “JavaScript virtual machine”
```

3. What does context means in Global Execution Context?

```js
context is a enviromentin which you created once for each program.so global execution context canonly get created once for each program.Global execution context (GEC): This is the default execution context in which JS code start its execution when the file first loads in the browser. All of the global code i.e. code which is not inside any function or object is executed inside the global execution context.
```

4. When do you create a global execution context.

```js
The Global execution context is the 1st execution context thats get created by JavaScript engin whneever  its running our code .
```

5. Execution context consists of what all things?

```js
The two type of execution context .one get created only once throughout the program the another one is knowm as function execution context.
```

6. What are the different types of execution context?
   There are Two types of execution context in JavaScript.
   Global Execution Context — This is the default or base execution context. ...
   Functional Execution Context — Every time a function is invoked, a brand new execution context is created for that function.

7. When global and function execution context gets created?

The Global execution context is the 1st execution context thats get created by JavaScript engin whneever its running our code .
and function executing context get created whenever you are executing any function.

````
8. Function execution gets created during function execution or while declaring a function.
```js
Function execution gets created during function execution
```
9. Create a execution context diagram of the following code on your notebook. Take a screenshot/photo and store it in the folder named `img`. Use `![](./img/image-name.png)` to display it here.

```js
var user = "Arya";

function sayHello() {
  return `Hello ${user}`;
}

var userMsg = sayHello(user);
````

<!-- Put your image here -->

![](./img/image-name.jpg)

```js
var marks = 400;
var total = 500;

function getPercentage(amount, totalAmount) {
  return (amount * 100) / totalAmount;
}

var percentageMarks = getPercentage(marks, total);
var percentageProfit = getPercentage(400, 200);
```

<!-- Put your image here -->

![](./img/image-name.jpg)

```js
var age = 21;

function customeMessage(userAge) {
  if (userAge > 18) {
    return `You are an adult`;
  } else {
    return `You are a kid`;
  }
}

var whoAmI = customeMessage(age);
var whoAmIAgain = customeMessage(12);
```

<!-- Put your image here -->

![](./img/image-name.jpg)
