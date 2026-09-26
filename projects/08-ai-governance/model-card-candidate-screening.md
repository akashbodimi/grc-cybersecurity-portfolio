# Model Card — Candidate Screening Assistant

**System ID:** AI-003  
**Status:** Simulated / governance review required

## Intended Use

Assist recruiters in organizing candidate profiles and prioritizing profiles for human review.

## Out of Scope

The system should not make final employment decisions, infer protected characteristics, or be used outside the approved recruitment workflow.

## Inputs

CV text, role requirements and approved structured applicant fields.

## Outputs

Candidate relevance score / ranking.

## Human Oversight

Recruiters remain responsible for decisions and should be able to challenge or override AI suggestions.

## Evaluation

The governance process should define accuracy/error measures and relevant fairness/adverse-impact checks before production approval. Current portfolio evidence is incomplete.

## Security / Privacy

Least privilege, MFA, access logging, data minimisation, retention limits and vendor due diligence apply.

## Monitoring

Monitor performance drift, error trends, user overrides, complaints and material incidents.

## Change Management

Model/version changes require impact review, regression testing, updated documentation and approval before release.

## Reassessment Triggers

Material model change, new data source, new geography, significant drift, security/privacy incident or material regulatory change.