# Premier League Match Registration Page

## Short Note: Accessibility Note & AI Reflection

### 1. Issues Identified by AI Audit:
* **Missing Explicit Labels:** Several form controls lacked proper `<label>` elements linked with matching `for` and `id` attributes.
* **Lack of Semantic Structure:** Form elements were not grouped with semantic tags, making navigation difficult for screen readers.
* **Missing HTML5 Validation Constraints:** Form inputs were missing standard accessibility attributes like `required`, `min`, and `max`.

### 2. Improvements Implemented:
* **Added Explicit Labels:** Linked every `<input>` and `<select>` control directly to a corresponding `<label>` using matching `id` and `for` attributes.
* **Enhanced Semantic Grouping:** Enclosed the main content in a `<main>` tag and organized form fields into sections using `<fieldset>` and `<legend>` tags (`Personal Details` and `Match Selection`).
* **Applied Native Validation:** Added `required`, `min`, `max`, and proper input types (`email`, `number`) to ensure accessible browser-level error handling.
* **W3C Standards Verification:** Validated the HTML structure against W3C standards to guarantee zero markup errors.