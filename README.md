# Secured Login System

A secured login system built using **React** for the frontend, **Flask** for the backend, **PostgreSQL** for the database, and **JWT (JSON Web Tokens)** for authentication.

---

## Features

- **User Registration**: Securely register new users.
- **User Login**: Authenticate users using JWT.
- **Token Management**: Generate, validate, and revoke JSON Web Tokens.
- **Password Security**: Passwords are hashed using industry-standard algorithms.

---

## Technology Stack

### Frontend
- **React**: For building a responsive and interactive user interface.

### Backend
- **Flask**: A lightweight Python web framework for handling backend logic and API endpoints.

### Database
- **PostgreSQL**: A robust relational database for storing user data.

### Authentication
- **JWT**: For secure and stateless user authentication.

---


## Security Measures
- **Password Hashing**: User passwords are hashed using secure algorithms before being stored in the database.
- **JWT Expiry**: Tokens have an expiration time to minimize unauthorized access.
- **CORS**: Configured to restrict API access to trusted domains.
- **Environment Variables**: Sensitive configurations are stored in `.env` files.

---
