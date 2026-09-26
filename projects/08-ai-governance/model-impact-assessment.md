# Sample AI Impact Assessment — Candidate Screening Assistant

> Fictional portfolio work. This assessment demonstrates the governance method; it is not a legal determination.

## System

**AI-003 — Candidate Screening Assistant**

### Purpose

Support recruiters by organizing and ranking applicant profiles for human review.

### Stakeholders

Applicants, recruiters, HR administrators, hiring managers and the organization.

### Potential Impacts

- Inaccurate ranking may reduce access to opportunities.
- Historical data patterns may create unfair outcomes.
- Proxy variables may affect candidate scoring.
- Recruiters may over-rely on automated recommendations.
- Applicant data may be processed by external technology providers.

### Necessity / Proportionality Questions

1. Which fields are necessary for the stated recruitment purpose?
2. Can sensitive or proxy attributes be excluded?
3. Can ranking be replaced with less intrusive workflow support?
4. Can human reviewers understand and challenge model outputs?
5. Are outputs retained only as long as needed?

### Safeguards

- Documented model purpose and prohibited uses
- Data minimisation
- Validation using representative test data
- Performance/error monitoring
- Fairness/adverse-impact analysis where appropriate
- Human review and override
- Access control and audit logging
- Provider due diligence
- Versioned change management
- Incident escalation

### Residual Risk

**High** until validation, impact-assessment evidence and human-oversight evidence are complete.

### Approval Gate

Do not treat completion of the assessment as approval. Production use requires documented evidence that required safeguards are implemented and validated.