## 2026-03-29 - Form Labels & Floating Action Buttons Accessibility
**Learning:** Icon-only or emoji-only floating action buttons lack accessible names without `aria-label` attributes, rendering them unannounced to screen readers. Form inputs without explicit `for` attributes on `<label>` elements reduce clickable area and impair screen reader navigation.
**Action:** Always pair form `<label>` tags with input `id`s using `for`, supply `aria-label`s and `title`s for emoji/icon-only links/buttons, and apply `focus-visible` ring indicators across interactive elements.
