# template

Reference starter project used as a base template for creating new microservices in the [AlgaShop](https://github.com/jeanmalvessi/ems-algashop-meta) platform.

Contains the standard project structure, build configuration, and common dependencies shared across AlgaShop microservices.

## Includes

- Spring Boot 4.0.1 setup with Gradle
- Spring Web MVC, Data JPA, Validation, REST Client, Flyway, Spring Cloud Contract
- PostgreSQL driver and Flyway PostgreSQL support
- Testcontainers (PostgreSQL), WireMock, AssertJ, REST Assured
- Separate unit test / integration test / contract test task configuration
- Lombok annotation processing
- Mockito agent setup
- Multi-platform Docker image build via `dockerBuild` Gradle task

## Tech Stack

- **Java 25**, Spring Boot 4.0.1, Spring Cloud 2025.1.0
- **Build:** Gradle
- **Database:** PostgreSQL + Flyway
- **Utilities:** Lombok, Hypersistence TSID, Commons Validator
- **Testing:** JUnit 5, Mockito, AssertJ, REST Assured, Testcontainers, Spring Cloud Contract
