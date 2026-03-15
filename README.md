
# 🌐 CONNECT – Mini Social Media Platform

An elegant full-stack Social Media Platform where users can create profiles, share posts, interact through comments, and follow other users.

This project was developed as part of the **CodeAlpha Internship Task – Social Media Platform**.

---

## 👩‍🎓 Intern Details

Name: **GADDAM BHAVANA**

Student ID: **CA/DF1/24315**

Internship Domain: **Full Stack Development**

Organization: **CodeAlpha**

Project Name: **MINI SOCIAL MEDIA PLATFORM**

---

## 🚀 Live Features

- 👤 User Registration & Login
- 🧑 User Profiles
- 📝 Create Posts
- 💬 Comment on Posts
- ❤️ Like System
- 👥 Follow / Unfollow Users
- 📰 Social Feed
- 📱 Responsive Modern UI
- 🗄️ Data Stored in Database

---

## 🧠 Project Architecture

### 🔹 Frontend
- HTML5
- CSS3
- JavaScript
- Responsive UI Design

### 🔹 Backend
- Node.js
- Express.js
- REST API Development

### 🔹 Database
- MongoDB
- Mongoose ODM

---

## 📂 Folder Structure

CodeAlpha_SocialMedia
│
├── frontend
│   ├── css
│   ├── js
│   ├── pages
│   └── index.html
│
├── backend
│   ├── models
│   ├── routes
│   ├── controllers
│   ├── server.js
│   └── package.json
│
└── README.md

---

## 📱 Platform Workflow

1. User registers an account.
2. User logs into the platform.
3. Users can create posts, like posts, comment on posts, and follow other users.
4. Feed page displays posts created by users.
5. All user data, posts, likes, and comments are stored in MongoDB.

---

## 🗄️ Database Schema Overview

### User
- username
- email
- password (hashed)
- followers
- following

### Post
- userId
- content
- likes
- createdAt

### Comment
- userId
- postId
- commentText
- createdAt

---

## 📸 Screenshots

### Home / Feed Page
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(866).png" width="250"/>
</p>


### Login Page
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(868).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(870).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(871).png" width="250"/>
</p>


### Register Page
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(867).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(869).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(870).png" width="250"/>
</p>


### Profile Page
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(872).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(873).png" width="250"/>
</p>


### Types of posts
### 1.Text 
<img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(499).png" width="250"/>

### 2.Image 
<img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(500).png" width="250"/>
<img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(502).png" width="250"/>

### Create Post
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(874).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(875).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(876).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(504).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(505).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(506).png" width="250"/>
  
</p>


### Comments
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(877).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(878).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(879).png" width="250"/>
</p>


### Likes System
<p align="center">
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(881).png" width="250"/>
  <img src="https://github.com/Bhavana29gaddam/project/blob/main/Screenshot%20(882).png" width="250"/>
</p>


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

git clone (https://github.com/Bhavana29gaddam/project)

---

### 2️⃣ Backend Setup

cd backend
npm install

Create a .env file and add:

MONGO_URI=mongodb+srv://god376853_db_user:33RAr4aXIgMPmbJB@cluster0.4fbojva.mongodb.net/socialmedia?retryWrites=true&w=majority
PORT=5000


Run backend server:

node server.js

---

### 3️⃣ Frontend Setup

Open the frontend folder and runs using npm start on http://localhost:3000 and the backend server runs on http://localhost:5000.

---

## 🎯 Internship Requirements Completed

✔ User Profiles  
✔ Post Creation  
✔ Comment System  
✔ Like Feature  
✔ Follow / Unfollow System  
✔ Database Integration  

---

## 🌟 Future Improvements

- Image Upload in Posts
- Real-time Chat System
- Notifications
- Dark Mode UI
- Mobile Application Version
- Deployment (Render / Vercel / Railway)

---

## 👩‍💻 Author

**GADDAM BHAVANA**  
Full Stack Developer  
CodeAlpha Internship Submission

---

## 📜 License

This project is developed for educational and internship purposes.
