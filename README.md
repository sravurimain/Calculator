# Simple Calculator (C++)

This C++ program implements a basic calculator that can perform addition, subtraction, multiplication, and division operations on two numbers.

## Features

- Basic arithmetic operations: +, -, *, /
- Error handling for invalid inputs and division by zero
- Option to perform multiple calculations

## How to Run

1. Ensure you have a C++ compiler installed on your system (e.g., g++).
2. Clone this repository or download the `calculator.cpp` file.
3. Open a terminal or command prompt and navigate to the directory containing the file.
4. Compile the code using the following command:

   ```
   g++ calculator.cpp -o calculator
   ```

5. Run the compiled program using:

   ```
   ./calculator
   ```

## How to Use

Follow the on-screen prompts to enter numbers and choose operations. The calculator will display the result and ask if you want to perform another calculation.

## Example Usage

```
Enter first number: 10
Enter operation (+, -, *, /): +
Enter second number: 5
Result: 15

Do you want to perform another calculation? (y/n): y

Enter first number: 20
Enter operation (+, -, *, /): /
Enter second number: 4
Result: 5

Do you want to perform another calculation? (y/n): n
Thank you for using the calculator!
```

## Error Handling

The calculator includes error handling for common issues:

- Division by zero
- Invalid operators
- Non-numeric input

Example of error handling:

```
Enter first number: 10
Enter operation (+, -, *, /): /
Enter second number: 0
Error: Division by zero!

Do you want to perform another calculation? (y/n): y

Enter first number: 15
Enter operation (+, -, *, /): %
Error: Invalid operator!

Do you want to perform another calculation? (y/n): n
Thank you for using the calculator!
```
