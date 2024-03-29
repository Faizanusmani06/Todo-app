

# Todo App using Express.js and MongoDB

This project implements a simple Todo application using Express.js for the backend and MongoDB for data storage. It allows users to create, read, update, and delete tasks in a MongoDB database.

## Features

- Create todo
- get all todos
- get todo by id
- update todo
- delete todo

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js and npm (Node Package Manager)
- MongoDB

## Installation

1. Clone this repository to your local machine:

```
git clone https://github.com/Faizanusmani06/Todo-app.git
```

2. Navigate to the project directory:

```
cd Todo-app
```

3. Install dependencies:

```
npm install
```

## Configuration

1. Ensure MongoDB is running on your local machine or update the MongoDB connection string in `.env` to connect to your MongoDB database instance.


## Usage

1. Start the server:

```
npm start
```

2. Access the Todo app through your browser or API client at `http://localhost:3000`.

## API Endpoints

- `GET /getTodos`: Get all tasks
- `POST /createTodo`: Create a new task
- `GET /getTodos/:id`: Get a specific task by ID
- `PUT /updateTodo/:id`: Update a specific task by ID
- `DELETE /DeleteTodo/:id`: Delete a task by ID
