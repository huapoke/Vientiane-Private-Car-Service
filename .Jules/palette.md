## 2026-09-23 - Accessibility & Keyboard Focus Enhancements
**Learning:** Single-page landing applications with floating emoji buttons often lack ARIA labels and keyboard focus indicators (`focus-visible`). Adding `for` attributes on labels and explicit `aria-label`s on icon/emoji links ensures full screen reader compatibility and seamless keyboard navigation.
**Action:** Always verify floating widgets and form control labeling with `for` and `aria-label` attributes and ensure `focus-visible:ring` styles are present on interactive elements.
