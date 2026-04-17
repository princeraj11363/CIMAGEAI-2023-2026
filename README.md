# CIMAGEAI-2023-2026

# 🎓 EduPath LMS (Learning Management System)

EduPath LMS is a modern web-based Learning Management System designed to streamline online education. It provides an interactive platform for students, instructors, and administrators to manage courses, track progress, and enhance learning experiences.

---

## 🚀 Features

### 👨‍🎓 Student

* Register and login securely
* Browse and enroll in courses
* Access video lectures and study materials
* Track learning progress
* Attempt quizzes and assignments

### 👩‍🏫 Instructor

* Create and manage courses
* Upload videos, notes, and resources
* Create quizzes and assignments
* Monitor student performance

### 🛠️ Admin

* Manage users (students & instructors)
* Approve or remove courses
* Monitor platform activity
* Handle system-level configurations

---

## 🧰 Tech Stack

* **Frontend:** HTML, CSS, JavaScript (React.js if used)
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Authentication:** JWT (JSON Web Token)
* **Version Control:** Git & GitHub

---

## 📂 Project Structure

```
EduPath-LMS/
│── client/          # Frontend files
│── server/          # Backend API
│── models/          # Database schemas
│── routes/          # API routes
│── controllers/     # Business logic
│── config/          # Configuration files
│── public/          # Static files
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/EduPath-LMS.git
cd EduPath-LMS
```

### 2️⃣ Install dependencies

```
npm install
cd client
npm install
```

### 3️⃣ Configure environment variables

Create a `.env` file in the root and add:

```
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

### 4️⃣ Run the application

```
# Start backend
npm run server

# Start frontend
cd client
npm start
```

---

## 🔐 Authentication Flow

* User registers → credentials stored in database
* Login → JWT token generated
* Token used for protected routes

---

## 📊 Future Enhancements

* Live classes integration
* Payment gateway for paid courses
* Certificate generation
* AI-based course recommendations
* Mobile app support

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Prince Raj**
GitHub: https://github.com/princeraj11363

---

## 🌟 Acknowledgements

* Open-source community
* Developers and contributors

---

⭐ If you like this project, don't forget to star the repository!
