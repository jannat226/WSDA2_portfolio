

This repository contains the code for a Blogging API . The API allows users to create, retrieve, and manage blog posts through various endpoints.

## Project Structure

The project is organized as follows:

- **`controllers`**: This directory contains controller functions responsible for handling HTTP requests and responses. Specifically, `blog.js`, `login.js`, and `user.js` handle blog-related operations, user authentication, and user management, respectively.

- **`middleware`**: Middleware functions used for various purposes, such as error handling, JWT verification, pagination, and API feature management, are stored here. Files like `errorHandler.js`, `getBearerToken.js`, `pagination.js`, and `verifyUser.js` are included in this directory.

- **`models`**: The data models for MongoDB are defined here. `Article.js` defines the schema for blog posts, while `User.js` defines the schema for user data.

- **`routes`**: This directory contains route handlers for different API endpoints. `blog.js` and `signup.js` handle blog-related routes and user authentication routes, respectively.

- **`utils`**: Utility functions used within the project are stored here. Notably, `utils.js` contains a function for calculating the estimated reading time of a blog post.

- **`config`**: Configuration files, including environment variables and database connection settings, are stored in this directory. `config.js` defines the database connection string, port number, and secret key used for encryption.

- **`app.js`**: The main application file where the Express app is configured and initialized. It sets up middleware, routes, and connects to the MongoDB database.

- **`server.js`**: This file creates an HTTP server and listens for incoming requests. It utilizes the Express app created in `app.js`.

## Models Used

- **Article Model**: Defined in `models/Article.js`, this model represents blog posts and includes fields such as title, description, author, state, read count, and timestamps.

- **User Model**: Defined in `models/User.js`, this model represents user data and includes fields such as first name, last name, username, email, password, and an array of articles authored by the user.

## API Endpoints

- **POST /api/signup**: Endpoint for user registration.

- **POST /api/login**: Endpoint for user authentication.

- **GET /api/blog**: Endpoint to retrieve all blog posts.

- **GET /api/blog/:id**: Endpoint to retrieve a specific blog post by ID.

- **POST /api/blog**: Endpoint to create a new blog post.

## Evaluation Criteria

During evaluation, the following aspects will be considered:

1. **Project Structure**: The clarity and organization of the project structure, including the separation of concerns between different directories and files.

2. **Model Usage**: The appropriate use of data models (`Article` and `User`) for representing blog posts and user data, respectively.

3. **Middleware Implementation**: The correct implementation of middleware functions for error handling, authentication, pagination, and API feature management.

4. **API Routes**: The correctness and functionality of API routes for user authentication and blog-related operations.

5. **Code Quality**: The overall quality of the code, including readability, adherence to best practices, and consistency in coding style.

6. **Functionality**: The functionality and correctness of the API endpoints for user authentication, blog creation, and retrieval.

## Instructions for Evaluation

1. Clone this repository to your local machine.
2. Ensure that Node.js and MongoDB are installed.
3. Navigate to the project directory and install dependencies using `npm install`.
4. Start the server by running `npm start`.
5. Test the API endpoints using a tool like Postman or curl.
6. Evaluate the project based on the provided criteria.

Feel free to reach out if you have any questions or need further clarification on any aspect of the project. Happy evaluating!


**MADE BY LOVE WITH FUSION FALCONS || JANNAT & HRISHABH GAUTUM**
