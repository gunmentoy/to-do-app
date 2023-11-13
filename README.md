# Task Tracker

## Description
This is a simple task tracker application built using JavaScript, HTML, and CSS. The application allows you to add, delete, and toggle tasks. It also includes a search feature to filter tasks. This project was created as a learning experience and is not maintained. It may contain errors and issues.

## Features
- **Add Tasks**: The application allows you to add new tasks with a title and a reminder property.
- **Delete Tasks**: The application allows you to delete tasks.
- **Toggle Reminder**: The application allows you to toggle the reminder status of tasks.
- **Search Tasks**: The application allows you to search for tasks by their titles.
- **Routing**: The application uses Express.js for routing.

## How It Works
The application is implemented using JavaScript, HTML, and CSS. Here's a brief overview of how it works:

1. **HTML Files**: The application includes two HTML files, `homepage.html` and `to-do.html`, which define the structure of the homepage and the to-do list page, respectively.
2. **JavaScript Files**: The application includes several JavaScript files that add functionality to the application. The `app.js` file sets up an Express server that serves the HTML files. The `style.js` file defines several functions that are used to add, delete, and toggle tasks, and to search for tasks. The `homepage.js` file defines a function that creates a new button element and sets its `onclick` attribute to redirect to the To-Do page.
3. **CSS Files**: The application includes CSS files that add styling to the HTML elements.

## Testing
The application includes test files for the Express server (`app.test.js`) and the homepage button (`homepage.test.js`). These tests are written using Jest and Supertest (for the server tests) and Jest and Enzyme (for the button tests).

## Usage
To run the application, you need to have Node.js and npm installed on your computer. You can start the application by running `node app.js` in the project directory.

## Conclusion
This task tracker application was created as our first web application project ever. While it may contain errors and issues, it serves as a valuable learning experience in web development using JavaScript, HTML, and CSS.
