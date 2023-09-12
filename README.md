# Calculator Website

## Website Usage Instructions

1. **Calculator Interface**: When you open the website, you will see a calculator interface with two input fields, a dropdown menu to select an operation, and a "Calculate" button.

2. **Enter Numbers**: Enter two numeric values in the input fields.

3. **Select Operation**: Choose an operation (Add, Subtract, Multiply, or Divide) from the dropdown menu.

4. **Calculate**: Click the "Calculate" button to perform the selected operation on the two numbers.

5. **Result**: The result of the calculation will be displayed below, or an error message will appear if an issue arises (e.g., division by zero).

## Walkthrough

### Classes:
- The website incorporates three CSS classes for styling:
  - `.header-style`: Defines the header's appearance with a blue background and white text.
  - `.button-style`: Styles buttons with an orange background, dark text, and rounded edges.
  - `.paragraph-style`: Defines the appearance of paragraphs with a medium font size and gray text.

### Switch Statements:
- JavaScript's switch statement is utilized to determine the selected mathematical operation.
- The user's choice from the dropdown menu is evaluated, and the corresponding calculation function is called (add, subtract, multiply, or divide).

### Try-Catch-Finally Statements:
- Try-catch-finally statements are employed for error handling:
  - If a user attempts to divide by zero, an error is caught, and an error message is displayed.
  - For other exceptions, the default catch block handles invalid operations.

## Conclusion

This website showcases the usage of classes for styling HTML elements, switch statements for selecting operations, and try-catch-finally statements for handling errors. It provides a simple calculator interface for performing basic calculations and demonstrates how to create an interactive and visually appealing web application.
