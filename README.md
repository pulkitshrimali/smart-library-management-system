# 📚 Smart Library Management System

A full-stack Library Management System built using Spring Boot that allows users to browse books, make reservations, join waitlists, write reviews, and manage resources through an administrative dashboard.

This system demonstrates secure authentication, role-based access control, database integration, and a clean layered architecture.

---

## 🚀 Features

### 👤 User Features
- 🔐 User Registration & Login
- 📖 Browse and Search Books
- 📅 Book Reservation System
- ⏳ Waitlist Management
- ⭐ Reviews & Comments
- 🔑 Password Reset Functionality

### 🛠 Admin Features
- ➕ Add / Edit / Delete Books
- 👥 Manage Users
- 📊 View Library Statistics
- 📚 Manage Reservations
- 🗂 Manage Reviews

---

## 🏗 Tech Stack

### Backend
- Java
- Spring Boot
- Spring Security
- JPA / Hibernate

### Frontend
- HTML
- CSS
- JavaScript

### Database
- MySQL (or H2, depending on configuration)

---

## 📂 Project Structure

```
library-management-system/
│
├── src/main/java/
│   ├── controller/
│   ├── service/
│   ├── repository/
│   ├── model/
│   └── LibraryManagementApplication.java
│
├── src/main/resources/
│   ├── templates/
│   ├── static/
│   ├── application.properties
│   └── schema.sql / data.sql
│
└── pom.xml
```

---

## ⚙️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/yourusername/smart-library-management-system.git
cd smart-library-management-system
```

### 2️⃣ Configure Database

Update `application.properties`:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/library_db
spring.datasource.username=root
spring.datasource.password=yourpassword
```

Create the database:

```sql
CREATE DATABASE library_db;
```

---

### 3️⃣ Run the Application

Using Maven:

```bash
mvn spring-boot:run
```

Or run `LibraryManagementApplication.java` directly from your IDE.

---

### 4️⃣ Access the Application

Open your browser and navigate to:

```
http://localhost:8080
```

---

## 🔐 Role-Based Access

| Role  | Permissions |
|-------|------------|
| USER  | Browse, reserve, review books |
| ADMIN | Manage books, users, reservations, statistics |

---

## 🏛 Architecture

This project follows a layered architecture:

- **Controller Layer** → Handles HTTP requests  
- **Service Layer** → Business logic  
- **Repository Layer** → Database operations  
- **Model Layer** → Entity definitions  

This ensures separation of concerns, scalability, and maintainability.

---

## 🧠 Potential Enhancements

- Responsive UI redesign  
- Docker containerization  
- Automated testing (Unit & Integration)  
- Email notifications  
- REST API documentation (Swagger/OpenAPI)  

---

## 👨‍💻 Author

Pulkit Shrimali  
Software Engineering Student  
Interested in Backend Systems, Security & Intelligent Systems  

---

## 📄 License

This project is available for learning and demonstration purposes.
