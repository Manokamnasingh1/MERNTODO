# 📝 MERN Stack To-Do App

A simple and responsive **To-Do List** application built with the **MERN Stack (MongoDB, Express, React, Node.js)**. Add, complete, and delete tasks — with full backend integration and responsive design.

---

## 🚀 Features

- Add new tasks
- Mark tasks as completed
- Delete tasks
- Persistent storage with MongoDB
- Responsive design (mobile-friendly)
- Clean UI with React & CSS
- Footer designed by **Manaokamna**

---

## 📸 Screenshots

![To-Do App Screenshot](screenshot.png) <!-- Replace with your actual image or remove -->

---

## 🛠️ Tech Stack

- **Frontend:** React, Axios, CSS
- **Backend:** Node.js, Express
- **Database:** MongoDB with Mongoose

---

## Backend Setup
bash
Copy
Edit
cd backend
npm install
node server.js
Make sure MongoDB is running locally on mongodb://localhost:27017.

3. Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm start
🌐 API Endpoints
Method	Route	Description
GET	/api/todos	Get all todos
POST	/api/todos	Add a new todo
PUT	/api/todos/:id	Toggle complete
DELETE	/api/todos/:id	Delete todo

🧑‍🎨 Designed By
Manaokamna – Footer and UI styling inspiration ❤️

📄 License
This project is open-source and available under the MIT License.

🙌 Support
Star ⭐ this repo if you find it helpful!
Pull requests and suggestions welcome.

yaml
Copy
Edit

---

### 👉 What to Do Next:

- Replace `https://github.com/your-username/todo-mern.git` with your actual GitHub repo link.
- Add a screenshot (`frontend/public/screenshot.png`) if you want.
- Optionally add a [LICENSE](https://choosealicense.com/licenses/mit/) file.

Let me know if you want to deploy this on Vercel (frontend) and Render (backend) or write setup instructions for MongoDB Atlas (cloud DB).






You said:
complet in one


ChatGPT said:
Here is the complete README.md for your MERN Stack To-Do App, all in one block, ready to copy and paste into your GitHub repo:

markdown
Copy
Edit
# 📝 MERN Stack To-Do App

A simple and responsive **To-Do List** application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**. This app lets you create, complete, and delete tasks with real-time database storage and responsive design.

---

## 🚀 Features

- ✅ Add new tasks
- ✏️ Mark tasks as completed
- 🗑 Delete tasks
- 🗃 Data stored in MongoDB using Mongoose
- 💻 Responsive design with CSS
- 🎨 UI designed with cards
- 🧑‍🎨 Footer designed by **Manaokamna**

---

## 🛠️ Tech Stack

- **Frontend:** React, Axios, HTML, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Local or Cloud via Compass/Atlas)

---

## 📂 Folder Structure

TodoApp/
├── backend/
│ ├── models/
│ │ └── Todo.js
│ ├── routes/
│ │ └── todoRoutes.js
│ └── server.js
├── frontend/
│ ├── src/
│ │ ├── App.js
│ │ ├── Todo.css
│ │ └── index.js
├── README.md

yaml
Copy
Edit

---

## ⚙️ Getting Started

### 🔧 Prerequisites

- Node.js & npm installed
- MongoDB installed locally or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- Code editor (e.g., VSCode)

---

### 📥 Installation Steps

#### 1. Clone the Repository

```bash
git clone https://github.com/your-username/todo-mern.git
cd todo-mern
2. Set Up Backend
bash
Copy
Edit
cd backend
npm install
node server.js
MongoDB must be running locally on mongodb://localhost:27017.
Or update your MongoDB connection string in server.js.

3. Set Up Frontend
bash
Copy
Edit
cd ../frontend
npm install
npm start
Visit the app in your browser: http://localhost:3000

🔗 API Endpoints
Method	Endpoint	Description
GET	/api/todos	Fetch all todos
POST	/api/todos	Add a new todo
PUT	/api/todos/:id	Toggle complete
DELETE	/api/todos/:id	Delete a todo

📸 Screenshots
(Optional: Add screenshots to visually represent the UI)

bash
Copy
Edit
📷 Place screenshots in frontend/public and link here if needed.
🎨 UI Design
To-Dos displayed as styled cards

Responsive layout using external CSS

Clean and modern look

Footer:

csharp
Copy
Edit
Designed with ❤️ by Manaokamna
📄 License
This project is licensed under the MIT License.

🙌 Contribution
Feel free to submit issues or pull requests.
If you like this project, give it a ⭐ on GitHub!

