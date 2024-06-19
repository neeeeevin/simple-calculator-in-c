# simple-calculator-in-c
This C program demonstrates how to create a simple calculator using the switch statement. The calculator can perform basic arithmetic operations such as addition, subtraction, multiplication, and division based on user input. Additionally, it includes an option to exit the program.

Key Features:

User Input for Operator and Operands: The program prompts the user to enter an arithmetic operator (+, -, *, /) and two operands.

Arithmetic Operations: Depending on the operator entered by the user, the program performs the corresponding arithmetic operation.

Exit Option: The program will terminate when the user inputs the character 'x'.

Error Handling: If the user enters an invalid operator, the program displays an error message.

How It Works:
The program runs in an infinite loop using while (1), allowing continuous operation until the user decides to exit.
The user is prompted to enter an operator. If the user inputs 'x', the program terminates using exit(0).
If a valid operator is entered, the user is then prompted to input two operands.
Using a switch statement, the program performs the operation corresponding to the entered operator and displays the result.
If an invalid operator is entered, the program displays an error message.


Example Usage:
Enter an operator (+, -, *, /), if you want to exit press x: +
Enter the first and second operand: 5 3
Output: 5.0 + 3.0 = 8.0
