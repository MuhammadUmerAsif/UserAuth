﻿# UserAuth

UserAuth is a Node.js application designed for user authentication, built with TypeScript. It provides endpoints for user registration, login, and session management, leveraging JWT for secure token-based authentication and Redis for session caching.

## Table of Contents

- [UserAuth](#userauth)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Technologies](#technologies)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)

## Features

- User registration and login
- JSON Web Token (JWT) for secure authentication
- Redis caching for session management

## Technologies

- **Node.js**: JavaScript runtime environment
- **TypeScript**: Type-safe JavaScript superset
- **Express**: Fast, minimal, and flexible Node.js web framework
- **Redis**: In-memory data structure store used for caching sessions
- **JWT (jsonwebtoken)**: For secure, token-based authentication

## Getting Started

### Prerequisites

Make sure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [Redis](https://redis.io/) server running locally or accessible remotely

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MuhammadUmerAsif/userauth.git
   cd userauth
2. Install dependencies:
   ```bash
   npm install
3. Create a .env file in the root directory and define necessary environment variables, such as JWT_SECRET and Redis connection details.

4. Running the Server
To start the development server, use:
    ```bash
    npm run dev

This markdown provides a clear, structured overview for the **UserAuth** project.
