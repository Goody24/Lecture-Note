## Conditionals 

In JavaScript, conditionals are statements that let your code make decisions — that is, they run different blocks of code depending on whether certain conditions are true or false.

1. **if Statement**

Runs a block of code if a condition is true.

```JavaScript
let age = 18;

if (age >= 18) {
  console.log("You are an adult.");
}
```

2. **if...else Statement**

Runs one block if the condition is true, and another if it’s false.

```JavaScript
let age = 16;

if (age >= 18) {
  console.log("You are an adult.");
} else {
  console.log("You are a minor.");
}
```

3. **if...else if...else Chain**
   Used to check multiple conditions in order.

```JavaScript
let score = 75;

if (score >= 90) {
  console.log("Excellent!");
} else if (score >= 70) {
  console.log("Good job!");
} else {
  console.log("Keep trying!");
}
```

4. **switch Statement**

Useful when comparing a value against many possible matches.

```Javascript
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
