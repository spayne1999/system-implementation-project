# Test Plan

## Testing Scope
The testing process covers:
- login validation
- transaction processing
- account lookup
- reporting
- migrated data accuracy
- error handling
- API functionality

## Testing Levels

| Test Type | Purpose | Responsibility |
|----------|---------|----------------|
| Unit Testing | Test individual functions and components | Developers |
| Integration Testing | Test interaction between modules | QA Team |
| System Testing | Test the full working system | QA Team |
| Acceptance Testing | Verify business requirements with users | Business Users |

## Tools Used
- Selenium
- JUnit
- Postman

## Test Case 1 – Login Validation

**Objective:** Verify that authorized users can log in successfully.

**Steps:**
1. Open login page
2. Enter valid username
3. Enter valid password
4. Click login

**Expected Result:**  
User is authenticated and taken to the dashboard.

## Test Case 2 – Transaction Processing

**Objective:** Verify that a transfer between accounts updates balances correctly.

**Steps:**
1. Log in
2. Open transfer page
3. Select source account
4. Select destination account
5. Enter $500
6. Submit transfer

**Expected Result:**  
Balances update correctly and confirmation appears.
