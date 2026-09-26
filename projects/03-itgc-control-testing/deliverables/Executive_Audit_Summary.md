# Executive Audit Summary — ITGC Control Testing

**Entity:** Northstar Cloud Services Pvt. Ltd.  
**Review period:** Q3 2026  
**Engagement type:** Simulated ITGC assurance exercise  
**Prepared for:** Portfolio demonstration

> This document is fictional and educational. It is not an audit report for a real organization and does not provide an external assurance opinion.

## Objective

The simulated review assessed whether selected IT General Controls across access management, change management and IT operations were suitably designed and operated as expected during the review period.

## Scope

10 controls were tested across three domains:

- Access Management — AC-01 to AC-04
- Change Management — CH-01 to CH-03
- IT Operations — OPS-01 to OPS-03

Testing included Test of Design (ToD) and Test of Effectiveness (ToE), supported by simulated evidence and sampled transactions.

## Executive Result

The simulated environment identified **4 findings**:

| Severity | Count | Primary Theme |
|---|---:|---|
| High | 1 | Restore testing evidence |
| Medium | 2 | Privileged access review; emergency change review |
| Low | 1 | Access review evidence retention |

**Control result:** 7 of 10 controls operated without identified exceptions in the simulated sample; 3 controls had direct ToE exceptions, with an additional evidence-retention finding noted in access review documentation.

## Key Observations

### 1. Privileged access governance
The privileged-account review did not clearly evidence complete population coverage for two accounts. The main improvement is to reconcile the privileged account inventory to the review population before sign-off.

### 2. Emergency change governance
One emergency change exceeded the simulated one-business-day retrospective review target. This points to a monitoring and escalation opportunity rather than a design gap.

### 3. Backup recoverability evidence
One critical system did not have complete documented restore-test evidence. This is the highest-risk simulated observation because backup execution alone does not demonstrate recoverability.

### 4. Evidence retention
One application access review had approval evidence outside the standard repository. The control activity occurred, but auditability and evidence consistency can be improved.

## Overall Conclusion

Based on the simulated procedures and fictional evidence set, the selected ITGC environment is **partially effective for the purposes of this portfolio exercise**. The control framework is broadly defined, but remediation is required for privileged access review completeness, emergency change review timeliness, restore-test evidence, and evidence retention.

## Recommended Management Actions

1. Strengthen completeness checks for privileged-account reviews.
2. Track emergency-change review SLAs and escalate overdue items.
3. Maintain a system-level restore testing calendar for critical services.
4. Standardize retention of control evidence in the approved repository.

## Follow-up

A follow-up test would verify remediation evidence and retest affected controls before closure. Portfolio evidence should clearly distinguish remediation implemented from remediation validated.