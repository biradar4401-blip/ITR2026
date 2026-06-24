1. History of JavaScript (History_JS)

Theory:
JavaScript is a programming language used to make websites interactive and dynamic. It was created by Brendan Eich in 1995 at Netscape. It was first called Mocha, then LiveScript, and later renamed JavaScript.

Example:

<button onclick="showMessage()">Click Me</button>

<script>
function showMessage() {
  alert("Hello, JavaScript!");
}
</script>

2. Starter JavaScript (Starter_JS)

Theory:
Starter JavaScript is the basic way to write JavaScript code. It can be written inside the <script> tag of an HTML file or in a separate .js file.

Example:

<!DOCTYPE html>
<html>
<body>

<h2>Hello JavaScript</h2>

<script>
  console.log("Welcome to JavaScript!");
</script>

</body>
</html>

3. Variables in JavaScript (Variable_JS)
Theory:
A variable is a container used to store data values that can be used and changed throughout a program. Think of it like a labeled box. In modern JavaScript, variables are declared using three main keywords: let, const, or var.

Example:

JavaScript
// Declaring variables
let name = "Yash";
let age = 20;

// Accessing and printing variables
console.log(name); // Output: Yash
console.log(age);  // Output: 20

4. Variable Keywords (Variable_Keyword)
Theory:
Variable keywords are used to declare variables in JavaScript. Modern JavaScript primarily uses three keywords, each handling scope and re-assignment differently:

let: Allows you to declare variables that can be reassigned later. Block-scoped.

const: Used for values that should remain constant and cannot be reassigned. Block-scoped.

var: The older way to declare variables. It is function-scoped and largely avoided in modern code.

Example:

JavaScript
let age = 20;          // Can be changed later
const PI = 3.14;       // Fixed value, cannot be changed
var city = "Pune";     // Older keyword

console.log(age, PI, city);

5. String Indexing in JavaScript (String_Indexing_JS)
Theory:
String indexing is used to access individual characters within a string. Every character in a string is assigned a position number called an index, which strictly starts at 0 for the first character, 1 for the second, and so on.

Example:

JavaScript
let name = "JavaScript";

// Accessing characters using square brackets
console.log(name[0]); // Output: J (First character)
console.log(name[4]); // Output: S (Fifth charac4