### 📄 README Update: Real-Time Chat Application

# Real-Time Chat Application

A real-time chat platform built using **React.js** and **Firebase**, allowing users to join chat rooms, send messages, and engage in live discussions.

## 🚀 Features
- Real-time messaging using Firebase Realtime Database
- Secure user authentication with Firebase Auth
- Create, join, and leave chat rooms
- Persistent message history
- Deployed on **Vercel** for seamless CI/CD

## 🛠️ Tech Stack
- **Frontend:** React.js
- **Backend:** Firebase Realtime Database, Firebase Authentication
- **Deployment:** Vercel
- **Tools:** React Developer Tools, Firebase Logs

## 📊 Documentation
- [Design Document](./docs/design-doc.md)
- [STRIDE Threat Model](./docs/stride-threat-model.md)

## ⚡ Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/chuksieee/real-time-chat-app.git
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the app:
   ```bash
   npm start
   ```
4. Access the app at `localhost:3000`

## 🛡️ Security
- Uses Firebase Authentication for secure logins
- HTTPS encryption for all data transfers

---

### 📄 README Update: Dynamic Event Scheduler Web Application

# Dynamic Event Scheduler

A comprehensive event scheduling application built with **Spring Boot** and **MySQL**, allowing users to manage events and view schedules efficiently.

## 🚀 Features
- Full CRUD operations for events
- JWT-based secure user authentication
- Event calendar views (Day, Week, Month)
- Comprehensive API documentation using Swagger

## 🛠️ Tech Stack
- **Backend:** Spring Boot 3.0
- **Database:** MySQL
- **Authentication:** JSON Web Tokens (JWT)
- **API Documentation:** Swagger UI

## 📊 Documentation
- [Design Document](./docs/design-doc.md)
- [STRIDE Threat Model](./docs/stride-threat-model.md)

## ⚡ Setup Instructions
1. Clone the repo:
   ```bash
   git clone https://github.com/chuksieee/Event-Scheduler-Application.git
   ```
2. Build the project:
   ```bash
   mvn clean install
   ```
3. Run the application:
   ```bash
   mvn spring-boot:run
   ```
4. Access API docs at `http://localhost:8080/swagger-ui.html`

## 🛡️ Security
- JWT tokens for user authentication
- HTTPS encryption for all sensitive data
- Input validation and role-based access control

---

This README update ensures that engineers and recruiters can easily access the **Design Docs**, **Threat Models**, and have clear instructions for running each project.



```vercel```

This command will start the deployment process. Follow the prompts, and Vercel will guide you through the setup.

Once the deployment is successful, Vercel will provide you with a deployment link. You can include this link in your README file under a "Deployment" section.
