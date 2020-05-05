## Function Defination-writeCode

1.  Define a function named `sayHello` when called `alert` saying "Hello JavaScript".

    - Call above function.
    - Store the return value in a variable named `one`
    - What is the `typeof` the value in `one`

    function sayHello() {
      alert("Hello JavaScript");
    }
    let one = sayHello();
    typeof one 
    // "undefined"


2.  Change function (from Part 1 above) to accept name from user using `prompt` and store it in a variable named `usename` and alert message saying `Hello username`.
//FEEDBACK: Typo username has been written as usename

    - Call above function.
    - Store the return value in a variable named `two`
    - What is the `typeof` the value in `two`

    let username = prompt("Enter your name")
    function sayHello(name) {
      alert(`Hello `+ name);
    }

    let two = sayHello(username);
    typeof two;
    //"undefined"

3.  Change the function (from Part 2 above) to accept `username` as a parameter not from prompt.
//FEEDBACK : Not able to understand the question

4.  Change (from Part 4 above) return the message `Hello username` instead of alerting it.

    - Call above function.
    - Store the return value in a variable named `four`
    - What is the `typeof` the value in `four`

    let username = prompt("Enter your name")
    function sayHello(name) {
      return `Hello `+ name;
    }

    let four = sayHello(username);
    typeof four;
    //"string"

## writeQuiz

```js
function hello() {
  console.log("Hello World!");
}
let message = hello();
alert(typeof message);
```

What will be the message in alert in above code.

- [ ] Hello World!
- [ ] null
- [x] undefined
- [ ] string


## writeQuiz

```js
function hello() {
  return "Hello World!";
}
let message = hello();
alert(typeof message);
```

What will be the message in alert in above code.

- [ ] Hello World!
- [ ] null
- [ ] undefined
- [x] string

## writeQuiz

```js
function hello() {
  return "Hello World!";
}
let message = hello();
alert(typeof typeof message);
```

What will be the message in alert in above code.

- [ ] Hello World!
- [ ] null
- [ ] undefined
- [x] string

## writeTextAnswer

Why you can store function as a value in a variable? Explain with example.
//In Javascript functions are an object. So as object can be stored in variables so are the functions. And this is called function expression.

## Different Function Types-writeCode

For the given problems write do the following:

1. Write a Function Declaration
2. Write a Function Expression
3.
4. Write a Arrow Function with curly brackets (if possible)
5. Function Execution
6. Store the value of function execution in a variable
7. Find the `typeof` of the the variable

```js
/**
 * Write a function named convertToString that accepts a number,
 converts the number into a string (hint: use String()) and return the converted value.
 */
// Do the following for the given problem:
//1. Write a Function Decleration
function convertToString(n) {
  return String(n);
}

//2. Write a Function Expression
let convertToString = function(n) {
  return String(n);
};

//3. Write an Arrow Function
let convertToString = n => String(n);

//4. Write an Arrow Function with curly brackets (if possible)
let convertToString = n => {
  return String(n);
};

//5. Execute the function
convertToString(21);

//6. Execute the function and store the return value in a variable.
let returnValue = convertToString(23);

//7. What is the typeof returnValue
// typeof returnValue is "string"
```

Do the same for the following problems:

### 1. Read the questions and do what is asked.

```js
/**
 Write a function named addOne that accepts a number,
 add one to the given value and return it(hint: use return keyword).
 */
//1. Write a Function Decleration
 function addOne(n) {
   return n + 1;
 }

//2. Write a Function Expression
 let addOne = function(n){
   return n + 1;
 }

//3. Write an Arrow Function
 let addOne = n => n + 1;

//4. Write an Arrow Function with curly brackets (if possible)
 let addOne = n => {
   return n + 1;
 }

//5. Execute the function
 addOne(21);

//6. Execute the function and store the return value in a variable.
let increment = addOne(21);

//7. What is the typeof returnValue
typeof increment // "number"
```

### 2. Read the questions and do what is asked.

