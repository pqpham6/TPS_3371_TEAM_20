# Main Transaction

## Transaction Name
**Submit Patient Referral**

## Description
The primary transaction supported by this system is the submission, validation, routing, and tracking of a patient referral from a referring provider to a receiving healthcare department or specialist.

## Transaction Flow
1. A **referring provider** initiates a referral for a patient, specifying the patient's information, the reason for referral, and the requested service.
2. The system **records** the referral and assigns it a unique referral ID.
3. The system **validates** that all required information has been provided (patient identifiers, reason for referral, requested service, urgency level, referring provider information).
   - If information is missing, the referral is flagged as **Incomplete** and returned to the referring provider for correction.
4. Once validated, the system **routes** the referral to the correct receiving department based on the requested service.
5. The receiving department **reviews** the referral and either:
   - **Accepts** it (moves toward scheduling),
   - **Rejects** it (with a reason), or
   - **Requests additional information** (returns to referring provider).
6. Once accepted, the referral is **scheduled** with the patient.
7. The system **tracks** the referral status at every step and makes it visible to the referring provider, receiving department, and administrative staff until the referral reaches a final state (Scheduled/Completed, Rejected, or Cancelled).

## Actors Involved
- Referring Provider (initiates)
- System (validates and routes)
- Receiving Department / Specialist (reviews and decides)
- Scheduling Staff (schedules appointment)
- Referral Coordinator (monitors and intervenes when needed)

## Trigger
A referring provider determines that a patient requires a service that must be provided by another department or specialist.

## Outcome
A successfully processed referral results in the patient being scheduled for the requested service, with a complete audit trail of the referral's status from submission to completion.
