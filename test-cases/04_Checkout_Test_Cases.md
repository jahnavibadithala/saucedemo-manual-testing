
# Checkout Test Cases

**Application:** SauceDemo  
**Module:** Checkout  
**Test Type:** Manual Functional Testing

## TC-CHECKOUT-001: Proceed to Checkout

- **Priority:** High
- **Preconditions:** User is logged in and has at least one product in the cart.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Add a product to the cart.
  2. Open the shopping cart.
  3. Click Checkout.
- **Expected Result:** The checkout information page should open.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; no additional observations recorded.

## TC-CHECKOUT-002: Checkout with All Fields Empty

- **Priority:** High
- **Preconditions:** User is on the checkout information page.
- **Test Data:** First name, last name, and postal code left empty.
- **Steps:**
  1. Leave all required fields empty.
  2. Click Continue.
- **Expected Result:** The application should prevent continuation and display a required-field validation message.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact error message not recorded.

## TC-CHECKOUT-003: Checkout with First Name Empty

- **Priority:** High
- **Preconditions:** User is on the checkout information page.
- **Test Data:** First name empty; other required fields populated.
- **Steps:**
  1. Leave First Name empty.
  2. Enter a last name and postal code.
  3. Click Continue.
- **Expected Result:** The application should prevent continuation and indicate that the first name is required.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact error message not recorded.

## TC-CHECKOUT-004: Checkout with Last Name Empty

- **Priority:** High
- **Preconditions:** User is on the checkout information page.
- **Test Data:** Last name empty; other required fields populated.
- **Steps:**
  1. Enter a first name.
  2. Leave Last Name empty.
  3. Enter a postal code.
  4. Click Continue.
- **Expected Result:** The application should prevent continuation and indicate that the last name is required.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact error message not recorded.

## TC-CHECKOUT-005: Checkout with Postal Code Empty

- **Priority:** High
- **Preconditions:** User is on the checkout information page.
- **Test Data:** Postal code empty; first and last names populated.
- **Steps:**
  1. Enter a first name and last name.
  2. Leave Postal Code empty.
  3. Click Continue.
- **Expected Result:** The application should prevent continuation and indicate that the postal code is required.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact error message not recorded.

## TC-CHECKOUT-006: Checkout with Valid Customer Details

- **Priority:** High
- **Preconditions:** User has products in the cart and is on the checkout information page.
- **Test Data:** Valid first name, last name, and postal code.
- **Steps:**
  1. Enter a first name.
  2. Enter a last name.
  3. Enter a postal code.
  4. Click Continue.
- **Expected Result:** The application should accept the required information and navigate to the order overview.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; specific field values and observations not recorded.

## TC-CHECKOUT-007: Verify Order Overview

- **Priority:** High
- **Preconditions:** Customer information has been accepted and the order overview is displayed.
- **Test Data:** Products selected for checkout.
- **Steps:**
  1. Review the products in the order overview.
  2. Check product names, prices, and quantities.
  3. Review the displayed totals.
- **Expected Result:** The order overview should display the selected products and relevant pricing information.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; detailed item-by-item observations not recorded.

## TC-CHECKOUT-008: Verify Item Total Calculation

- **Priority:** High
- **Preconditions:** The order overview is displayed with at least one product.
- **Test Data:** Sauce Labs Backpack, listed at $29.99 in the earlier reported cart test.
- **Steps:**
  1. Review the products and prices in the order overview.
  2. Calculate the sum of the displayed item prices.
  3. Compare the calculated sum with the displayed item total.
- **Expected Result:** The displayed item total should equal the sum of the item prices before tax.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact displayed item total and calculation were not recorded.

## TC-CHECKOUT-009: Verify Tax Calculation

- **Priority:** High
- **Preconditions:** The order overview displays the item total and tax.
- **Test Data:** Order overview pricing information.
- **Steps:**
  1. Observe the item total.
  2. Observe the displayed tax.
  3. Check whether the displayed final total equals the item total plus tax.
- **Expected Result:** The final total should equal the item total plus the displayed tax.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact tax amount and final total were not recorded.

## TC-CHECKOUT-010: Cancel Checkout

- **Priority:** Medium
- **Preconditions:** User is on a checkout page.
- **Test Data:** Cancel control.
- **Steps:**
  1. Click Cancel.
  2. Observe the destination page.
- **Expected Result:** The application should navigate to the appropriate previous shopping page without completing the order.
- **Status:** PASS (reported)
- **Actual Result:** Test was reported as passed; exact destination page was not recorded.

## Execution Notes

- PASS (reported) means the tester previously reported a passing result.
- Exact error messages, totals, and tax amounts have not been added where they were not recorded.
- Capture the actual values during a retest if detailed evidence is required.
