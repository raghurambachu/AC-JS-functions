## Function Defination-writeCode

1.  Define a function named `sayHello` when called `alert` saying "Hello JavaScript".

    - Call above function.
    - Store the return value in a variable named `one`
    - What is the `typeof` the value in `one`

2.  Change function (from Part 1 above) to accept name from user using `prompt` and store it in a variable named `usename` and alert message saying `Hello username`.

    - Call above function.
    - Store the return value in a variable named `two`
    - What is the `typeof` the value in `two`

3.  Change the function (from Part 2 above) to accept `username` as a parameter not from prompt.

4.  Change (from Part 4 above) return the message `Hello username` instead of alerting it.

    - Call above function.
    - Store the return value in a variable named `four`
    - What is the `typeof` the value in `four`

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
- [x] undefined
- [ ] string

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
- [x] undefined
- [ ] string

## writeTextAnswer

Why you can store function as a value in a variable? Explain with example.

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

//2. Write a Function Expression

//3. Write an Arrow Function

//4. Write an Arrow Function with curly brackets (if possible)

//5. Execute the function

//6. Execute the function and store the return value in a variable.

//7. What is the typeof returnValue
```

### 2. Read the questions and do what is asked.

```js
/**
 Write a function named substractOne that accepts a number,
 substract one from the given value and return it. (hint: use return keyword)
 */
//1. Write a Function Decleration

//2. Write a Function Expression

//3. Write an Arrow Function

//4. Write an Arrow Function with curly brackets (if possible)

//5. Execute the function

//6. Execute the function and store the return value in a variable.

//7. What is the typeof returnValue
```

### 3. Read the questions and do what is asked.

```js
/**
 Write a function named sum that accepts two numbers,
 returns the sum of the passed value.
 */
//1. Write a Function Decleration

//2. Write a Function Expression

//3. Write an Arrow Function

//4. Write an Arrow Function with curly brackets (if possible)

//5. Execute the function

//6. Execute the function and store the return value in a variable.

//7. What is the typeof returnValue
```

### 4. Read the questions and do what is asked.

```js
/**
 Write a function named square that accepts a number,
 returns the number multiplied by itself.
 */
//1. Write a Function Decleration

//2. Write a Function Expression

//3. Write an Arrow Function

//4. Write an Arrow Function with curly brackets (if possible)

//5. Execute the function

//6. Execute the function and store the return value in a variable.

//7. What is the typeof returnValue
```

### 5. Read the questions and do what is asked.

```js
/**
 Write a function named isGreater that accepts two numbers x and y and returns true if x is greater than y or return false.
 */
//1. Write a Function Decleration

//2. Write a Function Expression

//3. Write an Arrow Function

//4. Write an Arrow Function with curly brackets (if possible)

//5. Execute the function

//6. Execute the function and store the return value in a variable.

//7. What is the typeof returnValue
```

### 6. Read the questions and do what is asked.

```js
/**
 Write a function named oddOrEven that accepts a number and returns "Number is odd" for odd number and "Number is even" for even number.
 */
//1. Write a Function Decleration

//2. Write an anonymous Function Expression

//3. Write an named Function Expression

//4. Write an Arrow Function

//5. Write an Arrow Function with curly brackets (if possible)

//6. Execute the function

//7. Execute the function and store the return value in a variable.

//8. What is the typeof returnValue
```
