# Educational Quality Project

This is an educational Java project using Spring Boot and Maven for teaching quality concepts to students. The project implements a simple student and teacher registration system with a basic web interface.

## Features

- Student registration and management
- Teacher registration and management
- Simple web interface using Thymeleaf and Bootstrap
- H2 in-memory database for easy setup

## Technologies Used

- Java 17
- Spring Boot 3.2.0
- Maven
- JPA/Hibernate
- Thymeleaf
- Bootstrap
- H2 Database

## Getting Started

### Prerequisites

- Java 17 or higher
- Maven 3.6.0 or higher

### Running the Application

1. Clone the repository
2. Navigate to the project directory
3. Run the application using Maven:

```bash
./mvnw spring-boot:run
```

Or build and run the JAR:

```bash
./mvnw clean package
java -jar target/educational-quality-project-0.0.1-SNAPSHOT.jar
```

### Accessing the Application

After starting the application, you can access it at:
- Main page: http://localhost:8080
- Students page: http://localhost:8080/students
- Teachers page: http://localhost:8080/teachers
- H2 Console: http://localhost:8080/h2-console

For the H2 console, use the JDBC URL: `jdbc:h2:mem:testdb`

## Project Structure

- `entity/` - JPA entities for Student and Teacher
- `repository/` - Data access layer interfaces
- `service/` - Business logic layer
- `controller/` - Web controllers
- `templates/` - Thymeleaf templates with Bootstrap

## Educational Value

This project demonstrates:
- Basic CRUD operations
- MVC architecture
- Spring Boot fundamentals
- JPA/Hibernate usage
- Dependency injection
- RESTful API design
- Database integration
- Frontend templating with Thymeleaf