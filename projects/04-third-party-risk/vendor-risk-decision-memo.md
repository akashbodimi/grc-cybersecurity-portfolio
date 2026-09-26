# Vendor Risk Decision Memo — BluePeak Cloud Monitoring

> Simulated portfolio artifact. BluePeak Cloud Monitoring is fictional.

## Decision Context

Northstar Cloud Services is considering BluePeak Cloud Monitoring for centralized monitoring and alerting. The service would receive security telemetry and connect to production systems through APIs and administrative integration.

## Inherent Risk

The vendor scored **23/25 (Critical)** before considering control evidence.

| Factor | Score | Rationale |
|---|---:|---|
| Data Sensitivity | 5 | Security telemetry and potentially sensitive operational information |
| Access / Integration | 5 | Production integrations and administrative paths |
| Business Criticality | 5 | Monitoring availability affects incident detection and response |
| Regulatory Exposure | 4 | Contractual and privacy obligations may apply |
| Concentration / Dependency | 4 | Material operational dependency once integrated |

## Due Diligence Outcome

Evidence supports several baseline practices, including governance, access governance, vulnerability management, incident response, continuity and privacy contracting.

Four open items remain:

- Admin MFA evidence is incomplete.
- Current penetration-test evidence is not supplied.
- Subprocessor notification process is not fully evidenced.
- Secure deletion evidence is missing.

Two findings are treated as high-risk for this simulation: privileged administrative MFA evidence and secure deletion assurance.

## Residual Risk

The simulated residual assessment is **18/25 — High**, reflecting the vendor's importance and the unresolved evidence/control gaps.

## Portfolio Decision

**Conditional approval with restrictions.**

The simulated recommendation is to allow onboarding activities and limited non-production integration while requiring remediation of the two high-priority items before unrestricted production access or processing is enabled.

This is a portfolio exercise demonstrating how a TPRM decision can be tied to evidence and remediation rather than questionnaire completion alone.

## Required Conditions

1. Obtain independent or configuration evidence for privileged administrator MFA.
2. Obtain secure deletion procedure and representative deletion attestation.
3. Close medium-risk assurance and subprocessor governance items within the remediation target dates.
4. Reassess residual risk after remediation evidence is validated.

## Ongoing Monitoring

Monitor for:

- Security incidents or material breaches
- Major changes in service architecture
- New or changed subprocessors
- Material changes to data processing
- Expiry of assurance reports/certifications
- Repeated remediation slippage

## Final Note

No statement in this memo represents an approval of a real vendor. All organizations, evidence, findings and decisions are fictional.