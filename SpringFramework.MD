```mermaid
graph TD
    A[Spring Boot]
    A --> C[Spring Core Concepts]
    C[Spring Core Concepts]:::greenText
    A --> D[Build Automation - Maven/Gradle]
    D[Build Automation - Maven/Gradle]:::greenText
    A --> E[Spring Boot Starters]
    E[Spring Boot Starters]:::greenText
    
    %% Core Concepts
    C --> F[Dependency Injection]:::greenText
    C --> G[Autoconfiguration]
    
    %% Configuration & DevTools
    G --> H[Properties & YAML]
    G --> I[Actuator]
    G --> J[DevTools]
    H --> P[Profiles]
    
    %% Web Development
    F --> K[Spring Web & RestController]:::greenText
    K --> Q[API Documentation - Swagger/OpenAPI]
    
    %% Security
    K --> L[Spring Security Basics]
    L --> L2[Advanced Spring Security OAuth2, JWT]

    %% Data Layer
    F --> M[Spring Data JPA]
    M --> M2[ORM - Hibernate]
    M --> M3[H2 In-Memory Database]
    M --> N[Database Migrations - Flyway/Liquibase]
    M --> R[Caching]

    %% External Integrations
    F --> V[Feign Client for REST API Calls]
    F --> W[Emailing with Spring Mail]
    F --> X[Scheduling Tasks]

    %% Testing & Monitoring
    K --> O[Spring Boot Testing - JUnit/MockMvc]
    I --> S[Monitoring & Metrics Integration]
    S --> S2[Logging with SLF4J & Logback]

    %% Deployment
    S --> T[Building & Deploying with Docker]
    T --> U[Embedded Tomcat/Web Servers]

    %% Logical Connections
    L --> O
    N --> R


    classDef greenText fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
