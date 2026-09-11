# TPS_3371_TEAM_20 — Patient Referral Management System

**Course:** MIS 3371 — Capstone Project
**Milestone:** Milestone 1 — Project Definition

## Project Purpose
Clinics send patient referrals by phone, fax, paper, and email. Coordinators re-key the details, chase missing information, and decide by hand which department should receive each referral. Referrals get lost, the same patient can be referred twice for the same service, and providers and patients cannot see where a referral stands.

This project builds a **Patient Referral Management System** that handles one transaction: a referring provider **submits a patient referral**, and the system validates it, routes it to the correct receiving department, and tracks it to a final status.

## Scenario
A referring provider submits a referral for a patient to receive a specific service. The system checks required fields and blocks duplicate active referrals, assigns a referral ID, and routes the referral to the department that offers the service. The receiving department accepts it, rejects it with a reason, or requests more information. Every status change is recorded with a timestamp so the provider and referral coordinator can see where it stands.

All demo data is fictional — no real patient information is used.

## Team
| Name | Role |
|---|---|
| Peter | Team Lead / PM |
| Daja | Requirements & Documentation Lead |
| Sophia | Systems Analyst / Design Lead |
| Elizabeth | Development & Git Lead |
| Yoki | QA / Testing Lead |

## Milestone 1 Documents
| # | Deliverable | File |
|---|---|---|
| 1 | Business Problem + Scope | [docs/business-problem-scope.docx](docs/business-problem-scope.docx) |
| 2 | Stakeholders | [docs/stakeholders.docx](docs/stakeholders.docx) |
| 3 | Main Transaction | [docs/main-transaction.docx](docs/main-transaction.docx) |
| 4 | Requirements (Functional + Quality) | [docs/requirements.docx](docs/requirements.docx) |
| 5 | User Stories + Acceptance Criteria | [docs/user-stories-acceptance.docx](docs/user-stories-acceptance.docx) |
| 6 | Business Rules + States | [docs/business-rules-states.docx](docs/business-rules-states.docx) |
| 7 | Team Charter | [docs/team-charter.docx](docs/team-charter.docx) |
| 8 | GitHub Repository | This repository |

Presentation: [Milestone1_Patient_Referral.pptx](Milestone1_Patient_Referral.pptx)

## Repository Structure
```
TPS_3371_TEAM_20/
├── README.md
├── Milestone1_Patient_Referral.pptx
└── docs/
    ├── business-problem-scope.docx
    ├── stakeholders.docx
    ├── main-transaction.docx
    ├── requirements.docx
    ├── user-stories-acceptance.docx
    ├── business-rules-states.docx
    └── team-charter.docx
```

## Git Workflow
Pull before starting · one focused branch per task · pull request with one reviewer before merging to `main` · no real patient data or secrets in the repo.

## Milestone Status
- [x] Milestone 1 — Project definition
- [ ] Milestone 2 — Implementation begins after Milestone 1 approval
