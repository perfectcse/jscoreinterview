1️⃣ Scope
✅ Definition

Scope defines where a variable can be accessed in the code.

🔹 Types of Scope

1. Global Scope
Declared outside all functions
Accessible everywhere

let name = "Vishal";

function greet() {
  console.log(name);
}
2. Function Scope
Declared inside a function
Accessible only inside that function

function test() {
  let age = 25;
  console.log(age);
}
3. Block Scope
Declared using let or const inside { }
Accessible only inside that block

if (true) {
  let city = "Delhi";
}
📌 2️⃣ Hoisting
✅ Definition

Hoisting is JavaScript's behavior of moving variable and function declarations to the top of their scope before execution.

🔥 Hoisting Summary
| Type                 | Hoisted       | Initialized |
| -------------------- | ------------- | ----------- |
| var                  | Yes           | undefined   |
| let                  | Yes           | No (TDZ)    |
| const                | Yes           | No (TDZ)    |
| Function Declaration | Fully         |             |
| Function Expression  | Variable only |             |

📌 3️⃣ Callback
✅ Definition

A callback is a function passed as an argument to another function that executes later.
🔥 Why Needed?

JavaScript is single-threaded
Used for asynchronous operations

📌 4️⃣ Closures
✅ Definition

A closure is when a function remembers variables from its outer scope even after the outer function has finished execution.

🔥 Why Important?
Data privacy
Private variables
Used in React, event handlers, etc.

📌 5️⃣ Promise
A Promise is an object representing the eventual completion or failure of an async operation.

6️⃣ Async / Await
Async/Await is a modern way to handle promises in a cleaner and more readable way
.............................................................................
🎯 Important Interview One-Liners
✔ What is Scope?

Scope defines where variables are accessible.

✔ What is Hoisting?

Hoisting is moving declarations to the top during memory phase.

✔ What is Closure?

Closure allows a function to remember variables from its outer scope.

✔ What is Callback?

A function passed into another function as an argument.

✔ What is Promise?

An object representing future completion of async operation.

✔ Difference between Promise and Async/Await?

Async/Await is syntactic sugar over Promises.

✅ Phase 1: JavaScript Core (Completed)
You finished:
🔹Fundamentals
* Variables (var, let, const)
* Data Types
* Functions (normal + arrow)
* Arrays (map, filter, reduce)
* Objects

🔹Important Concepts
*Scope (global, function, block)
* Hoisting
* TDZ
* Closures
* Callback
* Promise
* Async/Await

✅ Phase 2: Advanced JavaScript (Currently Ongoing)

We have started and covered:
🔹 Execution Context
Creation phase
Execution phase
Global Execution Context
Function Execution Context

🔹 Call Stack
LIFO
How functions push & pop
🔹 Event Loop

Call Stack
Web APIs
Callback Queue
Microtask Queue
Why Promise runs before setTimeout

🔹 this Keyword
Global
Inside object
Arrow function behavior

🔹 Shallow vs Deep Copy
Spread operator
Nested object issue
JSON deep copy method