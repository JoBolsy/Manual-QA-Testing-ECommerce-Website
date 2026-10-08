# Manual QA Test Plan
## QA Automation Labs E-Commerce Website

## 1. Introduction

This test plan defines the manual testing activities for the QA Automation Labs E-Commerce website.

The purpose of this testing is to verify that the main user flows function correctly, validate form and input behavior, and identify functional bugs that may affect the user experience.

**Website Under Testing:**  
https://shop.qaautomationlabs.com/

**Test Type:** Manual Testing

---

## 2. Test Objectives

The objectives of this testing are to:

- Verify that the main e-commerce features work as expected.
- Validate positive and negative user scenarios.
- Verify input validation and error handling.
- Ensure users can complete important workflows such as registration, login, filter products, adding products to the cart, and checkout.
- Identify and document functional bugs. 
- Produce structured testing documentation including test cases, bug reports, and test summary.

---

## 3. Test Scope

### 3.1 In Scope

The following modules will be manually tested:

- Registration

- Login & Logout


- Product Browsing

- Shopping Cart

- Checkout

---

### 3.2 Out of Scope

The following areas will not be included in this project:

- Automation testing
- Performance/load testing
- API testing
- Database testing
- Cross-browser testing
- Mobile application testing

---

## 4. Testing Approach

Testing will be performed manually using the following approaches:

### Functional Testing
Verify that each feature behaves according to its expected functionality.

### Positive Testing
Verify application behavior using valid inputs and normal user workflows.

### Negative Testing
Verify how the application handles invalid or incomplete inputs.


---

## 5. Test Environment

| Component | Environment |
|---|---|
| Application | QA Automation Labs E-Commerce |
| Platform | Web |
| Device | Laptop/Desktop |
| Operating System | Windows 11 |
| Browser | Google Chrome |
| Network | Stable Internet Connection |
| Testing Method | Manual Testing |

---

## 6. Test Data

Testing will use both valid and invalid test data.

Account used for testing:

**Email:** fihoda7231@calirona.com 
**Password:** 7231

---

## 7. Entry Criteria

Testing can begin when:

- The website is accessible.
- The required modules are available.
- Test scenarios have been prepared.
- Required test data or user accounts are available.
- The test environment is ready.

---

## 8. Exit Criteria

Testing will be considered complete when:

- All planned test cases have been executed.
- Every test case has a Pass, or Fail status.
- All identified bugs have been documented.
- Evidence has been collected for failed test cases.
- A Test Summary Report has been completed.

---

## 9. Bug Reporting

Any bug identified during testing will be documented with the following information:

- Bug ID
- Bug Title
- Module
- Bug Description
- Preconditions
- Steps to Reproduce
- Test Data
- Expected Result
- Actual Result
- Severity
- Priority
- Status
- Environment
- Screenshot/Evidence

### Severity Levels

**Critical**  
The main application workflow cannot continue.

**High**  
An important feature does not function correctly.

**Medium**  
A feature has incorrect behavior, but the main workflow can still continue.

**Low**  
Minor functional or user-interface issue with limited impact.

---

## 10. Test Deliverables

The project will produce:

- Test Plan
- Test Cases
- Bug Reports
- Test Summary Report

---

## 11. Summary

After all testing activities are completed, the following metrics will be documented:

- Total Test Cases
- Passed Test Cases
- Failed Test Cases
- Pass Rate
- Number of Bugs Found
- Bugs by Severity   
- Overall Testing Result