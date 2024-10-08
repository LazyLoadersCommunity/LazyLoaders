```mermaid
graph TD
    A[Core Java] --> B[Object-Oriented Programming]
    B --> C[Java Collections Framework]
    C --> D[Generics]
    D --> E[Streams API]
    E --> F[Lambda Expressions]
    F --> G[Concurrency]
    G --> H[Java Memory Model]
    
    A --> I[Exception Handling]
    I --> J[Input/Output Streams]
    J --> K[NIO and NIO.2]
    
    H --> L[Multithreading with Executor Service]
    L --> M[CompletableFuture]
    
    F --> N[Optional Class]
    
    K --> O[File I/O and Path API]
    
    G --> P[Synchronized Keyword and Locks]
    
    M --> Q[Reactive Programming with Project Reactor]
    
    Q --> R[Spring Framework Introduction]
    R --> S[Spring Boot]
    
    S --> T[REST API with Spring]
    T --> U[Spring Data JPA]
    
    U --> V[Spring Security]
    V --> W[Microservices with Spring Cloud]
    W[Microservices with Spring Cloud]:::greenText
    
    H --> X[Garbage Collection Tuning]
    X[Garbage Collection Tuning]:::greenText
    
    X --> Y[JVM Performance Monitoring and Profiling]
    
    W --> Z[Docker and Kubernetes Integration]

    classDef greenText fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
