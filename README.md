# QA Website Testing Project

## Project Overview

This project documents manual QA testing performed on SauceDemo, a practice e-commerce web application.

The goal of the project was to simulate the work of an entry-level QA tester by creating and executing test cases, validating expected behavior, identifying defects, and documenting bugs.

## Testing Performed

Testing included:

- User login
- Product inventory
- Add to cart functionality
- Remove from cart functionality
- Checkout form validation
- Complete checkout flow
- Product navigation
- Product sorting
- Menu navigation

## Test Environment

- Application: SauceDemo
- Testing Type: Manual Functional Testing
- Platform: Web
- Browser: Safari

## Test Results

| ID | Test Case | Result |
|---|---|---|
| TC-001 | Login with valid credentials | PASS |
| TC-002 | Add product to cart | PASS |
| TC-003 | Remove product from cart | PASS |
| TC-004 | Checkout with all required fields blank | PASS |
| TC-005 | Checkout with missing last name | PASS |
| TC-006 | Checkout with missing ZIP/postal code | PASS |
| TC-007 | Complete checkout with valid information | PASS |
| TC-008 | Verify product images using problem_user | FAIL |
| TC-009 | Add backpack to cart using problem_user | PASS |
| TC-010 | Verify product-detail navigation | FAIL |
| TC-011 | Verify product sorting | FAIL |
| TC-012 | Verify About menu navigation | FAIL |

## Bugs Identified

During testing, defects were identified involving:

1. Incorrect product images displayed for multiple products.
2. Selecting the Sauce Labs Backpack opened an incorrect product-detail page.
3. Product sorting selections reverted to the default option and products did not reorder correctly.
4. The About menu link led to a 404 Page Not Found page.

## Skills Demonstrated

- Manual Testing
- Functional Testing
- Test Case Execution
- Bug Identification
- Bug Reporting
- Expected vs. Actual Results
- E-Commerce Testing
- UI Testing
- Form Validation
- Regression Thinking

## Project Status

Testing completed and defects documented.
