# To-Do App Backend CRUD Server Using Node.js, Express, and MongoDB (MERN Stack)

This is a backend server for a simple to-do application that allows you to perform CRUD (Create, Read, Update, Delete) operations on tasks. It is built using Node.js, Express, and MongoDB, following the MERN stack architecture.


**Special Note:** This backend task was assigned by senior developers during my internship at CORTRACKER IT Private Limited.


## Features

- Create a new task with a title, description, due date, and completion status.
- Retrieve a list of all tasks.
- Retrieve a specific task by its unique ID.
- Update an existing task.
- Delete a task by its ID.

## Prerequisites

Before getting started, make sure you have the following prerequisites installed:

- Node.js: [Download and install Node.js](https://nodejs.org/)

## Getting Started

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/your-username/to-do-app-backend.git

   ```

2. Navigate to the project directory:
   `cd to-do-app-backend`
3. Install project dependencies:
   `npm install`
4. Set up a MongoDB database:
   Make sure you have MongoDB installed and running on your system.
   Update the MongoDB connection string in `app/index.js` to point to your MongoDB instance.
5. Start the server:
   `npm start`

The server will start and listen on the specified port (default is 5000).

# API Endpoints

```
GET /to-do/tasks: Get a list of all tasks.
POST /to-do/tasks: Create a new task.
GET /to-do/tasks/:id: Get a specific task by its ID.
PUT /to-do/tasks/:id: Update an existing task by its ID.
DELETE /to-do/tasks/:id: Delete a task by its ID.
```

Please note that the base URL for these endpoints is `http://localhost:5000` by default.
