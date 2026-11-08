# Palette's Journal - Critical Learnings Only

## 2026-03-06 - Form Label Associations and Floating Emoji Contact Links in Static Landing Pages
**Learning:** In single-page static landing applications using modern utility CSS, form `<label>` elements are frequently written without `for` attributes matching `<input id="...">`, which breaks click-to-focus behavior and fails accessibility checks for assistive tech. Floating action buttons using emoji characters (💬, 📱, ✉️) are announced as meaningless unicode or skipped entirely unless explicit `aria-label`s are applied, and lack visible keyboard focus rings.
**Action:** When working on standalone marketing and booking landing pages, always ensure every `<label>` has an explicit `for` attribute and `cursor-pointer`, and add descriptive `aria-label`s along with Tailwind `focus-visible:ring-2` styles to all icon-only and emoji-only interactive anchors.
