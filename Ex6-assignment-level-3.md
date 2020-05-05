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
function calculator(operation, num1, num2) {
  if((operation === "sub" || operation === "div") && (num1 < num2)) {
    alert("First number should not be smaller than second number.")
  } else {
    let result;
    let sign;
    if(operation === "add") {
      sign = "+"
      result = num1 + num2;
    } else if(operation === "sub") {
      sign = "-"
      result = num1 - num2;
    } else if(operation === "mul") {
      sign = "*"
      result = num1 * num2;
    } else if(operation === "div") {
      sign = "/"
      result = num1 / num2;
    }
    alert(`${operation} => ${num1} ${sign} ${num2} = ${result}`)
  }
}

//2. Write an anonymous Function Expression
let calculator = function(operation, num1, num2) {
  if((operation === "sub" || operation === "div") && (num1 < num2)) {
    alert("First number should not be smaller than second number.")
  } else {
    let result;
    let sign;
    if(operation === "add") {
      sign = "+"
      result = num1 + num2;
    } else if(operation === "sub") {
      sign = "-"
      result = num1 - num2;
    } else if(operation === "mul") {
      sign = "*"
      result = num1 * num2;
    } else if(operation === "div") {
      sign = "/"
      result = num1 / num2;
    }
    alert(`${operation} => ${num1} ${sign} ${num2} = ${result}`)
  }
}

//3. Write an named Function Expression
let calculator = function calculatorSimulator(operation, num1, num2) {
  if((operation === "sub" || operation === "div") && (num1 < num2)) {
    alert("First number should not be smaller than second number.")
  } else {
    let result;
    let sign;
    if(operation === "add") {
      sign = "+"
      result = num1 + num2;
    } else if(operation === "sub") {
      sign = "-"
      result = num1 - num2;
    } else if(operation === "mul") {
      sign = "*"
      result = num1 * num2;
    } else if(operation === "div") {
      sign = "/"
      result = num1 / num2;
    }
    alert(`${operation} => ${num1} ${sign} ${num2} = ${result}`)
  }
}


//4. Write an Arrow Function

//5. Write an Arrow Function with curly brackets (if possible)
//FEEDBACK : I think it should be arrow functions without curly braces

let calculator = (operation, num1, num2) => {
  if((operation === "sub" || operation === "div") && (num1 < num2)) {
    alert("First number should not be smaller than second number.")
  } else {
    let result;
    let sign;
    if(operation === "add") {
      sign = "+"
      result = num1 + num2;
    } else if(operation === "sub") {
      sign = "-"
      result = num1 - num2;
    } else if(operation === "mul") {
      sign = "*"
      result = num1 * num2;
    } else if(operation === "div") {
      sign = "/"
      result = num1 / num2;
    }
    alert(`${operation} => ${num1} ${sign} ${num2} = ${result}`)
  }
}

//6. Execute the function
calculator("mul", 75, 25);

//7. Execute the function and store the return value in a variable.
let calculatedVal = calculator("mul", 75, 25);

//8. What is the typeof returnValue
typeof calculatedVal;
//"string"
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
//The code above is invalid, there is variable being declared and assigned
//Doubt

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

//FEEDBACK : there will be an ERROR  as parameters are seperated by ";" and not ",".

## writeQuiz

```js
function add(a = 0, b = 0) {
  return a + b;
}
add(undefined, 21);
```

What will be the output of the above code?

- [ ] 21
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

//Output will be an error
//The code is invalid;
// As return statement is bound to return value or an expression but there is an unexpected token if;


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

//It will throw an error as if which comes under statement is treated as expression and assigned to variable ifElse, thus leading to error unexpected token "if"; A variable can only take either value or expression that evaluates out to a value.
// So above code is invalid