flowchart TD
    A[User] --> B[CyberGuard AI Frontend]
    B --> C[Backend API - FastAPI]

    C --> D[Phishing Analysis]
    C --> E[Deepfake Analysis]

    D --> F[Risk Assessment]
    E --> F

    F --> G[Results Dashboard]
    G --> H[Threat Indicators]
    G --> I[Risk Level]
    G --> J[Security Recommendations]
