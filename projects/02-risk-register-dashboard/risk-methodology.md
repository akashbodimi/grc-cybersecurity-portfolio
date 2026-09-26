# Risk Methodology

## Purpose

This simulated methodology provides a repeatable way to identify, score, treat and monitor cybersecurity risks.

## 1. Risk statement

Use the structure:

**Because of [threat/condition], [asset/process] could experience [event], resulting in [business/security impact].**

## 2. Likelihood

| Score | Description |
|---:|---|
| 1 | Rare — unlikely under normal conditions |
| 2 | Unlikely — could occur but not expected frequently |
| 3 | Possible — credible scenario |
| 4 | Likely — expected to occur without effective treatment |
| 5 | Almost certain — highly probable or recurring |

## 3. Impact

| Score | Description |
|---:|---|
| 1 | Limited operational or information impact |
| 2 | Minor business disruption or localized exposure |
| 3 | Moderate operational, financial, privacy or security impact |
| 4 | Major impact affecting important services or information |
| 5 | Severe impact involving critical services, sensitive information or major business consequences |

## 4. Risk calculation

**Risk score = Likelihood × Impact**

| Score | Rating |
|---:|---|
| 1–7 | Low |
| 8–14 | Medium |
| 15–25 | High |

This scale is a portfolio assumption. A real organization should use its approved risk appetite and methodology.

## 5. Treatment options

- **Mitigate:** reduce likelihood or impact through additional controls.
- **Avoid:** stop the activity creating unacceptable exposure.
- **Transfer/Share:** shift part of the financial or operational exposure through contractual or insurance mechanisms where appropriate.
- **Accept:** retain the risk within approved appetite with documented ownership and approval.

## 6. Residual risk

Residual risk represents the remaining exposure after existing and/or planned controls are considered. It should have an accountable owner and should be monitored when material.

## 7. Monitoring

Useful KRIs/KPIs include:

- Critical vulnerabilities past SLA
- Privileged accounts without recent review
- Overdue access reviews
- High-risk vendor reviews overdue
- Backup restore success rate
- Log-source coverage
- Phishing simulation failure rate
- Mean time to acknowledge security incidents
- Open high-risk findings past due date

## 8. Governance principle

The register is not just a list of technical problems. Each risk should have a business-relevant statement, accountable owner, treatment decision, target date and evidence of follow-up.
