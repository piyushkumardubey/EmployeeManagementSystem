🚀 Employee Management System

A full-stack Employee Management System built to manage employee records efficiently.
The project follows a modern, scalable architecture with a Spring Boot REST API backend and a React (Vite) frontend, connected via clean RESTful services.

📌 Overview

Backend: Spring Boot + Spring Data JPA + MySQL

Frontend: React (Vite) + JavaScript + Bootstrap

Architecture: REST-based, layered, and scalable

Operations: Full CRUD (Create, Read, Update, Delete)


                                                              ✨ Features

✔ View all employees

✔ Add new employees

✔ Update existing employee details

✔ Delete employees

✔ Responsive UI with Bootstrap

✔ RESTful APIs using Spring Boot

✔ Persistent storage using MySQL

                                                               🛠️ Tech Stack

🔙 Backend

Java 17

Spring Boot

Spring Data JPA

Hibernate

REST APIs

🗄️ Database

MySQL

                                                               📂 Project Structure

Employee-Management-System

├── backend

│   ├── controller

│   ├── service

│   ├── repository

│   ├── dto

│   ├── mapper

│   └── model

└── frontend
    ├── components 
    ├── services
    └── pages



                                                                  🔗 API Endpoints


| Method | Endpoint             | Description        |
| ------ | -------------------- | ------------------ |
| POST   | `/api/employee`      | Create employee    |
| GET    | `/api/employee`      | Get all employees  |
| GET    | `/api/employee/{id}` | Get employee by ID |
| PUT    | `/api/employee/{id}` | Update employee    |
| DELETE | `/api/employee/{id}` | Delete employee    |



                                                                 ▶️ How to Run the Project

🔙 Backend Setup

1.Create MySQL database: CREATE DATABASE employee;

2.Update application.properties

3.Run:EmployeeManagementSystemApplication

4.Backend runs at:http://localhost:8080


🎨 Frontend Setup

1. Navigate to frontend folder

2. Install dependencies: npm install

3. Start application:npm run dev

4.Frontend runs at:http://localhost:3000


                                                                    🚀 Future Enhancements

🔐 Authentication & Authorization (JWT)

📄 Pagination & Sorting

👥 Role-based access (Admin / User)

🐳 Docker containerization

☁️ Cloud deployment

                                                                  👨‍💻 Author

Piyush Kumar Dubey

Spring Boot • React • MySQL • REST APIs






                                                           




