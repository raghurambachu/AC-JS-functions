## writeCode

### Read the questions and do what is asked.

```js
/**
 Write a function named calculator that accepts three parameter
 - operation ('add', 'sub', 'mul','divide')
 - num1 (number)
 - num2 (number)
 and if operation is
    - 'add' returns num1 + num2.
    - 'sub' returns num1 - num2 (if num1 is smaller than num2 alert "First number should not be smaller than second number.)
    - 'mul' return num1 * num2
    - 'div' return num1 / num2 (if num1 is smaller than num2 alert "First number should not be smaller than second number.)

  also print the operation in alert after operation like if 'add' => 5 + 66 = 71 etc
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

## writeTextAnswer

```js
function add(var a = 0,var b = 0){
  return a + b;
}
add(21, 23);
```

- Is the code above valid or not?
- Explain the reason.

## writeQuiz

```js
function add(a = 0; b) {
  return a + b;
}
add(21);
```

What will be the output of the above code?

- [x] 21
- [x] 0
- [x] 210
- [x] NaN

## writeQuiz

```js
function add(a = 0, b = 0) {
  return a + b;
}
add(undefined, 21);
```

What will be the output of the above code?

- [x] 21
- [x] 0
- [x] 210
- [x] NaN

## writeTextAnswer

```js
function knowWhy(value) {
  return if(value === 21){
    return "Yes"
  } else {
    return "No"
  }
}
knowWhy(211);
```

- Output of the above code
- Is the code above valid or not?
- Explain the reason.

## writeTextAnswer

```js
function isItIf(ifElse) {
  return ifElse;
}
isItIf(if(true){console.log('Testing')});
```

- Output of the above code
- Is the code above valid or not?
- Explain the reason.
