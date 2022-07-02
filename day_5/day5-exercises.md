#Chapter 2
1. How do you declare a variable. What does the equals sign really mean in JavaScript? What is it called in JavaScript?
You declare a variable by using the var keyword, followed by the name you want to call the variable.  For example, var name;
To assign a value to the variable you use the equal sign (known as the assignment operator).  For example:  name = "Beth";
1. There are three big data types in JavaScript: numbers, strings, and booleans. Describe what each of them are.
Number data types are used to assign numbers and calculations.
Strings are used to assign text.
Booleans are used to determine a true or false statement.
1. What are the six rules for naming variables? What are a few JavaScript reserved words that you should avoid using for variable names?
The 6 rules for naming variables are: (1) names must start with a letter, $ sign or underscore _.  The cannot start with a number.  (2) You cannot use a dash or (.) in a variable name. (3) You cannot use reserved keywords in a name variable, for example: var  (4) all variables are case sensitive so they have to match  (5) use a name that makes sense and matches what the stored value is, for example firstName would store the users first name (6) if the variable uses two words, use camelCase to for the name or and underscore.  
A few reserved JS words are: while, else, abstract, boolean, const, etc.
1. How can an array be useful when dealing with multiple related values? How do you access/change a value in an array?
Arrays are useful when creating lists or related items.  You do need to declare how many items are in the array, and may only use some of the items in the array.  To access an array:  the arry name is specified along with the index number in square brackets.  A variable is declared, called thirdItem, and then that variable accesses the third color.  For example:
var thirdItem;
thirdItem = color[2];
//Note the index counter starts at 0, so the third item will be number 2, not 3.
To change a value of an array you select it and assign a new value, just like you do with a variable.  For example:
color[2] = "beige";
1. What is the difference between an expression and a statement?
A statement is an individual instruction the computer should follow.  It starts on a new line of code and ends in a semicolon.  For example: var age = 30;
An expression is the value that is returned.  Expressions can return a single assigned value, or they can turn two or more values into a single value.  For example, var age = 30; is an expression that returns the value of 30.  var age = 28 + 2; returns the same value of 30 but uses two values to return the single value of 30.
1. What are three types of operators and how are they used?
Assignment operators return a value to a variable.
color = "beige"; //the value is beige
Arithmetic operators perform basic math.
area = 3 * 2; //the value is 6
String operators combine two strings (known as concatentation)
greeting = "Hi " + "Beth!"; //the value of greeting is now Hi Beth!
# Console exercises:
var kids = 3;
undefined
var name = "Jake"
undefined
var loc = "Texas";
undefined
var name = "Jake";
undefined
var job = "Tiger Trainer";
undefined
"You will be a " + job + " in " + loc + "," + " and married to " + name + " with " + kids + " kids.";
'You will be a Tiger Trainer in Texas, and married to Jake with 3 kids.'
## exercise 2:
var currentYear = 2022;
undefined
var birthYear = 1979;
undefined
var age = currentYear - birthYear;
undefined
console.log("you are either " + age + " or " + (age - 1));
VM2097:1 you are either 43 or 42
### exercise #3:
var age = 42;
undefined
age
42
var maxAge = 100;
undefined
var perDay = 2;
undefined
var totalNeeded = (perDay * 365) * (maxAge - age);
undefined
var message = "you will need " + totalNeeded + " to last you until the ripe old age of " + maxAge;
undefined
console.log(message);
VM2727:1 you will need 42340 to last you until the ripe old age of 100
