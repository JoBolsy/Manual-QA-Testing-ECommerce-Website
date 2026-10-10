# Manual QA Testing – QA Automation Labs E-Commerce

A manual software testing portfolio project focused on validating key user workflows of the [QA Automation Labs E-Commerce website](https://shop.qaautomationlabs.com/). The project includes a test plan, executed test cases, defect reports, and a test execution summary.

## Project Overview

**Application Under Test:** QA Automation Labs E-Commerce  
**Testing Type:** Manual Functional Testing  
**Approaches:** Positive Testing, Negative Testing, Input Validation, and Error Handling  
**Environment:** Windows 11, Google Chrome, Desktop/Laptop

## Testing Scope

The following modules were tested:

- User Registration
- Login and Logout
- Product Browsing
- Shopping Cart
- Checkout

**Out of scope:** Test automation, performance/load testing, API testing, database testing, cross-browser testing, and mobile application testing.

## Test Execution Results

| Metric | Result |
|---|---:|
| Total Test Cases | 64 |
| Passed | 62 |
| Failed | 2 |
| Pass Rate | 96.87% |
| Total Bugs Reported | 2 |
| Critical | 0 |
| High | 0 |
| Medium | 2 |
| Low | 0 |

## Defects Identified

| Bug ID | Description | Module | Severity |
|---|---|---|---|
| BUG-CHK-01 | Continue Payment button accepts an invalid first-name format | Checkout | Medium |
| BUG-CHK-02 | Continue Payment button accepts an invalid last-name format | Checkout | Medium |

Both issues concern checkout form validation: the application allows users to proceed to the payment step despite invalid name formats.

## Test Documentation

| Document | Description |
|---|---|
| [Test Plan](./Manual%20QA%20Test%20Plan%20-%20QA%20Automation%20Labs%20E-Commerce.md) | Test objectives, scope, methods, environment, and completion criteria |
| [Test Cases](./Test%20Cases%20-%20QA%20Automation%20Labs%20E-Commerce.xlsx) | Test scenarios, steps, data, expected and actual results, and execution status |
| [Bug Reports](./Bug%20Reports%20-%20QA%20Automation%20Labs%20E-Commerce.xlsx) | Reported defects with reproduction steps and supporting details |
| [Test Summary](./Manual%20QA%20Test%20Summary%20-%20QA%20Automation%20Labs%20E-Commerce.md) | Execution metrics and overall test conclusion |

## Key Findings

Of the 64 test cases executed, 62 passed and 2 failed, resulting in a **96.87% pass rate**. The two reported medium-severity bugs occur during checkout and relate to insufficient validation of first-name and last-name formats. Improving these validations would help ensure correct billing details before users proceed with payment.

## Skills Demonstrated

- Manual functional testing
- Test planning and test case design
- Positive and negative scenario testing
- Input validation and error handling checks
- Defect reporting and documentation
- Test execution reporting
