# Palette's Journal

## 2026-03-03 - Form Accessibility and Focus Styles
**Learning:** Custom form elements in Tailwind/custom CSS projects often omit basic accessibility structures like linking labels to inputs using the `for` attribute, and focus-ring styles on custom styled buttons. This severely limits keyboard navigation and screen-reader usability.
**Action:** Link all labels to inputs via `for` and `id` attributes, provide `aria-label` attributes for icon/emoji-only links, and apply consistent focus-ring indicators (e.g. using Tailwind's `focus:` utilities) to all interactive controls.
