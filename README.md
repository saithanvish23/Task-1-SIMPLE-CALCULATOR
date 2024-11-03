# Task-1-SIMPLE-CALCULATOR

This Java code represents a simple console-based calculator that allows users to perform basic arithmetic operations: addition, subtraction, multiplication, and division. Here’s a detailed breakdown of the code and its key points:

### Key Points and Code Explanation

1. **User Input Handling**:
   - The program uses the `Scanner` class to capture user inputs, which include two numbers and a choice of arithmetic operation.
   - The input prompts make it clear what the user needs to enter at each step.

2. **Prompting for Two Numbers**:
   - The program first asks the user to enter two numbers, which are stored as `num1` and `num2`.
   - These numbers are read as `double` values to support both integer and floating-point arithmetic.

3. **Displaying Operations Menu**:
   - After the numbers are entered, a menu displays four arithmetic operations:
     - 1: Addition
     - 2: Subtraction
     - 3: Multiplication
     - 4: Division
   - This menu guides the user to select the desired operation by entering a corresponding number (1, 2, 3, or 4).

4. **User's Choice of Operation**:
   - The program then reads the user’s choice, stored as an integer in `choice`.

5. **Switch-Case for Operation Execution**:
   - A `switch` statement executes the selected operation based on the user’s choice:
     - **Case 1**: Performs addition (`num1 + num2`).
     - **Case 2**: Performs subtraction (`num1 - num2`).
     - **Case 3**: Performs multiplication (`num1 * num2`).
     - **Case 4**: Checks for division by zero before performing division (`num1 / num2`). If `num2` is zero, the program outputs an error message to avoid division by zero and sets `validOperation` to `false`.
     - **Default Case**: If the user enters a number other than 1–4, the program outputs an invalid choice message and sets `validOperation` to `false`.

6. **Displaying the Result**:
   - If `validOperation` is `true`, the result of the chosen operation is displayed.
   - If an invalid operation was selected, or if there was an attempt to divide by zero, the result is not displayed.

7. **Resource Management**:
   - After all operations, `scanner.close()` is called to close the `Scanner` object, freeing system resources.

### Summary
This code is a basic calculator program that allows users to perform one of four arithmetic operations on two numbers entered via the console. It includes simple error handling for invalid choices and division by zero, enhancing user experience and preventing runtime errors. The program uses a `switch` statement for concise branching logic based on the user’s choice.


![Screenshot 2024-11-03 180856](https://github.com/user-attachments/assets/baf9c651-74b3-4422-9280-9039ca1e9d76)

