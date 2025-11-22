Student Record Management System

A backend application built using Node.js, Express.js, and MongoDB to manage student information. This system allows users to perform CRUD operations on student data while following a clean MVC folder structure for easy maintainability and scaling.

🚀 Features

✔ Add new student records
✔ View all students or a specific student
✔ Update existing student details
✔ Delete student records
✔ RESTful API architecture
✔ Secure environment configuration (.env file)
✔ Clean MVC folder structure

📂 Project Structure

STUDENT-RECORD/
│── server.js

│── package.json

│── package-lock.json

│── .env

│

├── config/

│   └── db.js               # MongoDB connection

│


├── controllers/

│   └── studentController.js

│

├── models/

│   └── studentModel.js

│

├── routes/

│   └── studentRoutes.js

│

└── node_modules/

🛠️ Technologies Used

Node.js

Express.js

MongoDB / Mongoose

dotenv

Nodemon (optional for development)

🔧 Installation & Setup
1️⃣ Clone the repository
git clone  https://github.com/Nishu-Kumari2027/Student-Record

2️⃣ Navigate to the project folder
cd STUDENT-RECORD

3️⃣ Install dependencies
npm install

4️⃣ Create a .env file

Inside the root folder, add:

MONGO_URI=your_mongodb_connection_string
PORT=5000

5️⃣ Start the server
node server.js


or (if using nodemon)

nodemon server.js

📡 API Endpoints
Base URL: http://localhost:5000/api/students
Method	Endpoint	Description
GET	/	Get all students
GET	/:id	Get a specific student
POST	/	Add a new student
PUT	/:id	Update student details
DELETE	/:id	Remove a student
🧪 Example Student JSON
{
  "name": "John Doe",
  "age": 21,
  "course": "Computer Science",
  "email": "john@example.com"
}

📝 License

This project is open-source and free to use.
