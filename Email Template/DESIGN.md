---
name: Premium Travel Identity
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf1'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fa'
  on-surface: '#111c2c'
  on-surface-variant: '#44474c'
  inverse-surface: '#263142'
  inverse-on-surface: '#ebf1ff'
  outline: '#74777d'
  outline-variant: '#c4c6cd'
  surface-tint: '#4f6073'
  primary: '#041627'
  on-primary: '#ffffff'
  primary-container: '#1a2b3c'
  on-primary-container: '#8192a7'
  inverse-primary: '#b7c8de'
  secondary: '#0c6780'
  on-secondary: '#ffffff'
  secondary-container: '#9ae1ff'
  on-secondary-container: '#09657f'
  tertiary: '#121618'
  on-tertiary: '#ffffff'
  tertiary-container: '#262a2c'
  on-tertiary-container: '#8d9194'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d2e4fb'
  primary-fixed-dim: '#b7c8de'
  on-primary-fixed: '#0b1d2d'
  on-primary-fixed-variant: '#38485a'
  secondary-fixed: '#baeaff'
  secondary-fixed-dim: '#89d0ed'
  on-secondary-fixed: '#001f29'
  on-secondary-fixed-variant: '#004d62'
  tertiary-fixed: '#e0e3e6'
  tertiary-fixed-dim: '#c3c7ca'
  on-tertiary-fixed: '#181c1e'
  on-tertiary-fixed-variant: '#43474a'
  background: '#f9f9ff'
  on-background: '#111c2c'
  surface-variant: '#d8e3fa'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 2.5rem
  section-gap: 5rem
  component-gap: 1rem
---

## Brand & Style

This design system targets high-end travelers seeking reliability, clarity, and a sense of calm during their journey. The brand personality is **Professional, Exploratory, and Serene**. It utilizes a **Modern Corporate** aesthetic with a distinct focus on editorial spacing and high-quality visual hierarchy.

The visual direction prioritizes a "breathable" interface where whitespace acts as a luxury element. By combining deep architectural blues with airy sky tones, the system evokes the transition from a premium lounge to the open sky. The overall feel should be sophisticated but approachable, avoiding unnecessary clutter to ensure the user feels in total control of their travel logistics.

## Colors

The palette is anchored by **Deep Midnight Blue (#1a2b3c)**, used for primary actions, headlines, and navigation to establish authority and depth. **Clear Sky Blue (#87CEEB)** serves as the accent color, highlighting active states, secondary buttons, and success indicators, providing a refreshing contrast that prevents the UI from feeling too heavy.

A supporting **Tertiary Ice Blue (#F4F7FA)** is used for large section backgrounds and card containers to maintain a soft, premium look without the harshness of pure white on every surface. Neutral grays are tinted with blue to maintain temperature consistency throughout the interface. High-contrast white is reserved for primary text on dark backgrounds and core content surfaces.

## Typography

The typography uses **Plus Jakarta Sans** across all levels to maintain a cohesive, modern, and friendly tone. The font's geometric yet soft curves mirror the rounded UI components. 

Headlines utilize tighter letter spacing and heavier weights to command attention, while body copy is set with generous line heights (1.6) to ensure maximum readability during travel planning. For labels and metadata, a slight increase in letter spacing and uppercase styling is used to provide a clear distinction from narrative content.

## Layout & Spacing

This design system employs a **12-column fixed grid** for desktop, centering the content within a 1280px max-width container. For mobile, a fluid single-column layout is used with 16px side margins. 

The spacing rhythm is built on an **8px base unit**. Generous "Section Gaps" (80px+) are encouraged between major content blocks to create a high-end, editorial feel. Content density should remain low; never crowd information. Use padding to create internal "breathing room" within cards and containers, typically using 24px or 32px of internal padding.

## Elevation & Depth

Hierarchy is established through **Ambient Shadows** and tonal layering. Surfaces are elevated using extremely soft, diffused shadows with a slight blue tint (`rgba(26, 43, 60, 0.05)`) rather than pure black. This keeps the shadows feeling integrated with the sky-blue palette.

- **Level 0 (Background):** Pure White or Ice Blue (#F4F7FA).
- **Level 1 (Cards/Inputs):** White surface with a 4px blur shadow.
- **Level 2 (Hover/Floating):** White surface with a 12px blur shadow, creating a distinct "lift."
- **Level 3 (Modals/Overlays):** White surface with a 24px blur shadow and a subtle 1px border in a very light neutral blue.

## Shapes

The design system uses a **Rounded** shape language to reinforce the friendly and modern nature of the brand. The standard corner radius is **8px** for smaller components like inputs and buttons, scaling up to **12px-16px** for larger containers and cards. 

This consistent rounding helps soften the professional Midnight Blue, making the application feel like a helpful travel companion rather than a rigid corporate tool. Interactive elements should never have sharp corners.

## Components

### Buttons
- **Primary:** Deep Midnight Blue background with white text. 8px border radius. No border.
- **Secondary:** Transparent background with Clear Sky Blue 1.5px border and text. 
- **Tertiary:** Clear Sky Blue background with Midnight Blue text (for high-visibility "Book Now" actions).

### Cards
Cards are the primary content vehicle. They feature a 12px corner radius, a subtle Level 1 shadow, and at least 24px of internal padding. Images within cards should always carry the same 12px corner radius on their outer edges.

### Inputs
Text fields use an 8px radius with a light blue-gray border (#E2E8F0). On focus, the border transitions to Clear Sky Blue with a soft outer glow.

### Chips & Tags
Used for destination categories or flight status. These should be pill-shaped (fully rounded) with low-saturation background colors and high-saturation text for readability.

### Special Components
- **Search Bar:** A prominent, oversized input with a Level 2 shadow to serve as the primary entry point for travel discovery.
- **Progress Steppers:** Thin, Sky Blue lines with Midnight Blue nodes to guide users through multi-step booking processes.