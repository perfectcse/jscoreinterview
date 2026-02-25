JavaScript Core – Interview Revision README
1️⃣ Variables (var, let, const)
✅ Definition
A variable is a container used to store data values.

🔹 var
Function scoped
Can be re-declared
Can be updated
Hoisted (initialized as undefined)

* Code
var name = "Vishal";
var name = "Rahul"; // allowed
name = "Amit"; // allowed

🔹 let
Block scoped
Cannot re-declare
Can update
Hoisted but in TDZ

🔹 const
Block scoped
Cannot re-declare
Cannot update
Must initialize at declaration

🔥 Interview Difference
| Feature    | var      | let       | const     |
| ---------- | -------- | --------- | --------- |
| Scope      | Function | Block     | Block     |
| Re-declare | ✅        | ❌         | ❌         |
| Update     | ✅        | ✅         | ❌         |
| Hoisting   | Yes      | Yes (TDZ) | Yes (TDZ) |

2️⃣ Data Types

🔹 Primitive (Immutable)

String

Number

Boolean

Undefined

Null

Symbol

BigInt

Non-Primitive (Reference Type)

🔥 null vs undefined
| undefined                          | null                    |
| ---------------------------------- | ----------------------- |
| Variable declared but not assigned | Intentional empty value |

3️⃣ Functions
A function is a reusable block of code.

🔹 Normal Function

function greet(name) {
  return "Hello " + name;
}

🔹 Arrow Function
const greet = (name) => {
  return "Hello " + name;
};

🔥 Difference
| Normal             | Arrow                 |
| ------------------ | --------------------- |
| Has its own this   | No own this           |
| Can be constructor | Cannot be constructor |

4️⃣ Arrays
let numbers = [1, 2, 3, 4];
🔹 map()

numbers.map(n => n * 2);

🔹 filter()
numbers.filter(n => n % 2 === 0);

reduce()
numbers.reduce((acc, curr) => acc + curr, 0);

🔥 map vs forEach
| map               | forEach           |
| ----------------- | ----------------- |
| Returns new array | Returns undefined |

5️⃣ Objects

let user = {
  name: "Vishal",
  age: 22
};

Access:
user.name
user["age"]
