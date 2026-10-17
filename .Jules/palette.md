# Palette's Journal - UX & Accessibility Learnings

## 2026-10-17 - Form Labels and Floating Emoji Navigation
**Learning:** Floating action widgets with emoji icons and custom-styled glassmorphism form inputs often lack explicit `for` bindings on `<label>` elements and ARIA labels on icon-only links. Connecting labels directly and providing `aria-label` attributes ensures screen readers announce input contexts and button actions accurately.
**Action:** Always check form input-label pairs for `for`/`id` associations and ensure icon/emoji-only links include `aria-label` and `focus-visible` ring indicators.
