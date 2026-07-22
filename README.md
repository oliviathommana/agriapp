# 🌾 AgriApp – Smart Agriculture Management System

AgriApp is a Spring Boot REST API developed to simplify agricultural management by providing a centralized platform for managing farmers, fields, crops, distributors, and irrigation schedules.

The application demonstrates CRUD operations using Spring Boot ,RESTful APIs with an in-memory database, making it suitable for learning and academic projects.

---

# 🚀 Features

- Farmer Management
- Field Management
- Crop Management
- Distributor Management
- Irrigation Schedule Management
- RESTful APIs
- CRUD Operations
- JSON Request & Response
- Swagger API Documentation
- In-Memory Database (H2)

---

## 🛠️ Tech Stack

- Java 21
- Spring Boot 3
- Spring Data JPA
- Maven
- H2 Database
- Swagger / OpenAPI
- Postman

---

## 📂 Project Structure

```
agriapp/
│── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/example/agriapp/
│   │   │       ├── controller/
│   │   │       ├── service/
│   │   │       ├── repository/
│   │   │       ├── model/
│   │   │       └── AgriAppApplication.java
│   │   └── resources/
│   │       ├── application.properties
│── pom.xml
│── README.md
```

---

## 📌 Modules

### 👨‍🌾 Farmer
- Add Farmer
- View Farmers
- Update Farmer
- Delete Farmer

### 🌱 Field
- Register Field
- View Fields
- Update Field
- Delete Field

### 🌾 Crop
- Add Crop
- Manage Crop Details
- Delete Crop

### 🚚 Distributor
- Add Distributor
- Update Distributor
- Delete Distributor

### 💧 Irrigation Schedule
- Create Schedule
- Update Schedule
- Delete Schedule

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/agriapp.git
```

### Move into Project

```bash
cd agriapp
```

### Build Project

```bash
mvn clean install
```

### Run Application

```bash
mvn spring-boot:run
```

Application runs at:

```
http://localhost:8080
```

---

## 📖 API Documentation

Swagger UI

```
http://localhost:8080/swagger-ui/index.html
```

OpenAPI Docs

```
http://localhost:8080/v3/api-docs
```

---

## 🧪 Testing

Use Postman or Swagger UI to test the REST APIs.

Example:

```
POST /farmers
GET /farmers
PUT /farmers/{id}
DELETE /farmers/{id}
```

---

## 📦 Dependencies

- Spring Web
- Spring Boot Starter Data JPA
- H2 Database
- Spring Boot DevTools
- Springdoc OpenAPI
- Lombok (Optional)

---

## 🎯 Learning Outcomes

- Spring Boot Fundamentals
- REST API Development
- MVC Architecture
- Dependency Injection
- CRUD Operations
- JPA & Hibernate
- Maven Build Management
- API Documentation using Swagger

---

## 🔮 Future Enhancements

- MySQL Database
- Spring Security Authentication
- JWT Authorization
- File Upload Support
- Docker Deployment
- Cloud Deployment
- Email Notifications

---

## 👩‍💻 Author

**Olivia Thommana**

B.Tech Computer Science Engineering

---

## 📄 License

This project is developed for educational purposes.

