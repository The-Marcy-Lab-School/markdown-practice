## Prompt:

Imagine you are teaching a brand new programmer a brief lesson about functions and function calls. Your lesson should have the following components:
* A technical definition ("According to MDN, a function is...").
* An explanation of the concept with an analogy ("You can think of a function a ...")
* An example of the syntax for an arrow function using a JavaScript code block (triple backticks)
* An explanation of the syntax using the terms arrow function, parameter, code block, return statement, and call/invoke.

Below, we've provided an outline for your response but feel free to modify it as you see fit.

## Response: 

### What is a function?

According to MDN, a **function** is a reusable block of code designed to perform a particular task. Functions are one of the fundamental building blocks in JavaScript.

### Understanding functions through an analogy

You can think of a function like a recipe in a cookbook. Just like a recipe has a name, lists the ingredients it needs, provides step-by-step instructions, and produces a finished dish, a function has a name, can accept inputs called **parameters**, contains instructions to execute, and can return a result. 

Writing down a recipe doesn't make the food appear - you have to actually follow the recipe to get the meal. Similarly, defining a function doesn't run the code inside it - you have to **"call"** or **"invoke"** the function to make it execute.

### An example of function syntax

```js
const greetUser = (name) => {
  const greeting = "Hello, " + name + "!";
  return greeting;
}
const message = greetUser("Ada");
console.log(message);
```

### Breaking down the syntax

In the example above, we created an **arrow function** called `greetUser`. Let's break it down:
* The function accepts one parameter called `name`, which acts as a placeholder for whatever value we pass in when we call the function.
* The code block is everything between the curly braces `{}` - this is where we write the instructions the function should follow. 
* Inside the code block, we create a `greeting` message and use a `return` statement to send that value back to wherever the function was called. 
* Finally, we call or invoke the function by writing its name followed by parentheses with an **argument** inside: `greetUser("Ada")`. This executes the code inside the function with `"Ada"` as the value for the `name` parameter.
