# Bug Report – Close button does not close confirmation modal

## ID
BUG-001

## Application
DemoQA

## Page
https://demoqa.com/automation-practice-form

## Environment
Browser: Chrome  
OS: Windows 10  
Device: Desktop

## Type
Functional Bug

## Category
UI Interaction

## Severity
Medium

## Priority
Medium

## Description
After submitting the practice form, a confirmation modal appears displaying the message **"Thanks for submitting the form"**.

However, clicking the **Close** button does not close the modal dialog as expected.

The modal only closes when clicking outside the dialog.

## Steps to Reproduce

1. Navigate to https://demoqa.com/automation-practice-form
2. Fill in the required fields
3. Click the **Submit** button
4. Wait for the confirmation modal to appear
5. Click the **Close** button

## Expected Result
Clicking the **Close** button should close the modal dialog.

## Actual Result
The modal remains open and only closes when clicking outside the modal area.

## Impact
Users may believe the system is unresponsive because the button does not perform the expected action.

## Evidence
GIF stored in `/evidence/gifs/bug-001-close-button-not-working.gif`