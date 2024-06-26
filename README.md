### Social Media Website API using Node.js and MongoDB

This project provides a backend API for a social media website, implemented with Node.js and MongoDB.

#### Features

- **User Authentication**: Register, login, and manage user accounts securely.
- **Posts**: Perform CRUD operations for posts, including comments and likes.
- **Follow System**: Implement a system for users to follow each other.
- **Search**: Enable searching for users and posts.

#### Technologies Used

- **Node.js**: Runtime environment for server-side JavaScript.
- **Express**: Fast, minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing user and post data.
- **Mongoose**: MongoDB object modeling tool for Node.js.

#### Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/long-vux/social-media-mern
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Set up environment variables:**

   - Create a .env file in the root directory.
   - Define environment variables such as PORT, MONGODB_URI, and JWT_SECRET.

4. **Start the server:**
   ```bash
   npm start
   ```

#### API Endpoints

POST /api/auth/register: Register a new user.
POST /api/auth/login: Authenticate and log in a user.
PUT /api/users/:id: Update a user.
DELETE /api/users/:id: Delete a user.
GET /api/users/:id: Get a user.
PUT /api/users/:id/follow: Follow a user.
PUT /api/users/:id/unfollow: Unollow a user.

POST /api/post: Create a post.
PUT /api/post/:id: Update a post.
DELETE /api/post/:id: Delete a post.
PUT /api/post/:id/like: Like a post.
PUT /api/post/:id/dislike: Dislike a post.
