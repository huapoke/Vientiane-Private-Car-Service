## 2026-07-25 - Associated Form Labels & Accessible Floating Emoji Buttons
**Learning:** Icon-only floating widgets with raw emojis lack screen reader context, and unlinked form labels reduce tap targets for mobile and accessibility users.
**Action:** Always link form labels to control IDs using `for` attributes and ensure floating emoji links have explicit `aria-label`s, `rel="noopener noreferrer"`, and visible focus rings.
