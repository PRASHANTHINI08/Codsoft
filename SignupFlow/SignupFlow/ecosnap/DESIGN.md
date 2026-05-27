---
name: EcoSnap
colors:
  surface: '#f9f9f8'
  surface-dim: '#dadad9'
  surface-bright: '#f9f9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f3'
  surface-container: '#eeeeed'
  surface-container-high: '#e8e8e7'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#42493e'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1f0'
  outline: '#72796e'
  outline-variant: '#c2c9bb'
  surface-tint: '#3b6934'
  primary: '#154212'
  on-primary: '#ffffff'
  primary-container: '#2d5a27'
  on-primary-container: '#9dd090'
  inverse-primary: '#a1d494'
  secondary: '#7d562d'
  on-secondary: '#ffffff'
  secondary-container: '#ffca98'
  on-secondary-container: '#7a532a'
  tertiary: '#273d3a'
  on-tertiary: '#ffffff'
  tertiary-container: '#3e5451'
  on-tertiary-container: '#afc7c3'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#bcf0ae'
  primary-fixed-dim: '#a1d494'
  on-primary-fixed: '#002201'
  on-primary-fixed-variant: '#23501e'
  secondary-fixed: '#ffdcbd'
  secondary-fixed-dim: '#f0bd8b'
  on-secondary-fixed: '#2c1600'
  on-secondary-fixed-variant: '#623f18'
  tertiary-fixed: '#cfe8e3'
  tertiary-fixed-dim: '#b3cbc7'
  on-tertiary-fixed: '#091f1c'
  on-tertiary-fixed-variant: '#354b48'
  background: '#f9f9f8'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.25'
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Lexend
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Lexend
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-md:
    fontFamily: Lexend
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Lexend
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 40px
  xl: 64px
  margin-mobile: 20px
  gutter: 16px
---

## Brand & Style
The brand personality is grounded, optimistic, and transparent. It aims to evoke a sense of environmental responsibility without being clinical or alarmist. The UI focuses on "Conscious Clarity," ensuring that users feel empowered and calm while making sustainable choices.

This design system utilizes a **Minimalist** foundation infused with **Soft Organic** elements. It prioritizes heavy whitespace to reduce cognitive load during the scanning process, while using subtle natural textures and soft edges to move away from cold, corporate aesthetics. The interface should feel like a digital extension of the natural world—breathable, functional, and inherently honest.

## Colors
The palette is rooted in a "Forest and Soil" concept. The primary color is a deep, trustworthy leafy green used for key actions and brand presence. The secondary tone is a warm, earthy clay used for accents and to balance the coolness of the greens. 

The background is not a pure white but a soft, warm Alabaster to reduce eye strain and feel more natural. Neutrals are tinted with warm olives rather than cool blues to maintain the organic atmosphere. High-contrast success states use a vibrant sap-green, while errors are a muted terracotta-red to remain visible but stay within the earthy aesthetic.

## Typography
Typography is the primary driver of the "friendly and accessible" requirement. **Plus Jakarta Sans** is used for headlines; its soft, rounded terminals provide a welcoming and modern character. 

For body text and functional labels, **Lexend** is utilized. Chosen specifically for its research-backed legibility and accessibility, it ensures that product information and sustainability metrics are easily digestible for all users. Line heights are purposefully generous to maintain the "breathable" feel of the layout.

## Layout & Spacing
The design system employs a **Fluid Grid** model designed for mobile-first scanning interactions. It uses an 8px base unit to ensure rhythmic consistency. 

Layouts should favor vertical stack patterns to simplify the scanning experience. Margins are kept wide (24px on larger handsets) to frame content and prevent the UI from feeling cramped. Elements like product cards and scan results should utilize "Negative Space as a Feature," giving the user's eyes a clear path to the most critical environmental data.

## Elevation & Depth
Depth is communicated through **Tonal Layers** and **Ambient Shadows**. Instead of harsh drop shadows, this design system uses soft, diffused shadows with a slight primary-color tint (e.g., a dark green-grey shadow) to make elements feel like they are resting naturally on a surface.

Backgrounds use very subtle shifts in value—moving from the Alabaster base to a slightly deeper "Sand" tone—to denote hierarchy. Product cards should appear slightly lifted to invite interaction, while secondary information remains flush with the background.

## Shapes
The shape language is **Rounded**, reflecting the organic curves found in nature. There are no sharp 90-degree corners in the design system. Standard components use a 0.5rem (8px) radius, while larger containers like product cards and modals use a 1rem (16px) radius. This softness reinforces the "friendly" brand attribute and makes the app feel approachable and safe.

## Components
- **Scan Button:** The primary action is a large, circular floating action button or a pill-shaped centered button. It should use the Primary Green with a high-contrast icon.
- **Sustainability Chips:** Small, rounded indicators for "Recyclable," "Vegan," or "Carbon Neutral." These use low-opacity versions of the green and clay colors with bold text.
- **Product Cards:** Use a soft 16px corner radius, a subtle 1px border in a muted earth tone, and a very light ambient shadow. Information is grouped by "Immediate Impact" (top) and "Technical Details" (bottom).
- **Input Fields:** Search and data entry fields use a solid, light-neutral background with no heavy borders, relying on subtle inner shadows or 1px strokes to define the area.
- **Lists:** Clean, edge-to-edge lists with generous 16px padding between items and thin, low-contrast separators to maintain a light visual weight.
- **Progress Bars:** Used for sustainability scores; these should be thick with rounded caps, using a gradient transition from secondary clay to primary green to visualize improvement.