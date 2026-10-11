
# SauceDemo Manual Testing Project

## Project Overview

This project demonstrates manual software testing of the SauceDemo e-commerce web application. It covers functional testing of the main shopping journey, from user login to order confirmation.

The project documents test scenarios, detailed test cases, execution results, and defect-reporting procedures.

## Objectives

- Understand and apply manual software testing concepts.
- Verify positive and negative application behavior.
- Validate login, product browsing, cart, and checkout workflows.
- Document expected and actual results.
- Maintain an organized test execution report.
- Practice professional QA documentation.

## Application Under Test

- **Application:** SauceDemo
- **URL:** https://www.saucedemo.com/
- **Testing Approach:** Manual Functional Testing
- **Environment:** macOS and web browser
- **Project Status:** In Progress

## Scope of Testing

### Modules Covered

1. Login and logout
2. Product listing and sorting
3. Shopping cart
4. Checkout information and validation
5. Order overview and confirmation

### Testing Types

- Functional Testing
- Positive Testing
- Negative Testing
- Input Validation Testing
- End-to-End Testing
- UI Verification

## Tools Used

- **Visual Studio Code:** Test documentation
- **Microsoft Excel:** Test execution reporting
- **Git:** Version control
- **GitHub:** Project hosting and portfolio presentation
- **Web Browser:** Manual test execution

## Project Structure

```text
Shopping-Application-Testing/
├── README.md
├── requirements/
│   └── Application_Requirements.md
├── test-scenarios/
│   └── Test_Scenarios.md
├── test-cases/
│   ├── 01_Login_Test_Cases.md
│   ├── 02_Product_Test_Cases.md
│   ├── 03_Cart_Test_Cases.md
│   ├── 04_Checkout_Test_Cases.md
│   └── 05_Order_Test_Cases.md
├── test-execution/
│   └── Test_Execution_Report.xlsx
├── bug-reports/
│   └── Bug_Report_Template.md
└── screenshots/
    ├── login/
    ├── products/
    ├── cart/
    ├── checkout/
    └── order-confirmation/
```

## Test Execution Summary

| Metric | Current Status |
|---|---:|
| Planned Test Cases | 40 |
| Reported PASS | 32 |
| Not Run | 8 |
| Confirmed Defects Reported | 0 |
| Reported Execution Coverage | 80% |

**Note:** PASS results are based on the tester's reported observations. Eight test cases remain pending. No confirmed defects have been reported so far; this does not establish that the application is defect-free.

## Test Case Distribution

| Module | Planned Cases |
|---|---:|
| Login | 8 |
| Products and Sorting | 8 |
| Shopping Cart | 8 |
| Checkout | 10 |
| Order Confirmation | 6 |
| **Total** | **40** |

## Documentation Deliverables

- Application requirements
- Test scenarios
- Detailed manual test cases
- Excel test execution report
- Reusable bug report template
- Screenshot evidence folders

## How to Review This Project

1. Read `requirements/Application_Requirements.md`.
2. Review `test-scenarios/Test_Scenarios.md`.
3. Open the detailed test cases under `test-cases/`.
4. Review `test-execution/Test_Execution_Report.xlsx`.
5. Review the template in `bug-reports/`.
6. Inspect supporting evidence under `screenshots/` when available.

## Future Improvements

- Execute all pending test cases.
- Capture and link actual screenshot evidence.
- Document any confirmed defects with reproducible steps.
- Add Selenium with Java automation for selected test cases.
- Integrate automated execution and reporting into a future version.

## Disclaimer

This is a learning and portfolio project using a publicly accessible demo shopping application. It is intended for educational testing practice and does not represent official testing performed for SauceDemo.

---

**Project Type:** QA / Manual Software Testing
**Status:** In Progress
