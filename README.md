# Basic Calculator Program

## Description
This is a simple command-line calculator program written in C. It allows users to perform basic arithmetic operations such as addition, subtraction, multiplication, and division.

## Features
- Supports four basic operations: Addition (+), Subtraction (-), Multiplication (*), and Division (/)
- Takes user input for operator selection and two numbers
- Handles division by zero with an appropriate error message
- Displays results with two decimal precision

## How to Use
1. Compile the program using a C compiler (e.g., GCC):
   ```sh
   gcc calculator.c -o calculator
   ```
2. Run the compiled executable:
   ```sh
   ./calculator
   ```
3. Enter an operator when prompted ( +, -, *, / ).
4. Enter two numbers when prompted.
5. The program will display the result of the operation.

## Example Usage
```
Enter an operator (+, -, *, /): +
Enter two numbers: 5 3
5.00 + 3.00 = 8.00
```

## Error Handling
- If an invalid operator is entered, the program displays: "Invalid operator. Please use +, -, *, or /."
- If the user attempts division by zero, the program displays: "Error: Division by zero is not allowed."

## Requirements
- C compiler (GCC or equivalent)
- Basic knowledge of running command-line applications

## Author
Abir Mal
