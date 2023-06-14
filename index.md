Day 1 Tasks:
(i) Naming Convention
(ii) scriptTag

Line 10 (scriptTag1-Path)
Line 11 scriptTag2-Command (This is how we can add 2 script tags in file regardless keeping everything in single script tag.)

(iii) Statements
Line 14 without semicolon
Line 15,16 without semi colon
Line 17 with semi colon best practice
We need to end the statement with semicolon, because JavaScript does not assume a semicolon as end in very few cases, for example before square brackets […]
For Example:
alert("Hello")
[1, 2].forEach(alert); 
You will get error for above code

(iv) Comments
// Single line comment
/*
Multiple line
comments
*/

(v) Use Strict
Modern JavaScript supports “classes” and “modules” so use strict is not necessary. But if you want to use ”use strict" below is ignored--it must be at the top.

(vi) Variables
Var(old school), Let(Replaced to var), Const(For constant values)
use a **single line per variable**.
Variable name **should not start with numbers** and it **should not be in kebab case.**
We **cannot use variable names as let, class, return, and function** because these are reserved
When you add new value old data is removed from the variable as example 1, But when we refer with let in next line as well will get error as example 2.
**Eg 1**:
let message;
message = 'Hello!';
message = 'World!'; // value changed
alert(message);
**Eg 2:**
let message = "This";
// repeated 'let' leads to an error
let message = "That"; // SyntaxError: (Variable hosting) 'message' has already been declaredA repeated declaration of the same variable is an error:

(vii) Naming Conventions:
**Pascal Case (PascalCase):** Component Names, File Names
**Camel Case(camelCase):** Props, state variables, General Variables, 
File Names only contains Utility Functions, Helper methods Eg: utilityFunctions.js, apiService.js
**Kebab Case(Kebab-case):** CSS class name (<div className="my-class-name"></div>)
**Snake Case (SNAKE_CASE):** Constants
