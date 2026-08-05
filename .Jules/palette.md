# Palette UX Journal - Vientiane Private Car Service

## 2026-02-15 - Interactive Accessibility and Keyboard Navigation on Static Tailwind App
**Learning:** In a static HTML page without UI libraries, floating action widgets and contact buttons using emojis/icons or generic wrappers lack focus-visible outlines, proper roles, and accessible labels. High contrast focus rings and ARIA support should be added to interactive elements to ensure full WCAG conformity, specifically for icon-only components.
**Action:** Enhance floating widget buttons and form inputs with high-contrast Tailwind focus indicators (e.g., `focus-visible:ring-2 focus-visible:ring-purple-400 focus-visible:outline-none`) and add ARIA attributes such as `aria-label` to floating widgets.
