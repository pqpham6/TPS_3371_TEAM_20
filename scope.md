# Scope

## In Scope
- Submission of patient referrals by referring providers, including patient details, reason for referral, requested service, and urgency level.
- Validation of referral completeness before it enters the review workflow.
- Automatic routing of referrals to the correct receiving department based on requested service.
- Review workflow allowing receiving departments to accept, reject, or request more information.
- Status tracking and notifications throughout the referral lifecycle (Submitted, Incomplete, Under Review, Accepted, Rejected, Scheduled, Completed, Cancelled).
- Search and view functionality for referral history by patient, referring provider, or receiving department.
- Role-based access control distinguishing referring providers, receiving department staff, referral coordinators, and system administrators.
- Basic reporting on referral volume and status (e.g., number of pending, overdue, or completed referrals) for administrative visibility.

## Out of Scope
- Direct integration with external hospital or clinic Electronic Health Record (EHR) systems (the system will be a standalone referral management tool for this project).
- Insurance verification, billing, or claims processing.
- Actual appointment calendar/scheduling system integration beyond marking a referral as "Scheduled" (no real-time calendar booking with external systems).
- Telehealth or video consultation functionality.
- Patient-facing self-service portal for submitting referrals directly (only providers submit referrals in this version).
- Mobile native applications (the system will be delivered as a web-based application).

## Notes
As this is a capstone project developed within an academic timeframe, the scope is intentionally limited to the core referral management workflow described above. Future extensions (patient portal access, EHR integration, real scheduling system integration) are noted as potential future work but are not part of this project's deliverables.
