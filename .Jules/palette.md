# Palette's Journal - Critical Learnings

## 2026-03-04 - Accessible floating icon buttons and form labels
**Learning:** Floating action buttons with only emojis provide zero accessible name to screen readers and lack visual cues for mouse hover tooltips on desktop. Pairing `aria-label`, `title`, and `focus-visible` ensures seamless interaction across mouse, keyboard, and screen reader modalities without altering visual aesthetics. In addition, associating `<label for="...">` with `<input id="...">` is critical for form clarity and touch target usability.
**Action:** Always provide explicit accessible names (`aria-label`) and tooltips (`title`) on icon-only and emoji-only links/buttons, hide decorative emojis with `aria-hidden="true"`, and verify label-input linkage.
