
# Product Test Cases

**Application:** SauceDemo  
**Module:** Products and Sorting  
**Test Type:** Manual Functional Testing

## TC-PROD-001: Verify Product Listing

- **Priority:** High
- **Preconditions:** User is logged in successfully.
- **Test Data:** standard_user / secret_sauce
- **Steps:**
  1. Log in to SauceDemo.
  2. Observe the products page.
  3. Check the displayed product names, images, and prices.
- **Expected Result:** Products should be displayed with their corresponding details.
- **Status:** PASS (reported)
- **Actual Result:** Product listing and details displayed correctly after rechecking.

## TC-PROD-002: Sort Price Low to High

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Price: Low to High sorting option.
- **Steps:**
  1. Open the product sorting dropdown.
  2. Select Price (low to high).
  3. Observe the order of product prices.
- **Expected Result:** Products should be sorted by price in ascending order.
- **Status:** PASS (reported)
- **Actual Result:** Prices appeared in ascending order.

## TC-PROD-003: Add Product to Cart

- **Priority:** High
- **Preconditions:** User is on the products page.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Find Sauce Labs Backpack.
  2. Click Add to cart.
  3. Observe the product button and cart badge.
- **Expected Result:** The product should be added to the cart, the button should change to Remove, and the cart badge should show 1.
- **Status:** PASS (reported)
- **Actual Result:** Button changed to Remove and cart badge showed 1.

## TC-PROD-004: Sort Price High to Low

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Price: High to Low sorting option.
- **Steps:**
  1. Open the product sorting dropdown.
  2. Select Price (high to low).
  3. Observe the order of product prices.
- **Expected Result:** Products should be sorted by price in descending order.
- **Status:** NOT RUN

## TC-PROD-005: Sort Product Name A to Z

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Name (A to Z) sorting option.
- **Steps:**
  1. Open the product sorting dropdown.
  2. Select Name (A to Z).
  3. Observe the product names.
- **Expected Result:** Product names should appear in alphabetical ascending order.
- **Status:** NOT RUN

## TC-PROD-006: Sort Product Name Z to A

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Name (Z to A) sorting option.
- **Steps:**
  1. Open the product sorting dropdown.
  2. Select Name (Z to A).
  3. Observe the product names.
- **Expected Result:** Product names should appear in alphabetical descending order.
- **Status:** NOT RUN

## TC-PROD-007: Verify Product Details

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Sauce Labs Backpack.
- **Steps:**
  1. Click the Sauce Labs Backpack name or image.
  2. Observe the product details page.
  3. Check the product name, description, price, and available cart action.
- **Expected Result:** The selected product's details should be displayed correctly.
- **Status:** NOT RUN

## TC-PROD-008: Verify Product Images and Prices

- **Priority:** Medium
- **Preconditions:** User is on the products page.
- **Test Data:** Displayed products.
- **Steps:**
  1. Inspect the product images.
  2. Check the product names and prices.
  3. Verify that each image and price corresponds to the displayed product.
- **Expected Result:** Product images should load correctly, and names and prices should be displayed consistently.
- **Status:** NOT RUN

## Execution Notes

- "Reported" indicates a result previously provided by the tester.
- NOT RUN cases must be executed before the final report is prepared.
- Record actual results only after observing the application.
- Capture screenshots where useful as supporting evidence.
