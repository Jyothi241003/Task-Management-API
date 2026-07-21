Task Management API

This is a simple Task Management REST API developed using Flask. It allows users to register, log in using JWT authentication, and perform CRUD operations on tasks.

Features
User Registration
User Login
JWT Authentication
Create Task
View Tasks
Update Task
Delete Task
Filter Tasks by Status
Technologies Used
Python
Flask
Flask-SQLAlchemy
SQLite
Flask-JWT-Extended
Werkzeug
Postman
Git & GitHub
Run the Project
1. Install the required packages
pip install -r requirements.txt
2. Run the project
python app.py

The server runs locally at:

http://127.0.0.1:5000

This is a backend REST API project, so it can be tested using Postman.

API Endpoints
User APIs
POST /register – Register a new user
POST /login – Login and receive a JWT token
GET /profile – Get the logged-in user's profile
Task APIs
POST /tasks – Create a new task
GET /tasks – Retrieve all tasks
PUT /tasks/<id> – Update a task
DELETE /tasks/<id> – Delete a task
GET /tasks?status=Completed – Filter tasks by status
Testing

All API endpoints were successfully tested using Postman.

Author

Jyothi Guled
