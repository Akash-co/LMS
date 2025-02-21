# Library Management System

## Overview

This is a Library Management System built using the MERN stack (MongoDB, Express.js, React, Node.js). The system allows users to view books in the online library, while admins can add, delete, update, and search for books. Role-based authentication is implemented using JWT, with separate roles for admins and users. State management is handled using React Context, and Tailwind CSS is used for styling.

## Prerequisites

Ensure you have the following installed:

- Node.js (latest LTS version recommended)
- MongoDB (local or cloud instance)

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-repo/library-management-system.git
   cd library-management-system
   ```

2. Install dependencies for both client and server:

   ```sh
   cd client
   npm install
   cd ../server
   npm install
   ```

## Running the Application

### Start the Server

Navigate to the `server` directory and run:

```sh
npm run dev
```

### Start the Client

Navigate to the `client` directory and run:

```sh
npm start
```

## Environment Variables

Create a `.env` file inside the `server` directory and define the following:

```env
PORT=8080
MONGO_URI=your_mongodb_connection_string
SESSION_SECRET="secret"
```

## Features

- User authentication (JWT)
- Role-based access control (Admin & User)
- CRUD operations for books
- Search functionality
- Responsive UI with Tailwind CSS

## License

This project is licensed under the MIT License.

