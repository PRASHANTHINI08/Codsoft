---
name: Warm Epicurean
colors:
  surface: '#fff8f3'
  surface-dim: '#e1d9d1'
  surface-bright: '#fff8f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf2ea'
  surface-container: '#f5ece5'
  surface-container-high: '#efe7df'
  surface-container-highest: '#eae1da'
  on-surface: '#1f1b17'
  on-surface-variant: '#494740'
  inverse-surface: '#34302b'
  inverse-on-surface: '#f8efe8'
  outline: '#7a776f'
  outline-variant: '#cac6bd'
  surface-tint: '#605e5d'
  primary: '#161615'
  on-primary: '#ffffff'
  primary-container: '#2b2a29'
  on-primary-container: '#94918f'
  inverse-primary: '#c9c6c4'
  secondary: '#5f5e5a'
  on-secondary: '#ffffff'
  secondary-container: '#e5e2dc'
  on-secondary-container: '#656460'
  tertiary: '#2c0b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#4d1a00'
  on-tertiary-container: '#ef681d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2e0'
  primary-fixed-dim: '#c9c6c4'
  on-primary-fixed: '#1c1b1a'
  on-primary-fixed-variant: '#484645'
  secondary-fixed: '#e5e2dc'
  secondary-fixed-dim: '#c9c6c1'
  on-secondary-fixed: '#1c1c18'
  on-secondary-fixed-variant: '#474743'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb595'
  on-tertiary-fixed: '#351000'
  on-tertiary-fixed-variant: '#7c2e00'
  background: '#fff8f3'
  on-background: '#1f1b17'
  surface-variant: '#eae1da'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Be Vietnam Pro
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Be Vietnam Pro
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  price-lg:
    fontFamily: Be Vietnam Pro
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 24px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  margin-mobile: 20px
  gutter-mobile: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 48px
---

## Brand & Style

The design system is built on a foundation of **Warm & Sophisticated Minimalism**. It targets a discerning audience that appreciates culinary craft and refined atmosphere. The UI evokes an emotional response of comfort, hunger, and premium hospitality by balancing high-end editorial aesthetics with the accessibility of a modern mobile application.

The style leverages generous whitespace and a "Quiet Luxury" approach—avoiding cluttered UI patterns in favor of breathing room and large, high-resolution food photography. It mixes elements of **Minimalism** (clean lines, purposeful negative space) with **Tonal Layering** to create a digital environment that feels as tactile and inviting as a physical linen-bound menu.

## Colors

The palette is anchored in organic, appetizing tones that reflect natural ingredients and sophisticated interiors:

*   **Primary (Deep Charcoal):** Used for primary text and high-contrast UI elements to provide an authoritative, grounding presence.
*   **Secondary (Soft Cream):** The base surface color. It is warmer than pure white, reducing eye strain and providing a premium, parchment-like feel.
*   **Tertiary (Vibrant Terracotta):** An accent color used sparingly for calls to action, price highlights, and status indicators (like "Chef's Special" or "Spicy"). It stimulates appetite and provides warmth.
*   **Neutral (Warm Grey):** Used for secondary text, borders, and disabled states to maintain a soft hierarchy without breaking the warm tone of the system.

## Typography

This design system employs a high-contrast typographic pairing to signal sophistication and utility:

*   **Headlines (Playfair Display):** A classic serif that brings an editorial, high-end restaurant feel. It should be used for dish names and category headers.
*   **Body & Labels (Be Vietnam Pro):** A contemporary sans-serif chosen for its exceptional readability on mobile screens. It handles descriptions, ingredients, and nutritional data with professional clarity.
*   **Hierarchy:** Use the `label-md` for dietary tags (e.g., VEGAN) with increased letter spacing to differentiate them from descriptions. Prices should be weighted heavily (`price-lg`) to ensure they are legible at a glance during the browsing experience.

## Layout & Spacing

The layout follows a **Fluid Grid** model optimized for a mobile-first experience. 

*   **Margins:** Use a generous 20px side margin to ensure content doesn't feel cramped against the screen edges.
*   **Vertical Rhythm:** Emphasize whitespace between menu categories (`section-gap`) to allow the user's eyes to rest.
*   **The "Plate" Rule:** Food imagery should either be full-bleed at the top of a detail view or contained in a square/4:5 aspect ratio card with consistent padding. 
*   **Touch Targets:** All interactive elements (add to cart, filters) must maintain a minimum 44px height for accessibility.

## Elevation & Depth

To maintain a sophisticated feel, the design system avoids heavy, artificial shadows. Depth is communicated through:

*   **Tonal Layers:** The base surface is Cream (`secondary`). Overlays like "Add to Order" modals should use a slightly lifted white surface with a very soft, diffused ambient shadow (10% opacity, 20px blur, tinted with terracotta).
*   **Subtle Outlines:** Use 1px borders in `neutral` at low opacity (20%) to define card boundaries without creating visual noise.
*   **Imagery as Depth:** High-quality photography with natural depth of field provides the "texture" of the UI, making the interface feel three-dimensional without needing heavy gradients.

## Shapes

The shape language is **Soft** and intentional. 

*   **Cards:** Use a 0.5rem (8px) radius for food item cards to feel modern but structured.
*   **Buttons:** Action buttons use a slightly higher 0.75rem (12px) radius to make them feel inviting to touch. 
*   **Dietary Icons:** Icons for Vegan (leaf), Spicy (chili), and Gluten-Free should be contained within circular or soft-pill containers to distinguish them from functional UI buttons.

## Components

*   **Menu Item Cards:** Feature a high-res image on the left or top, followed by the Playfair Display dish name, a short description in Be Vietnam Pro, and the price in the bottom right using the Terracotta accent.
*   **Buttons:** 
    *   *Primary:* Solid Deep Charcoal with Cream text for "Order Now."
    *   *Secondary:* Terracotta text with a thin border for "Add to Cart."
*   **Dietary Badges:** Small, minimalist icons (line-art style) with a label in `label-md` typography. Use a soft Terracotta tint for the "Spicy" icon background.
*   **Category Scroller:** A horizontal, edge-to-edge scrolling list at the top of the menu using `label-md` text. The active category is indicated by a Deep Charcoal underline.
*   **Input Fields:** Quantities and special instructions should use a Soft Cream background with a Deep Charcoal 1px border when focused.