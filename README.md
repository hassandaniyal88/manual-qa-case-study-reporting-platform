# Manual QA Case Study  
## Multi-Role Web & Mobile Reporting Platform (v1 Release)

---

## 1. Background

This case study documents the manual Quality Assurance effort performed for a multi-platform reporting system designed to support structured incident reporting and internal communication across multiple user roles.

The system required high levels of data accuracy, role-based access control, and cross-platform consistency prior to its initial production release (v1).

---

## 2. Objective

The objective of this QA engagement was to:

- Validate functional correctness of core reporting workflows  
- Ensure data integrity between user input and generated reports  
- Verify role-based access and feature visibility  
- Identify high-risk defects impacting release readiness  
- Support informed decision-making for v1 production release  

---

## 3. Application Overview

| Attribute | Details |
|---------|--------|
| Application Type | Web & Mobile |
| Domain | Public Safety / Reporting |
| Platforms | Web, Android, iOS |
| User Roles | Civilian, Officer, Command, Super Admin |
| QA Type | Manual Testing |
| Test Phases | Functional, Regression, UI/UX |

---

## 4. QA Scope

### In Scope
- Authentication & role-based authorization  
- Incident and motor accident reporting  
- Inbox and report sharing  
- Identity panel  
- Map & location handling  
- Attachments (Dropbox integration)  
- Data persistence & validation  
- UI consistency across platforms    
- Performance and load testing  
- Security testing  

---

## 5. QA Approach & Methodology

A requirement-driven, risk-based manual testing approach was followed:

- Analysis of functional requirements and acceptance criteria  
- Design and execution of test scenarios and test cases  
- Smoke testing on each new build  
- Functional validation of business-critical flows  
- Regression testing after defect resolution  
- Cross-platform verification (Web vs Mobile)  
- UI/UX validation for usability and layout issues  

---

## 6. Key Challenges

### 6.1 Requirement Volatility
Several features evolved during development and were introduced as new or modified requirements.  
QA ensured changes were validated against original scope and did not negatively impact existing functionality.

### 6.2 Data Integrity Risks
Multiple discrepancies were identified between user-entered data and final report output, posing a risk to system reliability.

### 6.3 Role-Based Logic Complexity
Feature behavior varied significantly across user roles, increasing the risk of incorrect access or data exposure.

---

## 7. Defect Analysis (Representative Examples)

### Defect 1 – Application Crash During Report Editing
- Category: Stability  
- Severity: Critical  
- Impact: Users were unable to edit active reports, blocking core workflows  
- Outcome: Root cause fixed and regression verified  

---

### Defect 2 – Incorrect Incident Location Display
- Category: Data Accuracy  
- Severity: High  
- Impact: Incident location displayed incorrectly, affecting reporting credibility  
- Outcome: Location logic corrected and validated  

---

### Defect 3 – Loss of Draft Data on Navigation
- Category: Data Persistence  
- Severity: Critical  
- Impact: Users lost entered information before submission  
- Outcome: Draft persistence implemented and verified  

---

## 8. Test Execution Summary

| Metric | Result |
|------|-------|
| Test Cases Executed | 200+ |
| Critical Defects Identified | 10+ |
| Release Blockers | 3 |
| Platforms Tested | Web, Android, iOS |
| Final QA Recommendation | Approved for v1 Release |

---

## 9. QA Contribution & Value

- Identified and mitigated release-blocking defects  
- Improved system stability and data reliability  
- Strengthened role-based access behavior  
- Reduced risk of production incidents  
- Supported a confident v1 release decision  

---

## 10. Conclusion

This case study demonstrates a structured manual QA engagement focused on functional validation, defect risk assessment, and release readiness.

QA involvement played a key role in improving product quality and ensuring a stable initial production release.

---

## Confidentiality Notice

Application name and sensitive information have been anonymized to maintain confidentiality.  
This case study is shared for demonstration and learning purposes only.

---

## Repository Structure (Optional)

