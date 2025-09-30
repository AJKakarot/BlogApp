# 📝 Blog App (MERN)

A **full-stack MERN Blog Application** where users can **create, read, update, and delete (CRUD)** blog posts with authentication and image upload support.  

---

## 🚀 Features

- ✅ User Authentication (Signup, Login, Logout)  
- ✅ Create, Edit, and Delete Blog Posts  
- ✅ Image Uploads using **Cloudinary**  
- ✅ Secure Authentication with **JWT**  
- ✅ Responsive UI with **React & Bootstrap**  
- ✅ Like & Comment on Posts  

---

## 🛠 Tech Stack

**Frontend:** React, React Router, Axios, Bootstrap  
**Backend:** Node.js, Express.js  
**Database:** MongoDB (Mongoose ODM)  
**Authentication:** JSON Web Tokens (JWT)  
**File Uploads:** Cloudinary  
**Other Dependencies:** bcryptjs, cors, dotenv, validator, express-fileupload  

---

## 🔧 Installation

### 1️⃣ Clone the repository
```sh
git clone https://github.com/AJKakarot/BlogApp.git
cd blog-app-mern
```

### 2️⃣ Install dependencies

**Backend**
```sh
cd backend
npm install
```

**Frontend**
```sh
cd ../frontend
npm install
```

### 3️⃣ Set up environment variables

Create a `.env` file in the **backend** folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 4️⃣ Start the application

**Backend**
```sh
cd backend
npm start
```

**Frontend**
```sh
cd ../frontend
npm start
```

The app will run on:  
- Frontend → [http://localhost:3000](http://localhost:3000)  
- Backend → [http://localhost:5000](http://localhost:5000)  

---

## 📂 Folder Structure

```bash
/blog-app-mern
│── /backend               # Backend (Express.js, MongoDB, JWT)
│   ├── /models            # Mongoose Schemas
│   ├── /routes            # API Routes
│   ├── /controllers       # Business Logic
│   ├── server.js          # Entry Point
│   ├── .env               # Environment Variables
│   ├── package.json
│
│── /frontend              # Frontend (React, Bootstrap)
│   ├── /src
│   │   ├── /components
│   │   ├── /pages
│   │   ├── App.js
│   │   ├── index.js
│   ├── package.json
│
│── .gitignore
│── README.md
```

---

## 🔥 API Endpoints

### Auth Routes
| Method | Endpoint            | Description        |
|--------|---------------------|--------------------|
| POST   | `/api/auth/register`| Register a new user|
| POST   | `/api/auth/login`   | Login user         |

### Blog Routes
| Method | Endpoint          | Description           |
|--------|-------------------|-----------------------|
| GET    | `/api/posts`      | Get all blog posts    |
| GET    | `/api/posts/:id`  | Get a single blog post|
| POST   | `/api/posts`      | Create a new blog post|
| PUT    | `/api/posts/:id`  | Update a blog post    |
| DELETE | `/api/posts/:id`  | Delete a blog post    |

---

## 🚀 Deployment

- **Frontend** → Vercel, Netlify  
- **Backend** → Render, Railway, Heroku  
- **Database** → MongoDB Atlas  

---

## 🎯 Contributing

1. Fork the repository  
2. Create a new branch → `git checkout -b feature-name`  
3. Commit changes → `git commit -m "Added feature"`  
4. Push to branch → `git push origin feature-name`  
5. Open a Pull Request  

---

## 📜 License

This project is **open-source** and available under the [MIT License](LICENSE).  

---

✨ Happy Coding! 🚀
