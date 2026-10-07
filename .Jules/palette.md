## 2026-10-07 - Floating Action Widgets & Form Field Label Associations
**Learning:** Icon/emoji-only floating action widgets and custom form layouts often lack accessibility names (`aria-label`) and explicit `<label for="...">` associations, rendering them difficult to use for screen reader users and keyboard navigators.
**Action:** Always ensure floating emoji buttons have descriptive `aria-label` attributes and `:focus-visible` ring/outline styles, and explicitly connect `<label>` elements to input `id`s.
