let numbers = [1, 2, 3, 4];

Important Methods:

1.map()
let doubled = numbers.map(num => num * 2);

2.filter()
let even = numbers.filter(num => num % 2 === 0);

3.reduce()
let sum = numbers.reduce((acc, curr) => acc + curr, 0);

🧠 Interview Question:

👉 Difference between map and forEach?

map() returns new array

forEach() does not return anything