# Bug Report – Edited record not reflected in WebTable view

## ID
BUG-005

## Application
DemoQA

## Page
https://demoqa.com/webtables

## Environment
Browser: Chrome  
OS: Windows 10  
Device: Desktop

## Type
UI Bug / Data Refresh Issue

## Severity
Medium

## Priority
Medium

## Description
When editing an existing record and submitting the changes, the updated values are not reflected in the WebTable view.

However, when clicking the Edit button again for the same record, the updated values appear in the form, indicating that the data was successfully updated but the table view was not refreshed.

## Steps to Reproduce

1. Open https://demoqa.com/webtables
2. Click the edit icon for an existing record
3. Modify one or more fields
4. Click Submit
5. Observe the table values
6. Click Edit again for the same record

## Expected Result
The WebTable should immediately display the updated values after submission.

## Actual Result
The WebTable continues to display the previous values, even though the updated values are stored and visible when opening the edit form again.

## Impact
Users may believe the update failed because the table does not reflect the changes.

## Evidence
GIF stored in `/evidence/gifs`