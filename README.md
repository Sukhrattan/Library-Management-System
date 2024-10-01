# library-management-system
This project provides a simple REST API for a library management system, developed using Spring Boot. The API allows for efficient management of books, authors, and copies, enabling operations such as adding, updating, deleting, and retrieving information.

## Key Features

1. **Full CRUD Functionality**
   - Comprehensive Create, Read, Update, and Delete operations
2. **Data Transfer Object (DTO) Pattern**
   - Efficient data exchange between layers
3. **PostgreSQL Database Integration**
   - Robust and scalable data storage solution
4. **Advanced Error Handling**
   - Custom exceptions for specific scenarios
   - Global error handling for consistent responses
5. **Comprehensive Testing Suite**
   - Integration tests using TestContainers for realistic database interactions
   - Unit tests with Mockito and JUnit 5 for thorough code coverage
6. **API Documentation**
   - Interactive API documentation using Swagger/OpenAPI
7. **Best Practices Implementation**
   - Adherence to software design principles and industry standards

## Contributing

We appreciate your interest in contributing to **Library Management System**. Here's how you can get started:


0. **Find Issues or Create your Own** We appreciate you solving existing issues in the repository in the issues tab or to create new

1. **Fork the Repository:** Click the "Fork" button at the top of this repository to create a copy in your GitHub account.


2. **Clone Your Fork:** Clone your fork to your local machine with `git clone`.

    git clone https://github.com/<your_github_username>/Library-Management-System.git

3. **Change the working directory:**  cd Library-Management-System

4. **Add an upstream link to the main branch in your cloned repo:**

    git remote add upstream https://github.com/<your_github_username>/Library-Management-System.git

5. **Keep your cloned repo up to date by pulling from upstream (this will also avoid any merge conflicts while committing new changes):**

    git pull upstream main

6. **Create a New Branch:** Make a new branch for your work with a descriptive name.

    git checkout -b <branch-name>

7. **Make Changes:** Implement your desired feature or fix a bug.

8. **Track and stage your changes:**

    git status

9. **Add all the required changes:**

    git add .

10. **Commit all the changes (Write commit message as "Small Message"):**

    git commit -m "<your-commit-message>"

11. **Push the changes for review:**

    git push origin <branch-name>

12. **Open a Pull Request:** Create a pull request from your fork to this repository. Provide a concise title and description.

We'll review your contribution and collaborate to merge it into the project. Please adhere to our code of conduct and guidelines.

If you have questions or need assistance, feel free to open an issue.

## Installation

1. **Running PostgreSQL for Integration Testing with Docker Desktop** <br>
   To run a PostgreSQL image for integration testing, you need to use Docker Desktop. You can download Docker Desktop from the official website: [Docker Desktop](https://www.docker.com/products/docker-desktop/)
2. **Configure the application properties:** <br>
To connect your application to the PostgreSQL database, update the following properties in your application configuration file:
   ```properties
   spring.datasource.url=jdbc:postgresql://<HOST>:<PORT>/<DATABASE_NAME>
   spring.datasource.username=<USERNAME>
   spring.datasource.password=<PASSWORD>
   ```
5. **Start The Application**
   ```bash
   ./mvnw spring-boot:run

## API Documentation 
1. **Start The Application**
   ```bash
   ./mvnw spring-boot:run
   ```
2.   **Access API Documentation** <br>
     Open your web browser and navigate to <br>
     http://localhost:8080/swagger-ui/index.html
     


