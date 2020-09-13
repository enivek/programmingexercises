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
/**
 * Given two points, (x1,y1) and (x2,y2) return the midpoint.
 */
function midpoint(x1, y1, x2, y2) {

}

console.log("Should return '(6,6)' => " + midpoint(1,1,11,11));
console.log("Should return '(0,1)' => " + midpoint(5,8,-5,-6));
console.log("Should return '(9,-0.5)' => " + midpoint(8,-2,10,1));
console.log("Should return '(1,1)' => " + midpoint(1,1,1,1));
console.log("Should return '(8.5,9)' => " + midpoint(12,8,5,10));
```


```javascript
/**
 * Given the lengths of three sides of a triangle, 
 * return a string that says: 
 *  - "Scalene" if the triangle is scalene, 
 *  - "Isoceles" if the triangle is isoceles 
 *  - "Equilateral" if the triangle is an equilateral triangle 
 *  - "Other" if the triangle is some other kind of triangle. 
 *  - "Not a triangle" if the sides given is not a 
 * triangle.
 */
function whatKindOfTriangle(side1, side2, side3) {

}

console.log("Should return 'Equilateral' => " + whatKindOfTriangle(1,1,1));
console.log("Should return 'Equilateral' => " + whatKindOfTriangle(16,16,16));
console.log("Should return 'Scalene' => " + whatKindOfTriangle(16,11,21));
console.log("Should return 'Scalene' => " + whatKindOfTriangle(12,21,13));
console.log("Should return 'Isosceles' => " + whatKindOfTriangle(16,11,11));
console.log("Should return 'Isosceles' => " + whatKindOfTriangle(10,10,12));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(6,10,14));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(2,16,13));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(6,10,0));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(2,-1,13));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(-2,5,13));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(-1,-1,-1));
console.log("Should return 'Not a triangle' => " + whatKindOfTriangle(0,5,0));
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
