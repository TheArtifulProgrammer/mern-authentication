# MERN Authentication

![MERN Stack](https://img.shields.io/badge/MERN-Stack-green)

Full MERN Authentication Implementation - User Activation, Forgot Password, Refresh Tokens, Access Tokens.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project demonstrates a complete authentication system built using the MERN stack (MongoDB, Express.js, React.js, Node.js). It includes user registration, activation via email, password reset, and the use of access and refresh tokens for secure authentication.

## Features

- User Registration
- Email Activation
- Login/Logout
- Forgot Password
- Password Reset
- Access Tokens
- Refresh Tokens
- Protected Routes

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- [Node.js](https://nodejs.org/) (v14.x or later)
- [MongoDB](https://www.mongodb.com/)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/mern-authentication.git
    ```

2. Navigate to the project directory:

    ```bash
    cd mern-authentication
    ```

3. Install server dependencies:

    ```bash
    cd server
    npm install
    ```

4. Install client dependencies:

    ```bash
    cd ../client
    npm install
    ```

## Usage

1. Create a `.env` file in the `server` directory with the following environment variables:

    ```env
    MONGO_URI=your_mongodb_connection_string
    JWT_SECRET=your_jwt_secret
    EMAIL_SERVICE=your_email_service
    EMAIL_USER=your_email_user
    EMAIL_PASS=your_email_password
    CLIENT_URL=http://localhost:3000
    ```

2. Start the development server:

    ```bash
    cd server
    npm run dev
    ```

3. Start the React development server:

    ```bash
    cd ../client
    npm start
    ```

4. Open your browser and navigate to `http://localhost:3000`

## Project Structure

```bash
mern-authentication/
├── client/         # React frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── utils/
│       └── App.js
├── server/         # Express backend
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   └── server.js
└── README.md
