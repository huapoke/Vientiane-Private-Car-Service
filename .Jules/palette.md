# Palette's Journal - Critical UX Learnings

## 2026-07-25 - Static Landing Page Floating Actions and Label Associations
**Learning:** In single-page static marketing/booking templates styled with utility CSS, floating action buttons frequently rely on emoji characters without text equivalents or accessible landmarks (`<nav>`). Furthermore, uppercase micro-labels often omit `for` attribute mappings, which degrades mobile tap targets and screen reader input identification.
**Action:** Always wrap floating action buttons in a semantic `<nav aria-label="...">`, attach clear `aria-label`s with `aria-hidden="true"` emojis, and explicitly link every `<label for="...">` with `cursor-pointer` to maximize clickable target area on touch and desktop devices.
