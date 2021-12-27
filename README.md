# social-network-API

Description

A social network web application where users can share their thoughts, react to friends’ thoughts, and create a friend list. It uses Express.js for routing, a MongoDB database, and the Mongoose ODM.

User Story

As a social media startup, I want an API for my social network that uses a NoSQL database so that my website can handle large amounts of unstructured data.

Usage

    Clone the repo,
    Install dependencies with npm -i
    Run npm start to start the server 
    Open Insomnia to test the API routes.

Models

    User
    Thought
    Reaction 

Endpoints
![insomniauser](https://user-images.githubusercontent.com/79805880/147492467-1553e4b6-f6b9-48fe-bad1-2f93ce55de66.png)

User

    Get all users: GET /api/users
    Create a user: POST /api/users
    Get user by ID: GET /api/users/:id
    Update a user: PUT /api/users/:id
    Delete a user: DELETE /api/users/:id
    Add a friend: PUT /api/users/:userId/friends/:friendId
    Delete a friend: DELETE /api/users/:userId/friends/:friendId

Thought

    Get all thoughts: GET /api/thoughts
    Create a thought: POST /api/thoughts
    Get thought by ID: GET /api/thoughts/:id
    Update a thought: PUT /api/thoughts/:id
    Delete a thought: DELETE /api/thoughts/:id

Reaction

    Add a reaction: PUT /api/thoughts/:id/reactions
    Delete a reaction: DELETE /api/thoughts/:id/reactions

Packages

    Express
    Moment
    Mongoose
