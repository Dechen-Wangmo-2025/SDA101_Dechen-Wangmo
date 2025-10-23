# Instructions:
- Exercise 2 - Basic form validation
Implement client-side form validation using Vanilla JavaScript.
Your goal is to make sure the form checks for valid user input in real-time (as the user types), without reloading the page.
A simple registration form with the following fields:
-- Username
-- Email
-- Password
-- Confirm Password
-- Validation Rules:
Field	                Validation Rule
Username	            Must be at least 3 characters long
Email	                Must follow correct email format (e.g., someone@example.com)
Password    	        Must include:
                            - Minimum 8 characters
                            - At least one uppercase letter
                            - At least one lowercase letter
                            - At least one special character (e.g., @, #, $, %)
 Confirm Password	    Must match the password field
-- Show error messages dynamically;
    Use DOM manipulation to display helpful messages below each input field.
-- Disable the Submit button until all fields are valid
    - Initially, keep the Submit button disabled.
    - Only enable it when all validations pass.
-- Step 6: (Optional) Style your form
Use CSS to make:

Error messages appear in red.
Valid inputs have green borders.
