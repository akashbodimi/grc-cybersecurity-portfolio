# Executive Summary — Cloud GRC Assessment

**Company:** Northstar Cloud Services Pvt. Ltd. (fictional)  
**Period:** Q3 2026  
**Type:** Simulated AWS cloud review

## What I reviewed

The assessment covered:

- 12 cloud assets
- 15 controls
- 15 evidence records
- 4 findings

The main areas were IAM, network security, logging, encryption, vulnerability management, backup/recovery, secure configuration, incident response and provider assurance.

## Findings

Three findings were High severity and one was Medium:

1. Privileged-access review evidence was incomplete.
2. Restore testing was not fully evidenced for one critical workload.
3. One storage configuration allowed broader access than intended.
4. One critical patch item passed its remediation target.

## Shared responsibility

One of the main checks was separating what AWS provides from what the customer still has to configure and manage.

For this exercise, provider assurance was treated as supporting evidence for inherited controls, not as proof that customer-side settings were correct.

## Next step

The affected controls should be fixed and then checked again using current configuration/evidence.

> All cloud assets, evidence and findings are fictional.