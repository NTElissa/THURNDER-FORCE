## THURNDER-FORCE
#### join Here !!!! Open ➡️➡️➡️⛷️
#### https://github.com/orgs/Kalumeli/repositories


# 🌟 JavaScript Level 3 Exercises

This repository contains a set of **JavaScript exercises** designed to enhance your skills through hands-on coding problems. Each exercise targets a fundamental concept, ranging from basic control structures to more advanced array manipulations and algorithm-based challenges.

## 📜 Table of Contents

1. [Odd or Even Checker](#exercise-1-odd-or-even-checker)
2. [Sum of Array Elements](#exercise-2-sum-of-array-elements)
3. [Smallest Number in Array](#exercise-3-smallest-number-in-array)
4. [Vowel Counter in String](#exercise-4-vowel-counter-in-string)
5. [Letter Grade Feedback](#exercise-5-letter-grade-feedback)
6. [Prime Numbers (1 to 50)](#exercise-6-prime-numbers-1-to-50)
7. [Value Finder in Array](#exercise-7-value-finder-in-array)
8. [Count Positives, Negatives, Zeros](#exercise-8-count-positives-negatives-zeros)
9. [Average of Array Elements](#exercise-9-average-of-array-elements)
10. [Remove Specific Value from Array](#exercise-10-remove-specific-value-from-array)
11. [Multiples of 3 (1 to 30)](#exercise-11-multiples-of-3-1-to-30)
12. [Separate Even and Odd Numbers](#exercise-12-separate-even-and-odd-numbers)
13. [Day of the Week](#exercise-13-day-of-the-week)
14. [Find Common Elements](#exercise-14-find-common-elements)
15. [Count Occurrences in Array](#exercise-15-count-occurrences-in-array)
16. [Reverse Words in a Sentence](#exercise-16-reverse-words-in-a-sentence)
17. [Simple Calculator](#exercise-17-simple-calculator)
18. [Find Second Largest Number](#exercise-18-find-second-largest-number)
19. [Check Palindromic Array](#exercise-19-check-palindromic-array)
20. [Pattern Printing](#exercise-20-pattern-printing)
21. [Find Largest Odd Number](#exercise-21-find-largest-odd-number)
22. [Sum of Digits](#exercise-22-sum-of-digits)
23. [Remove Duplicates from Array](#exercise-23-remove-duplicates-from-array)
24. [Word Count in Sentence](#exercise-24-word-count-in-sentence)
25. [Multiplication Table](#exercise-25-multiplication-table)

---

## Exercise 1: Odd or Even Checker ⚖️

**Description**: Write a program that checks if a number is odd or even.  
**Input**: A number.  
**Output**: "Odd" if the number is odd, and "Even" if the number is even.

```javascript
let number = 7;
if (number % 2 === 0) {
  console.log("Even");
} else {
  console.log("Odd");
}
``` 
Exercise 2: Sum of Array Elements ➕
Description: Write a program that calculates the sum of all elements in an array called numbers.
Input: An array of numbers.
Output: The total sum.

```javascript

let numbers = [10, 20, 30, 40];
let sum = numbers.reduce((acc, val) => acc + val, 0);
console.log("Sum:", sum);
```
Exercise 3: Smallest Number in Array 🔎
Description: Write a program that finds and prints the smallest number in an array called values.
Input: An array of numbers.
Output: The smallest number.

``` javascript
let values = [5, 2, 9, 1, 6];
let smallest = Math.min(...values);
console.log("Smallest Number:", smallest);
```
Exercise 4: Vowel Counter in String 🅰️
Description: Write a program that counts the number of vowels in a given string called sentence.
Input: A string.
Output: The total number of vowels.

```javascript

let sentence = "Hello World";
let vowels = sentence.match(/[aeiou]/gi) || [];
console.log("Vowel Count:", vowels.length);
```
Exercise 5: Letter Grade Feedback 🎓
Description: Write a program that takes a letter grade (like "A", "B", "C", etc.) and prints feedback.
Input: A grade.
Output: Feedback as follows:

"A" → "Excellent"
"B" → "Good"
"C" → "Average"
"D" → "Below Average"
"F" → "Fail"

``` javascript

let grade = "B";
switch (grade) {
  case "A":
    console.log("Excellent");
    break;
  case "B":
    console.log



```



---

## 📜 Table of Contents

1. [Odd or Even Checker](#exercise-1-odd-or-even-checker)
2. [Sum of Array Elements](#exercise-2-sum-of-array-elements)
3. [Smallest Number in Array](#exercise-3-smallest-number-in-array)
4. [Vowel Counter in String](#exercise-4-vowel-counter-in-string)
5. [Letter Grade Feedback](#exercise-5-letter-grade-feedback)
6. [Prime Numbers (1 to 50)](#exercise-6-prime-numbers-1-to-50)
7. [Value Finder in Array](#exercise-7-value-finder-in-array)
8. [Count Positives, Negatives, Zeros](#exercise-8-count-positives-negatives-zeros)
9. [Average of Array Elements](#exercise-9-average-of-array-elements)
10. [Remove Specific Value from Array](#exercise-10-remove-specific-value-from-array)

---

## Exercise 1: Odd or Even Checker ⚖️

**Description**: Write a program that checks if a number is odd or even.  
**Input**: A number.  
**Output**: "Odd" if the number is odd, and "Even" if the number is even.

```javascript

let number = 7;

if (number % 2 === 0) {
  console.log("Even"); // If the number is divisible by 2, it's even.
} else {
  console.log("Odd"); // Otherwise, it's odd.
}
```
Exercise 2: Sum of Array Elements ➕
Description: Write a program that calculates the sum of all elements in an array called numbers.
Input: An array of numbers.
Output: The total sum.

``` javascript

let numbers = [10, 20, 30, 40];
let sum = 0;

for (let i = 0; i < numbers.length; i++) {
  sum += numbers[i]; // Add each number in the array to the sum.
}

console.log("Sum:", sum); // Print the total sum.
```
Exercise 3: Smallest Number in Array 🔎
Description: Write a program that finds and prints the smallest number in an array called values.
Input: An array of numbers.
Output: The smallest number.

```javascript


let values = [5, 2, 9, 1, 6];
let smallest = values[0]; // Assume the first number is the smallest.

for (let i = 1; i < values.length; i++) {
  if (values[i] < smallest) {
    smallest = values[i]; // Update if a smaller number is found.
  }
}

console.log("Smallest Number:", smallest);
```
Exercise 4: Vowel Counter in String 🅰️
Description: Write a program that counts the number of vowels in a given string called sentence.
Input: A string.
Output: The total number of vowels.

```javascript

let sentence = "Hello World";
let count = 0;
let vowels = "aeiouAEIOU"; // List of vowels.

for (let i = 0; i < sentence.length; i++) {
  if (vowels.includes(sentence[i])) {
    count++; // Increment count if the character is a vowel.
  }
}

console.log("Vowel Count:", count);
```
Exercise 5: Letter Grade Feedback 🎓
Description: Write a program that takes a letter grade (like "A", "B", "C", etc.) and prints feedback.
Input: A grade.
Output: Feedback as follows:

"A" → "Excellent"
"B" → "Good"
"C" → "Average"
"D" → "Below Average"
"F" → "Fail"
```javascript


let grade = "B";

if (grade === "A") {
  console.log("Excellent");
} else if (grade === "B") {
  console.log("Good");
} else if (grade === "C") {
  console.log("Average");
} else if (grade === "D") {
  console.log("Below Average");
} else if (grade === "F") {
  console.log("Fail");
} else {
  console.log("Invalid Grade"); // Handle unexpected input.
}
```
Exercise 6: Prime Numbers (1 to 50) 🧮
Description: Write a program that prints all prime numbers between 1 and 50.
Input: None.
Output: A list of prime numbers.

```javascript

for (let num = 2; num <= 50; num++) {
  let isPrime = true;

  for (let i = 2; i < num; i++) {
    if (num % i === 0) {
      isPrime = false; // Mark as not prime if divisible by another number.
      break;
    }
  }

  if (isPrime) {
    console.log(num); // Print the prime number.
  }
}
```
Exercise 7: Value Finder in Array 🔍
Description: Write a program that checks if a specific value exists in an array.
Input: An array and a value to search.
Output: "Found" if the value exists, otherwise "Not Found".

```javascript

let arr = [1, 2, 3, 4, 5];
let value = 3;
let found = false;

for (let i = 0; i < arr.length; i++) {
  if (arr[i] === value) {
    found = true; // Set found to true if the value is in the array.
    break;
  }
}

if (found) {
  console.log("Found");
} else {
  console.log("Not Found");
}
```
Exercise 8: Count Positives, Negatives, Zeros ➕➖0️⃣
Description: Write a program that counts how many numbers in an array are positive, negative, or zero.
Input: An array of numbers.
Output: Counts for each category.

```javascript

let numbers = [1, -2, 0, 3, -4, 5, 0];
let positives = 0;
let negatives = 0;
let zeros = 0;

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] > 0) {
    positives++;
  } else if (numbers[i] < 0) {
    negatives++;
  } else {
    zeros++;
  }
}

console.log("Positives:", positives);
console.log("Negatives:", negatives);
console.log("Zeros:", zeros);
```
Exercise 9: Average of Array Elements 📊
Description: Write a program that computes the average of all numbers in an array called scores.
Input: An array of numbers.
Output: The average.

```javascript

let scores = [90, 80, 70, 100];
let total = 0;

for (let i = 0; i < scores.length; i++) {
  total += scores[i]; // Add each score to the total.
}

let average = total / scores.length; // Divide total by the number of scores.
console.log("Average:", average);
```
Exercise 10: Remove Specific Value from Array 🗑️
Description: Write a program to remove all occurrences of a specific value from an array called numbers.
Input: An array and a value to remove.
Output: The modified array.

```javascript

let numbers = [1, 2, 3, 2, 4, 2, 5];
let valueToRemove = 2;
let filteredArray = [];

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] !== valueToRemove) {
    filteredArray.push(numbers[i]); // Add to the new array if it’s not the value to remove.
  }
}

console.log("Modified Array:", filteredArray);

```
Exercise 11: Multiples of 3 (1 to 30) 🔢
Description: Write a program that prints all multiples of 3 from 1 to 30.
Input: None.
Output: Numbers that are multiples of 3.

``` javascript

for (let i = 1; i <= 30; i++) {
  if (i % 3 === 0) {
    console.log(i); // Print the number if it is a multiple of 3.
  }
}
```
Exercise 12: Separate Even and Odd Numbers ➗
Description: Write a program that separates even and odd numbers in an array and prints both groups in separate arrays.
Input: An array of numbers.
Output: Two arrays, one for even numbers and one for odd numbers.

```javascript

let numbers = [1, 2, 3, 4, 5, 6, 7, 8];
let evens = [];
let odds = [];

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] % 2 === 0) {
    evens.push(numbers[i]); // Add even numbers to the evens array.
  } else {
    odds.push(numbers[i]); // Add odd numbers to the odds array.
  }
}

console.log("Evens:", evens);
console.log("Odds:", odds)
```
Exercise 13: Day of the Week 📅
Description: Write a program that takes a number between 1 and 7 and prints the corresponding day of the week.
Input: A number between 1 and 7.
Output: The name of the day.

```javascript

let dayNumber = 4; // Example input
let day;

switch (dayNumber) {
  case 1:
    day = "Monday";
    break;
  case 2:
    day = "Tuesday";
    break;
  case 3:
    day = "Wednesday";
    break;
  case 4:
    day = "Thursday";
    break;
  case 5:
    day = "Friday";
    break;
  case 6:
    day = "Saturday";
    break;
  case 7:
    day = "Sunday";
    break;
  default:
    day = "Invalid day number";
}

console.log("Day:", day);
```
Exercise 14: Find Common Elements 🔗
Description: Write a program that finds all common elements between two arrays called array1 and array2.
Input: Two arrays of numbers.
Output: An array of common elements.

```javascript


let array1 = [1, 2, 3, 4, 5];
let array2 = [3, 4, 5, 6, 7];
let commonElements = [];

for (let i = 0; i < array1.length; i++) {
  if (array2.includes(array1[i])) {
    commonElements.push(array1[i]); // Add to common elements if it's found in both arrays.
  }
}

console.log("Common Elements:", commonElements);
```
Exercise 15: Count Occurrences in Array 📊
Description: Write a program that counts how many times each element appears in an array called items.
Input: An array of numbers or strings.
Output: A count of each element.

```javascript


let items = ["apple", "banana", "apple", "orange", "banana", "apple"];
let counts = {};

for (let i = 0; i < items.length; i++) {
  let item = items[i];
  if (counts[item]) {
    counts[item]++; // Increment count if the item already exists in the counts object.
  } else {
    counts[item] = 1; // Initialize count to 1 if it's the first occurrence.
  }
}

console.log("Counts:", counts);
```
Exercise 16: Reverse Words in a Sentence 🔄
Description: Write a program that reverses each word in a given string called sentence.
Input: A string.
Output: The sentence with each word reversed.

```javascript

let sentence = "Hello World";
let words = sentence.split(" "); // Split the sentence into words.
let reversedWords = [];

for (let i = 0; i < words.length; i++) {
  let reversedWord = words[i].split("").reverse().join(""); // Reverse each word.
  reversedWords.push(reversedWord);
}

let result = reversedWords.join(" "); // Join the reversed words back into a sentence.
console.log("Reversed Sentence:", result);
```
Exercise 17: Simple Calculator ➕➖✖️➗
Description: Write a simple calculator program that takes two numbers and an operation (+, -, *, /) and performs the operation.
Input: Two numbers and an operation.
Output: The result of the operation.

```javascript


let num1 = 10;
let num2 = 5;
let operation = "+"; // Choose from "+", "-", "*", or "/".
let result;

if (operation === "+") {
  result = num1 + num2;
} else if (operation === "-") {
  result = num1 - num2;
} else if (operation === "*") {
  result = num1 * num2;
} else if (operation === "/") {
  result = num1 / num2;
} else {
  result = "Invalid operation";
}

console.log("Result:", result);
```
Exercise 18: Find Second Largest Number 🥈
Description: Write a program that finds the second largest number in an array called numbers.
Input: An array of numbers.
Output: The second largest number.

```javascript


let numbers = [10, 20, 5, 8, 30];
let largest = -Infinity;
let secondLargest = -Infinity;

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] > largest) {
    secondLargest = largest; // Update second largest before updating largest.
    largest = numbers[i];
  } else if (numbers[i] > secondLargest && numbers[i] !== largest) {
    secondLargest = numbers[i]; // Update second largest if it's not equal to largest.
  }
}

console.log("Second Largest Number:", secondLargest);
```
Exercise 19: Check Palindromic Array 🔁
Description: Write a program that checks if an array reads the same forwards and backwards.
Input: An array of numbers or strings.
Output: "Palindrome" if it is, otherwise "Not a Palindrome".

``` javascript

let array = [1, 2, 3, 2, 1];
let isPalindrome = true;

for (let i = 0; i < array.length / 2; i++) {
  if (array[i] !== array[array.length - 1 - i]) {
    isPalindrome = false; // If any element doesn't match its counterpart, it's not a palindrome.
    break;
  }
}

if (isPalindrome) {
  console.log("Palindrome");
} else {
  console.log("Not a Palindrome");
}

```
Exercise 20: Pattern Printing 🖼️
Description: Write a program that uses a loop to print a pattern of stars (*) for a given n.
Input: A number n.
Output: A pattern of *.

```javascript


let n = 5; // Number of rows
for (let i = 1; i <= n; i++) {
  console.log("*".repeat(i)); // Repeat the "*" i times for each row
}
```
Exercise 21: Find Largest Odd Number 🔍
Description: Write a program that finds the largest odd number in an array called numbers.
Input: An array of numbers.
Output: The largest odd number. If no odd numbers are found, print "No odd numbers."

```javascript


let numbers = [2, 8, 6, 7, 11, 14];
let largestOdd = null;

for (let i = 0; i < numbers.length; i++) {
  if (numbers[i] % 2 !== 0 && (largestOdd === null || numbers[i] > largestOdd)) {
    largestOdd = numbers[i]; // Update the largest odd number
  }
}

if (largestOdd !== null) {
  console.log("Largest Odd Number:", largestOdd);
} else {
  console.log("No odd numbers");
}
```
Exercise 22: Sum of Digits ➕🔢
Description: Write a program that calculates the sum of the digits of a positive integer.
Input: A positive integer.
Output: The sum of its digits.

```javascript


let number = 12345; // Example input
let sum = 0;

while (number > 0) {
  sum += number % 10; // Add the last digit to the sum
  number = Math.floor(number / 10); // Remove the last digit
}

console.log("Sum of Digits:", sum);
```
Exercise 23: Remove Duplicates from Array 🚫🔁
Description: Write a program that removes duplicate elements from an array called values and prints the resulting array with unique values only.
Input: An array of numbers or strings.
Output: An array with duplicates removed.

```javascript

let values = [1, 2, 2, 3, 4, 4, 5];
let uniqueValues = [];

for (let i = 0; i < values.length; i++) {
  if (!uniqueValues.includes(values[i])) {
    uniqueValues.push(values[i]); // Add to uniqueValues if it's not already included
  }
}

console.log("Unique Values:", uniqueValues);
```
Exercise 24: Word Count in Sentence ✍️
Description: Write a program that counts the number of words in a given sentence.
Input: A sentence as a string.
Output: The total word count.

```javascript


let sentence = "The quick brown fox jumps over the lazy dog";
let words = sentence.split(" "); // Split the sentence into words
console.log("Word Count:", words.length);
```
Exercise 25: Multiplication Table 📊
Description: Write a program that prints the multiplication table of a given number up to 10.
Input: A number.
Output: Its multiplication table.

``` javascript

let number = 5; // Example input

for (let i = 1; i <= 10; i++) {
  console.log(`${number} x ${i} = ${number * i}`);
}
```
Exercise 26: Fibonacci Sequence 🔢➕🔢
Description: Write a program that prints the Fibonacci sequence up to a given number n.
Input: A number n.
Output: The Fibonacci sequence up to n terms.

```javascript

let n = 10; // Example: Print 10 terms
let a = 0, b = 1;

console.log(a); // Print the first term
if (n > 1) console.log(b); // Print the second term

for (let i = 3; i <= n; i++) {
  let next = a + b;
  console.log(next); // Print the next term
  a = b;
  b = next;
}
```
Exercise 27: Count Consonants in String 🔤
Description: Write a program that counts the number of consonants in a given string.
Input: A string.
Output: The total consonant count.

```javascript

let sentence = "Hello World";
let consonants = sentence.match(/[bcdfghjklmnpqrstvwxyz]/gi) || []; // Match all consonants
console.log("Consonant Count:", consonants.length);
````
Exercise 28: Merge and Sort Arrays 🔗📈
Description: Write a program that merges two arrays and sorts the resulting array in ascending order.
Input: Two arrays of numbers.
Output: A single sorted array.

```javascript


let array1 = [3, 1, 4];
let array2 = [6, 2, 5];
let mergedArray = array1.concat(array2).sort((a, b) => a - b); // Merge and sort

console.log("Merged and Sorted Array:", mergedArray);
```
Exercise 29: Factorial Calculator ✖️
Description: Write a program that calculates the factorial of a given number n.
Input: A number n.
Output: The factorial of n.

```javascript


let n = 5; // Example input
let factorial = 1;

for (let i = 1; i <= n; i++) {
  factorial *= i; // Multiply factorial by the current number
}

console.log("Factorial:", factorial);
```
Exercise 30: Check for Anagram 🔄
Description: Write a program that checks if two strings are anagrams of each other.
Input: Two strings.
Output: "Anagram" if they are anagrams, otherwise "Not an Anagram."

```javascript

let str1 = "listen";
let str2 = "silent";

let sortedStr1 = str1.split("").sort().join(""); // Sort the characters
let sortedStr2 = str2.split("").sort().join("");

if (sortedStr1 === sortedStr2) {
  console.log("Anagram");
} else {
  console.log("Not an Anagram");
}
```

Exercise 31: Replace Vowels in String ✏️
Description: Write a program that replaces all vowels in a string with a specific character (e.g., *).
Input: A string and a replacement character.
Output: The modified string.

```javascript


let sentence = "Hello World";
let replacement = "*";
let modifiedSentence = sentence.replace(/[aeiou]/gi, replacement); // Replace vowels with '*'

console.log("Modified String:", modifiedSentence);
```
Exercise 32: Sort Array of Strings by Length 📏
Description: Write a program that sorts an array of strings by their length in ascending order.
Input: An array of strings.
Output: The sorted array.

```javascript

let strings = ["apple", "kiwi", "banana", "cherry"];
strings.sort((a, b) => a.length - b.length); // Sort by length

console.log("Sorted Strings:", strings);
```
Exercise 33: Generate Random Numbers 🎲
Description: Write a program that generates n random numbers within a specified range (min to max).
Input: The range and the number of random numbers to generate.
Output: An array of random numbers.

```javascript

let n = 5; // Number of random numbers
let min = 10;
let max = 50;
let randomNumbers = [];

for (let i = 0; i < n; i++) {
  randomNumbers.push(Math.floor(Math.random() * (max - min + 1)) + min); // Generate random numbers
}

console.log("Random Numbers:", randomNumbers);
````
Exercise 34: Find Longest Word in Sentence 📜
Description: Write a program that finds the longest word in a given sentence.
Input: A sentence.
Output: The longest word.

```javascript

let sentence = "The quick brown fox jumps over the lazy dog";
let words = sentence.split(" ");
let longestWord = "";

for (let word of words) {
  if (word.length > longestWord.length) {
    longestWord = word; // Update the longest word
  }
}

console.log("Longest Word:", longestWord);
````
Exercise 35: Sum of Multiples ➕✖️
Description: Write a program that calculates the sum of all multiples of a given number n up to a limit m.
Input: Two numbers n and m.
Output: The sum of multiples.

```javascript

let n = 3; // Multiple
let m = 10; // Limit
let sum = 0;

for (let i = n; i <= m; i += n) {
  sum += i; // Add multiples of n
}

console.log("Sum of Multiples:", sum);
```
Exercise 36: Swap Two Variables 🔄
Description: Write a program that swaps the values of two variables without using a third variable.
Input: Two numbers.
Output: The swapped values.

```javascript

let a = 5;
let b = 10;

a = a + b;
b = a - b;
a = a - b;

console.log("Swapped Values:", "a =", a, ", b =", b);
```
Exercise 37: Check for Substring 🔍
Description: Write a program that checks if a given substring exists in a string.
Input: A string and a substring.
Output: "Found" if the substring exists, otherwise "Not Found."

```javascript

let string = "Hello, welcome to JavaScript programming!";
let substring = "JavaScript";

if (string.includes(substring)) {
  console.log("Found");
} else {
  console.log("Not Found");
}
```
Exercise 38: Convert Celsius to Fahrenheit 🌡️
Description: Write a program that converts a temperature from Celsius to Fahrenheit.
Input: Temperature in Celsius.
Output: Temperature in Fahrenheit.

``` javascript

let celsius = 25; // Example input
let fahrenheit = (celsius * 9) / 5 + 32; // Conversion formula

console.log(`${celsius}°C is equal to ${fahrenheit}°F`);
```
Exercise 39: Remove All Non-Alphanumeric Characters 🚫
Description: Write a program that removes all non-alphanumeric characters from a string.
Input: A string.
Output: A cleaned string with only alphanumeric characters.

```javascript

let sentence = "Hello, World! Welcome to 2024.";
let cleaned = sentence.replace(/[^a-z0-9]/gi, ""); // Remove non-alphanumeric characters

console.log("Cleaned String:", cleaned);
```
Exercise 40: Power Calculator 🔋
Description: Write a program that calculates the power of a number base raised to the exponent.
Input: A base and an exponent.
Output: The result.

``` javascript

let base = 2;
let exponent = 3;
let result = 1;

for (let i = 0; i < exponent; i++) {
  result *= base; // Multiply base exponent times
}

console.log(`${base}^${exponent} = ${result}`);

```

Exercise 41: Check for Palindrome 🪞
Description: Write a program that checks if a given string is a palindrome (reads the same forward and backward).
Input: A string.
Output: "Palindrome" if the string is a palindrome, otherwise "Not Palindrome."

```javascript

let str = "racecar";
let reversedStr = str.split("").reverse().join("");

if (str === reversedStr) {
  console.log("Palindrome");
} else {
  console.log("Not Palindrome");
```
Exercise 42: Reverse a Number 🔄
Description: Write a program that reverses the digits of a given number.
Input: A number.
Output: The reversed number.

``` javascript

let num = 12345;
let reversedNum = num.toString().split("").reverse().join("");
console.log("Reversed Number:", reversedNum);
Exercise 43: Find Factorial of a Number 🎯
Description: Write a program that calculates the factorial of a given number.
Input: A positive integer n.
Output: The factorial of n.

javascript
Copy code
let n = 5;
let factorial = 1;

for (let i = 1; i <= n; i++) {
  factorial *= i;
}

console.log("Factorial:", factorial);
```
Exercise 44: Find Maximum in Array 🌟
Description: Write a program that finds the maximum number in an array of numbers.
Input: An array of numbers.
Output: The maximum number.

```javascript

let numbers = [3, 5, 7, 2, 8];
let max = Math.max(...numbers);
console.log("Maximum Number:", max);
```
Exercise 45: Remove First Occurrence of Element in Array ❌
Description: Write a program that removes the first occurrence of a specified element from an array.
Input: An array and an element to remove.
Output: The array with the first occurrence of the element removed.

```javascript

let arr = [1, 2, 3, 4, 5, 2];
let element = 2;
let index = arr.indexOf(element);

if (index !== -1) {
  arr.splice(index, 1);
}

console.log("Updated Array:", arr);
```
Exercise 46: Merge Two Arrays 🧩
Description: Write a program that merges two arrays into a single array.
Input: Two arrays.
Output: A merged array.

```javascript

let array1 = [1, 2, 3];
let array2 = [4, 5, 6];
let mergedArray = array1.concat(array2);

console.log("Merged Array:", mergedArray);
```
Exercise 47: Count the Number of Digits in a Number 🔢
Description: Write a program that counts how many digits are in a given number.
Input: A number.
Output: The number of digits in the number.

```javascript

let num = 12345;
let digitCount = num.toString().length;

console.log("Number of Digits:", digitCount);
```
Exercise 48: Calculate Power of a Number (Exponentiation) 💡
Description: Write a program that calculates the power of a number base raised to the exponent exp.
Input: A base and an exponent.
Output: The result of base^exp.

```javascript

let base = 2;
let exp = 3;
let result = Math.pow(base, exp);

console.log("Result:", result);
````
Exercise 49: Find Second Smallest Number in Array 🔍
Description: Write a program that finds the second smallest number in an array.
Input: An array of numbers.
Output: The second smallest number.

```javascript

let numbers = [5, 3, 9, 2, 8];
numbers.sort((a, b) => a - b); // Sort array in ascending order
let secondSmallest = numbers[1]; // Second smallest number

console.log("Second Smallest Number:", secondSmallest);
Exercise 50: Check if a Number is Prime 🔢
Description: Write a program that checks if a number is prime.
Input: A number.
Output: "Prime" if the number is prime, otherwise "Not Prime."

javascript
Copy code
let num = 7;
let isPrime = true;

if (num < 2) {
  isPrime = false;
} else {
  for (let i = 2; i <= Math.sqrt(num); i++) {
    if (num % i === 0) {
      isPrime = false;
      break;
    }
  }
}

console.log(isPrime ? "Prime" : "Not Prime");



```

Exercise 50: Check if a Number is Prime 🔢
Description: Write a program that checks if a number is prime.
Input: A number.
Output: "Prime" if the number is prime, otherwise "Not Prime."

``` javascript
let num = 7;
let isPrime = true;

if (num < 2) {
  isPrime = false;
} else {
  for (let i = 2; i <= Math.sqrt(num); i++) {
    if (num % i === 0) {
      isPrime = false;
      break;
    }
  }
}

console.log(isPrime ? "Prime" : "Not Prime");
```
Exercise 51: Implement Binary Search 🧐
Description: Write a program that implements the binary search algorithm to find an element in a sorted array.
Input: A sorted array and a target element.
Output: The index of the element if found, otherwise -1.

```javascript

function binarySearch(arr, target) {
  let low = 0;
  let high = arr.length - 1;

  while (low <= high) {
    let mid = Math.floor((low + high) / 2);
    
    if (arr[mid] === target) {
      return mid;
    } else if (arr[mid] < target) {
      low = mid + 1;
    } else {
      high = mid - 1;
    }
  }
  
  return -1;
}

let sortedArray = [1, 3, 5, 7, 9, 11, 13];
let target = 7;
console.log(binarySearch(sortedArray, target)); // Output: 3
```
Exercise 52: Merge Sort Algorithm 🧩
Description: Write a program that implements the merge sort algorithm to sort an array of numbers.
Input: An unsorted array of numbers.
Output: A sorted array.

```javascript

function mergeSort(arr) {
  if (arr.length <= 1) {
    return arr;
  }
  
  const middle = Math.floor(arr.length / 2);
  const left = mergeSort(arr.slice(0, middle));
  const right = mergeSort(arr.slice(middle));
  
  return merge(left, right);
}

function merge(left, right) {
  let result = [], leftIndex = 0, rightIndex = 0;
  
  while (leftIndex < left.length && rightIndex < right.length) {
    if (left[leftIndex] < right[rightIndex]) {
      result.push(left[leftIndex]);
      leftIndex++;
    } else {
      result.push(right[rightIndex]);
      rightIndex++;
    }
  }
  
  return result.concat(left.slice(leftIndex), right.slice(rightIndex));
}

let unsortedArray = [4, 1, 3, 9, 7];
console.log(mergeSort(unsortedArray)); // Output: [1, 3, 4, 7, 9]
````
Exercise 53: Find Longest Substring Without Repeating Characters 🔑
Description: Write a program that finds the length of the longest substring without repeating characters in a string.
Input: A string.
Output: The length of the longest substring without repeating characters.

```javascript

function longestSubstring(str) {
  let map = new Map();
  let left = 0;
  let maxLength = 0;

  for (let right = 0; right < str.length; right++) {
    if (map.has(str[right])) {
      left = Math.max(left, map.get(str[right]) + 1);
    }
    map.set(str[right], right);
    maxLength = Math.max(maxLength, right - left + 1);
  }

  return maxLength;
}

let input = "abcabcbb";
console.log(longestSubstring(input)); // Output: 3 ("ABC")
````
Exercise 54: Find All Permutations of a String 🔀
Description: Write a program that finds all the permutations of a given string.
Input: A string.
Output: An array containing all the permutations of the string.

``` javascript

function getPermutations(str) {
  if (str.length === 0) return [''];
  let result = [];
  
  for (let i = 0; i < str.length; i++) {
    let char = str[i];
    let remainingChars = str.slice(0, i) + str.slice(i + 1);
    let permutations = getPermutations(remainingChars);
    
    for (let perm of permutations) {
      result.push(char + perm);
    }
  }
  
  return result;
}

let input = "abc";
console.log(getPermutations(input)); // Output: ['abc', 'acb', 'bac', 'bca', 'cab', 'cba']
```
Exercise 55: Find All Anagrams of a String 🧩
Description: Write a program that finds all anagrams of a given string from a list of words.
Input: A string and a list of words.
Output: A list of anagrams of the string from the provided list.

``` javascript

function findAnagrams(str, words) {
  let sortedStr = str.split('').sort().join('');
  return words.filter(word => word.split('').sort().join('') === sortedStr);
}

let input = "listen";
let wordList = ["enlist", "google", "inlets", "banana"];
console.log(findAnagrams(input, wordList)); // Output: ['enlist', 'inlets']
````
Exercise 56: Fibonacci Sequence Using Recursion 📈
Description: Write a program that generates the Fibonacci sequence up to the n-th number using recursion.
Input: A number n.
Output: The Fibonacci sequence up to the n-th number.

```javascript

function fibonacci(n) {
  if (n <= 1) return n;
  return fibonacci(n - 1) + fibonacci(n - 2);
}

let n = 6;
let sequence = [];
for (let i = 0; i < n; i++) {
  sequence.push(fibonacci(i));
}

console.log(sequence); // Output: [0, 1, 1, 2, 3, 5]
````
Exercise 57: Implement Trie Data Structure 🔠
Description: Write a program that implements a trie data structure to store strings.
Input: A list of strings to insert into the trie.
Output: A trie containing all the strings.

```javascript

class TrieNode {
  constructor() {
    this.children = {};
    this.isEndOfWord = false;
  }
}

class Trie {
  constructor() {
    this.root = new TrieNode();
  }

  insert(word) {
    let node = this.root;
    for (let char of word) {
      if (!node.children[char]) {
        node.children[char] = new TrieNode();
      }
      node = node.children[char];
    }
    node.isEndOfWord = true;
  }

  search(word) {
    let node = this.root;
    for (let char of word) {
      if (!node.children[char]) {
        return false;
      }
      node = node.children[char];
    }
    return node.isEndOfWord;
  }
}

let trie = new Trie();
trie.insert("hello");
trie.insert("world");
console.log(trie.search("hello")); // Output: true
console.log(trie.search("world")); // Output: true
console.log(trie.search("hell"));  // Output: false
```
Exercise 58: Implement a LRU Cache 🧳
Description: Write a program that implements a Least Recently Used (LRU) cache.
Input: A cache size and a list of key-value pairs to insert into the cache.
Output: The cache state after each operation.

```javascript

class LRUCache {
  constructor(capacity) {
    this.capacity = capacity;
    this.cache = new Map();
  }

  get(key) {
    if (!this.cache.has(key)) {
      return -1;
    }
    const value = this.cache.get(key);
    this.cache.delete(key);
    this.cache.set(key, value);
    return value;
  }

  put(key, value) {
    if (this.cache.size >= this.capacity) {
      this.cache.delete(this.cache.keys().next().value);
    }
    this.cache.set(key, value);
  }
}

let cache = new LRUCache(2);
cache.put(1, 1);
cache.put(2, 2);
console.log(cache.get(1)); // Output: 1
cache.put(3, 3);
console.log(cache.get(2)); // Output: -1 (removed due to capacity)
````
Exercise 59: Dijkstra’s Shortest Path Algorithm 🛣️
Description: Write a program that implements Dijkstra's algorithm to find the shortest path in a graph.
Input: A weighted graph and a starting node.
Output: The shortest path from the start node to every other node.

```javascript

function dijkstra(graph, start) {
  let distances = {};
  let pq = new PriorityQueue();

  for (let node in graph) {
    distances[node] = Infinity;
  }
  distances[start] = 0;
  pq.enqueue(start, 0);

  while (!pq.isEmpty()) {
    let node = pq.dequeue().element;

    graph[node].forEach(neighbor => {
      let alt = distances[node] + neighbor.weight;
      if (alt < distances[neighbor.node]) {
        distances[neighbor.node] = alt;
        pq.enqueue(neighbor.node, alt);
      }
    });
  }

  return distances;
}

// PriorityQueue is a custom implementation for managing the queue of nodes

let graph = {
  A: [{node: 'B', weight: 1}, {node: 'C', weight: 4}],
  B: [{node: 'A', weight: 1}, {node: 'C', weight: 2}, {node: 'D', weight: 5}],
  C: [{node: 'A', weight: 4}, {node: 'B', weight: 2}, {node: 'D', weight: 1}],
  D: [{node: 'B', weight: 5}, {node: 'C', weight: 1}]
};

console.log(dijkstra(graph, 'A'));

```

# 💻💻💻💻💻💻💻
# create a more advanced CRUD (Create, Read, Update, Delete) application with HTML, JavaScript, and CSS, let's build a user management system that allows users to:

### Add new users (Create)
### Display a list of users (Read)
### Edit user details (Update)
### Delete users (Delete)
The users will have basic details like name, email, and phone number. The application will allow the user to interact with the page directly through a simple web interface.

Advanced CRUD Application with HTML, JavaScript, and CSS
### 1. HTML (index.html): The Structure
The HTML file will provide the structure of our web page, including the form to add new users, a table to display the users, and buttons to update or delete user details.

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>User Management System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>User Management System</h1>
        
        <!-- Form to add new users -->
        <div class="form-container">
            <input type="text" id="name" placeholder="Enter Name" required>
            <input type="email" id="email" placeholder="Enter Email" required>
            <input type="text" id="phone" placeholder="Enter Phone Number" required>
            <button onclick="addUser()">Add User</button>
        </div>

        <h2>User List</h2>
        <table id="userTable">
            <thead>
                <tr>
                    <th>Name</th>
                    <th>Email</th>
                    <th>Phone</th>
                    <th>Actions</th>
                </tr>
            </thead>
            <tbody>
                <!-- User rows will be added here dynamically -->
            </tbody>
        </table>
    </div>

    <script src="app.js"></script>
</body>
</html>
```
### 2. CSS (styles.css): The Styling
The CSS file will provide styling to make the web page look better. It will format the form, the table, and buttons.

```css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    text-align: center;
    color: #444;
}

.form-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
}

input {
    padding: 8px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

table, th, td {
    border: 1px solid #ddd;
}

th, td {
    padding: 10px;
    text-align: center;
}

button.edit, button.delete {
    padding: 5px 10px;
    margin: 0 5px;
}

button.edit {
    background-color: #ff9800;
}

button.delete {
    background-color: #f44336;
}
```
### 3. JavaScript (app.js): The Logic
The JavaScript file will contain the logic to perform CRUD operations. It will handle the actions such as adding a user, displaying the user list, editing user information, and deleting users.

```javascript

// Sample user data (could be stored in localStorage or a database in real scenarios)
let users = [];

// Function to add a new user
function addUser() {
    const name = document.getElementById('name').value;
    const email = document.getElementById('email').value;
    const phone = document.getElementById('phone').value;

    // Input validation
    if (!name || !email || !phone) {
        alert("All fields are required!");
        return;
    }

    // Create a new user object
    const newUser = {
        id: Date.now(),  // Generate unique ID using timestamp
        name: name,
        email: email,
        phone: phone
    };

    // Add new user to the list
    users.push(newUser);

    // Clear input fields
    document.getElementById('name').value = '';
    document.getElementById('email').value = '';
    document.getElementById('phone').value = '';

    // Re-render the user list
    renderUserList();
}

// Function to render the user list
function renderUserList() {
    const tableBody = document.querySelector('#userTable tbody');
    tableBody.innerHTML = ''; // Clear the table before re-rendering

    users.forEach(user => {
        const row = document.createElement('tr');
        
        // Create table cells
        row.innerHTML = `
            <td>${user.name}</td>
            <td>${user.email}</td>
            <td>${user.phone}</td>
            <td>
                <button class="edit" onclick="editUser(${user.id})">Edit</button>
                <button class="delete" onclick="deleteUser(${user.id})">Delete</button>
            </td>
        `;
        tableBody.appendChild(row);
    });
}

// Function to edit a user
function editUser(id) {
    const user = users.find(user => user.id === id);
    if (user) {
        document.getElementById('name').value = user.name;
        document.getElementById('email').value = user.email;
        document.getElementById('phone').value = user.phone;

        // Remove the user from the list and allow updating
        deleteUser(id);
    }
}

// Function to delete a user
function deleteUser(id) {
    users = users.filter(user => user.id !== id); // Remove user with matching ID
    renderUserList(); // Re-render the list after deletion
}

// Initial render when the page loads
window.onload = renderUserList;
```
How the CRUD Application Works:
### Create:

Users can be added by filling out the form and clicking the "Add User" button. The data is stored in an array, and the table is updated to show the new user.
### Read:

The list of users is displayed in a table below the form. Each user is shown with their name, email, phone number, and actions (Edit/Delete).
### Update:

When a user clicks the "Edit" button next to a user, their information is pre-filled in the input fields. The user can update the details, and the old data is removed when they are edited.
### Delete:

-Users can be deleted by clicking the "Delete" button next to their name. This removes the user from the list.
### Key Features of the Advanced CRUD Application:
### Dynamic Table Rendering: 
The list of users is dynamically updated each time a user is added, edited, or deleted.
Input Validation: Ensures that all fields are filled before a new user is added.
Edit and Delete: Each user can be edited or deleted individually with their respective buttons.
Unique User IDs: Uses the timestamp (Date.now()) to generate a unique ID for each user.
Clear Form After Adding: After submitting the form, it clears the input fields for a smoother user experience.
#Conclusion:
This CRUD application is a more advanced implementation of user management, combining HTML, CSS, and JavaScript to create a fully functional user management system. It allows you to add, view, edit, and delete users in a seamless and interactive way. This basic system can later be extended by adding persistence (e.g., saving users to localStorage, or integrating with a backend server).


# ➡️➡️➡️➡️➡️➡️➡️➡️➡️➡️
# create an advanced CRUD application where a user can:

### Add a product with a name, description, and price.
### Like a product.
### Comment on a product.
### Send a message to the seller.
This application will involve a basic structure using HTML, CSS, and JavaScript. Each product can be liked and commented on, and users can send messages to the seller.

##1. HTML (index.html): The Structure
```html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Management System</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <div class="container">
        <h1>Product Management System</h1>
        
        <!-- Form to add new product -->
        <div class="form-container">
            <input type="text" id="productName" placeholder="Product Name" required>
            <input type="text" id="productDescription" placeholder="Product Description" required>
            <input type="number" id="productPrice" placeholder="Product Price" required>
            <button onclick="addProduct()">Add Product</button>
        </div>

        <h2>Product List</h2>
        <div id="productList"></div>
    </div>

    <script src="app.js"></script>
</body>
</html>
```
### 2. CSS (styles.css): The Styling
```css

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f4;
    color: #333;
}

.container {
    width: 80%;
    margin: 0 auto;
    padding: 20px;
    background-color: white;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

h1, h2 {
    text-align: center;
    color: #444;
}

.form-container {
    display: flex;
    justify-content: center;
    gap: 10px;
    margin-bottom: 20px;
}

input {
    padding: 8px;
    font-size: 16px;
    border: 1px solid #ccc;
    border-radius: 4px;
}

button {
    padding: 10px 20px;
    background-color: #4CAF50;
    color: white;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}

button:hover {
    background-color: #45a049;
}

.product-card {
    border: 1px solid #ddd;
    margin: 10px;
    padding: 20px;
    border-radius: 8px;
    background-color: #fff;
}

.product-card h3 {
    margin: 0;
    font-size: 18px;
}

.product-card p {
    font-size: 14px;
}

.product-actions button {
    margin: 5px;
}

.comment-section {
    margin-top: 10px;
}

.comment-section input {
    margin-right: 10px;
    padding: 5px;
}

.product-card .likes {
    margin-top: 10px;
}

button.like {
    background-color: #f44336;
}

button.comment {
    background-color: #ff9800;
}

button.message {
    background-color: #2196F3;
}
```
### 3. JavaScript (app.js): The Logic
 the JavaScript that handles the CRUD operations, including liking, commenting, and messaging.

``` javascript

let products = [];

// Function to add a product
function addProduct() {
    const name = document.getElementById('productName').value;
    const description = document.getElementById('productDescription').value;
    const price = document.getElementById('productPrice').value;

    if (!name || !description || !price) {
        alert("Please fill out all fields.");
        return;
    }

    const newProduct = {
        id: Date.now(),
        name: name,
        description: description,
        price: price,
        likes: 0,
        comments: [],
        messages: []
    };

    products.push(newProduct);
    document.getElementById('productName').value = '';
    document.getElementById('productDescription').value = '';
    document.getElementById('productPrice').value = '';

    renderProducts();
}

// Function to render all products
function renderProducts() {
    const productList = document.getElementById('productList');
    productList.innerHTML = '';

    products.forEach(product => {
        const productCard = document.createElement('div');
        productCard.classList.add('product-card');
        productCard.innerHTML = `
            <h3>${product.name}</h3>
            <p>${product.description}</p>
            <p>Price: $${product.price}</p>
            <div class="product-actions">
                <button class="like" onclick="likeProduct(${product.id})">Like (${product.likes})</button>
                <button class="comment" onclick="toggleCommentSection(${product.id})">Comment</button>
                <button class="message" onclick="sendMessage(${product.id})">Send Message</button>
            </div>
            <div class="comment-section" id="commentSection-${product.id}" style="display:none;">
                <input type="text" id="commentInput-${product.id}" placeholder="Add a comment">
                <button onclick="addComment(${product.id})">Add Comment</button>
                <ul id="commentsList-${product.id}">
                    ${product.comments.map(comment => `<li>${comment}</li>`).join('')}
                </ul>
            </div>
            <div class="message-section" id="messageSection-${product.id}" style="display:none;">
                <input type="text" id="messageInput-${product.id}" placeholder="Send a message to the seller">
                <button onclick="sendProductMessage(${product.id})">Send Message</button>
                <ul id="messageList-${product.id}">
                    ${product.messages.map(message => `<li>${message}</li>`).join('')}
                </ul>
            </div>
        `;

        productList.appendChild(productCard);
    });
}

// Function to like a product
function likeProduct(id) {
    const product = products.find(p => p.id === id);
    if (product) {
        product.likes++;
        renderProducts();
    }
}

// Function to toggle the comment section visibility
function toggleCommentSection(id) {
    const commentSection = document.getElementById(`commentSection-${id}`);
    commentSection.style.display = commentSection.style.display === 'none' ? 'block' : 'none';
}

// Function to add a comment to a product
function addComment(id) {
    const commentInput = document.getElementById(`commentInput-${id}`);
    const comment = commentInput.value.trim();

    if (comment) {
        const product = products.find(p => p.id === id);
        if (product) {
            product.comments.push(comment);
            commentInput.value = '';
            renderProducts();
        }
    } else {
        alert("Please enter a comment.");
    }
}

// Function to send a message to the seller
function sendMessage(id) {
    const messageSection = document.getElementById(`messageSection-${id}`);
    messageSection.style.display = messageSection.style.display === 'none' ? 'block' : 'none';
}

// Function to send a product message
function sendProductMessage(id) {
    const messageInput = document.getElementById(`messageInput-${id}`);
    const message = messageInput.value.trim();

    if (message) {
        const product = products.find(p => p.id === id);
        if (product) {
            product.messages.push(message);
            messageInput.value = '';
            renderProducts();
        }
    } else {
        alert("Please enter a message.");
    }
}

// Initial render when the page loads
window.onload = renderProducts;
```
# How the Application Works:
### Adding a Product:

Users can input a product’s name, description, and price, and then add it by clicking the "Add Product" button. The product is saved in the products array and displayed in the product list.
Liking a Product:

Users can click the "Like" button to increase the like count for a product. Each click will increment the like count and update the display.
Commenting on a Product:

By clicking the "Comment" button, a comment section will appear where users can add comments. Once a comment is added, it will be displayed under the product.
Sending a Message to the Seller:

Users can click the "Send Message" button to send a message to the product's seller. A message input field will appear where users can type their message, which will be added to a list of messages for the product.
## Key Features:
Dynamic Product List: Products are added dynamically and can be liked, commented on, and messaged.
Likes: Each product has a like button, and the number of likes increases as the button is clicked.
Comments: Each product allows users to add comments. Comments are displayed below each product.
Messages: Users can send messages to the seller for each product, and the messages are displayed under the product's details.
This is an advanced CRUD application that integrates multiple functionalities (like, comment, and send message) to manage products. It uses HTML, CSS, and JavaScript for the front-end functionality, and you could further enhance it by adding local storage, database connectivity, or backend integration for persistence.
🎉  🏁

