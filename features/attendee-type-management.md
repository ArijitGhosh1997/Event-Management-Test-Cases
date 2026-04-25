# FEATURE_005: Attendee Type Management & Mapping with Mandatory Event Configuration

## Module
Configuration Management → Attendee Type & Event Creation

---

## Summary
Introduce attendee type management with mapping to user types and badge categories, along with mandatory attendee selection during event creation.

---

## Description
Admins should be able to create attendee types, map them with user types and badge categories, preview badge design, and enforce attendee type selection during event creation.

---

## Key Features

### Attendee Type Creation
- Admin can create attendee types (e.g., VIP, General)
- Each type is assigned a default/random icon
- Newly created types appear in mapping table

---

### Mapping Configuration
- User Type selection enables Badge Category dropdown
- Badge Category selection enables "View" button
- Mapping links attendee type → user type → badge category

---

### Badge Preview
- View button opens modal
- Modal displays:
  - Attendee Type name (title)
  - User Type & Badge Category (subtitle)
  - Sample QR code preview
  - QR specifications (color, size)

- Modal can be closed via:
  - Close button (X)
  - Clicking outside
  - Escape key

---

### Attendee Type Deletion
- Delete button available per type
- Confirmation dialog appears before deletion
- Type removed after confirmation

---

### Event Creation Validation
- Attendee Type selection is mandatory
- Event cannot be saved without selecting at least one type
- Validation message should be displayed if not selected

---

## Edge Cases
- Empty attendee type name → show error
- Duplicate attendee type name → show error
- Badge Category disabled until User Type selected

---

## Expected Behavior
- Admin can create, map, preview, and delete attendee types
- Event creation enforces attendee type selection
- Mapping ensures correct badge generation

---

## Acceptance Criteria
- Attendee types can be created and listed
- Mapping between attendee type, user type, and badge category works
- Badge preview modal functions correctly
- Deletion requires confirmation
- Event creation fails without attendee type selection

---

## Type
Feature / Configuration Enhancement
