```mermaid
graph TD

  %% Behavioral Patterns
  A[Behavioral Patterns]:::green --> B[Memento]:::green
  A --> C[Observer]:::green
  A --> D[Chain of Responsibility]
  A --> E[Command]
  A --> F[State]
  A --> G[Strategy]:::green
  A --> H[Iterator]
  A --> I[Template Method]
  A --> J[Mediator]
  A --> K[Visitor]

  %% Creational Patterns
  L[Creational Patterns] --> M[Abstract Factory]
  L --> N[Builder]
  L --> O[Factory Method]
  L --> P[Prototype]
  L --> Q[Singleton]

  %% Structural Patterns
  R[Structural Patterns] --> S[Adapter]
  R --> T[Bridge]
  R --> U[Composite]
  R --> V[Decorator]
  R --> W[Facade]
  R --> X[Flyweight]
  R --> Y[Proxy]
  
  %% Dependencies and Learning Order

  B --> F  
  C --> E  
  D --> J  
  G --> C  
  F --> J  
  I --> F  

  M --> O  
  N --> P  
  O --> Q  

  S --> T  
  T --> V  
  U --> X  
  W --> Y  


    classDef green fill:#9f6,color:#000,stroke:#333,stroke-width:2px;
    classDef blue fill:#6400ff,color:#ffffff,stroke:#333,stroke-width:2px;
