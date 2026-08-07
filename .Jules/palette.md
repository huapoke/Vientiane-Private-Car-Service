# Palette's Journal - Vientiane Private Car Service

## 2026-07-25 - [Form Association & Floating Widget Accessibility]
**Learning:** In highly customized dark/neon/glassmorphic web pages, accessibility issues are frequently overlooked. Specifically:
1. Standard `<label>` tags must explicitly use the `for` attribute matching the nested or adjacent `<input>` or `<select>` `id` to allow correct screen reader announcement and click-to-focus behavior.
2. Icon-only or emoji-only floating contact/action anchors lack readable text. Adding descriptive `aria-label` attributes ensures screen readers can identify where these links navigate.
3. Custom styled pages that hide default browser outlines must provide custom `:focus-visible` styles so keyboard-only users can visibly navigate buttons, input fields, and links.
**Action:** Always verify form inputs have corresponding `id`/`for` label pairs, emoji/icon buttons have `aria-label`, and custom-themed interactive elements define clear `:focus-visible` styles that contrast well with custom dark backgrounds.
