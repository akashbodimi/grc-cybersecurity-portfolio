# Simulated Cloud Security Architecture — Northstar

```mermaid
flowchart LR
    Internet --> WAF[AWS WAF]
    WAF --> LB[Public Load Balancer]
    LB --> API[EC2 / EKS Application Tier]
    API --> DB[(Amazon RDS)]
    API --> S3[(Amazon S3)]
    API --> SEC[AWS Secrets Manager]
    IAM[AWS IAM] -. access .-> API
    IAM -. privileged roles .-> KMS[AWS KMS]
    API --> CT[CloudTrail / VPC Flow Logs]
    DB --> CT
    CT --> SIEM[Central SIEM]
    GD[GuardDuty] --> SIEM
    BK[AWS Backup] --> DB
    BK --> S3

    subgraph Governance
      GRC[Cloud GRC]
      GRC -. controls .-> IAM
      GRC -. controls .-> CT
      GRC -. controls .-> KMS
      GRC -. controls .-> BK
      GRC -. controls .-> SIEM
    end
```

## GRC Control Points

The architecture is designed to make control ownership visible:

**External Exposure → WAF / Network → Workload → Data Stores → Identity / Secrets → Logging → Detection → Recovery**

The portfolio assessment then attaches evidence, findings and remediation actions to those control points.