# Premier League Match Registration Page

## Short Note: Accessibility Note & AI Reflection

### 1. Issues Identified by AI Audit:
* **Missing Explicit Labels:** Several form controls lacked proper `<label>` elements linked with matching `for` and `id` attributes.
* **Lack of Semantic Structure:** Form elements and page structure were missing semantic container tags like `<nav>` and `<main>`, making navigation difficult for screen readers.
* **Insufficient Input Variety & Fields:** The form originally lacked enough fields and input types to fully comply with required criteria (required ≥6 fields across ≥4 input types).
* **Missing HTML5 Validation Constraints:** Form inputs lacked standard attributes like `required`, `min`, `max`, and `pattern`.

### 2. Improvements Implemented:
* **Enhanced Semantic Layout:** Structured the page using `<header>`, `<nav>`, `<main>`, and `<footer>` tags for complete semantic accuracy.
* **Expanded Form Fields & Input Types:** Created 6 distinct fields using 4 different input types (`text`, `email`, `tel`, and `number`), plus a `<select>` dropdown.
* **Added Explicit Labels & Grouping:** Linked every input control directly to a corresponding `<label>` using matching `id` and `for` attributes, grouped into logical sections using `<fieldset>` and `<legend>`.
* **Applied Native Validation:** Added `required`, `min`, `max`, and `pattern="[0-9]{10}"` attributes for robust browser-level validation.
* **W3C Standards Verification:** Ensured clean, error-free HTML markup compliant with W3C standards.