This Project is working on a Local Host Server.

please visit to see the presentation  --->  https://www.veed.io/view/a3bac377-3060-4136-906b-d62addc8c684?panel=share

MERN Stack Blogging Application

Overview

This project is a full-stack blogging application built with the MERN stack (MongoDB, Express.js, React, and Node.js). Users can create, edit, and delete blog posts, as well as read posts from other users. The application features user authentication and authorization, supporting two types of users: Readers and Authors.


Features

User Roles:

Reader: Can read and comment on posts

Author: Can create, edit, delete their own posts.

User authentication and authorization (sign up, log in, logout)

Rich text editor for creating and editing posts

User profiles

Responsive design

Technologies Used

Frontend:
React

Context

React Router

Axios

CSS (or SCSS)

Backend:

Node.js

Express.js

MongoDB

Mongoose

JWT (JSON Web Token) for authentication

Tools:

Babel

Webpack

VS Code

Installation

Prerequisites

Node.js (v14 or later)

MongoDB

Backend Setup

Clone the repository:

bash
Copy code

git clone https://github.com/yourusername/mern-blogging-app.git

cd mern-blogging-app/backend

Install dependencies:

bash

Copy code

npm install

Create a .env file in the backend directory and add the following:

env

Copy code

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

Start the backend server:

bash
Copy code

npm start

Frontend Setup

Navigate to the frontend directory:

bash
Copy code

cd ../frontend

Install dependencies:

bash
Copy code

npm install

Create a .env file in the frontend directory and add the following:

env
Copy code

REACT_APP_API_URL=http://localhost:5000

Start the frontend development server:

bash
Copy code

npm start

Usage

Open your browser and go to http://localhost:3000.

Sign up for a new account or log in if you already have one.

Depending on your user role (Reader or Author):

Reader: Read and comment on blog posts.

Author: Create new blog posts, edit or delete existing ones, and read and comment on posts.


Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure your code adheres to the existing coding conventions and passes all linting checks.


Acknowledgments

React

Node.js

Express

MongoDB

Mongoose

JWT

