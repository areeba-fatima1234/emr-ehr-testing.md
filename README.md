EMR & EHR Software Testing – Manual QA Project

1. Project Overview

This project demonstrates sample manual testing scenarios for Electronic Medical Records (EMR) and Electronic Health Records (EHR) systems.

The objective is to verify important healthcare application functionalities, data validation, and user workflows.

2. Testing Scope

- Patient Registration
- Patient Records Management
- Appointment Scheduling
- Medical History
- Doctor and Staff Login
- Patient Search
- Data Validation

3. Test Cases

Test Case ID| Test Scenario| Expected Result
EMR-001| Register a new patient| Patient should be registered successfully
EMR-002| Register patient with missing mandatory fields| Validation messages should appear
EMR-003| Search patient using patient ID| Correct patient record should appear
EMR-004| Update patient information| Updated information should be saved
EMR-005| Schedule a patient appointment| Appointment should be created successfully
EMR-006| View patient medical history| Correct medical history should be displayed
EMR-007| Login with invalid credentials| Appropriate error message should appear
EMR-008| Search using an invalid patient ID| No matching record should be displayed

4. Sample Bug Report

Bug ID: EMR-BUG-001

Module: Patient Registration

Title: Mandatory field validation is not displayed.

Severity: High

Priority: High

Steps to Reproduce:

1. Open the patient registration page.
2. Leave a mandatory field empty.
3. Enter other required information.
4. Click Save.

Expected Result: The system should display a validation message for the missing mandatory field.

Actual Result: Not yet verified. This is a sample defect scenario.

Status: Not Executed

5. Important Quality Considerations

- Patient data accuracy
- Role-based access control
- Data privacy and confidentiality
- Input validation
- Proper error handling
- Secure access to patient records

6. Project Summary

This sample project demonstrates knowledge of manual testing concepts and healthcare application workflows.

Note: These are portfolio demonstration scenarios, not confirmed defects or actual patient data. No real patient information is included.
