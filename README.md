# Contact Manager
 Simple Contact Manager built with Node.js and Express.

This repository contains the backend implementation of MyContacts, a simple contact management application built using Node.js and Express. The project focuses on creating a RESTful API to handle CRUD operations for user contacts.

## Key Features:

- RESTful API with Express
- MongoDB database using Mongoose
- User authentication with JWT (JSON Web Tokens)
- Middleware for handling token validation
- Error handling with custom middleware
- Secure password storage with bcrypt

## API Endpoints:

- `GET /api/contacts` - Get all user contacts
- `GET /api/contacts/:id` - Get a specific user contact
- `POST /api/contacts` - Create a new user contact
- `PUT /api/contacts/:id` - Update a user contact
- `DELETE /api/contacts/:id` - Delete a user contact

## User Authentication:

- User registration (`POST /api/auth/register`)
- User login (`POST /api/auth/login`)
- Protected routes with JWT authentication

## Authorization:

- Users can only manipulate their own contacts
- Authorization middleware to check user permissions

## How to Run:

1. Clone the repository: `git clone https://github.com/AmanJ10/Contact-Manager.git`
2. Install dependencies: `npm install`
3. Set up your environment variables (e.g., `.env` file)
4. Run the server: `npm start`

Feel free to explore the code and contribute to the project! If you encounter any issues or have suggestions, please open an [issue](https://github.com/AmanJ10/Contact-Manager/issues).

Image showing the GET request (all contacts of the User are shown).
![image](https://github.com/AmanJ10/Contact-Manager/assets/83915557/48d4c49a-67c2-46c3-9d22-488f6e26e112)



