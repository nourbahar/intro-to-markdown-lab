# Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.

## 1.  Basic syntax
```javascript
 const functionName = (params) => {
  // code to be executed
}
```
1. **const** : const should be used whenever a function expression is assigned to a variable.
The function name: The name you choose for the function.
2. **Parameters** : Optional comma separated parameters. This is the data passed into the function. If there are no parameters, the () is still required.
The arrow syntax: Indicates that this will be a function.
3. **The body** : The statements that make up the function itself. Surrounded by curly braces.Writing a Function in JavaScript
Writing a Function in JavaScript

In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.



## 2. Calling a function

To execute the function, you call or invoke it by using its name followed by parentheses.

***Example***

`greet('Alice');` // Outputs: Hello, Alice!

3. Return values

Functions can process data input and output a value using the return keyword.

***Example***
```javascript
 const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total)  // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs. 
[Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)
In JavaScript, functions are blocks of reusable code. They allow you to bundle functionality, make it more readable, and avoid repetition. Here's a brief tutorial on writing an arrow function in JavaScript.



## 3. Return values

Functions can process data input and output a value using the return keyword.

***Example***
```javascript
const addNums = (numA, numB) => {
  return numA + numB
}

const total = addNums(2, 4);

console.log(total) // Expected value: 6
```
For more information on functions and how they are used in JS, check out the MDN docs. 

[Functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Functions)

***Example***
```javascript
const greet = (name) => {
  console.log("Hello, " + name + "!");
}
```
>Tip: Functions often perform actions, so naming with a verb can make it clear what the function does. Examples include fetchData( ), calculateArea( ), or printReport( ). 





# PART TWO

## How to Create a File Using the Terminal

Creating a file using the Terminal is a basic skill that can be very useful, especially for tasks involving automation or remote server management. Here’s a step-by-step guide to create a file using common command-line interfaces like Bash (Unix-based) or PowerShell (Windows-based).

### For Unix-based Systems (Bash)

1. **Open your Terminal :**
    If you are using Linux, open your preferred terminal emulator (e.g., GNOME Terminal, Konsole, etc.).

2. **Navigate to the directory where you want to create the file:**
   ```bash
   cd path/to/directory

3. **Create a new file:**


```bash
touch filename.txt
```
4. **Verify that the file has been created:**


```bash
ls 
```

5. **Open your file:**

```bash

code .
```

> NOTE: For more informaions click the link below

[Files](files.com)

