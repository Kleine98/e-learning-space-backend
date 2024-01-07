# E-Learning-Space Web App - Backend

This repository contains the backend code for the E-Learning-Space web app. The backend is implemented using Node.js, Express.js, and JWT for authentication with access and refresh tokens.

## Concepts

### Authentication

The backend uses JSON Web Tokens (JWT) for authentication. The authentication flow involves:

- **Access Token:** 
  - Generated upon successful login.
  - Used to authenticate and authorize API requests.
  - Short-lived for security reasons.

- **Refresh Token:**
  - Issued along with the access token.
  - Used to obtain a new access token without requiring the user to re-enter their credentials.
  - Stored securely on the client-side.

### Express.js

The backend is built with Express.js, a web application framework for Node.js. Key features include:

- **Routing:** Define API endpoints for different functionalities.
- **Middleware:** Implement middleware functions for authentication, error handling, etc.
- **Modular Structure:** Organize code in a modular way for scalability and maintainability.

### MongoDB

The backend uses MongoDB as the database to store and retrieve data related to the E-Learning-Space web app.
