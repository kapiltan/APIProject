# 📝 Blog API & Frontend

A simple **blog platform** built using **Node.js**, **Express**, **EJS**, and **Axios**. It provides full CRUD operations for blog posts using a RESTful API and renders views with EJS templates.

---

## 🚀 Features

- Get all blog posts
- View a single post by ID
- Add a new blog post
- Edit/patch an existing blog post
- Delete a blog post
- Frontend views to create and display posts

---

## 🛠️ Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: HTML, CSS, EJS
- **Client**: Axios (for future expansion)
- **Middleware**: body-parser
- **Storage**: In-memory JavaScript array

---

## 📂 Project Structure

blog-project/ ├── public/ │ └── styles/ │ └── main.css # Stylesheet │ ├── views/ │ ├── index.ejs # Main blog list view │ └── modify.ejs # New/Edit post form │ ├── app.js # Express app with API & routing ├── package.json └── README.md

yaml
Copy
Edit

---

## 📦 Installation

1. **Clone the repo**
```bash
git clone https://github.com/your-username/blog-app.git
cd blog-app
Install dependencies

bash
Copy
Edit
npm install
Run the server

bash
Copy
Edit
node app.js
Visit in your browser

arduino
Copy
Edit
http://localhost:4000
🧪 API Endpoints
Method	Route	Description
GET	/posts	Get all posts
GET	/posts/:id	Get single post by ID
POST	/posts	Add new post
PATCH	/posts/:id	Update existing post
DELETE	/posts/:id	Delete a post
⚠️ Notes
Posts are stored in-memory and will reset on server restart.

API responds with JSON and uses status codes properly.

Includes both API endpoints and rendered views.
