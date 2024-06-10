The Student-Mentor Management System is designed to facilitate the management of mentors and students within an educational Institution. This App allows for the creation of mentors, assignment of students to mentors, and retrieval of information related to mentors and their assigned students.

Setup:

Clone the repository
Navigate to the project directory: cd mentor-student-management
Install dependencies: npm install
Create a .env file in the project root and define the MongoDB connection string.
Start the server: npm start
Access the application at http://localhost:<port>

API Endpoints
Student Routes

POST /api/student/create: Create a new student.
GET /api/student/students: Get all students.
PUT /api/student/assign/:id: Assign a mentor to a student.
GET /api/studnt/get-particular/:id: Get the assigned mentor for a student.

Mentor Routes

POST /api/mentor/create: Create a new mentor.
GET /api/mentor/mentors: Get all mentors.
PUT /api/mentor/assign/:id: Assign students to a mentor.
GET /api/mentor/ment-student/:id: Get students assigned to a specific mentor.

Technologies Used
Node.js
Express.js
MongoDB
Mongoose
dotenv
cors
NodeJs-


Postman documentation Link:
https://documenter.getpostman.com/view/35217393/2sA3XLFPmA