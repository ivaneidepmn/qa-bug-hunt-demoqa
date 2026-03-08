# Bug Report – Salary field does not display validation message

## ID
BUG-004

## Application
DemoQA

## Page
https://demoqa.com/webtables

## Environment
Browser: Chrome  
OS: Windows 10  
Device: Desktop

## Type
Validation Issue / UX Issue

## Category
Validation / UX

## Severity
Medium

## Priority
Medium

## Description
When entering a salary value using a decimal format (e.g., "15.600"), the system marks the field as invalid but does not display any validation message explaining the error or the accepted format.

## Steps to Reproduce

1. Open https://demoqa.com/webtables
2. Click "Add"
3. Fill in all required fields
4. Enter "15.600" in the Salary field
5. Click Submit

## Expected Result
The system should display a validation message explaining the accepted format for the salary field.

## Actual Result
The field is highlighted in red with an error icon, but no message explains the validation rule.

## Impact
Users may not understand why the value is invalid or what format should be used.

## Evidence
Screenshot stored in `/evidence/screenshots/bug-004-invalid-salary-format.png`