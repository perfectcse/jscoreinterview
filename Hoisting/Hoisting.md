Hoisting is JavaScript's default behavior of moving variable and function declarations to the top of their scope before code execution.console.log(a);

1️⃣ Hoisting with var
console.log(a);
var a = 10;

Output
undefined

Why?
JS internally converts it to:

var a;        // hoisted
console.log(a);
a = 10;
👉 var is hoisted and initialized with undefined.

2️⃣ Hoisting with let and const
Example:


console.log(b);
let b = 20;

Why?
let and const are hoisted BUT NOT initialized.

🔥 Temporal Dead Zone (TDZ)
📌 Definition:
TDZ is the time between variable hoisting and initialization where the variable cannot be accessed.

// Memory phase
let b;  // hoisted but uninitialized

// Execution phase
console.log(b); // ❌ Cannot access before initialization
b = 20;

3️⃣ Hoisting with Functions (Very Important)
✅ Function Declaration (Fully Hoisted)

JavaScript

greet();

function greet() {
    console.log("Hello Vishal");
}