# Contact Management System

A backend project developed using Node.js and Next.js, focusing on SQL, authentication, data validation, date-time handling, file handling, and CSV/Excel parsing. This project features a contact management system with a RESTful API.

## Table of Contents

- Project Overview
- Folder Structure
- Technologies Used
- Setup Instructions
- API Endpoints
- Running the Application
- Environment Variables
- License

## Project Overview

The Contact Management System allows users to manage their contacts with functionalities such as creating, reading, updating, and deleting contacts. It includes user authentication and JWT-based authorization.

## Technologies Used

- Node.js
- Next.js
- SQLite
- Sequelize
- JSON Web Tokens (JWT)
- Joi/Yup for data validation
- Express.js

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd contact-management-system
Install the dependencies: npm install


Set up the SQLite database: node scripts/seed.js


API Endpoints
Authentication

POST /api/auth/register - Register a new user
POST /api/auth/login - Login a user
Contacts

GET /api/contact - Get all contacts
GET /api/contact/:id - Get a specific contact by ID
POST /api/contact - Create a new contact
PUT /api/contact/:id - Update a specific contact by ID
DELETE /api/contact/:id - Delete a specific contact by ID


Running the Application
To start the server, run : node server.js 
The server will run on the default port (3000)

Environment Variables
JWT_SECRET: Secret key for JWT signing.

