Execution Context is the environment in which JavaScript code is evaluated and executed.
Whenever JS runs:
It creates an execution context.
JS runs inside that context.

🔹 Types of Execution Context
Global Execution Context (GEC)
Function Execution Context (FEC)

🏗 How Execution Context Works (2 Phases)
1️⃣ Creation Phase
JS scans the code and:
Allocates memory for variables → undefined

Stores function definitions in memory
2️⃣ Execution Phase
Assigns actual values
Executes code line by line

* code
console.log(a);

var a = 10;

function test() {
  console.log("Hello");
}

test();
