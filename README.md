# Preventing SQL Injection and CSRF Token Example
This is a simple web application built to demonstrate how to use prepared statements to prevent SQL injection attacks, as well as how to implement and submit CSRF tokens with forms. Additionally, validators are used to validate user input for added security.

Purpose
The main purpose of this project is to showcase the following security measures:
+ Preventing SQL Injection: Prepared statements are utilized when interacting with the database to prevent SQL injection attacks. This ensures that user input is properly sanitized and does not pose a security risk.
- CSRF Token Usage: CSRF (Cross-Site Request Forgery) tokens are implemented and submitted with forms to protect against CSRF attacks. These tokens help verify the authenticity of form submissions and prevent unauthorized requests.
+ Input Validation: Validators are employed to validate user input, ensuring that only valid data is accepted and processed by the application. This helps enhance security by mitigating the risk of accepting malicious or unexpected input.

## Setup
+ Clone the Repository:
    ```bash
    git clone https://github.com/Olakunleniola/preventing_sql_injections_crsftoken_validation_example.git
    ```
- Install Dependencies:
    ```bash
    npm install
    ```
+ Run the Application:
    ```bash
    npm start
    ```
- Access the Application: Once the server is running, you can access the application by navigating to http://localhost:4001 in your web browser.

## Usage
+ View and Interact with Forms: Explore the various forms provided in the application to see how CSRF tokens are included and validated.
- Submit Form Data: Experiment with submitting form data and observe how CSRF tokens are used to prevent unauthorized requests.
+ Check Database Interaction: Examine how prepared statements are used to interact with the database, preventing SQL injection vulnerabilities.

## Dependencies
+ Express.js: Web framework for Node.js
- SQLite3: SQLite database driver for Node.js
+ Express-partials: Middleware for rendering partial views
- Validator: Input validation library for Node.js
+ csurf: CSRF protection middleware for Express.js
- cookie-parser: Middleware for parsing cookies in Express.js
+ EJS: Embedded JavaScript template engine for Node.js
