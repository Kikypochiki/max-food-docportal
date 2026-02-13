Project Homepage > Product Catalog

# Product Catalog (FR1.0)

## Functional Description
The system shall display all available agricultural products uploaded by registered sellers and vendors.

Each product listing shall include:
- Product Name
- Category
- Price
- Seller Name
- Location
- Availability Status
- Product Image

## Actors
- Buyer / Consumer
- Vendor
- SuperAdmin

## Preconditions
- User has access to the system.
- Products have been uploaded by sellers.

## Postconditions
- Product listings are displayed successfully.

## Use Case Scenario

| Step | Actor | Action | System Response |
|------|-------|--------|----------------|
| 1 | Buyer | Accesses Product Catalog | System retrieves product list from database |
| 2 | Buyer | Scrolls or browses listings | System displays product information |
| 3 | Buyer | Clicks on product | System shows detailed product view |

## Exceptions
- If no products exist, system displays: "No listings available."

---

© 2026 UBest
