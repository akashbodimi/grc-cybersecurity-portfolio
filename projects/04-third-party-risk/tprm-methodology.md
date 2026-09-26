# TPRM Methodology — Northstar Cloud Services

> Simulated portfolio methodology. No real vendor or customer data is used.

## Purpose

This methodology demonstrates a practical Third-Party Risk Management (TPRM) process for technology vendors used by a fictional SaaS company.

## Lifecycle

**Vendor Intake → Inherent Risk Tiering → Due Diligence → Evidence Review → Findings → Remediation → Residual Risk → Approval / Exception → Ongoing Monitoring → Reassessment**

## Inherent Risk Tiering

Each vendor is assessed across five factors on a 1–5 scale:

| Factor | 1 | 3 | 5 |
|---|---|---|---|
| Data Sensitivity | Public / non-sensitive | Internal or limited personal data | Confidential, regulated or customer-sensitive data |
| Access / Integration | No system access | Limited integration | Privileged, API or production access |
| Business Criticality | Easily replaceable | Important to a process | Service outage materially affects operations |
| Regulatory Exposure | Minimal | Contractual/privacy obligations | Material privacy, regulatory or contractual exposure |
| Concentration / Dependency | Low dependency | Moderate dependency | High dependency or difficult replacement |

**Inherent Risk Score = sum of five factor scores.**

| Score | Tier |
|---:|---|
| 5–9 | Low |
| 10–16 | Medium |
| 17–21 | High |
| 22–25 | Critical |

## Due Diligence

High and Critical vendors receive enhanced review. Evidence may include:

- Security certifications and assurance reports
- Security policies
- Penetration-test summary
- Vulnerability-management process
- Identity and privileged-access controls
- Encryption and key-management practices
- Incident-response and breach-notification process
- Business continuity and disaster recovery
- Privacy terms and data-processing terms
- Subprocessor inventory
- Data retention and secure deletion
- Secure SDLC / change management

## Residual Risk

Residual risk is determined after considering control maturity and open findings.

**Residual risk is not reduced solely because a vendor supplies a questionnaire.** Evidence must support the stated control position, and material gaps remain open until validated.

For this portfolio exercise:

- **Low:** acceptable with routine monitoring
- **Medium:** approval with tracked improvement actions
- **High:** management approval and remediation plan required
- **Critical:** do not onboard / restrict processing until risk treatment is approved

## Reassessment

Suggested cadence for the simulation:

- Critical / High: at least annually and upon material change
- Medium: periodic reassessment based on risk
- Low: lighter-touch review based on service and change profile

Material changes include major incidents, new subprocessors, significant architecture changes, acquisition/merger events, new regulated data processing, or major control failures.