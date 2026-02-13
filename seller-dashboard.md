Project Homepage > Seller Dashboard

# Seller Dashboard (FR2.0)

## Functional Description
The system shall provide a dashboard interface for farmers and vendors to upload and manage product listings.

Sellers shall be able to:
- Add new product
- Edit product information
- Delete product
- View product status

## Actors
- Farmer / Seller
- Vendor
- SuperAdmin

## Preconditions
- Seller is registered and logged in.

## Postconditions
- Product information is saved and updated successfully.

## Use Case Scenario

| Step | Actor | Action | System Response |
|------|-------|--------|----------------|
| 1 | Seller | Logs into dashboard | System authenticates user |
| 2 | Seller | Clicks "Add Product" | System displays product form |
| 3 | Seller | Enters product details | System validates input |
| 4 | Seller | Submits form | System saves product to database |

## Exceptions
- If required fields are missing, system displays validation error.

---

© 2026 UBest
