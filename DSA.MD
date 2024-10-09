```mermaid
graph TD
A[Data Structures and Algorithms] --> B[Arrays]
A --> C[Linked Lists]
A --> D[Stacks and Queues]
A --> E[Hash Maps]

    B --> F[<a href='http://google.com'>Two Pointers</a>]:::violet

    B --> G[Binary Search]
    B --> H[Sorting Algorithms]
    H --> I[Quick Sort]
    H --> J[Merge Sort]
    
    C --> K[Singly Linked List]
    C --> L[Doubly Linked List]
    
    D --> M[Stack]
    D --> N[Queue]
    D --> O[Priority Queue]
    
    A --> P[Trees and Graphs]
    P --> Q[Binary Trees]
    Q --> R[DFS and BFS]
    Q --> S[Binary Search Tree]

    P --> T[Graphs]
    T --> U[Dijkstra's Algorithm]
    
    A --> V[Dynamic Programming]
    V --> W[Knapsack Problem]
    V --> X[Longest Common Subsequence]
    V --> Y[Memoization]
    
    A --> Z[Greedy Algorithms]
    Z --> AA[Activity Selection Problem]

    A --> AB[Backtracking]
    AB --> AC[N-Queens Problem]

    classDef green fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
    classDef violet fill:#6400ff,color:#ffffff,stroke:#333,stroke-width:2px;
