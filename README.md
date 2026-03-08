<p align="center">
<img src="assets/qa-bug-hunt-banner.png" width="900">
</p>

# QA Bug Hunt – DemoQA

Exploratory testing project documenting UI, validation and CRUD issues found in the DemoQA web application.

Application tested:  
https://demoqa.com/

---

## Table of Contents

- [Objective](#objective)
- [Test Environment](#test-environment)
- [Bug Summary](#bug-summary)
- [Bug Evidence](#bug-evidence)
- [Repository Structure](#repository-structure)
- [Testing Scope](#testing-scope)
- [Testing Approach](#testing-approach)

---

Repository documenting bugs identified during exploratory testing of the DemoQA website.

Application tested:  
https://demoqa.com/

---

## Objective

Demonstrate practical QA skills including:

- exploratory testing
- bug identification
- validation analysis
- CRUD testing
- UI interaction testing
- documentation of software defects

---

## Test Environment

Browser: Google Chrome  
Operating System: Windows 10  
Application Under Test: DemoQA  
Testing Type: Exploratory Testing

---

## Bug Summary

| ID | Title | Category | Severity | Priority | Evidence |
|----|------|----------|----------|----------|----------|
| BUG-001 | Close button does not close confirmation modal | UI Interaction | Medium | Medium | [View Evidence](evidence/gifs/bug-001-close-button-not-working.gif) |
| BUG-002 | Delete action removes incorrect record | CRUD / Delete | High | High | [View Evidence](evidence/gifs/bug-002-delete-removes-wrong-record.gif) |
| BUG-004 | Salary field does not display validation message | Validation / UX | Medium | Medium | [View Evidence](evidence/screenshots/bug-004-invalid-salary-format.png) |
| BUG-005 | Edited record not reflected in WebTable | CRUD / Update | Medium | Medium | [View Evidence](evidence/gifs/bug-005-edit-update-not-reflected-in-table.gif) |

---

## Bug Evidence

[![BUG-001 Evidence](https://img.shields.io/badge/BUG--001-Evidence-blue?style=for-the-badge)](evidence/gifs/bug-001-close-button-not-working.gif)

[![BUG-002 Evidence](https://img.shields.io/badge/BUG--002-Evidence-red?style=for-the-badge)](evidence/gifs/bug-002-delete-removes-wrong-record.gif)

[![BUG-004 Evidence](https://img.shields.io/badge/BUG--004-Evidence-orange?style=for-the-badge)](evidence/screenshots/bug-004-invalid-salary-format.png)

[![BUG-005 Evidence](https://img.shields.io/badge/BUG--005-Evidence-purple?style=for-the-badge)](evidence/gifs/bug-005-edit-update-not-reflected-in-table.gif)

---

## Repository Structure


# QA Bug Hunt – DemoQA
Exploratory testing project documenting UI, validation and CRUD issues found in the DemoQA web application.

```
qa-bug-hunt-demoqa
│
├── assets
│
├── bug-reports
│   ├── bug-001-close-button-not-working.md
│   ├── bug-002-delete-removes-wrong-record.md
│   ├── bug-004-invalid-salary-format.md
│   └── bug-005-edit-update-not-reflected-in-table.md
│
├── evidence
│   ├── gifs
│   └── screenshots
│
└── README.md
```


---

## Testing Scope

The testing focused on the following areas:

- form validation
- CRUD operations within the WebTables component
- UI interaction behavior
- modal interaction
- input validation

---

## Testing Approach

The issues documented here were discovered through:

- exploratory testing
- UI interaction testing
- validation testing
- CRUD operation testing