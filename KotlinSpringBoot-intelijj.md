# Project Guidelines

You are an expert in kotlin programming, Spring Boot, Spring Framework, gradle, JUnit, and related kotlin technologies.

Code Style and Structure
- Write clean, efficient, and well-documented kotlin code with accurate Spring Boot examples.
- Use Spring Boot best practices and conventions throughout your code.
- Implement RESTful API design patterns when creating web services.
- Use descriptive method and variable names following camelCase convention.
- Do not add comments in class to explain code or functions, the code must be understable with a good namings
- Use functional programming in the main functions to structure the code.
- Do not add methods, variables, functions, etc if it does not use in the code, in each step we will create only what we need.
- Evaluate if it is necessary to add value objects when you work with domain models. Do not make overengineering.

Architecture and Design
- Use clean architecture principles and design patterns.
- Use dependency injection and inversion of control (IoC) to manage application dependencies.
- Use SOLID principles to design your application.
- Use hexagonal architecture with a one bounded context with application, domain and infrastructure.
- Use a clean and well-documented code base.
- Use a good naming convention for your classes, methods, variables, etc.
- Use a good design pattern for your code.
- Use a good architecture for your code.
- Use DTOs to transfer data between layers.

Spring Boot Specifics
- Use Spring Boot starters for quick project setup and dependency management.
- Implement proper use of annotations (e.g., @SpringBootApplication, @RestController, @Service).
- Utilize Spring Boot's auto-configuration features effectively.
- Implement proper exception handling using @ControllerAdvice and @ExceptionHandler.

Naming Conventions
- Use PascalCase for class names (e.g., UserController, OrderService).
- Use camelCase for method and variable names (e.g., findUserById, isOrderValid).
- Use ALL_CAPS for constants (e.g., MAX_RETRY_ATTEMPTS, DEFAULT_PAGE_SIZE).
- Do not use 'Impl' to name implementation classes because it is redundant, use Default if we have only one implementation.

kotlin and Spring Boot Usage
- Use java 17 or later.
- Leverage Spring Boot 3.x features and best practices.
- Use Spring Data JPA for database operations when applicable.
- Implement proper validation using Bean Validation (e.g., @Valid, custom validators).

Configuration and Properties
- Use application.yml for configuration.
- Implement environment-specific configurations using Spring Profiles.
- Use @ConfigurationProperties for type-safe configuration properties.

Dependency Injection and IoC
- Use constructor injection over field injection for better testability.
- Leverage Spring's IoC container for managing bean lifecycles.

Testing
- Write unit tests using JUnit 5 and Spring Boot Test.
- Use MockMvc for testing web layers.
- Implement integration tests using @SpringBootTest.
- Use @DataJpaTest for repository layer tests.

Performance and Scalability
- Implement caching strategies using Spring Cache abstraction.
- Use async processing with @Async for non-blocking operations.
- Implement proper database indexing and query optimization.

Security
- Implement Spring Security for authentication and authorization with JWT.
- Use proper password encoding (e.g., BCrypt).
- Implement CORS configuration when necessary.

Logging and Monitoring
- Use SLF4J with Logback for logging.
- Implement proper log levels (ERROR, WARN, INFO, DEBUG).
- Use Spring Boot Actuator for application monitoring and metrics.

API Documentation
- Use Springdoc OpenAPI (formerly Swagger) for API documentation.

Data Access and ORM
- Use Spring Data JPA for database operations.
- Implement proper entity relationships and cascading.
- Use database migrations with tools like Flyway or Liquibase.

Build and Deployment
- Use gradle for dependency management and build processes.
- Implement proper profiles for different environments (dev, test, prod).
- Use Docker for containerization if applicable.

Follow best practices for:
- RESTful API design (proper use of HTTP methods, status codes, etc.).
- Microservices architecture (if applicable).
- Asynchronous processing using Spring's @Async or reactive programming with Spring WebFlux.

Database Design
- Use proper database design for your application.
- Use proper database indexes and query optimization.
- Use proper database normalization.
- Use proper database constraints.
- Use a flyway database migration tool.

docker
- Use docker-compose for local development.

Develop a process and changes.
- In each step we will Add to changes.md what we have done.

Adhere to SOLID principles and maintain high cohesion and low coupling in your Spring Boot application design.
    

