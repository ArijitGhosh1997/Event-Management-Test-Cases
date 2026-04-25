# BUG_008: Incorrect Event Date Display Due to Timezone Conversion

## Module
Event Management → Event Listing / Event Details

---

## Summary
Event date is displayed incorrectly due to unintended timezone conversion on the frontend.

---

## Steps to Reproduce
1. Create or view an event  
2. Check event date in UI  

---

## Expected Result
- Event date should remain consistent as stored  
- No timezone-based date shift should occur  

---

## Actual Result
- Event date is converted based on user timezone  
- Displays incorrect (previous day) date  

---

## Impact
- Confusion for users  
- Incorrect event scheduling information  
- Inconsistent display across regions  

---

## Severity
High  

## Priority
High  

## Type
Functional Bug  

---

## Suggested Fix
- Disable unnecessary timezone conversion  
- Ensure consistent date rendering across UI  
