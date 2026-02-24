A variable declared outside any function or block is in Global Scope.
It can be accessed from anywhere in the program.

let name = "Vishal";  // Global Scope

function greet() {
    console.log(name);  // Accessible here
}

greet();
console.log(name);  // Accessible here too