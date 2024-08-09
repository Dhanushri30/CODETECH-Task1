Name:Dhanushri M
Company:CODETECH IT SOLUTIONS
ID:CT21DS4851
Domain:Python Programming
Duration:July to August 2024

PROJECT OVERVIEW

1. Function Definitions
add(x, y): Returns the sum of x and y.
subtract(x, y): Returns the difference between x and y.
multiply(x, y): Returns the product of x and y.
divide(x, y): Returns the quotient of x and y, unless y is 0. If y is 0, it returns an error message "Error! Division by zero." to prevent division by zero.
2. calculator() Function
Menu Display:
The function first prints a menu that lists four operations: Add, Subtract, Multiply, and Divide, corresponding to the choices 1, 2, 3, and 4.
User Input:
The user is prompted to enter a choice (1/2/3/4) to select the desired operation.
If the input is valid (i.e., one of '1', '2', '3', or '4'), the program then asks the user to input two numbers (num1 and num2), which are converted to floating-point numbers.
Operation Execution:
Based on the user's choice:
If the user selects '1', the add function is called with num1 and num2 as arguments, and the result is printed.
If the user selects '2', the subtract function is called, and the result is printed.
If the user selects '3', the multiply function is called, and the result is printed.
If the user selects '4', the divide function is called, and the result is printed.
Invalid Input Handling:
If the user enters an invalid choice (anything other than '1', '2', '3', or '4'), the program prints "Invalid Input".
3. Program Flow
The program runs the calculator() function, presenting the user with options and handling their input.
It performs the requested operation and displays the result.
The program also includes basic error handling for invalid menu choices and division by zero.
Example Interactions:
Addition:
If the user chooses '1', enters 5 and 3, the program will output: 5.0 + 3.0 = 8.0.
Division by Zero:
If the user chooses '4' for division and enters 10 and 0, the program will output: 10.0 / 0.0 = Error! Division by zero.
Conclusion:
The code is a simple, user-friendly calculator that provides essential arithmetic functions with basic error handling, making it a good starting point for beginners learning Python.
