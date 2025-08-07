# 📝 Blog API

A simple RESTful Blog API built with **Express** and **Axios**, allowing users to create, edit, and delete blog posts. The project follows HTTP standards and separates concerns with modular file structure.

---

## 🚀 Features

- **Create Post** – Add a new blog entry with title and content.
- **Edit Post** – Update an existing post by ID.
- **Delete Post** – Remove a post by ID.
- **RESTful API** – Uses standard HTTP methods (`GET`, `POST`, `PUT`, `DELETE`).
- **Modular Structure** – Separate files for server setup and blog API logic.
- **Axios Integration** – For making HTTP requests (e.g., testing or frontend consumption).

---

## 📁 Project Structure
blog-api/ ├── server.js         # Entry point, sets up Express server ├── blogApi.js        # Handles blog routes and logic ├── package.json └── README.md

---

## 🛠️ Tech Stack

- **Node.js**
- **Express**
- **Axios**

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/blog-api.git
cd blog-api
npm install

▶️ Usage
Start the server
node server.js


Server runs on http://localhost:3000 by default.

📡 API Endpoints
| Method | Endpoint | Description | 
| POST | /posts | Create a new post | 
| GET | /posts | Get all posts | 
| GET | /posts/:id | Get a single post | 
| PUT | /posts/:id | Edit a post by ID | 
| DELETE | /posts/:id | Delete a post by ID | 


🧠 Notes
- All data is stored in memory (no database yet).
- Ideal for learning REST API structure and Express routing.
- Easily extendable to include authentication, database, or frontend.
