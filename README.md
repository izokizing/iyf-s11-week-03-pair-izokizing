iyf-s11-week-03-pair<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>js practice</title>
</head>
<body>
    <h1>check the console!</h1>
    <script>
        // Variable declarations
let name = "Fredie";              // string
let age = 22;                     // number
let isStudent = true;             // boolean
let favoriteColors = ["blue", "black", "white"]; // array
let today = new Date();           // Date object

// Console logging with descriptive messages
console.log("Name:", name);
console.log("Age:", age);
console.log("Is student:", isStudent);
console.log("Favorite colors:", favoriteColors);
console.log("Today's date:", today);

// typeof operator 
console.log("Type of name:", typeof name);
console.log("Type of age:", typeof age);
console.log("Type of isStudent:", typeof isStudent);
console.log("Type of favoriteColors:", typeof favoriteColors);
console.log("Type of today:", typeof today);

// let vs const 
let score = 100;
score = 150;  // Works fine

const PI = 3.14159;
// PI = 3;  // Error! const cannot be reassigned

// number operations
let a = 10;
let b = 3;
console.log("Addition:", a + b);
console.log("Subtraction:", a - b);
console.log("Multiplication:", a * b);
console.log("Division:", a / b);
console.log("Modulus:", a % b);

// increment/decrement
let count = 0;
count++; // count is now 1
count--; // count is now 0
console.log("Final count:", count);

// string operations
let greeting = "fredie";
let name2 = "njiru";
console.log("Greeting:", greeting);
console.log("Name:", name2);
    </script>

</body>
</html>
