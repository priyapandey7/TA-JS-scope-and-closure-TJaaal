Find the output of the code snippets below:

```js
console.log(numA + numB); //NaN
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //numA is not defined
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //51
// let ,in declaration phase it is not been initialize but execution it will give an output.
```

Find the output of the code snippets below:

```js
console.log(sayHello()); //hello
function sayHello() {
  console.log("Hey"); //undefind
}
function sayHello() {
  console.log("Hello"); //undefind
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); //Tyrion
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // Tryion
let username = "Tyrion";
function sayHello() {
  console.log(username); //undefnd
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); //sayHello is not define
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); //Error bacause we are calling a function before defining it.and function we are defineig it function declaration not a function expression.
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // error."same from upper one"
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // error we are calling a fumction before defining it.
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); //undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // John
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); //  Cannot access 'username' before initialization
```
