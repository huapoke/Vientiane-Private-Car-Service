## 2026-03-31 - Explicit Form Controls and Floating Emoji Links Accessibility
**Learning:** Icon/emoji-only floating action links and HTML form inputs without explicit `for`/`id` bindings fail screen reader navigation and keyboard accessibility checks in single-page static HTML forms.
**Action:** Always link form labels explicitly with `for` attributes and add descriptive `aria-label`s and `:focus-visible` ring outlines to floating emoji action buttons.
