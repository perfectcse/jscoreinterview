Call Stack is a data structure that keeps track of function execution.
It works on: 👉 LIFO (Last In First Out)
* Code
function one() {
  two();
}

function two() {
  three();
}

function three() {
  console.log("Done");
}

one();
..................................................................................................
🧠 4️⃣ Event Loop (Very Important 🔥)
JS Runtime includes:
Call Stack
Web APIs
Callback Queue
Microtask Queue
Event Loop
