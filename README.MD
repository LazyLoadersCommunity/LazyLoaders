graph TD
style A stroke:#333,stroke-width:4px;

    A[Distributed System Basics] --> B[CAP Theorem]
    B --> C[Consistency vs Availability]
    A --> D[Scalability Principles]
    D --> E[Horizontal vs Vertical Scaling]
    D --> F[Load Balancing]
    F --> G[Types of Load Balancers]
    G --> H[Round-robin, IP Hash, etc.]
    E --> I[Sharding]
    F --> J[Rate Limiting]
    C --> K[Data Replication]
    K --> L[Replication Strategies]
    L --> M[Leader-Follower, Leaderless, etc.]
    I --> N[Partitioning]
    N --> O[Consistent Hashing]

    C --> P[Eventual Consistency]
    P --> Q[Distributed Transactions]
    Q --> R[Two-Phase Commit, Three-Phase Commit]

    E --> S[Cache Strategies]
    S --> T[Write-through, Write-back, etc.]
    T --> U[Cache Invalidation]

    I --> V[NoSQL vs SQL Databases]
    V --> W[Choosing the Right Database]
    W --> X[ACID vs BASE]

    G --> Y[Content Delivery Networks CDNs]
Y --> Z[Edge Caching, Geo-Distribution]

F --> AA[Service Discovery]
AA --> AB[DNS-Based, Client-Side, Server-Side Discovery]
AB --> AC[Service Registry]

P --> AD[Message Queues]
AD --> AE[Kafka, RabbitMQ, etc.]

S --> AF[Distributed Caching]
AF --> AG[Redis, Memcached, etc.]

AG --> AH[Cache Coherency]

T --> AI[Cache Eviction Policies]
AI --> AJ[LRU, LFU, etc.]

K --> AK[Quorum Mechanisms]
AK --> AL[Read and Write Quorum]

AL --> AM[Vector Clocks, Lamport Timestamps]

classDef default stroke:#333,stroke-width:2px;
