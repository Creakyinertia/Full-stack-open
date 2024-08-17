# Full Stack Open Project

This repository contains the project I developed as part of the **Full Stack Open** course. The application demonstrates the use of modern web development technologies and practices, covering both frontend and backend development.

## Table of Contents

- [About the Project](#about-the-project)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Features](#features)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About the Project

This project is a part of the Full Stack Open course, which covers a wide range of web development topics, including React, Node.js, Express, and MongoDB. The goal of this project is to build a fully functional web application that integrates a React frontend with an Express backend, utilizing MongoDB for data storage.

## Technologies Used

- **Frontend:**
  - React
  - React Router
  - Axios (for HTTP requests)
  - CSS (or any CSS framework like Bootstrap/Tailwind)
  
- **Backend:**
  - Node.js
  - Express
  - MongoDB
  - Mongoose (for MongoDB object modeling)
  - JWT (for authentication)
  
- **Others:**
  - Git & GitHub for version control
  - Yarn for package management

## Getting Started

### Prerequisites

Ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/)
- [Yarn](https://yarnpkg.com/)
- [MongoDB](https://www.mongodb.com/)

### Installation

1. **Clone the repository:**
   `git clone https://github.com/your-username/full-stack-open-project.git
   cd full-stack-open-project`

2. **Install frontend dependencies:**
   `cd frontend
   yarn install`

3. **Install backend dependencies:**
   `cd ../backend
   yarn install`

### Running the Application
#### Start MongoDB:

Make sure MongoDB is running on your local machine or update the connection string in the backend configuration if using a remote database.

#### Start the backend server:

`cd backend
yarn start`

> The server will start on http://localhost:3001.

Start the frontend development server:

`cd ../frontend
yarn start`

> The frontend will start on http://localhost:3000.

### Features:

- User authentication and authorization with JWT
- CRUD operations for resources
- RESTful API design
- Responsive and dynamic user interface built with React
- State management with React hooks

### Folder structure 
full-stack-open-project/
│
├── frontend/          # frontend code
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── backend/           # backend code
    ├── controllers/
    ├── models/
    ├── routes/
    ├── app.js
    ├── server.js
    ├── package.json
    └── ...

### Contributing

Contributions are welcome! Please feel free to submit a Pull Request or open an issue if you find a bug or have a suggestion.

### License

This project is licensed under the MIT License.

### Acknowledgements

Thanks to the Full Stack Open course creators for providing an excellent learning platform.
