# Sample SoD Analysis — Finance & ITSM

> Simulated portfolio analysis.

## Conflict Logic

The review identifies role combinations that could allow one person to initiate, approve, administer or implement an activity without sufficient independent oversight.

## Identified Conflicts

| Conflict | Roles | Risk | Treatment |
|---|---|---|---|
| SOD-001 | AP User + Payment Approver | High | Remove conflicting role |
| SOD-002 | Vendor Master Admin + Payment Approver | High | Independent approval / role separation |
| SOD-003 | Change Implementer + Change Approver | Medium | Separate production approval |
| SOD-005 | Admin Support + Change Approver | Medium | Review necessity and add secondary approval |

## GRC Interpretation

Not every role overlap is automatically unacceptable. A valid business exception should have documented rationale, compensating controls, approval authority and periodic review.

The portfolio demonstrates the process of identifying, documenting and treating conflicts rather than claiming that every conflict must follow one universal model.