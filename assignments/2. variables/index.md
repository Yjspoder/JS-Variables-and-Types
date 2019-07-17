//Solution in the same file
1. In code below "Mark" is a string.  What is name?//string
```js
var name = "Mark";
```

2. Find the error if any
```js
  var product cost = 3.45;//var productCost = 3.45;
//There should be no space as it will create two variables,product and cost
```

3. Write `Right or Wrong` next to the code below.

```js
  "Hello World"//right
  'Hello World"//wrong
  "Hello World'//wrong
  'Hello World'//right
```

## Write `VALID` and `INVALID` infront of the variable name defined below
```js
var man;//valid
var 1girl;//invalid as variable cannot have a number
var woman3;//invalid
var -girl;//invalid as there cannot be '-' in a variable name
var blackDog;//valid
var 42;//valid
var $42;//valid
var userName;//valid
var x, y, z;//valid
var x = 5, y = 6, z = 7;//valid
var x = 5 + 10 + 2;//valid
```

## Basic Operations

Mathematical Operations:

Solve this using mathematical operations. (+, -, *, / , etc)

```js
var amount = 2080;
// Define a new variable and store the value that is 80 less then the value of amount.
var a = (amount - 80);
// Define a new variable and store the value that is 200 more then the value of amount.
var b = (amount + 200);
// Define a new variable and store the value that is 4 times the value of amount.
var c = (amount * 4);
// Define a new variable and store the reminder when the value of amount is  divided by 21.
var d = (amount / 21);
```

Logical Operation:

Solve this using logical operations. (<, >, &&, ||)

```js
var johnAge = 45;
var markAge = 35;

// Check who is older either John or Mark
(johnAge > markAge && alert("John is older") || johnAge < markAge && alert("Mark is older"));
// Check who is younger
(johnAge < markAge && alert("John is younger") || johnAge > markAge && alert("Mark is younger"));
// Check if their age is equal
(johnAge == markAge);
// Create a new variable and assign the age of john to new variable.
var a = johnAge;
// Check if john is equal to or greater then mark.
(johnAge == markAge && alert("John is equal to mark")|| johnAge > markAge && alert("John is greater than mark"));
// Check if john is less then or equal to mark.
(johnAge < markAge && alert("John is less than mark") || johnAge == markAge && alert("John is greater than mark"));
// Calculate the average age of john and mark and assign to a new variable.
var b = (johnAge + markAge / 2);//62.5
```
