Project Homepage > Messaging System

# Messaging System (FR3.0)

## Functional Description
The system will allow communication between buyers and sellers regarding product inquiries.

The messaging system shall:
- Send messages
- Receive messages
- Display message history

## Actors
- Buyer / Consumer
- Farmer / Seller
- Vendor
- SuperAdmin (monitoring purposes)

## Preconditions
- Both users are registered.
- Product exists.

## Postconditions
- Message is successfully delivered and stored.

## Use Case Scenario

| Step | Actor | Action | System Response |
|------|-------|--------|----------------|
| 1 | Buyer | Opens product page | System displays seller info |
| 2 | Buyer | Clicks "Message Seller" | System opens chat window |
| 3 | Buyer | Sends message | System delivers message |
| 4 | Seller | Views message | System displays notification |

## Exceptions
- If recipient is offline, system stores message for later delivery.

---

© 2026 UBest
