# API Testing Project – User Management System

## Project Overview

This project demonstrates API testing of a user management system using Postman. The APIs are tested using a publicly available demo API provided by **ReqRes (https://reqres.in)**.

This project focuses on validating API responses, handling different request scenarios, and identifying defects and improvements.

---

## Demo API Used

* Website: https://reqres.in
* Type: Public Demo REST API
* Purpose: Practice API testing without authentication setup

Note: This is a **demo API**, so some endpoints may not behave like real production systems (e.g., limited validation or static responses).

---

## Objectives

* To test REST APIs (GET, POST, PUT, DELETE)
* To validate status codes and response data
* To perform positive and negative testing
* To identify bugs and improvement areas

---

## Tools & Technologies Used

* Postman (API Testing)
* Mantis Bug Tracker (Defect Management)
* Microsoft Excel (Test Case Documentation)

---

## APIs Tested

* GET – Fetch users (`/api/users`)
* POST – Create user (`/api/users`)
* PUT – Update user (`/api/users/{id}`)
* DELETE – Delete user (`/api/users/{id}`)

---

## Test Scenarios Covered

* Valid API requests
* Invalid input handling (e.g., page=999)
* Empty request validation
* Edge case testing

---

## Project Structure

```plaintext id="h0zkhm"
API-Testing-Project/
│── TestCases/            → API test cases (Excel)
│── Collections/          → Postman collection (JSON)
│── BugReports/           → Bug & enhancement reports
│── API_Screenshots/      → Execution screenshots
│── README.md
```

---

## Test Cases

Test cases include positive, negative, and edge scenarios.

Example:

| Test Case ID | API         | Scenario      | Expected Result      |
| ------------ | ----------- | ------------- | -------------------- |
| TC01         | GET /users  | Valid request | Status 200 with data |
| TC02         | GET /users  | Invalid page  | Empty data array     |
| TC03         | POST /users | Valid data    | User created (201)   |

---

## Bug Reporting

Defects and improvements were documented with:

* Bug ID
* API endpoint
* Expected vs Actual result
* Severity

Example:

* Enhancement: API returns empty data without user-friendly message for invalid page input.

---

## Execution Details

* APIs were tested manually using Postman
* Requests were organized into collections
* API key authentication was handled via headers
* Responses were validated using status codes and JSON data

---

## Key Skills Demonstrated

* API Testing (REST APIs)
* Manual Testing
* Test Case Design
* Bug Reporting & Analysis
* Positive & Negative Testing

---

## Author

Rupam Baral
GitHub: https://github.com/Rupam0034

---

## Conclusion

This project demonstrates practical knowledge of API testing using a demo API, including validating endpoints, handling edge cases, and identifying improvements to ensure better API usability.
