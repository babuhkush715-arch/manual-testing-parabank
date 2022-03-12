# Test Plan — ParaBank Web Application

## 1. Project Overview
| Field | Details |
|-------|---------|
| Project Name | ParaBank Web Application Testing |
| Application URL | https://parabank.parasoft.com |
| Test Type | Manual — Functional Testing |
| Prepared By | Babusingh Kushwaha |
| Date | March 2022 |
| Version | 1.0 |

---

## 2. Objective
To verify that all functional modules of ParaBank web application
work as per expected requirements including positive, negative,
and boundary value test scenarios.

---

## 3. Scope

### In Scope
- Login Module
- Register Module
- Open New Account Module
- Accounts Overview Module
- Transfer Funds Module
- Bill Pay Module
- Find Transactions Module
- Update Contact Info Module
- Request Loan Module

### Out of Scope
- Performance Testing
- Security Testing
- Mobile Responsiveness
- API Testing

---

## 4. Test Approach
- **Testing Type:** Manual Functional Testing
- **Techniques Used:**
  - Equivalence Partitioning
  - Boundary Value Analysis
  - Exploratory Testing
  - Positive and Negative Testing

---

## 5. Test Environment
| Component | Details |
|-----------|---------|
| Application | ParaBank Demo |
| URL | https://parabank.parasoft.com |
| Browser | Google Chrome |
| OS | Windows 10 |
| Test Tool | MS Excel (Test Cases & Defect Reports) |

---

## 6. Test Credentials
| Field | Value |
|-------|-------|
| Username | testuser123 |
| Password | Test@1234 |

---

## 7. Modules and Test Case Count
| # | Module | Test Cases |
|---|--------|-----------|
| 1 | Login | 15 |
| 2 | Register | 20 |
| 3 | Open New Account | 12 |
| 4 | Accounts Overview | 10 |
| 5 | Transfer Funds | 15 |
| 6 | Bill Pay | 12 |
| 7 | Find Transactions | 12 |
| 8 | Update Contact Info | 15 |
| 9 | Request Loan | 10 |
| | **Total** | **121** |

---

## 8. Entry Criteria
- Application is accessible via browser
- Test credentials are available
- Test cases are prepared and reviewed

## 9. Exit Criteria
- All test cases executed
- All critical and high defects resolved
- Test summary report prepared

---

## 10. Defect Severity & Priority Definition
| Severity | Definition |
|----------|-----------|
| Critical | Application crash, data loss |
| High | Major feature not working |
| Medium | Feature working with workaround |
| Low | Minor UI issues |

---

## 11. Deliverables
- Test Plan (this document)
- Test Cases — Excel
- Defect Report — Excel
- Test Summary Report