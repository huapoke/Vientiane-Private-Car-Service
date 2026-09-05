## 2026-09-05 - Explicit Form Labels & Floating Icon Accessibility
**Learning:** Icon-only floating action widgets and unlinked form labels reduce screen reader accessibility and keyboard focus feedback in single-page HTML apps.
**Action:** Always associate `<label>` elements with `for="id"` and add explicit `aria-label` attributes plus Tailwind `focus-visible` ring styles to floating emoji/icon action links.
