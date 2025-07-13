# Express MongoDB CRUD API

A simple RESTful API built with **Node.js**, **Express.js**, and **MongoDB Atlas** to perform **CRUD operations** on a `User` entity.

---

## 🚀 Features

- 🔗 Connects to MongoDB Atlas
- 📥 Create, Read, Update, Delete users
- 🌱 Environment variable support using `.env`
- 🛠 Built with modular structure (controller, model, routes)
- 📦 Easily extendable for more entities

---

## 🧠 Technologies Used

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose ODM
- Dotenv
- Nodemon (for development)

---

## 📁 Project Structure

express-mongodb-crud/
│
├── controllers/
│ └── userController.js # Logic for user routes
├── models/
│ └── userModel.js # Mongoose schema/model
├── routes/
│ └── userRoutes.js # API routes for User
├── .env # Environment variables (not committed)
├── .gitignore # Ignore node_modules, .env, logs
├── package.json
├── server.js # Entry point
└── README.md

### ⚙️ Setup Instructions

1. Clone the Repo
```bash
git clone https://github.com/your-username/express-mongodb-crud.git
cd express-mongodb-crud

2. Install Dependencies
npm install

3. Configure .env
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/<dbname>?retryWrites=true&w=majority

4. Run the Server
npm run dev



