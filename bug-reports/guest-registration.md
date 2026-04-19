# Bug: Guest Registration Form Validation & UI Issues

## Module
Event Guests Registration

## Description
Multiple issues were observed in the guest registration form:

- System accepts invalid mobile numbers (less than or more than 10 digits)
- Mandatory field indicator (*) missing for Phone Number
- Email field asterisk misaligned
- Input fields do not show focus/blur state

---

## Steps to Reproduce
1. Open Guest Registration form
2. Enter invalid mobile numbers (e.g., 2525 or very long number)
3. Observe UI elements

---

## Expected Result
- Only 10-digit mobile numbers should be accepted
- Mandatory fields should show * indicator
- Asterisk should be properly aligned
- Input fields should show focus effect on click

---

## Actual Result
- Invalid numbers are accepted and stored
- Phone field appears optional
- Asterisk is misaligned
- No focus/blur effect on input fields

---

## Severity
High

## Type
Functional + UI Bug
