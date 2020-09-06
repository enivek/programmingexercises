# MORE LOOPS

# Store 1 to 100 into an array
```javascript
/**
Write a function stores numbers from 1 to 100 in an array.
**/
function oneToOneHundred() {
    // Write your code here.
}

var result = oneToOneHundred();
console.log("Should be equal to 100: " + result.length);
console.log("Should be a list of numbers from 1 to 100 => " + result);
```

# Write a function that takes in two numbers, w and h and displays a rectangle made of asterisks (*) with the number of characters specified in the width and height. 
```javascript
/**
 Write a function that takes in two numbers, w and h and displays a rectangle made of asterisks (*) with the 
  number of characters specified in the width and height. 
  For example: drawRect(3, 2) should return:
      ***
      ***
 **/
function drawRect(w, h) {
    // Write your code here.
}

drawRect(3, 2);
drawRect(5, 6);
drawRect(8, 2);
```

# Write a function that checks to see if a number is prime or not.
```javascript
/**
 Write a function that checks to see if a number is prime or not. 
 return true if num is prime.
 return false if num is not prime.
 **/
function isPrime(num) {
    // Write your code here.
}

console.log('3 is a prime number. This should be true: ' + isPrime(3));
console.log('19 is a prime number. This should be true: ' + isPrime(19));
console.log('107 is a prime number. This should be true: ' + isPrime(107));
console.log('1061 is a prime number. This should be true: ' + isPrime(1061));
console.log('10093 is a prime number. This should be true: ' + isPrime(10093));
console.log('102667 is a prime number. This should be true: ' + isPrime(102667));
console.log('4 is not a prime number. This should be false: ' + isPrime(4));
console.log('26 is not a prime number. This should be false: ' + isPrime(26));
console.log('538 is not a prime number. This should be false: ' + isPrime(538));
console.log('1874 is not a prime number. This should be false: ' + isPrime(1874));
console.log('16222 is not a prime number. This should be false: ' + isPrime(16222));
console.log('164938 is not a prime number. This should be false: ' + isPrime(164938));
```

# Write a function that returns the nth fibonacci number.
```javascript
/**
 Write a function that returns the nth fibonacci number.
 For example: 
     if n = 0, then return 0
     if n = 1, then return 1
     if n = 2, then return 1
     if n = 3, then return 2
     and so on...
 However if n is a negative number then return -1.
 **/
function getMeAFibonacci(num) {
    // Write your code here.
}

console.log('This should return a -1: ' + getMeAFibonacci(-1));
console.log('This should return a -1: ' + getMeAFibonacci(-10));

console.log('The 0th fibonacci is 0: Should be 0: ' + getMeAFibonacci(0));
console.log('The 1th fibonacci is 1: Should be 1: ' + getMeAFibonacci(1));
console.log('The 2nd fibonacci is 1: Should be 1: ' + getMeAFibonacci(2));
console.log('The 3rd fibonacci is 2: Should be 2: ' + getMeAFibonacci(3));
console.log('The 4th fibonacci is 3: Should be 3: ' + getMeAFibonacci(4));
console.log('The 5th fibonacci is 5: Should be 5: ' + getMeAFibonacci(5));
console.log('The 6th fibonacci is 5: Should be 8: ' + getMeAFibonacci(6));
console.log('The 7th fibonacci is 5: Should be 13: ' + getMeAFibonacci(7));

console.log('The 15th fibonacci is 610: Should be 610: ' + getMeAFibonacci(15));
console.log('The 20th fibonacci is 6765: Should be 6765: ' + getMeAFibonacci(20));
console.log('The 30th fibonacci is 832040: Should be 832040: ' + getMeAFibonacci(30));

```

# Return the smallest number in an array.
```javascript
/**
 Write a function that takes in an array of numbers and returns the smallest number.
 Parameter: @arr An array of numbers
 Return: The smallest number in @arr.
**/
function smallestNumber(arr) {
    // Write your code here.
}

console.log("Should be: 2 => " + smallestNumber([6,10,4,2]));
console.log("Should be: 10 => " + smallestNumber([90, 50, 40, 30, 10, 100]));
console.log("Should be: 13 => " + smallestNumber([13, 90, 100, 50, 63, 23, 14]));
console.log("Should be: 12 => " + smallestNumber([12, 12, 12, 12, 12]));
console.log("Should be: -1 => " + smallestNumber());
console.log("Should be: -1 => " + smallestNumber([]));
```

# Print out a triangle.
```javascript
/**
 * Write a function which, given a number (num), prints out a triangle made out of asterisks
 * where the bottom number of asterisks in the triangle is that number (num).
 * Example:
 *   if num = 3
 *     *
 *     **
 *     ***
 *   if num = 2:
 *     *
 *     **
 */
function printTriangle(num) {

}
 
printTriangle(3);
 ``` 

# Divisible by 7 but not by 5.
```javascript
/**
 * Write a function which will return an array of numbers which are divisible by 7 
 * but are not a multiple of 5, between the begin and end input variables (inclusive).
 */
function isDivisibleBy7Not5(beginNumber, endNumber) {

}
 
console.log("Should be: 7 => " + isDivisibleBy7Not5(1,10));
console.log("Should be: 7, 14 ,21, 28, 42, 49 => " + isDivisibleBy7Not5(1,50));
``` 

