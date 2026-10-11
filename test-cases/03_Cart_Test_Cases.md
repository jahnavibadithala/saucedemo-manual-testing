
# Shopping Cart Test Cases

**Application:** SauceDemo  
**Module:** Shopping Cart  
**Test Type:** Manual Functional Testing

## TC-CART-001: Verify Cart Contents

- **Priority:** High
- **Preconditions:** User is logged in and Sauce Labs Backpack has been added to the cart.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Add Sauce Labs Backpack to the cart.
  2. Click the shopping cart icon.
  3. Verify the product name, price, quantity, and available actions.
- **Expected Result:** The cart should display the correct product, price, quantity, and Checkout button.
- **Status:** PASS (reported)
- **Actual Result:** Correct product and price ($29.99), quantity, and Checkout button were displayed.

## TC-CART-002: Remove a Product

- **Priority:** High
- **Preconditions:** The cart contains at least one product.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Open the shopping cart.
  2. Click Remove for the selected product.
  3. Observe the cart contents.
- **Expected Result:** The selected product should be removed from the cart.
- **Status:** PASS (reported)
- **Actual Result:** Product was removed successfully.

## TC-CART-003: Verify Cart Badge Count

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Sauce Labs Backpack and Sauce Labs Bike Light.
- **Steps:**
  1. Add Sauce Labs Backpack to the cart.
  2. Observe the cart badge.
  3. Add Sauce Labs Bike Light.
  4. Observe the badge again.
  5. Remove one product and observe the badge.
- **Expected Result:** The cart badge should reflect the number of products added and removed.
- **Status:** PASS (reported)
- **Actual Result:** Badge reflected counts of 1, 2, and then 1.

## TC-CART-004: Verify Cart Persistence During Navigation

- **Priority:** Medium
- **Preconditions:** At least one product is in the cart.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Add Sauce Labs Backpack to the cart.
  2. Navigate to another page within the application.
  3. Return to the cart.
  4. Check whether the product remains.
- **Expected Result:** The cart should retain the selected product during the tested navigation.
- **Status:** PASS (reported)
- **Actual Result:** Product remained in the cart and the badge stayed at 1.

## TC-CART-005: Verify Product Quantity

- **Priority:** Medium
- **Preconditions:** A product has been added to the cart.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Add Sauce Labs Backpack to the cart.
  2. Open the cart.
  3. Observe the displayed quantity.
- **Expected Result:** The cart should display the expected quantity for the selected product.
- **Status:** PASS (reported)
- **Actual Result:** Backpack quantity was displayed as 1.

## TC-CART-006: Add Multiple Products

- **Priority:** High
- **Preconditions:** User is on the products page.
- **Test Data:** Sauce Labs Backpack and Sauce Labs Bike Light.
- **Steps:**
  1. Add Sauce Labs Backpack to the cart.
  2. Add Sauce Labs Bike Light to the cart.
  3. Open the cart.
  4. Verify both products and the cart badge.
- **Expected Result:** Both selected products should appear in the cart and the badge should show 2.
- **Status:** PASS (reported)
- **Actual Result:** Backpack and Bike Light appeared in the cart and the badge showed 2.

## TC-CART-007: Remove All Products

- **Priority:** High
- **Preconditions:** The cart contains products.
- **Test Data:** One or more selected products.
- **Steps:**
  1. Open the cart.
  2. Remove each product.
  3. Observe the cart contents and badge.
- **Expected Result:** The cart should contain no products after all items are removed.
- **Status:** PASS (reported)
- **Actual Result:** All products were removed successfully.

## TC-CART-008: Verify Continue Shopping

- **Priority:** Medium
- **Preconditions:** User is on the shopping cart page.
- **Test Data:** Continue Shopping control.
- **Steps:**
  1. Open the shopping cart.
  2. Click Continue Shopping.
  3. Observe the destination page.
- **Expected Result:** User should return to the products page.
- **Status:** PASS (reported)
- **Actual Result:** Continue Shopping navigation worked successfully.

## Execution Notes

- PASS statuses represent results previously reported by the tester.
- Record additional details or screenshots if available.
- Do not mark a test as PASS unless the observed result matches the expected result.