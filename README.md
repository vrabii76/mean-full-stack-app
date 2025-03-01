# MEAN Stack Application - Project Description

Application was deployed using AWS: Elastic Beanstalk
A live demo of the app can be found here: [MEAN App](http://node-angular-env.eba-v6xda7ej.eu-north-1.elasticbeanstalk.com/)

1. Overview

   This is a full-stack web application built using the MEAN stack (MongoDB, Express.js, Angular, Node.js). The application implements user authentication, file uploads, and features a modern UI using Angular Material components.

2. Core Technologies
   Backend Stack:

- Node.js

  - Runtime environment for executing JavaScript on the server
  - Handles HTTP requests and business logic
  - Manages file system operations and database connections

- Express.js

  - Web application framework for Node.js
  - Handles routing and middleware
  - Provides RESTful API endpoints

- MongoDB (with Mongoose)
  - NoSQL database for storing application data
  - Schema-based data modeling using Mongoose
  - Document-oriented storage

Frontend Stack:

- Angular (v19.1.0)

  - Frontend framework for building single-page applications
  - Component-based architecture
  - TypeScript-powered development

- Angular Material
  - Material Design components for Angular
  - Responsive UI elements
  - Pre-built accessibility features

Authentication & Security:

- JSON Web Tokens

  - Secure user authentication
  - Stateless session management
  - Token-based API authorization

- bcrypt
  - Password hashing and verification
  - Secure credential storage

File Handling:

- Multer
  - Middleware for handling multipart/form-data
  - File upload management
  - MIME type validation

3. Key Features

- User Authentication

  - Login/Signup functionality
  - JWT-based session management
  - Route guards for protected routes

- Post Management

  - CRUD operations for posts
  - Image upload support
  - Protecting resources with authorization
  - Responsive UI

4. Additional Tools

- nodemon: Development server with auto-reload capability
- TypeScript: Adds static typing to JavaScript
- RxJS: Reactive programming library for handling asynchronous data

This project demonstrates a full-stack JavaScript application with features for authentication, data management, and file handling, all built on the reliable MEAN stack architecture.
