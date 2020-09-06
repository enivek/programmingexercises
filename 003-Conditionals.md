# IF STATEMENTS

```javascript
// Write a function that takes a number and returns true if that number is a negative number or false if that number is a positive number.
function isNegative(num) {
  // Write your code here.
}

console.log("Should return true: " + isNegative(-1));
console.log("Should return true: " + isNegative(-0.1));
console.log("Should return true: " + isNegative(-103));
console.log("Should return true: " + isNegative(-2));
console.log("Should return false: " + isNegative(0));
console.log("Should return false: " + isNegative(1));
console.log("Should return false: " + isNegative(.5));
console.log("Should return false: " + isNegative(1000));
```

```javascript
// Write a function that takes a number and returns true if that number is an odd number, and false if it is an even number.
function isOdd(num) {
  // Your code goes here
}

console.log("Should return true: " + isOdd(1));
console.log("Should return true: " + isOdd(33));
console.log("Should return true: " + isOdd(701));

console.log("Should return false: " + isOdd(2));
console.log("Should return false: " + isOdd(22));
console.log("Should return false: " + isOdd(50));
```

```javascript
// Write a function returns true if the number is a whole number. False otherwise.
function isWholeNumber(num) {
  // Your code goes here
}

console.log("Should return true: " + isWholeNumber(0));
console.log("Should return true: " + isWholeNumber(1));
console.log("Should return true: " + isWholeNumber(33));
console.log("Should return true: " + isWholeNumber(701));

console.log("Should return false: " + isWholeNumber(2.2));
console.log("Should return false: " + isWholeNumber(-22.43));
console.log("Should return false: " + isWholeNumber(-3.2));
console.log("Should return false: " + isWholeNumber(3.141));
```

```javascript
// Write a function that returns the absolute value of a number.
function getAbsoluteValue(num) {
  // Your code goes here
}

console.log("Should return 0: " + getAbsoluteValue(0));
console.log("Should return 1: " + getAbsoluteValue(1));
console.log("Should return 123: " + getAbsoluteValue(-123));
console.log("Should return 456: " + getAbsoluteValue(456));

console.log("Should return 2.22: " + getAbsoluteValue(-2.22));
console.log("Should return 1.55: " + getAbsoluteValue(1.55));
console.log("Should return 1.23: " + getAbsoluteValue(-1.23));
console.log("Should return 4.56: " + getAbsoluteValue(4.56));
```

```javascript
// Write a function that returns the distance between two points.
// Given points (x1,y1) and (x2,y2) return the distance between those two points.

function getDistance(x1, y1, x2, y2) {
  // Your code goes here
}

console.log("Should return 8.0622: " + getDistance(-2,-3,5,1));
console.log("Should return 4:      " + getDistance(-1, -3, -1, 1));
console.log("Should return 7:      " + getDistance(3, 5, 10, 5));
console.log("Should return 0:      " + getDistance(0,0,0,0));
console.log("Should return 7.6157: " + getDistance(1,5,-2,-2));
```


```javascript
// Part 1: Write a function that takes a string and returns true if the first letter of that string is a capital "A" and false otherwise.
function isStartWithA(str) {
  // Write your code here.
}

console.log("Should return true: " + isStartWithA("Apple"));
console.log("Should return true: " + isStartWithA("Abracadabra"));
console.log("Should return false: " + isStartWithA("apple"));
console.log("Should return false: " + isStartWithA("abracadabra"));
console.log("Should return false: " + isStartWithA(" akin"));
console.log("Should return false: " + isStartWithA("bee"));
```

```javascript
// Part 2: Write a function that takes a string and returns true if the first letter of that string is a capital "A" and false otherwise.
function isStartWithA(str) {
  // Write your code here.
}

console.log("Should return true: " + isStartWithA("Apple"));
console.log("Should return true: " + isStartWithA("Abracadabra"));
console.log("Should return false: " + isStartWithA("apple"));
console.log("Should return false: " + isStartWithA("abracadabra"));
console.log("Should return false: " + isStartWithA(" akin"));
console.log("Should return false: " + isStartWithA("bee"));
console.log("Should return false: " + isStartWithA());
```

```javascript
// Write a function that takes a string and returns true if the second letter of that string is a lowercase "b" and false otherwise.
function isSecondLetterB(str) {
  // Write your code here.
}

console.log("Should return true: " + isSecondLetterB("Abba"));
console.log("Should return true: " + isSecondLetterB("Abracadabra"));
console.log("Should return false: " + isSecondLetterB("apple"));
console.log("Should return false: " + isSecondLetterB("bracadaabra"));
console.log("Should return false: " + isSecondLetterB(" aee"));
console.log("Should return false: " + isSecondLetterB("apple"));
console.log("Should return false: " + isSecondLetterB());
console.log("Should return false: " + isSecondLetterB(''));
```

```javascript
// Write a function that takes a string and returns the same string but with a * in front of it.
function starMe(str) {
  // Write your code here.
}

console.log("Should be *A: " + starMe("A"));
console.log("Should be *: " + starMe(""));
console.log("Should be *STAR: " + starMe("STAR"));
console.log("Should be ***: " + starMe("**"));
```

```javascript
// Write a function that takes a string and returns an asterisk and the 2nd character of that string. If the string is less than two characters long, then return an asterisk. If the string is null or undefined, also just return an asterisk.
function starMe(str) {
  // Write your code here.
}

console.log("Should be *B: " + starMe("ABCDEF"));
console.log("Should be *4: " + starMe("6454345"));
console.log("Should be *T: " + starMe("STAR"));
console.log("Should be *o: " + starMe("God save the Queen"));
console.log("Should be *: " + starMe("A"));
```
