# 🏥 GetaDoc – Full Stack Doctor Appointment System

GetaDoc is a full-stack healthcare web application that allows users to book doctor appointments online while providing separate dashboards for doctors and administrators to efficiently manage appointments and users.

---

## 🚀 Features

### 👤 User

* Secure authentication (JWT-based login/signup)
* Browse doctors
* Book appointments
* View and manage bookings

### 🩺 Doctor

* Login dashboard
* Manage appointments
* View patient details

### 🛠️ Admin

* Manage doctors and users
* Monitor appointments
* Control platform operations

---

## 🧑‍💻 Tech Stack

### Frontend

* React.js
* Context API
* Axios

### Backend

* Node.js
* Express.js
* MongoDB
* JWT Authentication

---

## 📁 Project Structure

```
GetaDoc/
├── backend/
│   ├── src/
│   ├── server.js
│   └── .env
├── frontend/
│   ├── src/
│   └── package.json
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/palakvohra/GetaDoc.git
cd GetaDoc
```

---

### 2️⃣ Backend Setup

```
cd backend
npm install
```

Create a `.env` file in backend folder:

```
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

Run backend:

```
npm start
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm start
```

---

## 🌐 API Base URL

```
http://localhost:8000/api
```

---

## 🔐 Environment Variables

Environment variables are stored in a `.env` file and are not included in the repository for security reasons.

---

## 🚀 Future Enhancements

* Payment integration
* Notification system
* Real-time chat
* Cloud deployment

---

## 👩‍💻 Author

**Palak Vohra**

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
