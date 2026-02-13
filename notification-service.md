Project Homepage > Notification Service

# Notification Service (FR5.0)

## Functional Description
The system will notify users when new product listings are uploaded or when messages are received.

Notifications may include:
- New product alerts
- Message alerts
- System announcements

## Actors
- Buyer / Consumer
- Farmer / Seller
- Vendor
- SuperAdmin

## Preconditions
- User account is active.

## Postconditions
- Notification is successfully delivered to the user.

## Use Case Scenario

| Step | Actor | Action | System Response |
|------|-------|--------|----------------|
| 1 | Seller | Uploads new product | System triggers notification event |
| 2 | System | Sends notification | User receives alert |
| 3 | User | Clicks notification | System redirects to relevant page |

## Exceptions
- If notification fails, system logs error for admin review.

---

© 2026 UBest
