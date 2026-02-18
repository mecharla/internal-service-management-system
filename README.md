# Internal Service Management System

A Spring Boot RESTful API project built to manage internal service operations.  
This application demonstrates CRUD operations using Spring Boot, Spring Data JPA, and REST APIs.

---

## 🚀 Features

- Create, Read, Update, Delete (CRUD) operations
- RESTful API architecture
- Global Exception Handling
- Layered architecture (Controller, Service, Repository)
- H2/MySQL compatible configuration
- Clean and maintainable project structure

---

## 🛠️ Technologies Used

- Java 17+
- Spring Boot
- Spring Data JPA
- Maven
- REST APIs
- H2 / MySQL Database

---

## 📁 Project Structure

```text
src
├── main
│   ├── java
│   │   └── com/poojitha/internalservice
│   │       ├── InternalServiceApplication.java
│   │       ├── controller/UserController.java
│   │       ├── service/UserService.java
│   │       ├── repository/UserRepository.java
│   │       ├── entity/User.java
│   │       └── exception
│   │           ├── GlobalExceptionHandler.java
│   │           └── ResourceNotFoundException.java
│   └── resources
│       └── application.properties
└── test
    └── java/com/poojitha/internalservice
        └── InternalServiceApplicationTests.java
```




## ⚙️ How to Run the Project

1. Clone the repository:

2. Navigate to project directory:

3. Run using Maven:

Or run `InternalServiceApplication.java` directly from your IDE.

---

## 🔗 API Endpoints Example

| Method | Endpoint | Description |
|--------|----------|------------|
| GET    | /api/users | Get all users |
| GET    | /api/users/{id} | Get user by ID |
| POST   | /api/users | Create new user |
| PUT    | /api/users/{id} | Update user |
| DELETE | /api/users/{id} | Delete user |

---

## 📌 Author

Poojitha Mecharla  

---

## ⭐ Future Enhancements

- Add Swagger Documentation
- Add Authentication (JWT)
- Add Docker support
- Deploy to Cloud

---

## 📄 License

This project is for educational and learning purposes.
