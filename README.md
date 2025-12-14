# Employee-Management-Sys 🚀

The Employee Management System is a full-stack web application designed to manage employee records efficiently.
The backend is built using Spring Boot, Spring Data JPA, and MySQL, providing secure and scalable RESTful APIs, while the frontend is developed using React (Vite), JavaScript, and Bootstrap for a clean and responsive user interface.

This application supports complete CRUD operations (Create, Read, Update, Delete) on employee data.

# Features ✨

- View a list of all employees
- Add a new employee
- Update existing employee details
- Delete an employee
- Responsive UI using Bootstrap
- RESTful APIs with Spring Boot
- Persistent data storage with MySQL

# Tech Stack 🛠️

- Backend: Spring Boot (Java), REST API
- Database: MySQL

# Project Structure

Employee-Management-System
├── backend
│ ├── controller
│ ├── service
│ ├── repository
│ ├── dto
│ ├── mapper
│ └── model
└── frontend
├── components
├── services
└── pages

🔗 API Endpoints

| Method | Endpoint             | Description         |
| ------ | -------------------- | ------------------- |
| POST   | `/api/employee`      | Create new employee |
| GET    | `/api/employee`      | Get all employees   |
| GET    | `/api/employee/{id}` | Get employee by ID  |
| PUT    | `/api/employee/{id}` | Update employee     |
| DELETE | `/api/employee/{id}` | Delete employee     |

▶️ How to Run the Project

Backend

1.Create MySQL database: employee
2.Update application.properties
3.Run EmployeeManagementSystemApplication
4.Backend runs on http://localhost:8080

Frontend

1.Navigate to frontend folder
2.Install dependencies
npm install

3.Start frontend
npm run dev

4.Frontend runs on http://localhost:3000

🚀 Future Enhancements

Authentication & Authorization (JWT)
Pagination & Sorting
Role-based access (Admin/User)
Docker deployment

👨‍💻 Author
Piyush Kumar Dubey
Spring Boot • React • MySQL • REST APIs
