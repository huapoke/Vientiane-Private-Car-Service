## 2026-09-17 - Floating Icon Links & Form Field Label Associations
**Learning:** Icon-only floating navigation links and unlinked form labels significantly impair screen reader navigation and keyboard focus feedback in single-page static HTML layouts.
**Action:** Always associate `<label>` tags to `<input>`/`<select>` elements using `for="..."` and add explicit `aria-label`, `rel="noopener noreferrer"`, and visible focus rings (`focus:ring-2`) to emoji or icon-only interactive links.
