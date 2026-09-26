# Privacy Data-Flow Diagram — Northstar Cloud Services

> Simplified simulated architecture for portfolio use. It shows where personal data enters, how it is used, and where privacy governance controls apply.

```mermaid
flowchart LR
    U[Customers / Employees / Applicants / Visitors]
    WEB[Website & Applications]
    IAM[Identity & Account Systems]
    CRM[CRM / Customer Data]
    ITSM[Support / ITSM]
    ANA[Product Analytics]
    MKT[Marketing Platform]
    HR[HR / ATS]
    BILL[Billing / Finance]
    SIEM[Security Monitoring]
    VEND[Third-Party Processors]
    PRIV[Privacy Governance]
    DEL[Retention / Deletion Controls]

    U --> WEB
    U --> IAM
    WEB --> CRM
    WEB --> ANA
    IAM --> CRM
    U --> ITSM
    U --> MKT
    U --> HR
    U --> BILL

    CRM --> VEND
    ITSM --> VEND
    ANA --> VEND
    MKT --> VEND
    HR --> VEND
    BILL --> VEND
    SIEM --> VEND

    PRIV -. "Notice / basis / rights / DPIA / TPRM" .-> WEB
    PRIV -. "ROPA / access / retention" .-> CRM
    PRIV -. "DPIA / minimisation" .-> ANA
    PRIV -. "Consent / withdrawal" .-> MKT
    PRIV -. "Retention / rights" .-> HR
    PRIV -. "Security / processor review" .-> VEND
    DEL -. "Lifecycle controls" .-> CRM
    DEL -. "Lifecycle controls" .-> ANA
    DEL -. "Lifecycle controls" .-> VEND
```

## Governance Control Points

The diagram is intentionally simple. In a real environment, the processing inventory would be linked to system owners, data stores, processors, transfer locations, retention rules and applicable safeguards.

The key portfolio objective is traceability:

**Data Subject / Principal → Processing Activity → System → Processor → Privacy Control → Evidence → Risk → Remediation**
