# Executive Summary — IAM Governance

**Company:** Northstar Cloud Services Pvt. Ltd. (fictional)  
**Period:** Q3 2026  
**Type:** Simulated IAM review

## What I checked

I looked at the main IAM governance areas:

- RBAC and least privilege
- Joiner / mover / leaver activity
- Periodic access review
- Privileged accounts
- MFA
- Segregation of Duties

The sample included 12 user-access records, 9 JML events, 8 privileged accounts and 5 SoD conflicts.

## Results

There were **4 findings**:

- 2 High: privileged MFA exception and Finance SoD conflict
- 2 Medium: JML timing and access-removal validation

## What I noticed

The basic IAM structure is in place, but exception handling needs more discipline.

The two main examples are a privileged account without complete MFA evidence and a Finance role combination that creates a SoD conflict.

There was also one mover event outside the simulated target and one access-removal request that still needed closure evidence.

## Next step

The fixes should be followed by another sample review. I would not close the findings only because the owner says the access was changed; I would keep the evidence showing the change and then verify it.

> All accounts, access decisions and evidence are fictional.