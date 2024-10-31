# 📚 Library Management System

This project provides a simple REST API for a library management system, developed using Spring Boot. The API allows for efficient management of books, authors, and copies, enabling operations such as adding, updating, deleting, and retrieving information.

## 🌟 Key Features

- **Full CRUD Functionality**: Comprehensive Create, Read, Update, and Delete operations.
- **Data Transfer Object (DTO) Pattern**: Efficient data exchange between layers.
- **PostgreSQL Database Integration**: Robust and scalable data storage solution.
- **Advanced Error Handling**: Custom exceptions for specific scenarios and global error handling for consistent responses.
- **Comprehensive Testing Suite**: Integration tests using TestContainers and unit tests with Mockito and JUnit 5.
- **API Documentation**: Interactive API documentation using Swagger/OpenAPI.
- **Best Practices Implementation**: Adherence to software design principles and industry standards.

## 👥 Contributing

We appreciate your interest in contributing to **Library Management System**. Here's how you can get started:

1. **Find Issues or Create Your Own**: Solve existing issues or create new ones in the repository's issues tab.
2. **Fork the Repository**: Click the "Fork" button at the top of this repository to create a copy in your GitHub account.
3. **Clone Your Fork**: Clone your fork to your local machine with:
   ```bash
   git clone https://github.com/<your_github_username>/Library-Management-System.git
   ```
4. **Change the Working Directory**:
   ```bash
   cd Library-Management-System
   ```
5. **Add an Upstream Link to the Main Branch**:
   ```bash
   git remote add upstream https://github.com/<your_github_username>/Library-Management-System.git
   ```
6. **Keep Your Fork Updated**:
   ```bash
   git pull upstream main
   ```
7. **Create a New Branch**:
   ```bash
   git checkout -b <branch-name>
   ```
8. **Make Changes**: Implement your desired feature or fix a bug.
9. **Track and Stage Your Changes**:
   ```bash
   git status
   git add .
   ```
10. **Commit Your Changes**:
    ```bash
    git commit -m "<your-commit-message>"
    ```
11. **Push the Changes for Review**:
    ```bash
    git push origin <branch-name>
    ```
12. **Open a Pull Request**: Create a pull request from your fork to this repository. Provide a concise title and description.

We'll review your contribution and collaborate to merge it into the project. Please adhere to our code of conduct and guidelines. If you have questions or need assistance, feel free to open an issue.

## 🛠️ Installation

1. **Running PostgreSQL for Integration Testing with Docker Desktop**:
   Download Docker Desktop from the official website: [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. **Configure the Application Properties**:
   Update the following properties in your application configuration file:
   ```properties
   spring.datasource.url=jdbc:postgresql://<HOST>:<PORT>/<DATABASE_NAME>
   spring.datasource.username=<USERNAME>
   spring.datasource.password=<PASSWORD>
   ```
3. **Start The Application**:
   ```bash
   ./mvnw spring-boot:run
   ```

## 📖 API Documentation

1. **Start The Application**:
   ```bash
   ./mvnw spring-boot:run
   ```
2. **Access API Documentation**:
   Open your web browser and navigate to: [Swagger UI](http://localhost:8080/swagger-ui/index.html)
