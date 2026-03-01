# 📚 Smart Library Management System

A full-stack **Spring Boot Library Management System** that allows users to browse books, make reservations, join waitlists, write reviews, and manage library resources through an admin workspace.

Built as part of ELEC5619, this project demonstrates backend architecture, database design, authentication, and frontend integration.

---

## 🚀 Features

### 👤 User Features
- 🔐 User Registration & Login
- 📖 Browse and Search Books
- 📅 Book Reservation System
- ⏳ Waitlist Management
- ⭐ Reviews & Comments
- 🔑 Password Reset

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
- MySQL (or H2 if configured)
- Schema + Seed Data Included

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

Open in browser:

```
http://localhost:8080
```

---

## 🔐 User Roles

| Role  | Access |
|-------|--------|
| USER  | Browse, reserve, review |
| ADMIN | Manage books, users, statistics |

---

## 🏛 Architecture

The system follows a layered architecture:

- Controller Layer → Handles HTTP requests  
- Service Layer → Business logic  
- Repository Layer → Database operations  
- Model Layer → Entity definitions  

This structure ensures maintainability, scalability, and clean separation of concerns.

---

## 🎯 Learning Outcomes

This project demonstrates:

- RESTful backend development  
- Authentication & authorization  
- Database schema design  
- MVC architecture  
- Role-based access control  
- Full-stack integration  

---

## 🧠 Future Improvements

- Responsive UI redesign  
- Docker containerization  
- Unit & Integration Testing  
- Advanced analytics dashboard  
- Email notifications for reservations  

---

## 👨‍💻 Author

Pulkit Shrimali  
Bachelor of Software Engineering (Honours)  
Major: Intelligent Information Engineering  

---

## 📄 License

Developed for academic purposes.
