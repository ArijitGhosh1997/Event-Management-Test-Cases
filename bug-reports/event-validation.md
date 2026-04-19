# Bug: Invalid Event Date Validation

## Description
System allows:
- Past event creation
- End date before start date
- Registration close date after event start

---

## Expected Result
- Event start date must be future
- End date ≥ start date
- Registration close ≤ start date

---

## Actual Result
- Invalid data accepted and event created

---

## Severity
Critical
