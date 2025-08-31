# Glassmorphism & 3D Effect Integration

This portfolio template has been enhanced with glassmorphism and 3D effects for all main sections. Each section is wrapped in a `.glass-card-3d` container, providing a modern frosted glass look and interactive 3D hover effect.

## Features
- **Glassmorphism:**
  - Background blur
  - Semi-transparent white background
  - Soft border and rounded corners
- **3D Effect:**
  - Subtle scale and rotation on hover
  - Enhanced box-shadow for depth

## How It Works
- The following sections are wrapped with the effect:
  - Header (Home)
  - About
  - Skills & Experience
  - Services
  - Projects
  - Contact
- The effect is defined in `css/style.css` under the `.glass-card-3d` class.

## Example CSS
```css
.glass-card-3d {
    background: rgba(255, 255, 255, 0.18);
    border-radius: 24px;
    box-shadow: 0 8px 32px 0 rgba(31, 38, 135, 0.37), 0 1.5rem 2rem rgba(98, 68, 197, 0.15);
    backdrop-filter: blur(12px);
    -webkit-backdrop-filter: blur(12px);
    border: 1px solid rgba(255, 255, 255, 0.3);
    transition: transform 0.3s cubic-bezier(.25,.8,.25,1), box-shadow 0.3s;
    transform-style: preserve-3d;
    perspective: 1000px;
}
.glass-card-3d:hover {
    transform: scale(1.03) rotateY(6deg) rotateX(2deg);
    box-shadow: 0 16px 48px 0 rgba(31, 38, 135, 0.37), 0 2.5rem 3rem rgba(98, 68, 197, 0.25);
}
```

## Customization
- You can adjust the blur, border-radius, and shadow for different visual styles.
- To apply the effect to other elements, simply add the `glass-card-3d` class.

---
**Author:** Automated by GitHub Copilot
**Date:** August 30, 2025
