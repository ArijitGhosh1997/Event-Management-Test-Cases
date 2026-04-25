# BUG_006: Unexpected Browser Alert on User Rejection

## Module
User Management → Registered Users

---

## Summary
When rejecting a user, the system displays a browser alert instead of a styled in-app notification, leading to inconsistent UI/UX.

---

## Steps to Reproduce
1. Navigate to Registered Users module  
2. Select a user  
3. Click on Reject action  

---

## Expected Result
- User should be rejected successfully  
- A styled in-app notification (toast/message) should be displayed  

---

## Actual Result
- Browser alert dialog appears with message "User rejected"  
- User interaction is blocked until dismissed  

---

## Impact
- Breaks UI consistency  
- Interrupts user workflow  
- Unprofessional user experience  

---

## Severity
Medium  

## Priority
High  

## Type
UI/UX Bug  

---

## Suggested Fix
- Replace browser alert with in-app toast notification  
- Ensure consistent UI behavior across application  
