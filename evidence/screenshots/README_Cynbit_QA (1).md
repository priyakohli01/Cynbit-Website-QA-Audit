# Cynbit Website QA Audit

Preliminary public-site review and execution-ready QA test plan for https://www.cynbit.in/

## Deliverables
- `Cynbit_QA_Audit_Report.docx` — scope, methodology, environment matrix, observations and recommendations.
- `Cynbit_Bug_Register_and_Test_Cases.xlsx` — issue register, test cases and execution guidance.
- `evidence/` — add screenshots and short recordings for reproducible findings.

## Audit boundary
This package is a preliminary public-page/content/navigation review. Interactive form submission, real-device responsive testing, DOM-level accessibility, Lighthouse performance measurements, API testing and security penetration testing have **not** been executed. Items marked `Not Tested` must not be reported as failures until reproduced.

## Suggested repository structure
```text
cynbit-website-qa/
├── README.md
├── reports/
│   ├── Cynbit_QA_Audit_Report.docx
│   └── Cynbit_Bug_Register_and_Test_Cases.xlsx
├── evidence/
│   ├── screenshots/
│   └── recordings/
└── test-notes/
    └── execution-log.md
```

## Suggested execution workflow
1. Record browser, OS, viewport, date/time and network profile.
2. Execute the test cases in the workbook using synthetic data only.
3. Capture evidence and record actual results; keep unexecuted cases as `Not Tested`.
4. Log only reproducible defects with steps, expected/actual results, severity and priority.
5. Retest fixes and run related regression scenarios.

## Git commands
```bash
git init
git add .
git commit -m "Initial Cynbit website QA audit"
git branch -M main
git remote add origin https://github.com/<your-username>/cynbit-website-qa.git
git push -u origin main
```

Create the GitHub repository first, replace `<your-username>` with your account name, and do not upload personal data, credentials, cookies, access tokens or unredacted applicant information.

## Public pages included
Home, Services, Products, Story, Team, Careers, QA Testing Intern details, Blog page 1 and 2, Contact, BitElevate and BitElevate Learning Paths.
