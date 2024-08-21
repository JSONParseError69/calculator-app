# Calculator App

## Overview

This project is a simple JavaScript-based calculator that can perform basic arithmetic operations like addition, subtraction, multiplication, and division. The calculator is built using object-oriented programming principles, ensuring clear and maintainable code. The user interface (UI) is designed with HTML and CSS, while the calculator's functionality is handled by JavaScript.

## Features

- Basic Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
- Clear: Reset the calculator to its default state.
  -Delete: Remove the last entered digit.
- Real-Time Display: Updates the display as numbers are inputted or operations are performed.
- Decimal Support: Handles decimal numbers and ensures correct input format.

## Files

- index.html: Contains the structure of the calculator UI.
- style.css: Styles the calculator interface.
- script.js: Contains the JavaScript code to manage calculator operations.

## Code Explanation

## Calculator Class

The Calculator class manages the state and functionality of the calculator.

- constructor(previousOperandTextElement, currentOperandTextElement): Initializes the calculator with elements for displaying the previous and current operands.

- clear(): Resets all variables to their default state.

- delete(): Removes the last digit from the current operand.

- appendNumber(number): Adds a number or decimal point to the current operand.

- chooseOperation(operation): Chooses the operation (addition, subtraction, multiplication, or division) and prepares the calculator to compute the result.

- compute(): Performs the selected arithmetic operation and updates the display with the result.

- getDisplayNumber(number): Formats the number for display, adding commas as necessary and preserving decimal points.

- updateDisplay(): Updates the calculator’s display based on the current state.

## Event Listeners

- numberButtons: Adds event listeners to all number buttons to append digits to the current operand.

- operationButtons: Adds event listeners to all operation buttons to select the operation to be performed.

- equalsButton: Computes and displays the result when the equals button is clicked.

- allClearButton: Resets the calculator when the "AC" button is clicked.

- deleteButton: Removes the last digit when the "DEL" button is clicked.

## Usage

1. Clone or download the project.
2. Open the index.html file in your browser.
3. Use the on-screen buttons to perform calculations.

## Future Enhancements

- Keyboard Support: Allow users to use their keyboard for input.
- Additional Operations: Implement more advanced mathematical operations like square root, exponentiation, etc.
- Memory Functions: Include memory storage functions to save and recall previous calculations.

## License

This project is open-source and available under the MIT License. You are free to use, modify, and distribute this code as per the terms of the license.
