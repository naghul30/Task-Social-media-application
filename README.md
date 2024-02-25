# Task-Social-media-application

# FullStack Social Media App

This project is a complete Fullstack social media application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) along with Material-UI for styling. The app includes features such as authentication, likes functionality, and dark mode. It's designed to be fully responsive, providing a seamless user experience across various devices.

## Features

- User Authentication: Users can sign up, log in, and log out securely.
- Post Creation: Authenticated users can create posts with images and descriptions.
- Like Posts: Users can like/unlike posts.
- Dark Mode: Toggle between light and dark mode for better user experience.

## Tech Stack

- MongoDB: NoSQL database for storing user data and posts.
- Express.js: Node.js framework for building the backend API.
- React.js: Frontend library for building user interfaces.
- Node.js: JavaScript runtime for running the backend server.
- Material-UI: React component library for styling the UI.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/social-media-app.git
   cd social-media-app
   ```

2. **Install dependencies:**
   ```bash
   cd client && npm install
   cd ../server && npm install
   ```

3. **Set up environment variables:**
   Create a `.env` file in the `server` directory with the following variables:
   ```
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret_key
   ```

4. **Start the server and client:**
   In separate terminal windows, run:
   ```bash
   # Terminal 1: Start the server
   cd server && npm start

   # Terminal 2: Start the client
   cd client && npm start
   ```

5. **Access the application:**
   Once both the server and client are running, open your browser and navigate to `http://localhost:3000` to use the application.


## Conclusion

Congratulations! You've successfully set up and deployed your Fullstack social media application. Feel free to customize and extend it further according to your requirements. Happy coding! 🚀
