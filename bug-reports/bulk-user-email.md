# BUG_007: Multiple Emails Sent Instead of Single Consolidated Email in Bulk User Registration

## Module
User Management → Bulk Registration

---

## Summary
Bulk user registration sends multiple separate emails instead of a single consolidated email with all QR codes.

---

## Steps to Reproduce
1. Navigate to Pending Users  
2. Click on Register Bulk User  
3. Upload multiple users  
4. Complete registration  
5. Check recipient inbox  

---

## Expected Result
- Only one email should be sent  
- Email should contain all QR codes as attachments or in a combined format  

---

## Actual Result
- Multiple emails are sent (one per user)  
- Each email contains a single QR code  

---

## Impact
- Inbox clutter for users  
- Poor user experience  
- Inefficient communication  

---

## Severity
High  

## Priority
High  

## Type
Functional Bug  

---

## Suggested Fix
- Aggregate all QR codes into a single email  
- Optimize email sending logic for bulk operations  
