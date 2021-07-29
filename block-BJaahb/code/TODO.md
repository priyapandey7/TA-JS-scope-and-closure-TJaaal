Create the execution context diagram for the following code snippets:

```js
function outer() {
  let b = 10;
  function inner() {
    let a = 20;
    console.log(a + b);
  }
  return inner;
}
let getSum = outer();
let num = getSum();
```

<!-- ![](./img/image-name.png) -->

![](./img/img-1.jpg)

Create the execution context diagram for following code. Also write the output of the code below.

```js
function getCounter() {
  let count = 0;

  return () => {
    return count++;
  };
}

let counter = getCounter();

counter(); // output 0
counter(); // output 1
counter(); // output 2
counter(); // output 3
```

![](./img/img-2.jpg)

3. Create the execution context diagram

```js
function makeColorChanger(color) {
  return function () {
    document.body.style.backgroundColor = color;
  };
}

let blue = makeColorChanger("blue");
let tomato = makeColorChanger("tomato");

blue(); //blue
tomato(); //tomato



// What will be the background color after the execution of last line
tomato.

```

![](./img/img-3.jpg);
