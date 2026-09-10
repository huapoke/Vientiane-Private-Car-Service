## 2026-09-10 - Form Label Associations and Floating Emoji Link Accessibility
**Learning:** Icon-only floating buttons and custom HTML form labels without `for` attributes severely hinder screen reader navigation and keyboard visibility.
**Action:** Always associate `<label>` elements with input IDs and add explicit `aria-label`, `rel="noopener noreferrer"`, and `focus-visible:ring-2` styling on floating emoji/icon controls.
