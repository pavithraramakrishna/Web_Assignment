Student Management Web Page

This is a simple web page for adding student details to a system and viewing student data. The page includes a form to input a student's name, age, and grade. The data is submitted to a server endpoint via a POST request. There is also a button to fetch and view student data from the server.

File Structure

index.html: The main HTML file containing the structure, styling, and script for the student management form.

Features

Responsive Design: The form is designed to be responsive, adjusting to various screen sizes for an optimal user experience.
Form Validation: The form fields are required, ensuring that the user cannot submit the form with empty fields.
AJAX Requests: The form uses asynchronous requests to communicate with the server, allowing data submission and retrieval without reloading the page.
Usage

Prerequisites

Ensure you have a server running locally on http://localhost:3000 with endpoints:
POST /addStudent: To handle the form submission and add a student.
GET /students: To fetch and display the list of students.

Running the Project

Open index.html in your preferred web browser.
Fill out the form with the student's name, age, and grade.
Click the "Submit" button to send the data to the server.
To view the student data, click the "Student Data" button.
