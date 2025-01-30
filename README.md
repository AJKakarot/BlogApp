📝 Blog App (MERN)

A full-stack MERN (MongoDB, Express.js, React, Node.js) blog application where users can create, read, update, and delete blog posts with authentication and image upload features.

🚀 Features
✅ User authentication (Signup, Login, Logout)
✅ Create, edit, and delete blog posts
✅ Upload images using Cloudinary
✅ Secure authentication with JWT
✅ Responsive UI with React & Bootstrap
✅ Like & comment on posts

🛠 Tech Stack
Frontend: React, React Router, Axios, Bootstrap
Backend: Node.js, Express.js
Database: MongoDB (Mongoose ODM)
Authentication: JSON Web Tokens (JWT)
File Uploads: Cloudinary
Other Dependencies: bcryptjs, cors, dotenv, validator, express-fileupload


🔧 Installation
1️⃣ Clone the repository
sh
Copy
Edit
git clone https://github.com/AJKakarot/BlogApp.git
cd blog-app-mern

2️⃣ Install dependencies
Install backend dependencies
sh
Copy
Edit
cd backend
npm install
Install frontend dependencies
sh
Copy
Edit
cd ../frontend
npm install
3️⃣ Set up environment variables
Create a .env file in the backend directory and add:

env
Copy
Edit
PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_secret_key  
CLOUDINARY_CLOUD_NAME=your_cloudinary_name  
CLOUDINARY_API_KEY=your_api_key  
CLOUDINARY_API_SECRET=your_api_secret 


4️⃣ Start the application
Start the backend
sh
Copy
Edit
cd backend
npm start
Start the frontend
sh
Copy
Edit
cd ../frontend
npm start
The app will run on:

Frontend: http://localhost:3000
Backend: http://localhost:5000

📂 Folder Structure
bash
Copy
Edit
/blog-app-mern  
│── /backend # Backend (Express.js, MongoDB, JWT)  
│ ├── /models # Mongoose schemas  
│ ├── /routes # API routes  
│ ├── /controllers # Business logic  
│ ├── server.js # Entry point  
│ ├── .env # Environment variables  
│ ├── package.json  
│  
│── /frontend # Frontend (React, Bootstrap)  
│ ├── /src  
│ │ ├── /components  
│ │ ├── /pages  
│ │ ├── App.js  
│ │ ├── index.js  
│ ├── package.json  
│  
│── .gitignore  
│── README.md  


🔥 API Endpoints
Auth Routes
Method Endpoint Description
POST /api/auth/register Register a new user
POST /api/auth/login Login user
Blog Routes
Method Endpoint Description
GET /api/posts Get all blog posts
GET /api/posts/:id Get a single blog post
POST /api/posts Create a new blog post
PUT /api/posts/:id Update a blog post
DELETE /api/posts/:id Delete a blog post


🚀 Deployment
You can deploy your app using:

Frontend: Vercel, Netlify
Backend: Render, Railway, Heroku
Database: MongoDB Atlas

🎯 Contributing
Fork the repository
Create a new branch (git checkout -b feature-name)
Commit changes (git commit -m "Added feature")
Push to branch (git push origin feature-name)
Open a pull request


📜 License
This project is open-source and available under the MIT License.

Happy coding! 🚀
