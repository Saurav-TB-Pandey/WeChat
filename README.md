# WeChat

This project is a full-stack application built with Node.js, Express.js, Sequelize, React, and Redux. It provides features for user authentication, messaging, group creation, and management.

# Table of Contents

- Project Description
- Installation
- Usage
- Folder Structure
- Technologies Used
- Contributing
- License

# Project Description

This project aims to create a comprehensive communication platform with features like user authentication, private messaging, group creation, group messaging, and real-time updates using Socket.io. It uses a client-server architecture where the client-side is built with React and Redux for state management, while the server-side is built with Node.js, Express.js, and Sequelize for database management.

# Installation

To run this project locally, follow these steps:

1. Clone the repository to your local machine:
   - git clone https://github.com/Saurav-TB-Pandey/WeChat
2. Navigate to the project directory:
   - cd project-directory
3. Install the dependencies for the client-side:
   - cd client
   - npm install
4. Install the dependencies for the server-side:
   - cd ..
   - cd server
   - npm install
5. Create a .env file in the server directory and add necessary environment variables:
   - SECRET_KEY = your_secret_key
   - PORT = 8090
6. Run the migration scripts to set up the database:
   - npx sequelize-cli db:migrate
7. Start the server:
   - npm start
8. Start the client:
   - cd client
   - npm start
9. Access the application in your web browser at http://localhost:3000.

# Usage

Once the application is running, you can:

- Sign up for a new account or log in with an existing account.
- Send private messages to other users.
- Create groups and invite users to join.
- Send messages within groups for group discussions.
- Receive real-time updates for new messages and group activities using Socket.io.

# Folder Structure

The project follows a structured folder hierarchy:

- Client: Contains the React.js front-end application.
  - Components: React components for different parts of the UI.
  - Redux: Redux store configuration and reducers.
  - App.js: Main component rendering and routing.
  - index.css: Global styles.

- Server: Contains the Node.js/Express.js back-end application.
  - bin: Server startup script.
  - config: Configuration files.
  - controller: Controllers for handling business logic.
  - migrations: Database migration scripts.
  - models: Sequelize database models.
  - public: Static assets like images and stylesheets.
  - routes: Express.js routes.
  - views: View templates (if using server-side rendering).
  - .env: Environment variables file.
  - app.js: Main application file.

- Other files: .gitignore, package.json, README.md, etc.

# Technologies Used

- Node.js
- Express.js
- Sequelize ORM
- React
- Redux
- Socket.io
- HTML/CSS
- JavaScript (ES6+)

# Contributing

Contributions to this project are welcome. You can fork the repository, make your changes, and submit a pull request. Please ensure that your code follows the project's coding standards and conventions.

# License

This project is licensed under the MIT License.
