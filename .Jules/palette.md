## 2026-10-20 - Explicit Form Labels & Icon-Only Floating Action Button Accessibility

**Learning:** Icon-only floating widgets and form inputs without explicit `for` attributes severely diminish screen reader accessibility and keyboard navigation UX. Adding explicit `for`/`id` bindings and `aria-label`s with `focus-visible` focus rings creates an intuitive experience for assistive technologies and keyboard users without altering layout visual design.
**Action:** Always verify all `<label>`s have explicit `for` bindings matching `<input>` IDs and ensure icon-only/emoji-only links include `aria-label`, `title`, `rel="noopener noreferrer"`, and visible keyboard focus ring styles.
