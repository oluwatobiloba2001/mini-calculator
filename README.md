# Arithmetic Calculator in JavaScript

This project demonstrates a simple arithmetic calculator implemented in JavaScript. It includes functions to perform basic mathematical operations such as addition, subtraction, multiplication, division, squaring a number, and finding the square root of a number.

## Table of Contents

- [Features](#features)
- [Usage](#usage)
- [Functions](#functions)
- [Examples](#examples)
- [How to Run](#how-to-run)
- [License](#license)

---

## Features

- **Addition**: Calculate the sum of two numbers.
- **Subtraction**: Calculate the difference between two numbers.
- **Multiplication**: Calculate the product of two numbers.
- **Division**: Calculate the quotient of two numbers with error handling for division by zero.
- **Square**: Calculate the square of a number.
- **Square Root**: Calculate the square root of a number.

---

## Usage

This code is a utility for basic arithmetic operations. It is suitable for educational purposes, small-scale applications, or as a reference for implementing mathematical functions in JavaScript.

---

## Functions

### `calculateSum(num1, num2)`
- **Description**: Adds two numbers and returns the sum.
- **Parameters**: 
  - `num1` (number): The first number.
  - `num2` (number): The second number.

### `calculateDifference(num1, num2)`
- **Description**: Subtracts the second number from the first and returns the difference.
- **Parameters**: 
  - `num1` (number): The first number.
  - `num2` (number): The second number.

### `calculateProduct(num1, num2)`
- **Description**: Multiplies two numbers and returns the product.
- **Parameters**: 
  - `num1` (number): The first number.
  - `num2` (number): The second number.

### `calculateQuotient(num1, num2)`
- **Description**: Divides the first number by the second and returns the quotient. Returns an error message if division by zero is attempted.
- **Parameters**: 
  - `num1` (number): The numerator.
  - `num2` (number): The denominator.

### `calculateSquare(num)`
- **Description**: Calculates and returns the square of a number.
- **Parameters**: 
  - `num` (number): The input number.

### `calculateSquareRoot(num)`
- **Description**: Calculates and returns the square root of a number.
- **Parameters**: 
  - `num` (number): The input number.

---

## Examples

```javascript
console.log(calculateSum(2, 5)); // Output: 7
console.log(calculateDifference(22, 5)); // Output: 17
console.log(calculateProduct(13, 5)); // Output: 65
console.log(calculateQuotient(7, 11)); // Output: 0.6363636363636364
console.log(calculateQuotient(3, 0)); // Output: Error: Division by zero
console.log(calculateSquare(9)); // Output: 81
console.log(calculateSquareRoot(25)); // Output: 5
