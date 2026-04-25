# ENHANCEMENT_002: Badge Category Management with Color-Coded QR Codes

## Module
Configuration Management → Badge Categories

---

## Summary
Enhance badge category creation by replacing image-based Badge URL with a color picker for generating color-coded QR codes for different guest categories.

---

## Description
The current system uses Badge URL for badge representation. This should be replaced with a color-based QR code system where each guest category (e.g., VIP, General) has a unique QR color.

---

## Key Requirements

### Category Management
- Support multiple guest categories (e.g., VIP 1, VIP 2, General)
- Each category should have its own configuration

---

### QR Code Customization
- Introduce color picker for each category
- Generate QR codes using selected color
- Default QR size: 1x1 (sticker-compatible)

---

### UI Changes
- Hide existing Badge URL field (do not remove from backend)
- Add color picker input for each category
- Allow easy category creation and editing

---

### Printing Compatibility
- Ensure QR codes are compatible with standard label printers
- Must support 1x1 sticker printing format

---

## Expected Behavior
- Admin can create multiple categories with different QR colors  
- QR codes are generated using selected colors  
- System maintains consistent QR size and format  

---

## Acceptance Criteria
- Badge URL field is hidden from UI  
- Color picker available for each category  
- QR codes generated in selected color  
- QR codes are printable and scanner-compatible  
- Admin can create, update, and manage categories  

---

## Type
Enhancement
