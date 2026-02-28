# AOP Codelab - Spring Boot 4 + Kotlin

This is a modern Spring Boot 4 project using Kotlin, Maven, and Swagger UI, designed to explore Aspect-Oriented Programming (AOP).

## 🚀 Features

- **Spring Boot 4.0.3**: Using the latest stable version of Spring Boot.
- **Kotlin 2.2.0**: Modern, concise programming language.
- **Swagger UI**: Integrated API documentation using `springdoc-openapi`.
- **Docker Support**: Multi-stage Dockerfile for optimized container builds.
- **REST API**: Simple `/hello` endpoint to get started.

## 🛠 Prerequisites

- **Java 17 or later** (Recommended: Java 21+)
- **Maven 3.8+**
- **Docker** (Optional)

## 🏃 Running Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/blasiusneri/aop-codelab.git
   cd aop-codelab
   ```

2. **Run the application:**
   ```bash
   mvn spring-boot:run
   ```

3. **Access the application:**
   - **Hello Endpoint:** [http://localhost:8081/hello](http://localhost:8081/hello)
   - **Swagger UI:** [http://localhost:8081/swagger-ui/index.html](http://localhost:8081/swagger-ui/index.html)

## 🐳 Running with Docker

1. **Build the image:**
   ```bash
   docker build -t aop-codelab .
   ```

2. **Run the container:**
   ```bash
   docker run -d -p 8081:8081 --name aop-app aop-codelab
   ```

## 📂 Project Structure

- `src/main/kotlin`: Application source code and controllers.
- `src/test/kotlin`: Integration and unit tests.
- `src/main/resources`: Configuration (`application.properties`).
- `pom.xml`: Maven dependency and build configuration.
- `Dockerfile`: Containerization instructions.
