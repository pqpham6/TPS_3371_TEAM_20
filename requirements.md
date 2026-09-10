# Requirements

## Functional Requirements

1. **FR-1:** The system shall allow a referring provider to submit a referral for a patient, including patient information, reason for referral, requested service, and urgency level.
2. **FR-2:** The system shall validate that all required referral fields are complete before accepting the referral into the workflow, and flag incomplete referrals for correction.
3. **FR-3:** The system shall automatically route a validated referral to the appropriate receiving department based on the requested service.
4. **FR-4:** The system shall allow the receiving department to accept, reject, or request additional information on a submitted referral.
5. **FR-5:** The system shall track and update the status of a referral throughout its lifecycle (e.g., Submitted, Incomplete, Under Review, Accepted, Scheduled, Rejected, Completed, Cancelled).
6. **FR-6:** The system shall notify the referring provider when the status of a referral changes.
7. **FR-7:** The system shall allow authorized users (referring provider, receiving department, referral coordinator) to search and view the referral history and current status for a given patient.

## Non-Functional Requirements

1. **NFR-1 (Security/Compliance):** The system shall protect all patient information in accordance with HIPAA requirements, including encryption of data in transit and at rest, and role-based access control.
2. **NFR-2 (Performance):** The system shall process and confirm a referral submission within 2 seconds under normal load conditions.
3. **NFR-3 (Availability):** The system shall be available at least 99.5% of the time during business hours.
4. **NFR-4 (Usability):** The system shall provide an interface that a non-technical clinical or administrative staff member can use to submit or review a referral without formal training beyond a brief onboarding session.

*(Minimum required: 5 functional, 2 non-functional. Team may add or refine additional requirements as the project develops.)*
