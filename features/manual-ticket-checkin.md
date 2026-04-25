# FEATURE_004: Manual Ticket Number Check-In Option

## Module
Event Check-In → QR Validation

---

## Summary
Introduce a manual check-in option allowing users to enter a ticket number instead of scanning via device.

---

## Description
Currently, users can check in using scanner-based methods. A new option should allow manual entry of ticket numbers to complete the check-in process without requiring a scanner.

---

## Key Features

### Check-In Options
- Existing:
  - Scanner-based validation
- New:
  - "Check with Ticket No" option

---

### Manual Entry Flow
- User selects "Check with Ticket No"
- System opens input screen
- User enters ticket number manually

---

### Ticket Format
- Ticket number is extracted from QR code format  
- Example: `#ABC-611` → Ticket Number: `611`

---

### API Integration
- Use existing scan API  
- Pass ticket number as input parameter  
- Fetch user details  

---

### Check-In Handling
- Based on API response, determine next action  
- If eligible → show Check-In button  
- Perform check-in using existing backend logic  

---

## Expected Behavior
- User can enter ticket number manually  
- System fetches correct user details  
- Check-in flow works similar to scanner-based process  

---

## Acceptance Criteria
- Manual ticket entry option is visible  
- User can input ticket number  
- System validates and retrieves user data  
- Check-in process completes successfully  
- Flow matches existing scanner-based behavior  

---

## Type
Feature
