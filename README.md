# Null Value Handling Bug in JavaScript Function

This repository demonstrates a common bug in JavaScript functions: incorrect handling of null values passed as parameters.

## Bug Description

The `foo` function is intended to add two numbers. However, it incorrectly handles null values, returning null instead of a more appropriate value (e.g., 0, or throwing an error).

## Bug Reproduction

1. Clone this repository.
2. Open `bug.js`.
3. Run the JavaScript code.
4. Observe the unexpected null return values when null is passed as parameter.