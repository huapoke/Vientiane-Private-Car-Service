# Palette Journal - Critical UX/a11y learnings

## 2026-08-04 - Accessible Form Labels and Floating Emoji Widgets in Static Tailwind Apps
**Learning:** In simple single-file static HTML templates, developers often skip semantic accessibility features such as connecting `<label>` tags to their inputs via the `for` attribute, adding `aria-label` to emoji-only or icon-only floating buttons, and styling focus-visible states for keyboard users.
**Action:** Associate all form label elements with inputs using explicit `for` and `id` attributes, add descriptive `aria-label` tags to emoji/icon-only floating widgets, and include standard focus-visible styles across interactive controls.
