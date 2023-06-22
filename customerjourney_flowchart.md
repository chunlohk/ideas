graph TD
    A[Potential Customer]
    B[Webinar]
    C[YouTube]
    D[Company Website]
    E[Social Media]
    F[Engagement] -->|Interest| G[Low-Cost Consultation]
    G -->|Decision| H[Exploration of AIenli Services]
    H --> I[Contact Sales/Submit Inquiry]
    I --> J[New Client]
    J --> K[Ongoing Support and Services]
    K --> F
    
    A --> B
    A --> C
    A --> D
    A --> E
    
    B --> F
    C --> F
    D --> F
    E --> F

    classDef stage fill:#f9d5e5,stroke:#35477d,stroke-width:2px;
    class A,B,C,D,E,F,G,H,I,J,K stage;
