# Palette UX & Accessibility Journal

## 2026-08-13 - Accessible Keyboard Focus States in Ambient Dark Designs
**Learning:** In highly customized dark, neon, and ambient gradient designs, default browser focus rings are virtually invisible or break the visual language. Explicit high-contrast focus rings tailored to the UI's aesthetic are critical for keeping the experience accessible to keyboard-only navigators without compromising on style.
**Action:** Always implement custom `focus-visible` outline rings using consistent theme accents (e.g., `focus-visible:ring-2 focus-visible:ring-purple-400 focus-visible:outline-none`) on all custom interactive links, action buttons, and floating utility widgets.

## 2026-08-13 - Screen Reader Context in Emoji-Only Interactive Elements
**Learning:** Decorative and floating widgets that contain only raw emojis (like 💬, 📱, ✉️) are entirely unhelpful or disorienting to screen readers, which announce them literalistically or skip them.
**Action:** Every icon-only or emoji-only interactive control must have an descriptive `aria-label` attribute (e.g., `aria-label="Contact via WhatsApp"`) to supply semantic context.
