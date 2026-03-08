# Bug Report – Delete action removes incorrect record

## ID
BUG-002

## Application
DemoQA

## Page
https://demoqa.com/webtables

## Environment
Browser: Chrome  
OS: Windows 10  
Device: Desktop

## Type
Functional Bug

## Category
CRUD / Delete

## Severity
High

## Priority
High

## Description
When clicking the delete icon for a specific row in the WebTables list, the system incorrectly deletes the last record in the table instead of the selected row.

## Steps to Reproduce

1. Navigate to https://demoqa.com/webtables
2. Ensure multiple records are present in the table
3. Click the delete icon on the first or middle row
4. Observe which record is removed

## Expected Result
The system should delete the record corresponding to the delete icon that was clicked.

## Actual Result
The system deletes the last record in the table regardless of which delete icon was selected.

## Impact
Users may accidentally delete the wrong records, causing data inconsistency and potential data loss.

## Evidence
GIF stored in `/evidence/gifs/bug-002-delete-removes-wrong-record.gif`