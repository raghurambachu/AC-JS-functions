# Store of action(Function)

## What is function?-readText

- Function is a store of steps you take to perform any specific task.
- You can execute a function by adding `()` in-front of function name.
- It can "take in" data, process it and return a result.
- Function can only 'take in' a **value** and return a **value**.
- Once you define a function you can call it multiple times.
- Values can be passed into functions and used within the function.
- Functions always return a value. In JavaScript, if there is no return statement it will return `undefined`
- **Functions are objects.**

For example you want a function to take two input from user and convert the value in number and sum them. So the steps to do this would be

1. Take a number using `prompt` from user and store them in variable named `numA`
2. Take another number and store them in variable called `numB`
3. Prompt the sum of the `numA + numB`

In code it will be:

```js
let numA = Number(prompt("Enter first number."));
let numB = Number(prompt("Enter second number."));
let sum = numA + numB;
alert(sum);
```

Using function we can wrap the steps so we can call it multiple times. To define a `function` we use `function` keyword like:

```js
function nameOfTheFunction(parameters) {
  // function body
  // steps
}
```

In the body we can add all the steps like.

```js
function add() {
  let numA = Number(prompt("Enter first number."));
  let numB = Number(prompt("Enter second number."));
  let sum = numA + numB;
  alert(sum);
}
```

To call the function we use `()` after the function name. It's also called function invocation or function call. Once you invoke the function all the steps will be executed.

```js
add();
```

### Function-writeCode

Define a function that does the following:

- Let user enter a name using `prompt`
- Using alert display `Hello Name`
- Now convert the name to `uppercase` letter using `.toUpperCase()` function like `"hello".toUpperCase()`
- If the name of user is `Sam` instead of `Hello Sam` say `Welcome Sam`.

### `return` statement

Every function in

### Function Expression

You can store `value` in a variable and function in JS are objects and object is value. So you can also store a function in a variable. This kind of function where you store them like an expression in a variable is called _function expression._

Example:

```js
var add = function sum() {
  return 21;
};
```

In above example you are storing a function with name `sum` in a variable called `add` so you will be accessing it through the variable name `add` so function name can be anonymous.

```js
var add = function() {
  // function with no name (anonymous function)
  return 21;
};
```

There are multiple forms of function expression

### Arrow Function Expression

```js
var add = () => {
  return 21; // explicit return
};
```

Arrow function is always a anonymous function.

    var add = () => 21; // implicit return

### Function execution

```

```

```

```
