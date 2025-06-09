# Bootstrap User Information Form

## Description
This is a simple user information form built using Bootstrap 5. The form collects basic user details including name, age, date of birth, gender, and email address.

## Features
- Responsive design that works on mobile and desktop devices
- Form validation for required fields
- Clean, modern Bootstrap styling
- Dropdown menu for gender selection
- Properly structured HTML5 form elements

## Form Fields
1. Name (First and Last name fields)
2. Age (numeric input)
3. Date of Birth (date picker)
4. Gender (dropdown selection)
5. Email address (with email validation)

## Requirements
- Bootstrap 5 CSS and JS files
- jQuery (for Bootstrap functionality)

## Installation
1. Include Bootstrap CSS in the head:
   ```html
   <link href="css/bootstrap.min.css" rel="stylesheet">
   ```
2. Include jQuery and Bootstrap JS before the closing body tag:
   ```html
   <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
   <script src="js/bootstrap.bundle.min.js"></script>
   ```

## Usage
Simply open the HTML file in a web browser to view and interact with the form. All fields are marked as required, so the form will prompt users to complete all information before submission.

## Customization
You can easily modify the form by:
- Adjusting column sizes in the grid classes
- Changing the color scheme by modifying Bootstrap's utility classes
- Adding or removing form fields as needed

## Notes
- The form currently doesn't have backend processing - it would need to be connected to a server-side script to handle submissions.
- Ensure all required Bootstrap and jQuery files are properly linked for full functionality.
