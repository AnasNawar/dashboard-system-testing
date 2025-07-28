🧪 Dashboard System Testing Portfolio

This repository showcases a complete QA Testing portfolio for an internal Dashboard system. The project simulates a real-world testing lifecycle using **Jira**, **Zephyr**, and **manual testing best practices**, including test case design, execution, and bug reporting.

---

📁 Project Overview

This project was built to demonstrate structured testing practices across multiple features inside a dashboard system. The test process was conducted as a **Team-managed Scrum project** with defined sprints, user stories, and organized execution cycles.

---

🧩 Features Covered

Each feature was managed as a separate User Story on Jira, tested via structured test cases, and executed through Zephyr.

| Feature Name                     | User Story ID | Status       |
|----------------------------------|----------------|--------------|
| Login Functionality              | US-1           | ✅ Completed |
| Add New Product Category         | US-2           | ✅ Completed |
| Manage Category Archive          | US-3           | ✅ Completed |
| Add Sub-Category to Category     | US-4           | ✅ Completed |
| Manage Sub-Category Archive      | US-5           | ✅ Completed |
| Add Brand to a Category          | US-6           | ✅ Completed |
| Manage Brand Archive             | US-7           | ✅ Completed |
| Add Sub-Brand under a Brand      | US-8           | ✅ Completed |
| Manage Sub-Brand Archive         | US-9           | ✅ Completed |
| Action Confirmation Popups       | US-10          | ✅ Completed |
| Session Handling & Timeout       | US-11          | ✅ Completed |

---

📝 Test Case Design

All test cases follow a consistent structure and are documented via Jira Zephyr with the following format:

| Step No. | Test Step                         | Test Data         | Expected Result                          | Actual Result   | Status |
|----------|-----------------------------------|-------------------|------------------------------------------|------------------|--------|
| 1        | Navigate to login page            | N/A               | Login form should be displayed           | As Expected     | ✅ Pass |
| 2        | Enter valid email + password      | test@example.com  | User should be redirected to dashboard   | As Expected     | ✅ Pass |
| ...      |                                   |                   |                                          |                  |        |

Each test case includes:
- Title
- Objective
- Precondition
- Estimated Run Time
- Owner
- Labels (e.g., login, negative, session, etc.)

---

🐞 Bug Reporting

All bugs discovered during execution are documented in Jira with:
- Clear summary
- Full reproduction steps
- Expected vs. Actual results
- Screenshots or attachments
- Linked Test Case and User Story

---

🔄 Execution Strategy

Each feature has its **own Test Cycle** inside Zephyr, and was executed manually step-by-step. During execution:
- Actual Result is recorded for each step.
- Bug is logged immediately upon failure.
- Status is marked Pass/Fail for every case.

---

## 📂 Folder Structure

```bash
dashboard-system-testing-portfolio/
├── README.md
├── attachments/
│   ├── login-feature-testcase.png
│   ├── category-feature-bug-example.png
│   └── ...
└── documents/
    └── Portfolio Summary.pdf (optional)
