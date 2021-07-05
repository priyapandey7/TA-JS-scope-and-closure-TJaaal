Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

Example:

```js
function hello() {
  var username = "Arya";
}
console.log(username); // `Reference Error username is not defined
```

In above code we are looking for the variable named `usename`. There is no variable named `username` in the global scope. The variable is inside the function named `hello` and we can't access the variable defined inside a function from outside.

The above code will throw an error `Reference Error username is not defined`.

2. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
{
  const username = "Arya";
}
console.log(username); // `Reference Error username is not defined
```

In above code we are looking for the variable named `username`. amd user name are defined inside the block , usging the keyword const.const create scope where it is define inside the block.so we can't acess it because it is define using const inside the const.
The above code will throw an error `Reference Error username is not defined`.

3. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
if (true) {
  let username = "Arya";
}
console.log(username); // The above code will throw an error `Reference Error username is not defined`.
```

In above code we are looking for the variable named `username`. There is `username` in the global scope. The username is defined inside if its craete scope.if is a block we are using let to create varibale, `let` and we can't access the variable defined inside a if.
The above code will throw an error `Reference Error username is not defined`.

4. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

````js
if (true) {
  var username = "Arya";
}
console.log(username); // "arya"
In above code we are looking for the variable named `username`. There is `username` in the global scope. The username is defined inside if its craete scope.if is a block we are using var to create varibale, `var` and we can access the variable defined inside a if.

The above code will give the value arya`.

5. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  var username = "Arya";
}
console.log(username); // output

```

In above code we are looking for the  variable named `username`. and here we have two variable username.define using two different keywords,let and var. var user name are defined inside the block , and  usging the keyword let in global scope..let doesn;t create scope.
The above code will throw an error `'username' has already been declared`.

6. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
if (true) {
  let username = "Arya";
}
console.log(username); // John
```
In above code we are looking for the  varible named `username`. and here we have  difined two variable username.define using one keywords,let but in diffrent scope. 1st user name are defined inside the block , and let in global scope..let doesn;t create scope.
The above code will give the output John .

7. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
let username = "John";
function sayHello() {
  let username = "Arya";
}
sayHello();
console.log(username); // john.
```
In above code we are looking for the  varible named `username`. and we are calling function syaHello().so the value of username is john.

8. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (var i = 0; i < 10; i++) {
  console.log(i, "First"); // 0 "First"....... 8 "First"9 "First"
}
console.log(i, "Second"); // 10."second"
```
In above code we are writting a loop.and we are defining the variable name using loop inside the var.

9. Go through the code below and write down the process of making decision about looking for the variable. Also write the output of the code below.

```js
for (let i = 0; i < 10; i++) {
  console.log(i, "First"); // 0 "First"....... 8 "First"9 "First"
}
console.log(i, "Second"); // error.because i is not be acess from outside.
```

````
