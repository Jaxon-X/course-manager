# Course Management System

![Node.js](https://img.shields.io/badge/Node.js-v16.x-green)
![MongoDB](https://img.shields.io/badge/MongoDB-v5.x-blue)
![JWT](https://img.shields.io/badge/JWT-Authentication-orange)

A secure and scalable Course Management System built with **Node.js**, **MongoDB**, and **JWT Authentication**. This project allows users to manage courses with CRUD operations while ensuring secure access through token-based authentication.

---

## Features

- **User Authentication**:
  - Register and log in with JWT-based authentication.
  - Secure password hashing using bcrypt.
- **Course Management**:
  - Create, read, update, and delete courses.
  - Only authenticated users can manage courses.
- **API Endpoints**:
  - RESTful APIs for user and course management.
- **Error Handling**:
  - Custom error handling for better debugging.
- **Scalable Architecture**:
  - Modular code structure for easy scaling.

---

## Technologies Used

- **Backend**: Node.js, Express.js
- **Database**: MongoDB (with Mongoose ODM)
- **Authentication**: JSON Web Tokens (JWT)
- **Password Hashing**: bcryptjs
- **Environment Variables**: dotenv
- **API Testing**: Postman or Thunder Client

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/course-management-system.git
   cd course-management-system

   
API Endpoints
User Routes
POST /api/auth/register - Register a new user.

POST /api/auth/login - Log in and get a JWT token.

Course Routes
GET /api/courses - Get all courses.

GET /api/courses/:id - Get a single course by ID.

POST /api/courses - Create a new course (requires authentication).

PUT /api/courses/:id - Update a course by ID (requires authentication).

DELETE /api/courses/:id - Delete a course by ID (requires authentication).

Contributing
Contributions are welcome! If you'd like to contribute, please follow these steps:

Fork the repository.

Create a new branch for your feature or bugfix.

Commit your changes.

Submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any questions or feedback, feel free to reach out:

Email: xudoyberdiyevjahon8@gmail.com.com

GitHub: github.com/Jaxon-X/

Enjoy managing your courses securely! 🎉
