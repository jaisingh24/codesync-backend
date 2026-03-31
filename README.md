# 🚀 CodeSync Backend

A scalable real-time code collaboration backend built using **Spring Boot**, **JWT Authentication**, and **WebSockets**.

---

## 📌 Features

* 🔐 JWT-based Authentication (Stateless Security)
* 🧑‍💻 User Registration & Login APIs
* 🔒 Protected Routes with Custom Security Filter
* ⚡ Spring Security Configuration (No default login)
* 🗄️ MySQL Database Integration
* 🧠 Clean layered architecture (Controller → Service → Repository)

---

## 🏗️ Tech Stack

* **Backend:** Spring Boot
* **Security:** Spring Security + JWT
* **Database:** MySQL
* **Build Tool:** Maven
* **Language:** Java

---

## 🔑 Authentication Flow

1. User registers/logs in
2. Server generates JWT token
3. Client sends token in header
4. Backend validates token using custom filter

---

## 🧪 API Endpoints

### 🔐 Auth APIs

* `POST /auth/register`
* `POST /auth/login`

---

### 🔒 Protected API

* `GET /test` → Requires JWT token

---

## ⚙️ Setup Instructions

1. Clone the repository
2. Configure your database in `application.properties`
3. Run the application

---

## 🔐 Security Notes

* Stateless authentication using JWT
* No session-based authentication
* Custom filter for request validation

---

## 🚀 Future Improvements

* Real-time collaboration using WebSockets
* Version control system for code snippets
* Redis for caching and scalability
* Role-based access control

---

## 👨‍💻 Author

Jai Singh Katiyar
