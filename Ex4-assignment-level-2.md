## writeCode

### 1. Read the questions and do what is asked.

```js
/**
 Write a function named calculator that accepts three parameter
 - operation ('add', 'sub', 'mul','divide')
 - num1 (number)
 - num2 (number)
 and if operation is
    - 'add' returns num1 + num2.
    - 'sub' returns num1 - num2
    - 'mul' return num1 * num2
    - 'div' return num1 / num2
 */
//1. Write a Function Decleration
function calculator(operation, num1, num2) {
   if(operation === "add") return num1 + num2;
   if(operation === "sub") return num1 - num2;
   if(operation === "mul") return num1 * num2;
   if(operation === "div") return num1 / num2;
}

//2. Write an anonymous Function Expression
let calculator = function(operation, num1, num2) {
   if(operation === "add") return num1 + num2;
   if(operation === "sub") return num1 - num2;
   if(operation === "mul") return num1 * num2;
   if(operation === "div") return num1 / num2;
}

//3. Write an named Function Expression
let calculator = function calculate(operation, num1, num2) {
   if(operation === "add") return num1 + num2;
   if(operation === "sub") return num1 - num2;
   if(operation === "mul") return num1 * num2;
   if(operation === "div") return num1 / num2;
}

//4. Write an Arrow Function
let calculator = (operation, num1, num2) =>  {
   if(operation === "add") return num1 + num2;
   if(operation === "sub") return num1 - num2;
   if(operation === "mul") return num1 * num2;
   if(operation === "div") return num1 / num2;
}

//5. Write an Arrow Function with curly brackets (if possible)

//6. Execute the function
calculator("add", 43, 57);

//7. Execute the function and store the return value in a variable.
let storeVal = calculator("add", 43, 57);

//8. What is the typeof returnValue
typeof storeVal;
//"number"
```

### 2. Read the questions and do what is asked.

```js
/**
 Write a function named calculator that accepts three parameter
 - operation ('add', 'sub', 'mul','divide')
 - num1 (number)
 - num2 (number)
 and if operation is
    - 'add' returns num1 + num2.
    - 'sub' returns num1 - num2
    - 'mul' return num1 * num2
    - 'div' return num1 / num2
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
//FEEDBACK: Question got repeated.

### 3. Read the questions and do what is asked.

```js
/**
 Write a function named grade that accepts a number (marks below 500) calculates the percentage out of (500) and returns the grade as following
 * "A": 90-100%
 * "B": 80-89%
 * "C": 70-79%
 * "D": 60-69%
 * "F": 0-59%
 */
//1. Write a Function Decleration
function grade(marks){
   let percentage = (marks / 500) * 100;
   let finalGrade = "";
   if(percentage < 60) {
      finalGrade = "F";
   } else if (percentage < 70) {
      finalGrade = "D";
   } else if (percentage < 80) {
      finalGrade = "C";
   } else if (percentage < 90) {
      finalGrade = "B";
   } else {
      finalGrade = "A";
   }
   return finalGrade;
}

//2. Write an anonymous Function Expression
let grade = function(marks){
   let percentage = (marks / 500) * 100;
   let finalGrade = "";
   if(percentage < 60) {
      finalGrade = "F";
   } else if (percentage < 70) {
      finalGrade = "D";
   } else if (percentage < 80) {
      finalGrade = "C";
   } else if (percentage < 90) {
      finalGrade = "B";
   } else {
      finalGrade = "A";
   }
   return finalGrade;
}

//3. Write an named Function Expression
let grade = function gradeCalculate(marks){
   let percentage = (marks / 500) * 100;
   let finalGrade = "";
   if(percentage < 60) {
      finalGrade = "F";
   } else if (percentage < 70) {
      finalGrade = "D";
   } else if (percentage < 80) {
      finalGrade = "C";
   } else if (percentage < 90) {
      finalGrade = "B";
   } else {
      finalGrade = "A";
   }
   return finalGrade;
}

//4. Write an Arrow Function
let marks = 475;
let percentage = (marks / 500) * 100;
let grade = (percentage) => (percentage < 60 ? "F" : percentage < 70 ? "D" : percentage < 80 ? "C" : percentage < 90 ? "B" : "A")

//5. Execute the function
grade(marks);

//6. Execute the function and store the return value in a variable.
let gradeVal = grade(marks);

//7. What is the typeof returnValue
typeof gradeVal;
//"string"
```

### 4. Read the questions and do what is asked.

```js
/**
 Write a function named fullName that accepts two strings (firstName, lastName) and return the full name with an space between firstName and lastName
 */
//1. Write a Function Decleration
function fullName(firstName, lastName) {
   return firstName + " " + lastName;
}

//2. Write an anonymous Function Expression
let fullName = function(firstName, lastName) {
   return firstName + " " + lastName;
}

//3. Write an named Function Expression
let fullName = function getFullName(firstName, lastName) {
   return firstName + " " + lastName;
}

//4. Write an Arrow Function
let fullName = (firstName, lastName) => (firstName + " " + lastName);

//5. Execute the function
fullName("Raghuram","Bachu");

//6. Execute the function and store the return value in a variable.
let completeName = fullName("Raghuram","Bachu")

//7. What is the typeof returnValue
typeof completeName;
//"string"
```

### 5. Write a function `toCelsius` which converts temperature from Fahrenheit to Celsius:

```js
function toCelsius(temp) {
   let celsius = (temp - 32) * (5/9);
  return `${temp}\xB0F is ${celsius.toFixed(2)}\xB0C`
}

let celsius = toCelsius(97);
```
