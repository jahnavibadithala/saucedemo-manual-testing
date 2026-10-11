
# SauceDemo Test Scenarios

## 1. Project Information

- **Project:** SauceDemo Manual Testing
- **Application:** https://www.saucedemo.com/
- **Testing Type:** Manual Functional Testing
- **Total Planned Test Cases:** 40
- **Status:** In Progress

## 2. Login Scenarios

| Scenario ID | Test Scenario | Priority |
|---|---|---|
| TS-LOGIN-001 | Verify login with valid credentials | High |
| TS-LOGIN-002 | Verify login with invalid credentials | High |
| TS-LOGIN-003 | Verify login with both fields empty | High |
| TS-LOGIN-004 | Verify login with password field empty | High |
| TS-LOGIN-005 | Verify login with a locked-out user | High |
| TS-LOGIN-006 | Verify login with username empty and password entered | High |
| TS-LOGIN-007 | Verify password masking | Medium |
| TS-LOGIN-008 | Verify logout functionality | High |

## 3. Product Listing and Sorting Scenarios

| Scenario ID | Test Scenario | Priority |
|---|---|---|
| TS-PROD-001 | Verify the product listing page | High |
| TS-PROD-002 | Verify sorting products by price, low to high | Medium |
| TS-PROD-003 | Verify adding a product to the cart from the products page | High |
| TS-PROD-004 | Verify sorting products by price, high to low | Medium |
| TS-PROD-005 | Verify sorting products by name, A to Z | Medium |
| TS-PROD-006 | Verify sorting products by name, Z to A | Medium |
| TS-PROD-007 | Verify product details | Medium |
| TS-PROD-008 | Verify product images and prices | Medium |

## 4. Shopping Cart Scenarios

| Scenario ID | Test Scenario | Priority |
|---|---|---|
| TS-CART-001 | Verify cart contents | High |
| TS-CART-002 | Verify removing a product from the cart | High |
| TS-CART-003 | Verify cart badge count | Medium |
| TS-CART-004 | Verify cart contents during navigation | Medium |
| TS-CART-005 | Verify product quantity in the cart | Medium |
| TS-CART-006 | Verify adding multiple products | High |
| TS-CART-007 | Verify removing all products from the cart | High |
| TS-CART-008 | Verify Continue Shopping navigation | Medium |

## 5. Checkout Scenarios

| Scenario ID | Test Scenario | Priority |
|---|---|---|
| TS-CHECKOUT-001 | Verify navigation to checkout | High |
| TS-CHECKOUT-002 | Verify checkout with all fields empty | High |
| TS-CHECKOUT-003 | Verify checkout with first name empty | High |
| TS-CHECKOUT-004 | Verify checkout with last name empty | High |
| TS-CHECKOUT-005 | Verify checkout with postal code empty | High |
| TS-CHECKOUT-006 | Verify checkout with valid customer details | High |
| TS-CHECKOUT-007 | Verify the order overview | High |
| TS-CHECKOUT-008 | Verify item total calculation | High |
| TS-CHECKOUT-009 | Verify tax calculation | High |
| TS-CHECKOUT-010 | Verify cancel checkout functionality | Medium |

## 6. Order Confirmation Scenarios

| Scenario ID | Test Scenario | Priority |
|---|---|---|
| TS-ORDER-001 | Verify successful order completion | High |
| TS-ORDER-002 | Verify the order confirmation message | High |
| TS-ORDER-003 | Verify the confirmation graphic | Low |
| TS-ORDER-004 | Verify Back Home navigation | Medium |
| TS-ORDER-005 | Verify cart state after order completion | Medium |
| TS-ORDER-006 | Verify the end-to-end shopping journey | High |

## 7. Test Execution Summary

- Total planned scenarios: 40
- Reported passed test cases so far: 32
- Remaining test cases: 8
- Confirmed defects: None reported so far
- Overall status: In Progress

## 8. Notes

- Record actual results based on observed application behavior.
- Mark a test case as Failed only when the actual result differs from the expected result.
- Record confirmed defects in the bug reports folder.
- Keep screenshots as supporting evidence where appropriate.
