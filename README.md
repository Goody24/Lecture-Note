
# 🧠 Introduction to JavaScript

## What is JavaScript?
JavaScript was initially created to make web pages "alive".  
The programs written in JavaScript are called *scripts*. They can be written directly inside an HTML file and automatically run when the page loads.

### Ways to Run JavaScript
1. **Browser Console**  
   - Open your browser  
   - Right-click and select *Inspect* 
   - Go to the *Console* tab

2. **Node.js (Backend)**  
   - Open your terminal  
   - Navigate to your file’s directory  
   - Run using:  
     ```bash
     node filename.js
     ```

3. **Script in HTML**
   ```html
   <script src="jsfilename.js"></script>
   ```

---

## Why JavaScript is Unique
- Full integration with HTML and CSS  
- Simple syntax and flexibility  
- Supported by all major browsers by default  

JavaScript is the only browser language that combines these three advantages, making it one of the most widely used languages in the world.

---

## Code Structure
Statements are commands that perform actions.

Example:
```javascript
console.log('Hello, world!');
```

You can write multiple statements:
```javascript
console.log('Hello');
console.log('World');
```

### Automatic Semicolon Insertion
JavaScript can interpret line breaks as semicolons automatically.

```javascript
console.log('Hello')
console.log('World')
```

---

## Comments
Comments explain what your code does and are ignored during execution.

**Single-line comment:**
```javascript
// This is a comment
console.log('Hello');
```

**Multi-line comment:**
```javascript
/* This is a 
multi-line comment */
console.log('World');
```

---

## Variables
A variable is a named storage for data.

Use `var`, `let`, or `const` to declare variables:

```javascript
let user = 'John';
let age = 25;
const country = 'Nigeria';
```

**Rules for naming variables:**
- Can contain letters, digits, `$`, and `_`
- Cannot start with a digit
- Use `camelCase` for multi-word names (e.g., `userName`)

---

## Constants
Use `const` to declare variables that should not change.

```javascript
const myBirthday = '28.08.1993';
```

Trying to reassign a constant causes an error.

---

## Data Types
JavaScript has 8 basic data types:

- Number  
- String  
- Boolean  
- Null  
- Undefined  
- Object  
- Symbol  
- BigInt

Examples:
```javascript
let age = 30;             // Number
let name = "Goodluck";    // String
let isStudent = true;     // Boolean
let car = null;           // Null
let x;                    // Undefined
```

Use `typeof` to check data types:
```javascript
typeof age; // "number"
typeof name; // "string"
```

---

# ⚙️ Conditionals in JavaScript

## Overview
Conditionals allow your code to make decisions — running different blocks depending on whether a condition is true or false.

---

## 🔹 1. `if` Statement
```javascript
let age = 18;

if (age >= 18) {
  console.log("You are an adult.");
}
```

---

## 🔹 2. `if...else` Statement
```javascript
let age = 16;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}
```

---

## 🔹 3. `if...else if...else` Chain
```javascript
let score = 75;

if (score >= 90) {
  console.log("Excellent!");
} else if (score >= 70) {
  console.log("Good job!");
} else {
  console.log("Keep trying!");
}
```

---

## 🔹 4. `switch` Statement
```javascript
let day = "Tuesday";

switch (day) {
  case "Monday":
    console.log("Start of the week.");
    break;
  case "Tuesday":
    console.log("Second day of the week.");
    break;
  case "Friday":
    console.log("Weekend is near!");
    break;
  default:
    console.log("Just another day.");
}
```

---

## 💡 Key Takeaways
- Use `if` for simple conditions  
- Use `if...else if...else` for multiple conditions  
- Use `switch` for fixed value comparisons  
- Always use `break` inside `switch` to prevent fall-through

---

## 📘 Related Topics
- [Variables in JavaScript](#variables)
- [Data Types](#data-types)
- [Operators](#)
- [Loops](#)

---

### ✍️ Author
**ONYENSO GOODLUCK C.**  
Part of the *Introduction to JavaScript* learning series.
