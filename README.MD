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

    Y --> AA[JVM Debugging Techniques]
    AA --> AB[Heap Dump Analysis]
    AA --> AC[Thread Dump Analysis]
    
    Z --> AD[Container Orchestration]
    AD --> AE[Kubernetes Scaling]
    AE --> AF[Helm for Kubernetes]

    V --> AG[OAuth2 and JWT]
    AG --> AH[Spring Security Customization]
    AH --> AI[Authentication and Authorization]

    Q --> AJ[Asynchronous Programming]
    AJ --> AK[Reactor Schedulers]
    AK --> AL[Backpressure in Reactive Streams]

    G --> AM[Thread Pool Tuning]
    AM --> AN[Lock-Free Algorithms]
    AN --> AO[Atomic Variables]

    D --> AP[Type Erasure]
    AP --> AQ[Bounded Wildcards]
    AQ --> AR[PECS Producer Extends Consumer Super]

    O --> AS[WatchService API]
    AS --> AT[File System Notifications]
    AT --> AU[Symbolic Links Handling]

    classDef greenText fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
