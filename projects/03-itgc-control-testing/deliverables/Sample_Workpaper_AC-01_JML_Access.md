# Sample Workpaper — AC-01 JML Access

> Simulated portfolio work for Northstar Cloud Services Pvt. Ltd. Not a real client workpaper.

## Control

**Control ID:** AC-01  
**Control:** Joiner, mover and leaver access is provisioned or removed based on approved HR events.  
**Frequency:** Per event  
**Owner:** IAM Manager  
**Control type:** Preventive

## Risk

Users may retain inappropriate access after joining, changing roles or leaving the organization.

## Test Objective

Determine whether the control is designed to address the risk and whether sampled HR events were handled consistently during the review period.

## Population and Sample

**Population:** 18 simulated HR lifecycle events during Q3 2026.  
**Sample:** 6 events selected across joiners, movers and leavers.

## Evidence Reviewed

- HR event / service ticket
- Manager approval
- Identity provisioning or deprovisioning record
- Timestamp comparison between HR event and account action

## Test Procedure

1. Confirm each sampled event had an approved HR request.
2. Confirm the requested role or access was reflected in the identity record.
3. For leavers, compare termination time with account disablement time.
4. Check for unexplained exceptions or delayed actions.
5. Record exceptions and conclude on operation.

## Sample Results

| Sample | Event | Evidence | Result | Exception |
|---|---|---|---|---|
| JML-01 | Joiner | HR-2401; IAM-771 | Pass | None |
| JML-02 | Mover | HR-2410; IAM-780 | Pass | None |
| JML-03 | Leaver | HR-2422; IAM-792 | Pass | None |
| JML-04 | Joiner | HR-2430; IAM-800 | Pass | None |
| JML-05 | Mover | HR-2441; IAM-811 | Pass | None |
| JML-06 | Leaver | HR-2450; IAM-820 | Pass | None |

## ToD Conclusion

**Pass.** The documented control design directly addresses the risk by linking identity actions to approved HR events.

## ToE Conclusion

**Pass.** All six sampled events had traceable evidence supporting timely access action.

## Auditor Note

The workpaper uses fictional identifiers and simulated evidence. It demonstrates the testing method rather than a real audit conclusion.