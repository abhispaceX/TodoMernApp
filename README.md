# Elegant MERN Stack Todo Application

## Overview

This is an elegant, professional-looking Todo application built using the MERN (MongoDB, Express.js, React, Node.js) stack. The application features a clean, modern UI styled with Tailwind CSS and allows users to add, view, and delete todo items.

## Features

- Add new todo items
- View list of existing todo items
- Delete todo items
- Responsive design
- Modern UI with gradient background and card layout

## Technologies Used

- MongoDB: Database
- Express.js: Backend framework
- React: Frontend library
- Node.js: Runtime environment
- Tailwind CSS: Styling
- Axios: HTTP client

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js (v14 or later)
- npm (usually comes with Node.js)
- MongoDB

## Installation

1. Clone the repository:
git clone https://github.com/your-username/elegant-mern-todo-app.git
cd elegant-mern-todo-app
2. Install backend dependencies:
cd backend
npm install
3. Install frontend dependencies:
cd ../frontend
npm install
## Configuration

1. Create a `.env` file in the `backend` directory and add your MongoDB connection string:
MONGODB_URI=your_mongodb_connection_string
2. If you're using a different port for your backend, update the `proxy` field in `frontend/package.json`:
```json
"proxy": "http://localhost:5000"

Running the Application
1. Start the backend server:
cd backend
npm start
2. Start the frontend server:
cd frontend
npm start

## Project Structure

elegant-mern-todo-app/
│
├── backend/
│   ├── models/
│   │   └── Todo.js
│   ├── routes/
│   │   └── todos.js
│   ├── .env
│   ├── package.json
│   └── server.js
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── TodoForm.js
│   │   │   ├── TodoItem.js
│   │   │   └── TodoList.js
│   │   ├── App.js
│   │   └── index.js
│   ├── package.json
│   └── tailwind.config.js
│
└── README.md
