# NexaCore Access Request Workflow

## Access Request Flow

```mermaid
flowchart TD
    A[Request] --> B[Business Justification]
    B --> C[Manager Approval]
    C --> D{Privileged?}

    D -->|No| E[App Owner Approval]
    D -->|Yes| F[App Owner + Security Approval]

    E --> G[Provisioning]
    F --> G

    G --> H[Verification]