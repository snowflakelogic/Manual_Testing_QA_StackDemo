# Manual_Testing_QA_StackDemo
QA Manual Testing Project 

## Project Overview

This repository documents a manual QA testing project performed on the **BStackDemo e-commerce web application**. It covers the software testing lifecycle, including test planning, test case design, test execution, defect identification, and bug reporting. Jira was used to organize testing activities and track issues through an Agile workflow.

## Objectives

- Test the major functional modules of the BStackDemo application.
- Design test cases for positive, negative, and edge-case scenarios.
- Execute test cases and document pass/fail results.
- Report defects with reproduction steps, expected and actual results, and severity.
- Manage Epics, User Stories, and Bugs using Jira.

## Application Under Test

- **Application:** BStackDemo
- **Website:** https://www.bstackdemo.com/

Testing was performed using the available demo accounts to validate application workflows and identify functional issues.

## Tools and Technologies

| Tool | Purpose |
|---|---|
| Jira | Agile project management and defect tracking |
| Microsoft Excel | Test case repository and execution reporting |
| Google Chrome / Firefox | Application and cross-browser testing |
| Screenshots | Defect evidence and documentation |

## Testing Scope

- **Login:** Authentication scenarios
- **Product Listing:** Product visibility and image loading
- **Product Details:** Product information and interactions
- **Cart:** Add-to-cart and cart functionality
- **Checkout:** Checkout flow and input validation
- **Logout / Session:** Logout and session behavior
- **UI / Cross-browser:** Interface consistency across browsers

## Test Execution Summary

| Metric | Count |
|---|---:|
| Test Cases Designed | 36 |
| Test Cases Executed | 36 |
| Passed | 34 |
| Failed | 2 |
| Bugs Identified | 2 |

**Execution result:** 34 of 36 test cases passed, giving a pass rate of 94.4%.

## Defect Summary

| Bug ID | Module | Description | Severity |
|---|---|---|---|
| BUG_001 | Product Listing | Product images fail to load for the `image_not_loading_user` account. | Medium |
| BUG_002 | Checkout | The postal code field accepts invalid formats without proper validation. | Medium |

Detailed defect reports and supporting screenshots are maintained in the `Bugs/` directory.

## Repository Structure

```text
BStackDemo-Manual-QA-Testing/
├── Bugs/
├── Jira/
├── BStackDemo_Test_Case_Repository.xlsx
├── BStackDemo_Test_Execution_Report.xlsx
├── Feature Analysis.docx
├── TEST PLAN.docx
└── README.md
```

## Jira Workflow

Jira was used to organize and track testing activities, including:

- Epic creation for major testing areas
- User Story creation for application modules
- Sprint planning and task organization
- Test execution tracking
- Bug reporting and linking defects to relevant User Stories

## Key Learnings

- Manual test case design and scenario coverage
- Positive, negative, and edge-case testing
- Test execution and result documentation
- Defect reporting and severity assignment
- Agile project management using Jira
- QA documentation and screenshot-based evidence

## Conclusion

This project demonstrates a structured manual QA workflow, from test planning and execution to defect documentation and Agile issue tracking. It showcases practical testing skills and organized QA deliverables relevant to a manual software testing role.
