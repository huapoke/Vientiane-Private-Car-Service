## 2026-08-29 - [Form Accessibility & Keyboard Focus]
**Learning:** Single-file static HTML pages often lack explicit form label associations (`for` attributes) and ARIA labels for icon/emoji-only links, hindering screen reader users and keyboard navigation.
**Action:** Always link `<label for="...">` with input IDs and apply explicit `aria-label` and `focus-visible:ring-2` styles to icon-only links and buttons.
