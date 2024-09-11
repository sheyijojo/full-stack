## Getting Started with JavaScript, v2

run.js

Kyle Simpson 

https://github.com/getify/you-dont-know-js
```js
typrof 42

typeof "kyle"

typeof {age:39}  - object


typeof [1,2,3]  - object

## operations with variables

var age = 39;

## add 1 to the value of age and also reassign the value to age 

## 40
age++;
age = age + 1

## 42
age += 2;
```

## expressions and statements 

```js
## statement, and the assignment makes it an expression

var age = 39;

## complex expression
age = 1 + (age * 2);
- 2 , age is an expressions, age * 2, 1 , 1+ , age =  is an expression

```

## Decisons 

```yaml
## if & else
var age = 39;

if  (age >= 18) {
     goVote();
}
```

## while loop 
```js
var stundents = ["Matt", "Sarah", "Susan" ];

while (students.length > 0) {

   let student  = students.pop();
   console.log(`Hello, ${student}!`);
}

```

## Functions

```js

## function no return
function greetStudent(student) {
    console.log(`Hello, ${student.name} !`);
}


## function with return
function timeRemaining(timeElaspsed, timeRemaining){
   return endtime - timeElaspsed;
}

var left = timeRemaining(43, 23);

left;

```

## Three Pillas of JS

- Primitiive types
- converting types
- checking Equalities


I JS, everything is an object - This is 100% false.

**primitive types**
- undefined is an empty type
- string
- number
- boolean
- symbol
- null is special type


**Object type**
- function is a subtype of the object type
- Arrays are subtype of the object type

## new with fundamental objects
**Use new:
- Object()
- Array()
- Function()
- Date()
- RegExp()
- Error()
  
**Don't Use New:
- String()
- Number()
- Boolean()

```js
//using new in front of one of the constructor forms of a fundamental object
var yesterday = new Date("March 6, 2019");
yesterday.toUTCString();

var myGPA = String(transcipt.gpa);
```

## Coercion: 
The way to convert from one type to another: coercion 
E.g: 
- string concatenation

```js
var msg1 = "There are ";
var numStudents = 16;
var msg2 = " students.";
console.log(msg1 + numStudents + msg2);

// "There are 16 students."
```

falsy and truthy values
