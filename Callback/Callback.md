A callback is a function passed as an argument to another function.

function greet(name, callback) {
  console.log("Hello " + name);
  callback();
}

function done() {
  console.log("Task completed");
}

greet("Vishal", done);