## **Todo List Application using MERN**

## Table of Contents

1. [Introduction](#introduction)
2. [Features](#features)
3. [Prerequisites](#prerequisites)
4. [Installation](#installation)
5. [Usage](#usage)
6. [API Endpoints](#api-endpoints)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

This project is a simple Todo List application built using the MERN stack (MongoDB, Express.js, React.js, Node.js). The application allows users to create, read, update, and delete (CRUD) their todo items.

## Features

- Add new todo items
- Mark todo items as completed
- Edit existing todo items
- Delete todo items
- Responsive design

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Node.js and npm installed on your machine
- MongoDB installed and running

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/todo-mern.git
   cd todo-mern
   ```

2. **Backend Setup:**

   ```bash
   cd backend
   npm install
   ```

   Create a `.env` file in the backend directory and add your MongoDB URI:

   ```env
   MONGO_URI=your_mongodb_uri
   ```

   Start the backend server:

   ```bash
   npm run dev
   ```

3. **Frontend Setup:**

   ```bash
   cd ../frontend
   npm install
   ```

   Start the React development server:

   ```bash
   npm start
   ```

## Usage

1. Open your browser and navigate to `http://localhost:3000`
2. Add, edit, complete, and delete your todos

## API Endpoints

- **GET /api/todos** - Retrieve all todos
- **POST /api/todos** - Create a new todo
- **PUT /api/todos/:id** - Update a todo by ID
- **DELETE /api/todos/:id** - Delete a todo by ID

## Contributing

To contribute to this project, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b feature-branch-name`.
3. Make and commit your changes: `git commit -m 'feature: add some feature'`.
4. Push to the original branch: `git push origin feature-branch-name`.
5. Create the pull request.

If not, you can see the GitHub documentation on [creating a pull request](https://help.github.com/articles/creating-a-pull-request/).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
