# Calculator Application Documentation

## Overview
This project is a basic calculator application built using Python's tkinter library. It allows users to perform simple arithmetic operations such as addition, subtraction, multiplication, and division.

## Features
Basic Arithmetic Operations: Supports addition, subtraction, multiplication, and division.
Dynamic Input: Buttons to input numbers and operators.
Expression Evaluation: Evaluates mathematical expressions entered by the user.
Clear Functionality: Clears the current input or result.
Error Handling: Displays "Error" for invalid expressions.

## User Interface
Entry Field: Displays the current input and results.
Buttons:
Number Buttons (0-9): For numerical input.
Operator Buttons (+, -, *, /): To specify arithmetic operations.
Dot (.): For decimal numbers.
Equals (=): Evaluates the entered expression.
Clear (C): Clears the entry field.

## Code Structure
### Functions:
button_click(value): Inserts the clicked button's value into the entry field.
evaluate_expression(): Evaluates the mathematical expression entered in the field.
clear_entry(): Clears the entry field.
### GUI Layout:
Entry widget for input and results.
Buttons arranged in a grid layout.
