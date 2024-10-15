```mermaid
graph TD

    A[Data Structures in Java] --> B[Arrays]
    A --> C[ArrayList]
    A --> D[LinkedList]
    A --> E[HashMap]
    A --> F[HashSet]
    A --> G[Stack]
    A --> H[Queue]
    H --> I[PriorityQueue]
    A --> J[TreeMap]
    A --> K[TreeSet]
    A --> L[ConcurrentHashMap]
    A --> M[CopyOnWriteArrayList]
    A --> N[BlockingQueue]
    N --> O[ArrayBlockingQueue]
    N --> P[LinkedBlockingQueue]
    A --> Q[ConcurrentSkipListMap]

    L & M & N & Q --> R[Multithreading Considerations]

    classDef green fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
    classDef violet fill:#6400ff,color:#ffffff,stroke:#333,stroke-width:2px;
