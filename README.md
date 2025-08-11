# EFFICIO | Smart Task and Team Management App

A modern and responsive Task Manager built using the MERN stack: MongoDB, Express.js, React, and Node.js.
This app helps individuals and teams organize tasks, set deadlines, track progress, assign responsibilities, and generate reports — all with an intuitive and responsive UI.

# ✨ Features
Authentication & Authorization – Secure login/signup with JWT.

Task Management – Create, edit, delete, and update tasks with priority and due dates.

Team Collaboration – Assign tasks to multiple users.

Progress Tracking – View task completion percentage and status via visual charts.

Automated Status Updates – Status changes dynamically based on checklist completion.

Reports & Data Export – Download task and team reports for offline use.

Attachments Support – File links can be attached to tasks.

Mobile-Friendly UI – Optimized for desktops, tablets, and smartphones.

# 📂 Project Structure
<img width="864" height="606" alt="image" src="https://github.com/user-attachments/assets/58b29864-27c8-4151-9055-5bab06cbf3a2"/>


# ⚙ Installation

1.Clone the repository

git clone <your-repo-url>
cd task-manager

2.Backend Setup

cd backend
npm install

Create a .env file in the backend/ directory:

PORT=5000

MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/<dbname>

JWT_SECRET=your_jwt_secret

3.Frontend Setup

cd ../frontend
npm install

4.Run the Application

*Start server*

cd backend

npm run dev

*Start frontend*

cd ../frontend

npm start

# 🔌 API Endpoints

Auth
POST /api/auth/signup – Create a new user

POST /api/auth/login – Login and get JWT token

GET /api/auth/me – Get current user

Tasks
GET /api/tasks – Get all tasks

POST /api/tasks – Create a task

PUT /api/tasks/:id – Update a task

DELETE /api/tasks/:id – Delete a task

PATCH /api/tasks/:id/status – Update task status

Reports
GET /api/reports/tasks – Generate a task report

GET /api/reports/users – Generate a user activity report

# 🛠 Tech Stack

Frontend: React, Tailwind CSS, Axios, Chart.js

Backend: Node.js, Express.js, Mongoose

Database: MongoDB

Auth: JWT

Others: Multer/File Upload, CSV export


# 📜 License
This project is licensed under the MIT License — you can modify and use it freely.