```js
/**
 Write a function named substractOne that accepts a number,
 substract one from the given value and return it. (hint: use return keyword)
 */
//1. Write a Function Decleration
 function subtractOne(n) {
  return n - 1;
}

//2. Write a Function Expression
let subtractOne = function(n){
  return n - 1;
}

//3. Write an Arrow Function
let subtractOne = n => n - 1;

//4. Write an Arrow Function with curly brackets (if possible)
let subtractOne = n => {
  return n - 1;
}

//5. Execute the function
subtractOne(21);

//6. Execute the function and store the return value in a variable.
let decrement = subtractOne(21);

//7. What is the typeof returnValue
typeof decrement; // "number"
```

### 3. Read the questions and do what is asked.

```js
/**
 Write a function named sum that accepts two numbers,
 returns the sum of the passed value.
 */
//1. Write a Function Decleration
 function sum(num1, num2) {
  return num1 + num2;
}

//2. Write a Function Expression
let sum = function(num1, num2){
  return num1 + num2;
}

//3. Write an Arrow Function
let sum = (num1, num2) => num1 + num2;

//4. Write an Arrow Function with curly brackets (if possible)
let sum = (num1, num2) => {
  return num1 + num2;
}

//5. Execute the function
sum(21,23);

//6. Execute the function and store the return value in a variable.
let summation = sum(21, 23);

//7. What is the typeof returnValue
typeof summation; //"number"
```

### 4. Read the questions and do what is asked.

```js
/**
 Write a function named square that accepts a number,
 returns the number multiplied by itself.
 */
//1. Write a Function Decleration
function square(number) {
  return number * number;
}

//2. Write a Function Expression
let square = function(number) {
  return number * number;
}

//3. Write an Arrow Function
let square = (number) => number * number;

//4. Write an Arrow Function with curly brackets (if possible)
let square = (number) => {
  return number * number;
}

//5. Execute the function
square(22)

//6. Execute the function and store the return value in a variable.
let squareOfNum = square(22);

//7. What is the typeof returnValue
typeof squareOfNum;
//"number"
```

### 5. Read the questions and do what is asked.

```js
/**
 Write a function named isGreater that accepts two numbers x and y and returns true if x is greater than y or return false.
 */
//1. Write a Function Decleration
function isGreater(x, y) {
  return x > y 
}

//2. Write a Function Expression
let isGreater = function(x, y){
  return x > y;
}

//3. Write an Arrow Function
let isGreater = (x, y) => x > y;

//4. Write an Arrow Function with curly brackets (if possible)
let isGreater = (x, y) => {
  return x > y;
}

//5. Execute the function
isGreater(23, 21);

//6. Execute the function and store the return value in a variable.
let isLarge = isGreater(23,21) 

//7. What is the typeof returnValue
typeof isLarge
//"boolean"
```

### 6. Read the questions and do what is asked.

```js
/**
 Write a function named oddOrEven that accepts a number and returns "Number is odd" for odd number and "Number is even" for even number.
 */
//1. Write a Function Decleration
function oddOrEven(num) {
  if(num % 2 === 0) {
    return "Number is even";
  } else {
    return "Number is odd";
  }
}

//2. Write an anonymous Function Expression
let oddOrEven = function(num) {
  if(num % 2 === 0) {
    return "Number is even";
  } else {
    return "Number is odd";
  }
}

//3. Write an named Function Expression
let oddOrEven = function oddEven(num) {
  if(num % 2 === 0) {
    return "Number is even";
  } else {
    return "Number is odd";
  }
}

//4. Write an Arrow Function
let oddOrEven = (num) => num % 2 === 0 ? "Number is even" : "Number is odd"

//5. Write an Arrow Function with curly brackets (if possible)
let oddOrEven = (num) => {
  if(num % 2 === 0) {
    return "Number is even";
  } else {
    return "Number is odd";
  }
}

//6. Execute the function
oddOrEven(25);

//7. Execute the function and store the return value in a variable.
let isOddOrEven = oddOrEven(25);

//8. What is the typeof returnValue
typeof isOddOrEven
// "number"
```
