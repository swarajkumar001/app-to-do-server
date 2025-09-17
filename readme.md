MERN To-Do App Backend

This is the backend for a MERN (MongoDB, Express, React, Node.js) To-Do app. It handles users and notes through a simple REST API.

**Features**
REST API for notes and users
MongoDB database with Mongoose
Organized routes for clean code
Environment variables for config

**Prerequisites**
Make sure you have:
Node.js & npm
MongoDB (local or cloud)
Git

**Setup**
Clone the repo
git clone https://github.com/swarajkumar001/app-to-do-server

cd app-to-do-server

**
Install dependencies**
npm install
Create .env file
PORT=5001
MONGO_URI=mongodb://127.0.0.1:27017/todoapp

**Start the server**
npm run dev
Server runs on the port from .env (default 5001).

API Endpoints
Notes (/api/notes)
GET / → Get all notes
POST / → Add new note { title, description, completed }
PUT /:id → Update note by ID
DELETE /:id → Delete note by ID
Users (/api/users)
GET / → Get all users
POST / → Register user { name, email, password }
PUT /:id → Update user by ID
DELETE /:id → Delete user by ID

GitHub

https://github.com/swarajkumar001/app-to-do-server