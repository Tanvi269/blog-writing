Blog Writing Application

This project is a full-stack blog writing application that allows users to create, view, and manage blog posts through a simple web interface. The system consists of a frontend for user interaction, a backend server for handling application logic, and a testing script to validate functionality.

Project Overview

The Blog Writing application demonstrates how frontend and backend technologies work together to build a simple blogging platform.

The frontend provides a user-friendly interface where users can write and view blogs.

The backend processes requests, manages blog data, and communicates with the frontend.

The test.py script is used to test and verify the functionality of the system.

Project Structure
blog-writing/
│
├── backend/
│   ├── app.py
│   └── other backend files
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── test.py
├── requirements.txt
└── README.md
Description of Files

backend/
Contains the server-side logic responsible for handling blog operations such as creating, retrieving, and managing posts.

frontend/
Contains the user interface built using HTML, CSS, and JavaScript.

test.py
A Python script used to test the functionality of the blog application.

requirements.txt
Lists the Python libraries required to run the backend.

README.md
Project documentation and setup instructions.

Technologies Used

Python

HTML

CSS

JavaScript

Flask / FastAPI (Backend framework)

Python Testing Scripts

Installation

Follow the steps below to run the project locally.

Clone the Repository
git clone https://github.com/your-username/blog-writing.git
Navigate to the Project Folder
cd blog-writing
Install Dependencies
pip install -r requirements.txt
Running the Application
Start the Backend Server
python backend/app.py

The server will start and handle requests from the frontend.

Run the Frontend

Open the following file in your browser:

frontend/index.html
Running Tests

To test the functionality of the application, run:

python test.py

This script checks whether the application components are functioning correctly.

Future Improvements

Add user authentication

Implement database support

Allow editing and deleting blog posts

Improve UI design

Deploy the application online
