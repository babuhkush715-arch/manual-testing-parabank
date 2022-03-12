# Test Summary Report — ParaBank Web Application

## 1. Document Information
| Field | Details |
|-------|---------|
| Project | ParaBank Manual Testing |
| Prepared By | Babusingh Kushwaha |
| Date | 12-Mar-2022 |
| Application URL | https://parabank.parasoft.com |
| Test Type | Manual Functional Testing |

---

## 2. Test Execution Summary

| Module | Total TCs | Pass | Fail | Pass % |
|--------|-----------|------|------|--------|
| Login | 15 | 7 | 8 | 47% |
| Register | 20 | 4 | 16 | 20% |
| Open New Account | 12 | 10 | 2 | 83% |
| Accounts Overview | 10 | 10 | 0 | 100% |
| Transfer Funds | 15 | 7 | 8 | 47% |
| Bill Pay | 12 | 3 | 9 | 25% |
| Find Transactions | 12 | 5 | 7 | 42% |
| Update Contact Info | 15 | 6 | 9 | 40% |
| Request Loan | 10 | 3 | 7 | 30% |
| **Total** | **121** | **55** | **66** | **45%** |

---

## 3. Defect Summary

### By Status
| Status | Count |
|--------|-------|
| Open | 14 |
| In Progress | 4 |
| Fixed | 12 |
| **Total** | **30** |

### By Severity
| Severity | Count |
|----------|-------|
| Critical | 1 |
| High | 16 |
| Medium | 12 |
| Low | 1 |

---

## 4. Critical Findings

- **DID015 (Critical):** Transfer Funds allows transactions exceeding available
  balance — no insufficient funds validation. This is the most severe defect
  found and needs immediate fix before production.
- Input validation is weak across most modules — empty fields, negative
  numbers, and invalid formats are frequently accepted without errors.
- Register and Bill Pay modules have the highest defect density, indicating
  these forms need a thorough validation review.

---

## 5. Modules with Best Quality
- **Accounts Overview** — 100% pass rate, no defects found
- **Open New Account** — 83% pass rate, only minor issues

## 6. Modules Needing Improvement
- **Register** — 20% pass rate, 16 open/fixed defects
- **Bill Pay** — 25% pass rate, weak field validation
- **Request Loan** — 30% pass rate, numeric validation issues

---

## 7. Test Environment
| Component | Details |
|-----------|---------|
| Browser | Google Chrome |
| OS | Windows 10 |
| Application | ParaBank Demo Environment |

---

## 8. Conclusion

Out of 121 test cases executed across 9 modules, 55 passed and 66 failed,
giving an overall pass rate of 45%. The application shows strong functional
stability in core account viewing features but exhibits significant gaps in
input validation across form-based modules (Register, Bill Pay, Request Loan,
Transfer Funds). It is recommended that input validation be strengthened
before the application is considered production-ready, with priority given
to the Critical defect (DID015) related to fund transfer balance checks.

---

## 9. Sign Off

| Role | Name | Date |
|------|------|------|
| Tester | Babusingh Kushwaha | 12-Mar-2022 |