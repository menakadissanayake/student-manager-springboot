# Student Registration System

A web-based Student Registration System developed using Spring Boot, Thymeleaf, Spring Data JPA, and the H2 database.

## Features

- Register new students
- View all registered students
- Edit student details
- Delete student records
- Validate student details, including email, phone number, and age
- Prevent duplicate email addresses
- Store student records using an H2 database

## Technologies Used

- Java 17
- Spring Boot
- Spring MVC
- Thymeleaf
- Spring Data JPA
- H2 Database
- Maven
- HTML and CSS

## How to Run

1. Clone or download this repository.
2. Open the project in IntelliJ IDEA.
3. Make sure Java 17 or a compatible configured JDK is installed.
4. Run `StudentManagerApplication.java`.
5. Open http://localhost:8080 in your browser.

## H2 Database Console

Open http://localhost:8080/h2-console.

For the in-memory database, use:

- **JDBC URL:** `jdbc:h2:mem:studentdb`
- **Username:** `sa`
- **Password:** Leave blank

Note: With the in-memory configuration, student records disappear when the application stops.

## Course

COSC 32133 / BECS 32263 — Full-Stack Software Development, Lab Sheet 04