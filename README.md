# Spring Boot Login API

This is a simple Spring Boot REST API project with a login endpoint.

## Running the Application

1. Ensure you have Java 17 and Maven installed.
2. Navigate to the project directory.
3. Run `mvn spring-boot:run`

The application will start on port 8080.

## API Endpoint

- POST /api/login
  - Body: JSON with username and password
  - Example: {"username": "admin", "password": "password"}
  - Response: "Login successful!" or "Invalid credentials"

## Security

Basic Spring Security is configured with default user admin/password.