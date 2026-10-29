# Palette Journal - UX & Accessibility Learnings

## 2026-03-30 - Floating Emoji Actions and Form Label Associations
**Learning:** Icon-only and emoji-only floating action buttons lack context for screen readers and screen magnifiers without explicit `aria-label` attributes and visible keyboard `focus-visible` rings. Additionally, form inputs missing explicit `for`/`id` label bindings reduce the click target area for touch and pointer users.
**Action:** Always bind form labels to `id` using `for`, add distinct `aria-label`s to emoji/icon-only links, and explicitly specify `focus-visible` ring classes on custom-styled dark theme links and buttons.
