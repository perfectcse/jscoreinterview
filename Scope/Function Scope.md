A variable declared inside a function is only accessible inside that function.

👉 Created using var, let, or const inside a function.

function test() {
    let age = 25;   // Function Scope
    console.log(age);
}

test();
console.log(age);  // ❌ Error