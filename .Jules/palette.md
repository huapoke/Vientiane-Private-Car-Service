# Palette's Journal - Vientiane Private Car Service

## 2026-11-02 - Dark-Theme Focus Contrast & Screen Reader Accessibility on Icon Links
**Learning:**
1. In deeply stylized dark-neon themes (dark background #07031C), default browser outline rings blend completely into dark backgrounds or are obscured by overflow settings. Adding explicit `focus-visible:ring-2 focus-visible:ring-purple-400` states ensures high-contrast keyboard navigability without altering visual aesthetics for mouse users.
2. Floating emoji-only action widgets (e.g. 💬, 📱, ✉️) are announced ambiguously or skipped by screen readers. Explicit `aria-label` tags coupled with explicit `for` attributes on form labels transform an inaccessible page into a standard-compliant, accessible experience.

**Action:**
1. Always pair emoji-only or icon-only interactive controls with descriptive `aria-label` tags and `focus-visible` ring indicators.
2. Ensure all form `<label>` tags explicitly associate with input `id`s using the `for` attribute.
