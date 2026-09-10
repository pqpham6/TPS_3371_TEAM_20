# Business Rules and System States

## Business Rules

1. **BR-1:** A referral cannot be submitted without, at minimum, patient identifying information, the reason for referral, and the requested service.
2. **BR-2:** A referral shall only be routed to a receiving department that offers the requested service.
3. **BR-3:** A referral cannot move to the **Scheduled** state unless it has first been marked **Accepted** by the receiving department.
4. **BR-4:** A referral missing required information must be flagged as **Incomplete** and returned to the referring provider; it cannot proceed to routing until corrected.
5. **BR-5:** A rejected referral must include a documented reason for rejection, visible to the referring provider.
6. **BR-6:** Only authorized roles (referral coordinator, receiving department staff) may change the status of a referral.
7. **BR-7:** A referral that remains in the **Under Review** state beyond a defined time threshold (e.g., 3 business days) shall be automatically flagged for follow-up by a referral coordinator.
8. **BR-8:** A referral may be cancelled by the referring provider or patient at any point prior to being marked **Completed**, with a reason recorded.

## Major Transaction / System States

| State | Description |
|---|---|
| **Submitted** | Referral has been created by the referring provider and entered into the system. |
| **Incomplete** | Referral is missing required information and has been returned to the referring provider. |
| **Under Review** | Referral has passed validation and is routed to the receiving department for review. |
| **Accepted** | Receiving department has approved the referral for scheduling. |
| **Rejected** | Receiving department has declined the referral, with a reason recorded. |
| **Scheduled** | Patient has been scheduled for the requested service. |
| **Completed** | The patient has received the service; referral lifecycle is closed. |
| **Cancelled** | The referral was withdrawn by the referring provider or patient before completion. |

## State Transition Summary

```
Submitted → Incomplete → Submitted (after correction)
Submitted → Under Review
Under Review → Accepted → Scheduled → Completed
Under Review → Rejected
Any state (before Completed) → Cancelled
```
