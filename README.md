# ParaBank — Manual Testing Project

A complete manual functional testing project for the **ParaBank** online
banking demo application, covering 9 modules with 121 test cases and
30 logged defects.

---

## Application Under Test
- **Name:** ParaBank
- **URL:** https://parabank.parasoft.com
- **Type:** Online Banking Demo Application

---

## Project Structure

```
manual-testing-parabank/
├── test-plan/
│   └── Test_Plan.md              # Scope, approach, environment
├── test-cases/
│   └── ParaBank_Test_Cases.xlsx  # 121 test cases across 9 modules
├── defect-reports/
│   └── ParaBank_Defect_Report.xlsx  # 30 logged defects
├── test-summary/
│   └── Test_Summary_Report.md    # Final execution summary
└── README.md
```

---

## Modules Tested

| # | Module | Test Cases | Pass | Fail |
|---|--------|-----------|------|------|
| 1 | Login | 15 | 7 | 8 |
| 2 | Register | 20 | 4 | 16 |
| 3 | Open New Account | 12 | 10 | 2 |
| 4 | Accounts Overview | 10 | 10 | 0 |
| 5 | Transfer Funds | 15 | 7 | 8 |
| 6 | Bill Pay | 12 | 3 | 9 |
| 7 | Find Transactions | 12 | 5 | 7 |
| 8 | Update Contact Info | 15 | 6 | 9 |
| 9 | Request Loan | 10 | 3 | 7 |
| | **Total** | **121** | **55** | **66** |

**Overall Pass Rate: 45%**

---

## Testing Approach

- **Type:** Manual Functional Testing
- **Techniques:** Equivalence Partitioning, Boundary Value Analysis,
  Positive and Negative Testing, Exploratory Testing
- **Tool:** MS Excel for test case design and defect logging

---

## Defect Summary

| Severity | Count |
|----------|-------|
| Critical | 1 |
| High | 16 |
| Medium | 12 |
| Low | 1 |

**Key Finding:** Transfer Funds module allows transactions exceeding
available balance — flagged as Critical severity defect (DID015).

---

## Deliverables

1. **Test Plan** — scope, approach, entry/exit criteria
2. **Test Cases** — 121 test cases with steps, data, expected results
3. **Defect Report** — 30 defects with severity, priority, status tracking
4. **Test Summary Report** — final pass/fail analysis and conclusion

---

## Skills Demonstrated

- Test Plan creation
- Test Case design (positive, negative, boundary scenarios)
- Defect Life Cycle management (Open → In Progress → Fixed)
- Severity and Priority classification
- Test Summary Reporting
- Exploratory testing on live web application

---

## Author

**Babusingh Kushwaha**
Project Associate, CSIR-NEERI Nagpur
Software Testing (Manual + Automation) | Data Analytics

[![GitHub](https://img.shields.io/badge/GitHub-babuhkush715--arch-blue)](https://github.com/babuhkush715-arch)

---

## Related Projects

- [Hostel ERP SQL Database](https://github.com/babuhkush715-arch/hostel-erp-sql)
- [India Air Quality Analytics](https://github.com/babuhkush715-arch/india-air-quality-analytics)
