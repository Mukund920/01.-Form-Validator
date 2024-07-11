Form_Validator
Form Validator  A simple form validation project using HTML, CSS, and JavaScript. This project provides a basic form with client-side validation for fields such as username, email, and password. The validation checks include required fields, length constraints, email format, and password matching.

Overview

This project provides a basic form with client-side validation for fields such as username, email, and password. The validation checks include required fields, length constraints, email format, and password matching.

Features

- Username, email, and password validation
- Real-time error messages
- Simple and clean UI

Technologies

- HTML
- CSS
- JavaScript

Setup

To get a local copy up and running follow these steps:

1. Clone the repository:

    bash
    git clone https://github.com/your-username/form-validator.git
    

2. Navigate to the project directory:

    bash
    cd form-validator
    

3. Open `index.html` in your browser:

    You can simply open the `index.html` file in your web browser to see the form in action.

Usage

- Fill in the username, email, and password fields.
- Submit the form to see real-time validation.
- Error messages will be displayed for invalid inputs.

How It Works

This app validates user input in real-time as they fill out the form. Here's a step-by-step explanation of how it works:

1. HTML Structure: 
   - The HTML file defines a form with fields for username, email, password, and password confirmation.
   - Each input field is wrapped in a `.form-control` div that also contains a `small` element for displaying error messages.

2. CSS Styling:
   - The CSS file styles the form, input fields, and error messages.
   - Classes such as `.form-control.error` and `.form-control.success` are used to change the appearance of input fields based on validation results.

3. JavaScript Validation:
   - When the form is submitted, the `submit` event is intercepted by a JavaScript function to prevent the default form submission.
   - The following validations are performed:
     - Required Fields: Each input field is checked to ensure it is not empty.
     - Length Check: The length of the username and password fields is checked to ensure they meet the specified minimum and maximum lengths.
     - Email Format: The email field is checked to ensure it matches a regular expression pattern for valid email addresses.
     - Password Match: The password and password confirmation fields are checked to ensure they match.

4. Displaying Validation Results:
   - For each validation check, the JavaScript functions `showError` and `showSuccess` are used to update the `.form-control` div classes and display appropriate messages.
   - If an input field fails validation, it is highlighted with a red border, and an error message is displayed.
   - If an input field passes validation, it is highlighted with a green border.


![Screenshot 2024-07-11 204017](https://github.com/Mukund920/Form_Validator/assets/67047343/4bdffec1-8ecf-45f6-832a-cbd25e434051)
![Screenshot 2024-07-11 203923](https://github.com/Mukund920/Form_Validator/assets/67047343/e890b5fc-c73e-4d17-804c-8274023a22ac)
![Screenshot 2024-07-11 202807](https://github.com/Mukund920/Form_Validator/assets/67047343/c7a1cb59-058b-4b81-b4e0-c7ba58a8a439)

