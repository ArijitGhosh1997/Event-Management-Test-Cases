# BUG_009: QR Code Sent as Attachment Instead of Inline Email Content

## Module
User Communication → Email Notification

---

## Summary
QR code is sent as an attachment instead of being displayed within the email body.

---

## Description
In the current implementation, emails sent to users include QR codes as separate attachments. This reduces usability and affects the visual consistency of the email.

---

## Steps to Reproduce
1. Trigger email notification (e.g., after user registration)  
2. Check received email  

---

## Expected Result
- QR code should be embedded within the email body  
- QR should be clearly visible without opening attachments  

---

## Actual Result
- QR code is sent as a separate attachment  
- User must download or open attachment to view QR  

---

## Impact
- Poor user experience  
- Reduced accessibility  
- Inconsistent email design  

---

## Severity
Medium  

## Priority
High  

## Type
UI/UX Bug  

---

## Suggested Fix
- Embed QR code directly in email body using inline image  
- Ensure proper formatting across email clients  
