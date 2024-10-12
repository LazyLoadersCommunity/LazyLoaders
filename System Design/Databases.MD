```mermaid
graph TD
    A[Database Fundamentals] --> B[Relational Databases]
    A --> C[NoSQL Databases]
    
    B --> D[ACID Transactions]
    C --> E[BASE Consistency]
    
    D --> F[Normalization]
    F --> G[Joins and Relationships]
    
    E --> H[Denormalization]
    H --> I[Document Stores e.g., MongoDB]
    
    G --> J[Indexing in SQL]
    I --> K[Indexing in NoSQL]
    
    B --> L[SQL MySQL, PostgreSQL]
    C --> M[Key-Value Stores e.g., Redis]
    C --> N[Wide-Column Stores e.g., Cassandra]
    
    L --> O[Query Optimization in SQL]
    N --> P[Query Optimization in NoSQL]
    
    O --> Q[Sharding in SQL Databases]
    P --> R[Sharding in NoSQL Databases]
    
    L --> S[Replication in Relational DBs]
    M --> T[Replication in NoSQL DBs]
    
    Q --> U[Consistency Models in SQL]
    R --> V[Consistency Models in NoSQL]

    V --> W[Use Cases for NoSQL vs SQL]


    classDef green fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
    classDef violet fill:#6400ff,color:#ffffff,stroke:#333,stroke-width:2px;
