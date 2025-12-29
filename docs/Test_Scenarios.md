# Test Scenarios – E-Commerce Web Application (SauceDemo)

## Project Name
E-Commerce Web Application – SauceDemo

## Prepared By
Sachini Jayaweera

## Purpose
This document defines high-level test scenarios derived from the Software Requirement Specification (SRS). These scenarios provide a basis for creating detailed manual and automation test cases.

---

## 1. Authentication (Login) Module

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-LOGIN-01 | FR-01 | Verify login with valid username and password |
| TS-LOGIN-02 | FR-02 | Verify error message for invalid login credentials |
| TS-LOGIN-03 | FR-03 | Verify login when username field is empty |
| TS-LOGIN-04 | FR-03 | Verify login when password field is empty |
| TS-LOGIN-05 | FR-02 | Verify login with locked-out user |

---

## 2. Product Listing Module

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-PROD-01 | FR-04 | Verify product list is displayed after successful login |
| TS-PROD-02 | FR-05 | Verify product name, price, and image are displayed |
| TS-PROD-03 | FR-05 | Verify product sorting by price (Low to High) |
| TS-PROD-04 | FR-05 | Verify product sorting by name (A to Z) |

---

## 3. Cart Module

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-CART-01 | FR-06 | Verify user can add a product to the cart |
| TS-CART-02 | FR-07 | Verify cart badge updates when product is added |
| TS-CART-03 | FR-06 | Verify user can remove product from the cart |
| TS-CART-04 | FR-07 | Verify cart retains selected products after navigation |

---

## 4. Checkout Module

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-CHK-01 | FR-08 | Verify user can proceed to checkout from cart |
| TS-CHK-02 | FR-09 | Verify error when mandatory checkout fields are empty |
| TS-CHK-03 | FR-09 | Verify checkout with valid user information |
| TS-CHK-04 | FR-10 | Verify order confirmation page is displayed |

---

## 5. Logout Module

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-LOGOUT-01 | FR-11 | Verify user can logout successfully |
| TS-LOGOUT-02 | FR-11 | Verify session is terminated after logout |

---

## 6. Navigation & UI Validation

| Scenario ID | Requirement ID | Test Scenario Description |
|------------|----------------|---------------------------|
| TS-UI-01 | NFR-01 | Verify application pages load within acceptable time |
| TS-UI-02 | NFR-02 | Verify UI elements are aligned and visible |
| TS-UI-03 | NFR-03 | Verify application is responsive across browser window sizes |

---

## 7. Regression Test Scenarios

| Scenario ID | Test Scenario Description |
|------------|---------------------------|
| TS-REG-01 | Verify core functionalities after new build |
| TS-REG-02 | Verify checkout flow after cart changes |
| TS-REG-03 | Verify login functionality after deployment |


