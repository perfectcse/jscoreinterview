📘 JavaScript Complete Progress Notes (Updated)
1️⃣ Variables (var, let, const)
* var
* Function scoped
* Can re-declare
* Can update
* Hoisted (initialized as undefined)

let
Block scoped
Cannot re-declare
Can update
Hoisted but in TDZ

const
Block scoped
Cannot re-declare
Cannot update
Must initialize at declaration


2️⃣ Data Types
Primitive (Immutable)
String
Number
Boolean
Null
Undefined
Symbol
BigInt

Non-Primitive (Reference)
Object
Array
Function
null vs undefined
undefined → declared but not assigned
null → intentional empty value

3️⃣ Functions
Types
Function Declaration
Function Expression
Arrow Function
Key Differences
Arrow function has no own this
Arrow cannot be constructor

4️⃣ Arrays (Important Methods)
map() → returns new array
filter() → filtered array
reduce() → single value
find()
forEach()
some()
every()

5️⃣ Objects
Dot notation
Bracket notation
Destructuring
Spread operator

6️⃣ Scope
Types:
Global Scope
Function Scope
Block Scope

7️⃣ Hoisting
JavaScript moves declarations to the top before execution.
var → undefined
let/const → TDZ

8️⃣ TDZ (Temporal Dead Zone)
The time between entering scope and variable declaration.

9️⃣ Closures
A closure remembers variables from its outer scope even after execution.
Used for:
Data privacy
Counters

Encapsulation
🔟 Callback
A function passed as argument to another function.
Problem:
Callback Hell (nested callbacks)

1️⃣1️⃣ Promise
States:
Pending
Fulfilled
Rejected
Methods:
then()
catch()
finally()

1️⃣2️⃣ Async / Await
Cleaner syntax for handling promises.
Uses:
async keyword
await keyword
try/catch for error handling

✅ PHASE 2 – Advanced JavaScript (Runtime & Internals)

1️⃣ Execution Context
JS creates execution context when running code.

Two Phases:
Creation Phase
Memory allocation
Variables → undefined
Functions → stored completely

* Execution Phase
Assign values
Execute line by line

Types:
* Global Execution Context
* Function Execution Context

2️⃣ Call Stack
Data structure (LIFO)
Tracks function calls
One stack → JS is single-threaded

3️⃣ Event Loop
JS Runtime includes:
Call Stack
Web APIs
Callback Queue
Microtask Queue
Event Loop
Important Rule:
Microtasks (Promise) run before Callback Queue (setTimeout).

4️⃣ this Keyword
Global
Browser → window
Node → global

Inside Object
Refers to object

Arrow Function
Does NOT have its own this
Inherits from parent

5️⃣ call(), apply(), bind()
call()
Executes immediately
Arguments separated

apply()
Executes immediately
Arguments in array

bind()
Returns new function
Does not execute immediately

