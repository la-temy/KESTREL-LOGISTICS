# Kestrel Logistics Ltd – End-to-End GRC Assessment

## Project Overview
An end-to-end Governance, Risk and Compliance (GRC) assessment of Kestrel Logistics Ltd, a Canadian freight and last-mile delivery company.

The project examines a ransomware incident that caused a 19-hour platform outage, a 26-hour data gap and unauthorised access to a recipient database containing information on approximately 2.6 million people. Data exfiltration remains unconfirmed.

**Objective:** Assess the incident, evaluate recovery capability, identify privacy and supplier risks, test key controls and develop a prioritised remediation plan.

## Frameworks and Regulations
- NIST Cybersecurity Framework (CSF) 2.0
- ISO 22301:2019 – Business Continuity
- ISO/IEC 27001:2022 – Information Security
- PIPEDA, Quebec Law 25 and Alberta PIPA
- Relevant US state breach-notification laws, subject to legal validation

## Key Findings

The assessment identified nine priority risks, including four rated Critical.

| Risk Area | Key Finding | Rating |
|---|---|---|
| Ransomware and security | Unescalated security alert, weak admin access and exposed backups | Critical |
| Business continuity | No BIA, approved recovery targets or tested recovery plan | Critical |
| Personal data | Attackers accessed the recipient database; exfiltration unknown | Critical |
| Privileged access | No admin MFA and former staff accounts remained active | Critical |
| Breach notification | No accountable notification decision-maker | High |
| Supplier risk | 70+ suppliers not tiered or adequately assessed | High |
| AI vendor privacy | No DPIA for AI route-planning data processing | High |
| Customer and revenue | Five major clients account for 60% of revenue | High |
| Security governance | No independent IT audit or adequate board-level resilience reporting | High |

## Key Control Gaps and Recommendations

| Identified Gap | Recommended Action |
|---|---|
| Backups connected to live network | Implement immutable/offline backups in a separate account and test restoration. |
| Administrator accounts lack MFA | Enforce phishing-resistant MFA, separate admin accounts and rotate credentials. |
| Former staff accounts remain active | Reconcile HR leaver records and disable access immediately. |
| Security alerts not escalated | Establish named 24/7 alert ownership and a 15-minute escalation standard. |
| No incident notification owner | Appoint a decision-maker, maintain a breach register and implement an incident response plan. |
| Recovery plan outdated and untested | Conduct a BIA, approve recovery objectives and test the updated plan. |
| Suppliers not risk-tiered | Classify suppliers and strengthen due diligence, audit rights and breach-notification clauses. |
| AI vendor has no DPIA | Complete a DPIA and apply data minimisation before continuing unrestricted data sharing. |
| No independent IT assurance | Commission an independent audit and introduce monthly board-level risk reporting. |

## Recovery Targets

| Measure | Actual | Recommended Target |
|---|---:|---:|
| Recovery Time Objective (RTO) | 19 hours | 2 hours |
| Recovery Point Objective (RPO) | 26 hours | 15 minutes |
| Platform availability | 97.4% (September baseline) | At least 99.5% |

## 30-Day Remediation Priorities

- **Days 0–7:** Appoint notification owner, engage forensic specialists, notify retail clients under contractual requirements, enforce admin MFA, disable leaver accounts and isolate backups.
- **Days 8–14:** Complete the notification assessment, conduct the BIA, approve recovery targets, complete the AI vendor DPIA and tier suppliers.
- **Days 15–30:** Test backup restoration, conduct an incident-response tabletop exercise, issue supplier contract amendments and verify corrective actions.

## Key Deliverables
- Incident timeline and response assessment
- Privacy and breach-notification analysis
- Business Impact Analysis and recovery targets
- Incident response and recovery runbook
- AI vendor DPIA and cloud security review
- Supplier risk-tiering and access review
- Audit evidence log and risk register
- KPI/KRI dashboard and executive report
- 30-day remediation roadmap

## Skills Demonstrated
GRC Assessment • Incident Response • Business Continuity • Disaster Recovery • NIST CSF 2.0 • ISO 27001 • ISO 22301 • Privacy Compliance • DPIA • Cloud Risk • Third-Party Risk Management • Control Testing • Risk Reporting

