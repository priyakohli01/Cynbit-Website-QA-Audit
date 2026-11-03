# Cynbit Website — Quality Assurance Audit

**Website Under Test:** https://www.cynbit.in/  
**Project Type:** Manual Website QA Assessment  
**Role:** QA Testing Intern — Technical Assessment  
**Tools:** Google Chrome, Chrome DevTools, Lighthouse, Microsoft Excel

## Project Overview

This project documents a quality assurance assessment of the Cynbit Technologies website, focusing on functional behaviour, usability, responsive design, accessibility, performance and privacy-related observations.

The assessment combines exploratory testing, positive and negative test scenarios, responsive viewport checks and a Lighthouse mobile performance audit.

## Testing Scope

- Navigation and website functionality
- Contact form validation and enquiry confirmation
- Careers application form validation
- Product demo form selection
- Blog search, filtering and pagination
- BitElevate learning track navigation
- Responsive layouts across six viewport widths
- Keyboard navigation accessibility
- Lighthouse mobile performance
- Privacy notice review

## Test Execution Summary

| Status | Test Cases |
|---|---:|
| Pass | 5 |
| Fail | 2 |
| Partially Tested | 5 |
| Needs Review | 1 |
| Not Tested | 2 |
| **Total** | **15** |

These counts follow the master Test Matrix. Partially tested and unexecuted scenarios are documented separately.

## Key Findings

1. Contact form displayed generic feedback for a malformed email address.
2. Nested navigation menu did not support the expected Enter and Escape keyboard interactions.
3. Careers Privacy Policy link opened Terms of Service content.
4. Lighthouse mobile homepage audit recorded a Performance score of 38, LCP of 10.2 seconds and TBT of 4,990 milliseconds.

## Project Structure

```text
Cynbit-Website-QA-Audit/
├── README.md
├── reports/
│   ├── Cynbit_QA_Audit_Updated.docx
│   └── Cynbit_QA_Testing_Updated.xlsx
└── evidence/
    ├── screenshots/
    └── recordings/ (optional)
```

## Reports and Evidence

The Word report includes the audit methodology, scope, test environment, findings and prioritized improvement recommendations.

The Excel workbook contains the Issue Register and Test Matrix, including expected results, actual observations, execution statuses and screenshot references.

Screens
