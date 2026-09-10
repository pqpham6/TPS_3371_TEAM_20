# User Stories and Acceptance Criteria

## 1. Referring Provider — Submit a Referral
**Story:** As a referring provider, I want to submit a referral online so that I know it was received.

**Acceptance Criteria:** Given complete required data, when I submit the referral, then the system returns a referral ID and sets the status to "Submitted."

## 2. Referral Coordinator — Catch Incomplete Referrals
**Story:** As a referral coordinator, I want incomplete referrals to be flagged automatically so that I can follow up before they stall.

**Acceptance Criteria:** Given a referral missing required fields, when it is submitted, then the system marks it "Incomplete" and returns it to the referring provider with the missing fields identified.

## 3. Receiving Department Staff — Review Queue
**Story:** As receiving department staff, I want to see a queue of referrals needing review so that I can process them consistently.

**Acceptance Criteria:** Given a referral has been routed to my department, when I open the review queue, then the referral and its details are visible with an option to accept, reject, or request more information.

## 4. Patient — Check Referral Status
**Story:** As a patient, I want to know the status of my referral so that I know when to expect care.

**Acceptance Criteria:** Given an existing referral, when the referring provider or coordinator looks it up, then the current status and the timestamp of the latest update are shown.

## 5. Receiving Department Staff — Reject with Reason
**Story:** As receiving department staff, I want to record a reason when I reject a referral so that the referring provider understands what to correct.

**Acceptance Criteria:** Given a referral under review, when I reject it, then the system requires a reason and makes it visible to the referring provider.
