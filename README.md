🔐 Secure Task Management Application
📌 Overview
The Secure Task Management Application is a full-stack web application built to help users efficiently manage their daily tasks with a focus on security and simplicity. The system allows users to create, update, delete, and track tasks through an intuitive frontend interface and a robust backend API.

🚀 Features

* ✅ User-friendly task management interface
* ✅ Create, Read, Update, Delete (CRUD) operations
* ✅ Task status tracking (Completed / Pending)
* ✅ Secure backend with API handling
* ✅ Database integration for persistent storage
* ✅ API testing using Postman

🛠️ Tech Stack
🌐 Frontend
* HTML
* CSS
* JavaScript
⚙️ Backend
* Node.js
* Express.js
🗄️Database
* MongoDB
* MongoDB Compass (GUI tool)

🔍 API Testing
* Postman

⚙️ Installation & Setup

1️⃣ Clone the Repository
git clone https://github.com/Monisha287/secure-task-app.git
cd secure-task-app

2️⃣ Setup Backend Server
cd backend
npm install
node server.js

Server runs on: `http://localhost:5000`

3️⃣ Setup Database (MongoDB Compass)
1. Open MongoDB Compass
2. Connect to:
mongodb://localhost:27017
3. Create a database (example: `taskdb`)

4️⃣ Run Frontend

* Open `frontend/register.html` in your browser
  *(or use Live Server in VS Code)*

🔗 API Endpoints

| Method | Endpoint       | Description       |
| ------ | -------------- | ----------------- |
| GET    | /api/tasks     | Fetch all tasks   |
| POST   | /api/tasks     | Create a new task |
| PUT    | /api/tasks/:id | Update a task     |
| DELETE | /api/tasks/:id | Delete a task     |

🔍 Testing with Postman
* Open Postman
* Use the API endpoints above
* Send requests (GET, POST, PUT, DELETE)
* Verify responses from backend

🔐 Security Features

* Input validation
* Structured API handling
* Secure data storage in database

🚀 Future Enhancements

* User authentication (Login/Register)
* JWT-based security
* Task reminders & notifications
* Cloud deployment
  
📄 License
This project is developed for educational purposes.
