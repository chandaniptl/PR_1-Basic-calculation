
![sub-](https://github.com/user-attachments/assets/77adf072-daa6-4a32-a0e6-d314482ba72d)
![mult](https://github.com/user-attachments/assets/31734ec4-973d-47d8-920b-b60105c79e98)
![divide](https://github.com/user-attachments/assets/919ef628-1730-4561-bf0b-8540f5ac8636)
![modulas](https://github.com/user-attachments/assets/f6dec4d4-2a4d-44f5-a39d-ad23749f76c5)
![sum](https://github.com/user-attachments/assets/301b3571-2864-4089-b8ce-a8093a60857a)


Simple Calculator – Project Documentation
Overview:

This project is a web-based simple calculator that allows users to perform basic arithmetic operations: addition, subtraction, multiplication, division, and modulus. The calculator takes two numerical inputs, performs the selected operation, and displays the result. It also includes a clear button to reset all fields.
Structure:
1. HTML (Structure Layer):

    The HTML defines the layout of the calculator.

    It includes:

        A heading titled "Simple Calculator"

        Two input fields to enter the first and second numbers

        A result field (read-only) to display the output

        Six buttons: five for arithmetic operations and one for clearing all fields

2. CSS (Styling Layer):

    The CSS styles the calculator to make it visually appealing.

    Key styling features include:

        Centered layout using Flexbox

        Rounded input fields and buttons

        Hover effects on buttons

        Background image for the calculator container

        Responsive button layout using Flexbox wrapping and gap spacing

3. JavaScript (Logic Layer):

    The JavaScript code provides the functionality of the calculator.

    There are two main functions:

    a. calculate(operator)

        Accepts an operator (+, -, *, /, %)

        Retrieves and parses input values

        Validates if both inputs are numbers

        Performs the selected operation using a switch statement

        Handles division by zero

        Displays the result in the result field

    b. clearFields()

        Clears the input and result fields, resetting the calculator

