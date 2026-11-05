# Palette's Journal

## 2026-03-06 - Floating action elements and input label association
**Learning:** In lightweight single-page static landing pages with dark glassmorphism styling, floating action widgets often use pure emoji icons without text or ARIA descriptors, causing screen readers to announce them ambiguously or skip context. Additionally, unassociated `<label>` elements decrease mobile tap target usability and prevent assistive tech from linking field instructions to form inputs.
**Action:** Pair `<label for="...">` with control `id`s for tap-to-focus and screen-reader accessibility, and always provide descriptive `aria-label`s and `focus-visible` ring indicators on emoji-only and icon-only floating buttons.
