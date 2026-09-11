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
| 1 | Business Problem + Scope | [docs/business-problem-scope.md](docs/business-problem-scope.md) |
| 2 | Stakeholders | [docs/stakeholders.md](docs/stakeholders.md) |
| 3 | Main Transaction | [docs/main-transaction.md](docs/main-transaction.md) |
| 4 | Requirements (Functional + Quality) | [docs/requirements.md](docs/requirements.md) |
| 5 | User Stories + Acceptance Criteria | [docs/user-stories-acceptance.md](docs/user-stories-acceptance.md) |
| 6 | Business Rules + States | [docs/business-rules-states.md](docs/business-rules-states.md) |
| 7 | Team Charter | [docs/team-charter.md](docs/team-charter.md) |
| 8 | GitHub Repository | This repository |

Presentation: [Milestone1_Patient_Referral.pptx](Milestone1_Patient_Referral.pptx)

## Repository Structure
```
TPS_3371_TEAM_20/
├── README.md
├── Milestone1_Patient_Referral.pptx
└── docs/
    ├── business-problem-scope.md
    ├── stakeholders.md
    ├── main-transaction.md
    ├── requirements.md
    ├── user-stories-acceptance.md
    ├── business-rules-states.md
    └── team-charter.md
```

## Git Workflow
Pull before starting · one focused branch per task · pull request with one reviewer before merging to `main` · no real patient data or secrets in the repo.

## Milestone Status
- [x] Milestone 1 — Project definition
- [ ] Milestone 2 — Implementation begins after Milestone 1 approval
