# TODO App

This is a simple TODO App built using Java Spring Boot, JSP, and Spring Data JPA.

## Features

- Create, Read, Update, and Delete (CRUD) operations for managing TODO items.
- User-friendly interface for managing TODO items.
- Secure authentication and authorization mechanisms.
- Integration with a database for persistent storage of TODO items.

## Tech Stack

- **Java**: The primary programming language used for backend development.
- **Spring Boot**: A powerful framework for building Java-based applications, providing dependency injection, embedded servers, and other features out of the box.
- **JSP (JavaServer Pages)**: A technology for developing web pages with dynamic content, which is used for rendering user interfaces in this application.
- **Spring Data JPA**: Part of the larger Spring Data project, Spring Data JPA simplifies data access layer development by providing a higher-level abstraction over JPA (Java Persistence API).
- **HTML/CSS/JavaScript**: Used for frontend development to create user interfaces and add interactivity.

## Setup Instructions

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Make sure you have Java JDK installed on your machine. If not, you can download and install it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
3. Install Maven build tool. You can download and install it from [here](https://maven.apache.org/download.cgi).
4. Set up a MySQL database. You can use any other relational database as well.
5. Update the database configuration in `application.properties` file located in `src/main/resources` with your database credentials.
6. Navigate to the project directory in your terminal.
7. Run `mvn spring-boot:run` to start the application.
8. Open your web browser and go to `http://localhost:8080` to access the TODO App.

## License

This project is licensed under the [MIT License](LICENSE).
