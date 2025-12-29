# Software Requirement Specification (SRS)
## E-Commerce Web Application

---

## 1. Introduction

### 1.1 Purpose
This document describes the functional and non-functional requirements of the E-Commerce Web Application. It serves as a reference for QA, development, and project stakeholders to understand system behavior and testing scope.

### 1.2 Scope
The application allows registered users to log in, browse products, add items to a shopping cart, and complete the checkout process.

### 1.3 Intended Audience
- QA Engineers
- Automation Testers
- Developers
- Project Managers

---

## 2. System Overview
The E-Commerce Web Application is a web-based platform that enables users to purchase products online through a simple and secure interface.

---

## 3. User Roles

| Role | Description |
|------|------------|
| Customer | User who logs in, browses products, and places orders |

---

## 4. Functional Requirements

### 4.1 Authentication Module

- **FR-01:** The system shall allow users to log in using valid username and password.
- **FR-02:** The system shall display an error message for invalid login credentials.
- **FR-03:** The system shall prevent login when mandatory fields are empty.

---

### 4.2 Product Module

- **FR-04:** The system shall display a list of available products after successful login.
- **FR-05:** The system shall display product name, price, and image details.

---

### 4.3 Cart Module

- **FR-06:** The system shall allow users to add products to the shopping cart.
- **FR-07:** The system shall update the cart item count accordingly.

---

### 4.4 Checkout Module

- **FR-08:** The system shall allow users to proceed to checkout from the cart.
- **FR-09:** The system shall require mandatory checkout information.
- **FR-10:** The system shall display order confirmation upon successful checkout.

---

### 4.5 Logout Module

- **FR-11:** The system shall allow users to log out successfully.

---

## 5. Non-Functional Requirements

### 5.1 Performance
- Pages shall load within 3 seconds under normal conditions.

### 5.2 Usability
- The application shall be easy to use and intuitive.

### 5.3 Security
- User credentials shall not be exposed.
- Sessions shall terminate after logout.

---

## 6. Assumptions and Constraints
- Users must have internet connectivity.
- Only registered users can place orders.

---

## 7. Out of Scope
- Payment processing
- Admin dashboard functionality

---

## 8. Traceability
Each functional requirement will be mapped to corresponding test cases and defects using unique IDs.




