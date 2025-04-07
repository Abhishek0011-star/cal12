# cal12
C Calculator
This is a simple calculator program written in C. It performs basic arithmetic operations such as addition, subtraction, multiplication, and division. The program runs in the terminal and allows the user to input two numbers and an operator.

Features
Addition (+)

Subtraction (-)

Multiplication (*)

Division (/) with zero division error handling

How It Works
The user is prompted to enter an operator.

The user is then prompted to enter two numbers.

The program performs the selected operation and displays the result.

If the division operator is selected and the second number is zero, the program displays an error message.

Getting Started
Prerequisites
To compile and run this program, you need:

A C compiler (e.g., GCC)

Compilation
Use the terminal to compile the program:gcc calculator.c -o calculator
Running the Program
Once compiled, run the executable:

bash
Copy
Edit
./calculator
Sample Output
cpp
Copy
Edit
Enter an operator (+, -, *, /): +
Enter two numbers: 5 3
5.00 + 3.00 = 8.00
