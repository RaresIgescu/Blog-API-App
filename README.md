# Blog Post Management System

## Overview
This project is a **Blog Post Management System** built using **Node.js, Express, and EJS**. It allows users to create, edit, delete, and view blog posts through a simple web interface. The system consists of two main components:

1. **API Server (`server.js`)** – A RESTful API that manages blog posts, using an in-memory datastore.
2. **Frontend Server (`app.js`)** – A frontend built with **EJS** that interacts with the API and provides an intuitive user interface.

## Features
- 📌 View all blog posts
- ✍️ Create new posts
- 📝 Edit existing posts
- ❌ Delete posts
- 🔗 Uses **Express.js** for backend API
- 🎨 Server-side rendering with **EJS**

## Installation & Setup
### Prerequisites
Ensure you have **Node.js** installed on your system.

### Steps to Run the Project
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/Blog-API-App.git
   cd blog-post-management
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the API server** (Runs on port 4000):
   ```bash
   node server.js
   ```

4. **Start the frontend server** (Runs on port 3000):
   ```bash
   node app.js
   ```

5. **Open the application in your browser**:
   ```
   http://localhost:3000
   ```

## API Endpoints
| Method | Endpoint         | Description                  |
|--------|-----------------|------------------------------|
| GET    | `/posts`        | Get all blog posts          |
| GET    | `/posts/:id`    | Get a specific post         |
| POST   | `/posts`        | Create a new post           |
| PATCH  | `/posts/:id`    | Update an existing post     |
| DELETE | `/posts/:id`    | Delete a post               |

## Technologies Used
- **Node.js** – JavaScript runtime
- **Express.js** – Web framework for Node.js
- **EJS** – Templating engine for rendering pages
- **Axios** – HTTP client for API communication
- **Body-parser** – Middleware for handling request data

## Contributing
Feel free to fork this repository and submit a pull request with improvements or new features!
