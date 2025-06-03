
---

# Java Custom Exception Example — Throw and Throws

## Description

This project demonstrates how to create and use a **custom exception** in Java, specifically showing the use of `throw` and `throws` keywords. It models an age verification system where an exception is thrown if the user is underage.

## Features

* Defines a custom checked exception class `AgeException`.
* Uses `throws` in method signature to declare the exception.
* Throws an `AgeException` if the age is less than 18.
* Handles the custom exception in the `main` method using a try-catch block.
* Demonstrates clean separation of error checking logic and exception handling.

## Code Structure

* `AgeException` class: Custom exception extending `Exception` with a message constructor.
* `ThrowThrowsExample` class:

  * `checkAge(int age)` method that throws `AgeException` if the age is less than 18.
  * `main` method where `checkAge` is called and exceptions are caught.

## How to Run

1. Compile the class:

   ```bash
   javac Concepts/ThrowThrowsExample.java
   ```

2. Run the program:

   ```bash
   java Concepts.ThrowThrowsExample
   ```

3. Expected output:

   ```
   Exception caught: You must be at least 18 years old.
   ```

## Requirements

* Java JDK 8 or above
* Understanding of Java exceptions, throw, and throws keywords

## Notes

* This example highlights how custom exceptions improve code readability and control flow.
* It also shows how to enforce business rules (like age restriction) using exceptions.

