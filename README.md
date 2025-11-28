# 🛍️ Swag Labs E-Commerce Testing Project

## 📌 Project Overview
Comprehensive Quality Assurance project for **Swag Labs (SauceDemo)**. This repository demonstrates the execution of the full **Software Testing Life Cycle (STLC)**, focusing on functional stability and regression testing.

![Status](https://img.shields.io/badge/Status-Completed-success) ![Type](https://img.shields.io/badge/Type-Manual%20%26%20Regression-blue)

### 🎯 Objective
To validate critical user journeys including Authentication, Inventory Management, and the Checkout Process, ensuring a bug-free experience for end-users.

---

## 🛠️ Tools & Technologies
- **Target App:** [SauceDemo.com](https://www.saucedemo.com/)
- **Test Management:** Excel / Google Sheets
- **Bug Tracking:** Jira / Trello simulation
- **Methodology:** Black Box Testing (Functional & UI)
- **Browser:** Chrome v120 & Firefox

---

## 📂 Project Artifacts
*(Files are located in the repository folders)*

1. **📄 Test Plan:** Strategy, Scope, and Entry/Exit criteria.
2. **🧪 Test Cases:**
   - [📂 View Test Cases (PDF)](./Test-Cases/TestCases_SwagLabs.pdf) *<-- Make sure to upload the PDF later*
3. **🐞 Defect Reports:** Documented bugs with Severity & Priority.
4. **📸 Evidence:** Screenshots of UI defects.

---

## 🧪 Test Scenarios Covered

### 1. Authentication Module
- Valid Login (Standard User).
- Locked Out User verification (Error Message Validation).
- Performance Glitch User simulation.

### 2. Inventory & Cart
- Sorting functionality (Name A-Z, Price Low-High).
- Add to Cart / Remove from Cart verification.
- Product Details page navigation.

### 3. Checkout Workflow (E2E)
- **Data Validation:** Checking mandatory fields (First Name, Zip Code).
- **Payment Calculation:** Verifying Item Total + Tax = Total.
- **Order Completion:** Successful "Thank You" landing page.

---

## 🐞 Sample Bugs Found
| Bug ID | Summary | Severity | Status |
| :--- | :--- | :--- | :--- |
| **BUG-001** | Filter "Price (Low to High)" fails for specific users | **Medium** | Open |
| **BUG-002** | Checkout accepts Special Characters in Name field | **Low** | To Do |
| **BUG-003** | Infinite loading loop on product images | **High** | Fixed |

---

## 👤 Author
**Arkan Essam**
*Software Test Engineer | QC Engineer*
