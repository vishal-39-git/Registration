# User Registration System
  This Spring Boot project implements a simple user registration and management system using MySQL for data storage. It provides RESTful       APIs for user registration, retrieval, update, and deletion operations.

# Technologies Used
**Spring Boot**: Framework for creating Java applications easily.
**MySQL**: Database used for storing user information.
**Spring Data JPA**: Simplifies data access using the Repository pattern.
**Thymeleaf**: Server-side Java template engine for web and standalone environments.
# Features
**User Registration**: Allows users to register with a username, email, and password.
**User Management**: CRUD operations (Create, Read, Update, Delete) for managing users.
**RESTful API**: Provides endpoints for registering a user, retrieving all users, updating a user, and deleting a user.

# Access the Application:
  Open a web browser and go to http://localhost:8080 to access the user registration form.
  
  # API Endpoints
  POST /api/users/register: Register a new user.
  GET /api/users: Retrieve all users.
  GET /api/users/{id}: Retrieve a user by ID.
  PUT /api/users/{id}: Update a user by ID.
  DELETE /api/users/{id}: Delete a user by ID.

# Usage
  Fill out the registration form on the web interface or use RESTful API endpoints to interact with the application.
