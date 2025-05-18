graph TD;
    A[User Interface]
    B[Payment API]
    C[Transaction Engine]
    D[Event Queue]
    E[Merchant Services]
    F[Cross-border Transactions]
    G[Digital Wallets]
    H[Database]
    I[Transaction Logs]
    J[Monitoring & Alerts]

    A --> B
    B --> C
    C --> D
    D --> E
    D --> F
    D --> G
    C --> H
    C --> I
    I --> J