# Print out a multiplication table.
```javascript
/**
 * Write a program that prints the multiplication table of a number. 
 * If multiplicationTable(4) then the output should be:
 *  4 x 1 = 4
 *  4 x 2 = 8
 *  ...
 *  4 x 10 = 40
 * 
 * If multiplicationTable(5) then the output should be: 
 *  5 x 1 = 5
 *  5 x 2 = 10
 *  ...
 *  5 x 10 = 50 
 */
function multiplicationTable(num) {
  for ( let i = 0; i < 10; i++) {
    console.log('3*' + i + '=' + 3*i)
  }
}

multiplicationTable(49);
``` 
 
# Factorial computation
```javascript
/**
 * Write a program to return the factorial value of any number.
 */
function factorial(num) {

}

console.log("Should be: 2! = 2, answer should be 2 => " + factorial(2));
console.log("Should be: 3! = 6, answer should be 6 => " + factorial(3));
``` 

# Exponent computation
```javascript
/**
 * Write a function to find the value of the power of one number raised to the power of another. (Do not use built-in method)
 */
function power(base, pow) {

}

console.log("2^0 = 1. Answer should be 1 => " + power(2, 0));
console.log("2^2 = 4. Answer should be 4 => " + power(2, 2));
``` 

# Reverse integers
```javascript
/**
 * Write a program that accepts an integer and returns an with the digits reversed. For example, if the input is 12345, the output should be 54321.
 */
function reverseNumber(num) {

}

console.log("Answer should be 321 =>" + reverseNumber(123));
console.log("Answer should be 9876 =>" + reverseNumber(6789));
``` 

# Sum of all odd numbers
```javascript
/**
 * Write a function that reads an array of integers, and then returns the sum of the odd numbers.
 */
function sumOfOdd(arr) {

}

console.log("Answer should be 9 => " + sumOfOdd([1,2,3,4,5]));
console.log("Answer should be 11 => " + sumOfOdd([2,4,6,8,11]));
console.log("Answer should be 5 => " + sumOfOdd([1,1,1,1,1,12,4,6,8,10]));
``` 

# Calculate the Greatest Common Factor
```javascript
/**
 * Write a program to calculate the GCF (Greatest Common Factor) of two given numbers.
 */
function getGCF(numA, numB) {

}

console.log("GCF of 20 and 28 = 4. Answer should be 4 =>" + getGCF(20,28));
console.log("GCF of 25 and 35 = 5. Answer should be 5 =>" + getGCF(25,35));
console.log("GCF of 2 and 8 = 2. Answer should be 2 =>" + getGCF(2,8));
console.log("GCF of 24 and 36 = 12. Answer should be 2 =>" + getGCF(24,36));
``` 

# Calculate the Armstrong number.
```javascript
/**
 * An Armstrong number is a number where the sum of the cubes of each digit is equal to the number itself.
 * For example, 153 is an Armstrong number because: 153 = ( 1 * 1 * 1 ) + ( 5 * 5 * 5 ) + ( 3 * 3 * 3 )
 * Write a function to print out all Armstrong numbers between 1 and 500. 
 */
function getArmstrongNumber() {

}

getArmstrongNumber();
``` 

# Calculate the sum of fractions.
```javascript
/**
 * Write a function which returns the sum of following series where n is input by user. 
 * 1 + 1/2 + 1/3 + 1/4 + 1/5 + .... + 1/n 
 */
function sumOfFractions(num) {

}

console.log("If num = 1,  answer should be: 1 => " + sumOfFractions(1));
console.log("If num = 3,  answer should be: 1.83333333 => " + sumOfFractions(3));
console.log("If num = 5,  answer should be: 2.28333333 => " + sumOfFractions(5));
console.log("If num = 10, answer should be: 2.92896825 => " + sumOfFractions(10));
``` 

# Calculate the natural log.
```javascript
/**
 * Write a function to compute the natural logarithm of 2, by adding up to n terms in the series
 *   1 - 1/2 + 1/3 - 1/4 + 1/5 - ... 1/n
 * where n is a positive integer and input by user.
 */
function naturalLog(n) {

}

console.log( "ln(10) = 2.3025. Should be equal to 2.3025 => " + naturalLog(10) );
console.log( "ln(5)  = 1.6094. Should be equal to 1.6094 => " + naturalLog(5) );
console.log( "ln(2)  = 0.6931. Should be equal to 0.6931 => " + naturalLog(2) );
``` 

# Print out a triangle.
```javascript
// Write a function to print this out with a for-loop:
        1
      222
    33333
  4444444
555555555
```

# Compute the sin(x) of a number.
```javascript
/**
 * Write a program to compute sin(x) for given x. We compute the sine of x using the series:
 * sin x = x - x3/3! + x5/5! - x7/7! + x9/9! .......
 */
function sine(x) {

}

console.log("");
```

# Calculate the cos(x) of a number.
```javascript
/**
 * Write a program to compute cos(x) for given x. We compute the sine of x using the series:
 * cos x = 1 - x2/2! + x4/4! - x6/6! .....
 */
function cosine(x) {

}

console.log("");
```