# Security Capability Diagram

```mermaid
flowchart TD
    A[Business Objectives and Risk Priorities] --> B[Security Strategy and Governance]
    B --> C[Identity and Access Management]
    B --> D[Cloud Security]
    B --> E[Detection and SIEM]
    B --> F[Incident Response]
    B --> G[Vulnerability Management]
    B --> H[Data Protection and GRC]

    C --> E
    D --> E
    E --> F
    G --> F
    H --> B

    C --> I[Access Reviews and MFA]
    D --> J[CSPM and Guardrails]
    E --> K[Threat Use Cases]
    F --> L[Playbooks and Escalation]
    G --> M[Remediation SLA Tracking]
    H --> N[Risk Register and Evidence]

    N --> O[Leadership Reporting and Roadmap Decisions]
    L --> O
    K --> O
    J --> O
    I --> O
```

## Purpose

This diagram shows how security strategy connects business risk, governance, and operational capabilities. It is intended to support roadmap discussions and explain capability relationships to technical and non-technical stakeholders.
