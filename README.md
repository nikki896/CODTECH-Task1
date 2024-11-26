**Name:** Nikki Chauhan  
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT08D10325  
**Domain:** PYTHON PROGRAMMING  
**Duration:** November to December 2024  
**Mentor:** Neela Santhosh Kumar

# Project Overview: Basic Calculator in Python

## Objective:
- **Provide a Simple Arithmetic Tool:** Create a basic calculator that allows users to perform fundamental arithmetic operations (addition, subtraction, multiplication, division).

## Output:
![image](https://github.com/user-attachments/assets/aacf1c6b-d819-47b8-8107-3382fe05e6bb)



## Key Activities:

1. **Design the User Interface:**
   - Display a menu with arithmetic operations.
   - Prompt the user to select an operation.

2. **Input Validation:**
   - Ensure the user's selection is valid (i.e., one of the four supported operations).
   - Handle invalid selections by displaying an appropriate error message.

3. **Accept User Input for Numbers:**
   - Prompt the user to input two numbers for the arithmetic operation.
   - Convert the input strings to floating-point numbers for accurate arithmetic calculations.

4. **Perform Arithmetic Operations:**
   - Based on the user's selection, perform the corresponding arithmetic operation:
     - **Addition:** Add the two numbers.
     - **Subtraction:** Subtract the second number from the first.
     - **Multiplication:** Multiply the two numbers.
     - **Division:** Divide the first number by the second, with a check to prevent division by zero.

5. **Display Results:**
   - Output the result of the arithmetic operation to the user in a clear and concise manner.

6. **Implement Error Handling:**
   - Check for and handle division by zero by displaying an error message and terminating the calculation.
   - Handle non-numeric inputs gracefully by validating input before performing operations.

## Detailed Steps:

1. **Display Menu:**
   - Print a list of operations (Addition, Subtraction, Multiplication, Division).

2. **User Selection:**
   - Use `input()` to capture the user's choice.
   - Validate the choice to ensure it is one of the allowed options (1, 2, 3, 4).

3. **Number Input:**
   - Prompt the user to enter two numbers.
   - Convert these inputs to `float` to handle decimal numbers.

4. **Operation Execution:**
   - Use conditional statements (`if`, `elif`) to execute the corresponding arithmetic operation based on the user's choice.
   - Check for division by zero before performing division.

5. **Result Display:**
   - Print the result of the calculation using formatted strings for clarity.

6. **Error Handling:**
   - Ensure the program handles invalid choices gracefully by providing appropriate feedback.
   - Implement checks for division by zero and provide an error message when detected.

## Expected Outcomes:
- Users will be able to perform basic arithmetic operations easily.
- The program will provide immediate feedback on the results of operations.
- The program will handle invalid inputs gracefully, ensuring a smooth user experience.

## Future Enhancements:
- Extend the calculator to handle more complex operations (e.g., exponentiation, square roots).
- Add functionality for continuous calculations without restarting the program.
- Implement a graphical user interface (GUI) for improved usability.

This project serves as a fundamental exercise in user interaction, input validation, and error handling in Python, providing a foundation for more advanced programming tasks.
