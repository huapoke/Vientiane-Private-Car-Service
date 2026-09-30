## 2026-09-30 - Floating Emoji Actions & Form Label Association
**Learning:** Floating corner action widgets using emoji icons are ignored or misread by screen readers if they lack explicit `aria-label` attributes, and lack visible keyboard focus without explicit Tailwind focus-visible utilities.
**Action:** Always add `aria-label`, `rel="noopener noreferrer"`, and `focus-visible:ring-2` to emoji-only or icon-only interactive elements, and pair `<label>` elements with `for` attributes matching control IDs.
