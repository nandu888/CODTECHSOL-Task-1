# CODTECHSOL-Task-1
NAME : Nandu Chandragiri
Company : CODTECH IT SOLUTIONS
ID : CT12WDRD
DOMAIN : JAVA PROGRAMMING
DURATION :DEC TO MARCH 2025
MENTOR : Neela Santhosh Kumar
**OVERVIEW OF THE PROJECT**
**project :To Build  Basic Calculator using Java Programming**
The provided Java code defines a class BasicCalculator that implements a simple calculator program. Here's an overview of its functionality:

**Components:**

**_Scanner:_** Imports the Scanner class to get user input from the console.
**_Welcome Message:_** Prints a welcome message and a separator line.
**_Input:_**
Prompts the user to enter two numbers (num1 and num2) using Scanner.
**_Operation Selection:_**
Prompts the user to choose an operation from a menu (addition, subtraction, multiplication, division, and modulo).
Uses Scanner to read the user's choice (choice).
**_Calculation:_**
Uses a switch statement to perform the selected operation based on the choice value:
Case 1: Addition (num1 + num2)
Case 2: Subtraction (num1 - num2)
Case 3: Multiplication (num1 * num2)
Case 4: Modulo (num1 % num2)
Case 5: Division (num1 / num2) with error handling for division by zero.
Prints the calculated result.
**Error Handling:**__
The division case checks for division by zero and displays an error message if encountered.
The default case handles invalid user choices for operations.
Closing Scanner: Closes the Scanner object to release resources.
Overall, this code provides a basic calculator functionality with essential arithmetic operations and division by zero error handling.

**___Here are some potential improvements:_**__**

**Enhance user experience:**
Provide a more user-friendly menu for operation selection (e.g., using characters like '+' instead of numbers).
Allow for multiple calculations in a single session.
