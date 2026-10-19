# Palette's Journal - UX & Accessibility Learnings

## 2026-10-19 - Form Label Associations and Floating Action Button Accessibility in Static HTML Apps
**Learning:** In single-page static HTML web applications without framework UI abstractions (e.g. React/Vue components), forms frequently omit explicit `for` attributes on `<label>` elements, rendering them inaccessible to screen reader users clicking labels to focus input fields. Additionally, floating action buttons (FABs) using raw emojis lack `aria-label` screen reader announcements and visible `focus-visible` focus outlines for keyboard navigation.
**Action:** Always ensure explicit `for="..."` attributes pair every label with its input ID, add clear `aria-label` descriptions to icon/emoji-only links, and apply Tailwind `focus-visible:ring-2 focus-visible:ring-purple-400 focus-visible:outline-none` ring utilities to ensure clean keyboard focus visibility.
