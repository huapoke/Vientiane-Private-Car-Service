## 2026-08-19 - Form Label Association and Floating Widget Accessibility
**Learning:** In static HTML applications using Tailwind, form labels often lack `for` attributes connecting them to inputs, and floating icon-only/emoji buttons lack explicit `aria-label` attributes.
**Action:** Always associate labels with inputs using `for` and `id`, add `aria-label`s to emoji-only action links, and include `focus-visible:ring-2` focus indicators on all interactive elements.
