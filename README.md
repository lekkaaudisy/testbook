# Test Book - MERN Stack Project

## Overview

Test Book is a straightforward project built with the MERN (MongoDB, Express.js, React, Node.js) stack. The primary functionality of this project is to allow users to input information about a new book through the front end, which is then stored in the backend database.

## Features

- **Add New Book:** Users can input details about a new book, including title, author, and other relevant information.
- **Book List:** View a list of all books stored in the database, displaying key details for each book.
- **Edit Book:** Edit the details of an existing book, updating the information in the database.
- **MERN Stack:** Utilizes MongoDB as the database, Express.js for the server, React for the front end, and Node.js as the runtime environment.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js
- npm (Node Package Manager)
- MongoDB

## Getting Started

1. **Clone the repository:**
   
   `git clone https://github.com/lekkaaudisy/testbook.git`

2. **Navigate to the project directory:**

   Backend
   `cd testbook/testbook-backend`

   Frontend
   `cd testbook/testbook-frontend`

4. **Install dependencies in each folder:**

   `npm install`

5. **Set up the MongoDB database:**

   - Ensure MongoDB is running locally or update the connection string in the 'testbook-backend/config/db.js` file.

6. **Run the application in each folder:**

   Backend
   `npm run app`

   Frontend
   `npm run dev`

## Project Structure

- **testbook-frontend:** Contains the React front-end application.
- **testbook-backend:** Houses the Express.js back-end server.
- **db.js:** Configuration file for MongoDB connection.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests. Contributions are welcomed and appreciated!

## Acknowledgments

- This project was inspired by the need for a simple book input system.
- Special thanks to the MERN stack for providing a robust development environment.
