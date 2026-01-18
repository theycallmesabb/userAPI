# 👥 UserManagementAPI

A secure and scalable RESTful API for user management built with **Spring Boot** and **Spring Security**. This API supports user registration, authentication, role-based access control, and CRUD operations on users.

---

## 🧱 Project Structure

  userManagementAPI/
├── config/ # Spring Security Configuration
├── controller/ # REST Controllers
├── service/ # Business Logic Layer
├── repository/ # JPA Repositories
├── model/ # Entity Classes (User, Role)
├── dto/ # DTOs for Requests & Responses
└── UserManagementApiApplication.java



---

## 🔧 Technologies Used

- Java 17
- Spring Boot 3.x
- H2 / MySQL
- Postman (for API testing)


---

## 🧪 API Endpoints

| Method | Endpoint                  | Role Access    | Description                  |
|--------|---------------------------|----------------|------------------------------|
| POST   | `/api/users/register`     | Public         | Register a new user          |
| GET    | `/api/users`              | ADMIN          | Fetch all users              |
| GET    | `/api/users/{id}`         | USER, ADMIN    | Fetch user by ID             |
| PUT    | `/api/users/{id}`         | USER, ADMIN    | Update user by ID            |
| DELETE | `/api/users/{id}`         | ADMIN          | Delete user by ID            |
| GET    | `/api/users/page`         | Public         | Paginated user fetch (test)  |









