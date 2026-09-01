## 2026-09-01 - Floating Emoji Contact Buttons Accessibility & Keyboard Navigation
**Learning:** Icon-only or emoji-only floating action buttons lack accessible names for screen readers and need explicit focus indicators for keyboard navigation in custom dark/neon themes.
**Action:** Always add descriptive `aria-label` attributes, `rel="noopener noreferrer"` for target="_blank" links, and `focus-visible:ring-2` Tailwind focus rings when working with floating quick-contact buttons.
