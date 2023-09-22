# Mongoose-API
Social Media API with Mongoose

Overview
This is a Node.js application that serves as the backend API for a social media platform, built using Mongoose, a MongoDB object modeling library. It provides a robust and scalable foundation for creating and managing social media content, user profiles, and interactions.

Features
User Management: Create, update, and delete user profiles.
Post Creation: Allow users to create and manage posts.
Comments and Likes: Enable users to interact with posts through comments and likes.
Authentication: Secure endpoints with user authentication using JWT (JSON Web Tokens).
Follow/Unfollow: Implement the ability for users to follow and unfollow other users.
Real-time Updates: Implement WebSocket support for real-time notifications.
Technologies Used
Node.js: The server-side runtime environment.
Express.js: A minimalist web application framework for Node.js.
Mongoose: An elegant MongoDB object modeling library.
MongoDB: A NoSQL database for storing application data.
JWT: JSON Web Tokens for secure authentication.
Getting Started
Clone the repository:

bash
Copy code
git clone $this repo
Install dependencies:

bash
Copy code
cd social-media-api
npm install
Configure your environment variables to connect to your local mongo:

API Endpoints

GET /api/users: Get a list of all users.

GET /api/users/:userId: Get a specific user by ID.

POST /api/users: Create a new user.

PUT /api/users/:userId: Update a user

DELETE /api/users/:userId: Delete a user's profile.

GET /api/thoughts: Get a list of all posts.

GET /api/thoughts/:thoughtId: Get a specific thought by ID.

POST /api/thoughts: Create a new thought.

PUT /api/thought/:postId: Update a thought.

DELETE /api/thoughts/:postId: Delete a thought.

POST /api/users/:userId/friends/:friendId Add a friend

DELETE /api/users/:userId/friends/:friendId Lose a friend





