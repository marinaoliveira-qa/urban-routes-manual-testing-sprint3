# Bug Report – Add Card Field Validation

**Bug ID:** UR-S3-001  
**Feature:** Payment Method – Add Card Form  
**Priority:** Medium  
**Severity:** Major  
**Environment:** Google Chrome (800x600)  

## Description
The Add Card form incorrectly accepts special characters in the Card Number input field.

## Preconditions
User navigates to Payment Method → Add Card window.

## Steps to Reproduce
1. Open Payment Method modal  
2. Click "Add Card"  
3. Enter special characters (e.g., @#$%) in the Card Number field  
4. Attempt to submit the form  

## Expected Result
The system should reject special characters and display a validation error message.

## Actual Result
The form accepts special characters without displaying an error message.

## Status
Reported
