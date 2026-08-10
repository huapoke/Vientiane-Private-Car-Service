# Palette's Journal - Vientiane Private Car Service

## 2024-11-20 - Dark-Theme Focus Contrast & Asynchronous Messaging Redirection
**Learning:**
1. In highly stylized, dark-themed applications (such as deep royal-purple/indigo backgrounds), default browser keyboard focus outlines (`focus-visible`) are often completely invisible or jarring. Ensuring accessibility requires designing a theme-consistent, high-contrast glow (using `#AA5DC6` to match the brand color) that maintains visual balance while meeting WCAG AAA non-text contrast requirements.
2. Direct asynchronous external triggers (like a "Book Now" redirecting to WhatsApp/Line) lack a native pending state, causing users to double-click in confusion. A transient loading state (disabling the button, inserting an SVG spinner, and changing the label to "Redirecting to WhatsApp...") for 800ms provides immediate feedback and prevents duplicate actions while maintaining a smooth experience.

**Action:**
1. Always inject a custom `:focus-visible` outline stylesheet rule with a high-contrast theme-coherent outline/glow when customizing interactive HTML components.
2. For all chat-based "immediate booking" triggers, wrap the redirection helper inside a transient loading state of ~800-1000ms, showing a loading indicator and disabling input before opening the external link.
