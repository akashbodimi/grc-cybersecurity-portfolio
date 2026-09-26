# IAM Governance Methodology

> Simulated portfolio methodology for Northstar Cloud Services Pvt. Ltd.

## Objective

Demonstrate how an organization can govern identity and access through role design, lifecycle management, periodic review, privileged-access controls and segregation of duties.

## Lifecycle

**Access Model → Joiner/Mover/Leaver → Access Request → Provisioning → Periodic Recertification → Privileged Review → SoD Review → Exceptions → Remediation → Revalidation**

## Core Control Areas

1. **Identity lifecycle:** access follows approved HR events and is removed when no longer required.
2. **RBAC / least privilege:** access is based on role and business need.
3. **Periodic access review:** application owners review and certify access.
4. **Privileged access:** administrative identities are separately identified, uniquely assigned, protected with strong authentication and periodically reviewed.
5. **Service accounts:** non-human identities have owners, purpose and credential lifecycle controls.
6. **Temporary access:** exceptions are approved, time-bounded and reviewed.
7. **Segregation of duties:** incompatible combinations are identified and remediated or formally mitigated.

## Testing

Sample-based testing checks authorization, evidence, timing, population completeness and reviewer decisions. Findings remain open until remediation evidence is validated.