
# Login Test Cases

**Application:** SauceDemo  
**Module:** Login  
**Test Type:** Manual Functional Testing

## TC-LOGIN-001: Valid Login

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** standard_user / secret_sauce
- **Steps:**
  1. Enter the valid username.
  2. Enter the valid password.
  3. Click Login.
- **Expected Result:** User should successfully log in and see the products page.
- **Status:** PASS (reported)
- **Actual Result:** Products page opened successfully.

## TC-LOGIN-002: Invalid Credentials

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** Invalid username and password.
- **Steps:**
  1. Enter invalid credentials.
  2. Click Login.
- **Expected Result:** Login should be rejected and an appropriate error message displayed.
- **Status:** PASS (reported)
- **Actual Result:** Login was rejected; error message displayed.

## TC-LOGIN-003: Both Fields Empty

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** Username and password left empty.
- **Steps:**
  1. Leave both fields empty.
  2. Click Login.
- **Expected Result:** A required-username validation message should appear.
- **Status:** PASS (reported)
- **Actual Result:** "Epic sadface: Username is required"

## TC-LOGIN-004: Password Empty

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** Username: standard_user; password empty.
- **Steps:**
  1. Enter standard_user as the username.
  2. Leave the password empty.
  3. Click Login.
- **Expected Result:** A password-required validation message should appear.
- **Status:** PASS (reported)
- **Actual Result:** "Epic Sadface: Password is required."

## TC-LOGIN-005: Locked-Out User

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** locked_out_user / secret_sauce
- **Steps:**
  1. Enter the locked-out username and password.
  2. Click Login.
- **Expected Result:** Login should be blocked and a locked-out message displayed.
- **Status:** PASS (reported after retest)
- **Actual Result:** Locked-out error message displayed.

## TC-LOGIN-006: Username Empty

- **Priority:** High
- **Preconditions:** User is on the login page.
- **Test Data:** Username empty; valid password.
- **Steps:**
  1. Leave the username empty.
  2. Enter secret_sauce as the password.
  3. Click Login.
- **Expected Result:** Login should be rejected and a username-required message displayed.
- **Status:** NOT RUN

## TC-LOGIN-007: Password Masking

- **Priority:** Medium
- **Preconditions:** User is on the login page.
- **Test Data:** Any password characters.
- **Steps:**
  1. Click the password field.
  2. Type a password.
  3. Observe the characters in the field.
- **Expected Result:** Password characters should be masked.
- **Status:** NOT RUN

## TC-LOGIN-008: Logout

- **Priority:** High
- **Preconditions:** User is logged in.
- **Test Data:** Valid demo account.
- **Steps:**
  1. Open the navigation menu.
  2. Click Logout.
- **Expected Result:** User should be returned to the login page.
- **Status:** NOT RUN

## Execution Notes

- "Reported" means the result was provided by the tester.
- NOT RUN cases must be executed before finalizing the report.
- Record detailed actual results based on what is observed.
