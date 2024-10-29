# 📝 Fullstack Blog

Welcome to my **Fullstack Blog**! This application showcases the power of full-stack development using **React, Express, Node.js, and MongoDB**. The frontend is built with **React**, styled with **Tailwind CSS**, and enhanced with **Framer Motion** animations. The backend is powered by **Node.js** and **Express**, with data stored in a **MongoDB database**.

---

## 🚀 Features

- **Create, Read, List Blog Posts** with real-time data from MongoDB.
- **Responsive Design** using Tailwind CSS for optimal viewing across devices.
- **Animations** with Framer Motion to enhance user experience.
- **RESTful API** for CRUD operations on blog posts.
- **Seamless Integration** between frontend and backend.

---

## 📂 Project Structure

fullstack-blog/ ├── frontend/ # React frontend │ ├── public/ # Static files │ ├── src/ # React components and pages │ │ ├── pages/ # Home, Posts, and CreatePost pages │ │ └── App.js # Main React app │ └── package.json # Frontend dependencies │ ├── backend/ # Express backend │ ├── index.js # Backend server setup │ ├── models/ # Mongoose models (e.g., Post) │ ├── routes/ # API routes for posts │ └── package.json # Backend dependencies │ └── README.md # Project documentation

yaml
Copy code

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS, React Router, Framer Motion  
- **Backend**: Node.js, Express, MongoDB, Mongoose  
- **Version Control**: Git, GitHub  
- **Deployment**: GitHub Pages (Frontend), Heroku or Render (Backend)

---

## ⚙️ Setup Instructions

### **1. Clone the Repository**

```bash
git clone https://github.com/kevin-369/fullstack-blog.git
cd fullstack-blog
2. Setup Backend
Navigate to the backend folder:

bash
Copy code
cd backend
Install backend dependencies:

bash
Copy code
npm install
Create a .env file in the backend folder:

bash
Copy code
MONGO_URI=mongodb://localhost:27017/fullstack-blog
Start the backend server:

bash
Copy code
node index.js
3. Setup Frontend
Open a new terminal and navigate to the frontend folder:

bash
Copy code
cd frontend
Install frontend dependencies:

bash
Copy code
npm install
Start the React frontend:

bash
Copy code
npm start
Open http://localhost:3000 in your browser to view the app.

🎯 Usage
Create a Blog Post: Navigate to the "Create Post" page and fill in the form to submit a new post.
View All Posts: Go to the "Posts" page to see a list of all posts.
Backend API: Test the API using Postman or any REST client:
GET /posts: Retrieve all posts
POST /posts: Create a new post
🌍 Deployment
Frontend on GitHub Pages:
Build the frontend:
bash
Copy code
cd frontend
npm run build
Deploy to GitHub Pages:
bash
Copy code
npm run deploy
Backend on Heroku or Render:
Commit your backend code:
bash
Copy code
cd backend
git add .
git commit -m "Deploy backend"
Follow deployment instructions for Heroku or Render.
🔥 Potential Improvements
User Authentication: Add login/signup functionality.
Post Editing & Deletion: Allow users to update and delete posts.
Comment System: Enable users to comment on blog posts.
🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, open an issue to discuss what you'd like to change.

📧 Contact
If you have any questions or want to connect:

Email: kev.okacha@gmail.com
GitHub: @kevin-369
LinkedIn: linkedin.com/in/kevin-okacha