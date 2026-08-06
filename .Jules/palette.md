# Palette's UX Journal

## 2026-02-23 - Micro-UX and Accessibility Enhancements
**Learning:** Adding explicit programmatic label association (`for` attribute) and visible focus indicators (`focus-visible`) drastically improves the accessibility and usability of forms for assistive technologies and keyboard-only navigation, especially on custom dark themes. Interactive emoji-only elements must always have explicit `aria-label` tags to avoid screen reader silence or confusing readouts.
**Action:** Always link labels to inputs with `for`, include accessible names on icons/emojis, and styled focused states with `focus-visible` ring enhancements.
