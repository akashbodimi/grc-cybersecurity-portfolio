# Cloud GRC Assessment

**Status:** Completed — simulated AWS environment

## What this project is

I used a fictional AWS environment to practice cloud-focused GRC work.

The main thing I wanted to show here is that cloud security is shared. The cloud provider handles some parts of the environment, while the customer still has to configure and govern things like IAM, logging, network rules, workloads, data and backups.

## What I worked on

- Built a cloud asset register
- Mapped provider vs customer responsibilities
- Built a cloud control matrix
- Reviewed IAM and privileged access
- Reviewed network exposure and segmentation
- Checked logging and monitoring
- Reviewed encryption and key management
- Looked at vulnerability and patch management
- Reviewed backup and restore evidence
- Logged findings and remediation actions
- Added a simple cloud architecture diagram

## Assessment flow

**Cloud Inventory → Shared Responsibility → Controls → Evidence → Findings → Remediation → Validation**

## Key results

The simulation covers **12 cloud assets**, **15 controls** and **4 findings**.

The main findings were around:

- Privileged-access review evidence
- Restore-test evidence
- Vulnerability remediation timing
- Storage configuration

## Files

- [Excel workpaper](./Cloud_GRC_Assessment_Northstar.xlsx)
- [Cloud GRC Methodology](./cloud-grc-methodology.md)
- [Shared Responsibility Matrix](./shared-responsibility-matrix.csv)
- [Cloud Asset Register](./cloud-asset-register.csv)
- [Cloud Control Matrix](./control-matrix.csv)
- [Evidence Index](./evidence-index.csv)
- [Findings Log](./findings-log.csv)
- [Remediation Tracker](./remediation-tracker.csv)
- [Cloud Architecture](./cloud-architecture.md)
- [Executive Summary](./executive-summary.md)
- [Sources](./sources.md)

## Skills shown

**Cloud GRC · AWS · Shared Responsibility · IAM · Network Security · Logging · Encryption · Vulnerability Management · Backup/Recovery · CSPM · Remediation**

> All cloud assets, evidence and findings are fictional. This is a portfolio exercise, not production cloud administration.