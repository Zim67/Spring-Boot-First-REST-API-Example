# Spring Boot First REST API Example

## 📌 Project Overview

This project is a beginner-friendly Spring Boot REST API example created to demonstrate how to build and test basic RESTful web services using Java and Maven.

The application exposes HTTP endpoints that return JSON responses instead of rendering web pages. It is designed for learning and practicing backend development concepts.

---

## 🛠 Technologies Used

* Java
* Spring Boot
* Maven
* RESTful Web Services
* JSON

---

## 🚀 Features

* Create REST endpoints using `@RestController`
* Handle HTTP GET and POST requests
* Return JSON responses
* Simple in-memory data handling
* Beginner-friendly structure for learning

---

## 📂 Project Structure

```
src/main/java/
    controller/     → Defines API endpoints
    model/          → Data models
    service/        → Business logic (if included)

src/main/resources/
    application.properties
```

---

## ▶️ How to Run the Application

### Option 1: Using Maven Wrapper

For Mac/Linux:

```
./mvnw spring-boot:run
```

For Windows:

```
mvnw.cmd spring-boot:run
```

### Option 2: Build and Run JAR

1. Build the project:

```
./mvnw clean package
```

2. Run the generated JAR:

```
java -jar target/*.jar
```

---

## 🌐 Access the API

Once the application is running, open:

```
http://localhost:8080
```

You can test endpoints using:

* Browser (GET requests)
* Postman
* curl

---

## 🧪 Running Tests

```
./mvnw test
```

---

## 📖 Learning Objectives

* Understand REST architecture
* Learn how HTTP methods work (GET, POST, etc.)
* Practice building APIs with Spring Boot
* Work with JSON data

---

## 👤 Author

Zimuzo Akanne

---

## 📌 Suggested GitHub Repository Names

Choose one of the following clean, professional names:

* springboot-first-rest-api
* java-rest-api-example
* springboot-rest-demo
* rest-api-learning-project
* backend-rest-api-practice

Recommended: **springboot-first-rest-api**

---

## 🔮 Future Improvements

* Add PUT and DELETE endpoints
* Connect to a database (MySQL/PostgreSQL)
* Add validation
* Implement exception handling
* Add Swagger API documentation
