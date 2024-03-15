# MERN Task Manager
A MERN application for basic tasks management.

## Table of Contents

- [Features](#features)
- [Tools and Technologies](#tools-and-technologies)
- [Dependencies](#dependencies)
- [Dev-dependencies](#dev-dependencies)
- [Prerequisites](#prerequisites)
- [Installation and setup](#installation-and-setup)
- [Backend API](#backend-api)
- [frontend pages](#frontend-pages)
- [Useful Links](#useful-links)

## Features

### User-side features

- Signup
- Login
- Logout
- Add tasks
- View tasks
- Update tasks
- Delete tasks

## Tools and Technologies

- HTML
- CSS
- Javascript
- Scss
- Node.js
- Express.js
- React
- Redux
- Mongodb

## Dependencies

Following are the major dependencies of the project:

- axios
- react
- react-dom
- react-redux
- react-router-dom
- yarn
- redux
- redux-toolkit
- bcrypt
- cors
- express
- jsonwebtoken
- mongoose

## Dev-dependencies

Following are the major dev-dependencies of the project:

- nodemon
- concurrently

## Prerequisites

- Node.js must be installed on the system.
- You should have a MongoDB database.
- You should have a code editor (preferred: VS Code)

## Installation and Setup

1. Install all the dependencies

   ```
   go to each individual folder and run yarn or yarn install
   ```

2. Start the application

   ```
   yarn dev
   ```

4. Go to http://localhost:5173

## Backend API

<pre>
- POST     /api/auth/signup
- POST     /api/auth/signin
- GET      /api/tasks
- GET      /api/tasks/:taskId
- POST     /api/tasks
- PUT      /api/tasks/:taskId
- DELETE   /api/tasks/:taskId
- GET      /api/profile
</pre>

## Frontend pages

<pre>
- /                 Home Screen (Public home page for guests and private dashboard (tasks) for logged-in users)
- /signup           Signup page
- /login            Signin page
- /dashboard        user dashboard
- /taskmanager      Add, delete, edit task
</pre>



## Useful Links


- Official Docs

  - Reactjs docs: https://reactjs.org/docs/getting-started.html
  - npmjs docs: https://docs.npmjs.com/
  - Mongodb docs: https://docs.mongodb.com/manual/introduction/
  - Github docs: https://docs.github.com/en/get-started/quickstart/hello-world

- Download links

  - Nodejs download: https://nodejs.org/
  - VS Code download: https://code.visualstudio.com/

