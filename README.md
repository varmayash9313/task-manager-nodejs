# Task Manager API

## Description
This is a simple Task Manager REST API built using Node.js, Express, and MongoDB.

## Features
- Create a task
- Get all tasks
- Update task
- Mark task as completed
- Delete task

## Tech Stack
- Node.js
- Express.js
- MongoDB
- Mongoose

## Setup Instructions

1. Clone the repo:
git clone https://github.com/varmayash9313/task-manager-nodejs.git

2. Install dependencies:
npm install

3. Create .env file:
PORT=5000
MONGO_URI=mongodb://127.0.0.1:27017/taskDB

4. Run server:
npm run dev

## API Endpoints

- POST /tasks
- GET /tasks
- PUT /tasks/:id
- PATCH /tasks/:id/complete
- DELETE /tasks/:id
