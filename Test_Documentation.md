# Layout Testing

Validated:
- Default state of the reservation form
- Visibility of tariff options
- Navigation map display
- UI element positioning and consistency

**Result:** All checklist items approved.



# Payment Method & Add Card Validation

Scenarios tested:
- Payment Method modal opens correctly
- Add Card window displays properly
- Card input fields accept valid data
- Special character handling
- Form submission behavior

**Result:**
- Most scenarios passed
- One validation defect identified related to incorrect handling of special characters
- Defect documented and reported


# “Reserve” Button – Business Logic Validation

Preconditions:
- Valid driver’s license added
- Valid payment method added

Validations performed:
- Button activates only after mandatory fields are completed
- Route calculation message appears
- Correct text update after click
- Reservation logic triggers successfully

**Result:** All scenarios passed in the test environment.



# Reservation Flow Testing

Validated complete reservation process:
1. Add required documents
2. Add payment method
3. Click “Reserve”
4. Confirm reservation

**Expected Result:** Confirmation modal appears indicating successful vehicle reservation.  
**Result:** Test executed successfully.
