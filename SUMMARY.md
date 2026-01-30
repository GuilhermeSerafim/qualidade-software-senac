# Educational Quality Project - Summary

This is an educational Java project using Spring Boot and Maven for teaching quality concepts to students. The project implements a simple student and teacher registration system with a basic web interface.

## Project Structure

```
educational-quality-project/
├── pom.xml
├── README.md
├── .mvn/
│   └── wrapper/
│       ├── maven-wrapper.jar
│       └── maven-wrapper.properties
├── mvnw
├── mvnw.cmd
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── educationalqualityproject/
│   │   │               ├── EducationalQualityProjectApplication.java
│   │   │               ├── controller/
│   │   │               │   ├── HomeController.java
│   │   │               │   ├── StudentController.java
│   │   │               │   └── TeacherController.java
│   │   │               ├── entity/
│   │   │               │   ├── Student.java
│   │   │               │   └── Teacher.java
│   │   │               ├── repository/
│   │   │               │   ├── StudentRepository.java
│   │   │               │   └── TeacherRepository.java
│   │   │               ├── service/
│   │   │               │   ├── StudentService.java
│   │   │               │   └── TeacherService.java
│   │   ├── resources/
│   │   │   ├── application.properties
│   │   │   └── templates/
│   │   │       ├── home.html
│   │   │       ├── layout.html
│   │   │       ├── student/
│   │   │       │   ├── form.html
│   │   │       │   └── list.html
│   │   │       └── teacher/
│   │   │           ├── form.html
│   │   │           └── list.html
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── educationalqualityproject/
│                       ├── EducationalQualityProjectApplicationTests.java
│                       └── controller/
│                           └── HomeControllerTest.java
```

## Features Implemented

1. **Student Management**:
   - View all students
   - Add new students
   - Edit existing students
   - Delete students

2. **Teacher Management**:
   - View all teachers
   - Add new teachers
   - Edit existing teachers
   - Delete teachers

3. **Frontend**:
   - Bootstrap-based responsive UI
   - Thymeleaf templates for server-side rendering
   - Clean, organized layout

4. **Backend**:
   - Spring Boot application
   - JPA/Hibernate for data persistence
   - H2 in-memory database
   - MVC architecture
   - Service layer for business logic
   - Repository layer for data access

## How to Run

1. Ensure you have Java 17+ and Maven installed
2. Navigate to the project directory
3. Run: `mvn spring-boot:run`
4. Open your browser to: http://localhost:8080

## Educational Objectives

This project serves as an excellent learning tool for:
- Understanding Spring Boot fundamentals
- Learning MVC architecture patterns
- Practicing CRUD operations
- Working with databases in Java applications
- Creating web interfaces with Thymeleaf
- Understanding layered architecture (Controller, Service, Repository)
- Learning about dependency injection
- Understanding RESTful API design principles
- Testing Spring Boot applications