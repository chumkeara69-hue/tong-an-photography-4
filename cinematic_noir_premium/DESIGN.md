---
name: Cinematic Noir Premium
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#3a3939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#d0c5af'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#99907c'
  outline-variant: '#4d4635'
  surface-tint: '#e9c349'
  primary: '#f2ca50'
  on-primary: '#3c2f00'
  primary-container: '#d4af37'
  on-primary-container: '#554300'
  inverse-primary: '#735c00'
  secondary: '#c8c6c5'
  on-secondary: '#313030'
  secondary-container: '#474746'
  on-secondary-container: '#b7b5b4'
  tertiary: '#cfcece'
  on-tertiary: '#2f3131'
  tertiary-container: '#b3b3b3'
  on-tertiary-container: '#444545'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffe088'
  primary-fixed-dim: '#e9c349'
  on-primary-fixed: '#241a00'
  on-primary-fixed-variant: '#574500'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#e3e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1a1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.05em
  caption:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.4'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1440px
---

## Brand & Style

The design system is engineered to evoke the atmosphere of a high-end art gallery, specifically tailored for the "Tong An Photography" marketplace. The brand personality is prestigious, authoritative, and deeply cinematic, focusing on the interplay of light and shadow—a core tenet of Cambodian cinematic photography. 

The design style utilizes **Minimalism** with **Glassmorphism** accents. By employing heavy whitespace (or "blackspace"), the UI retreats to the background, allowing high-resolution photography to serve as the primary visual driver. The emotional response is one of exclusivity and awe, positioning photography not just as media, but as fine art.

Key stylistic principles:
- **Atmospheric Depth:** Use of deep blacks and charcoals to create a sense of infinite space.
- **Precision:** Razor-sharp alignment and purposeful use of gold accents to denote value and "The Golden Hour."
- **Authenticity:** Layouts that respect the aspect ratios of professional cinematography (21:9 and 16:9).

## Colors

The palette is anchored in a "Midnight" spectrum to ensure maximum dynamic range for displayed imagery. 

- **Primary (Gold):** Reserved for high-value interactions: Call-to-Action buttons, premium badges, and active navigation states.
- **Backgrounds:** A base of `#0D0D0D` provides a pure canvas that eliminates screen glare, while `#121212` is used for subtle sectional shifts.
- **Surfaces:** `#1A1A1A` is utilized for card containers and elevated UI elements to provide a soft separation from the background.
- **Typography:** Pure white (`#FFFFFF`) is used for headlines to ensure "punch," while light gray (`#A0A0A0`) is used for secondary metadata to reduce visual noise.

## Typography

This design system employs a high-contrast typographic pairing to reflect the "sophisticated yet professional" visual direction.

- **Headlines (Playfair Display):** A timeless serif that brings an editorial, "Vogue-like" quality to the interface. Large sizes should use tighter letter spacing to maintain a cinematic feel.
- **Body & Interface (Manrope):** A modern, geometric sans-serif that ensures absolute legibility for technical details (shutter speed, aperture, pricing). 
- **Labels:** Always use Manrope with increased letter-spacing and uppercase styling for a refined, utilitarian look in navigation and metadata tags.

## Layout & Spacing

The layout philosophy is based on a **Fluid Grid** that prioritizes the "Frame." 

- **Desktop:** A 12-column grid with wide 64px margins to create a letterboxed, cinematic effect. Gutters are kept at 24px to allow images to breathe without feeling disconnected.
- **Mobile:** A 4-column grid with 16px margins.
- **Vertical Rhythm:** A strict 8px baseline grid is used. Spacing between major sections should be generous (80px, 120px, or 160px) to maintain the premium minimalist aesthetic.
- **Image Containers:** Should default to 16:9 or 3:2 aspect ratios, with full-bleed options for high-impact hero sections.

## Elevation & Depth

To maintain the "Noir" aesthetic, elevation is communicated through **Tonal Layers** and **Low-Contrast Outlines** rather than traditional heavy shadows.

- **Level 0 (Background):** `#0D0D0D` — The foundation.
- **Level 1 (Cards/Surface):** `#1A1A1A` — Slightly elevated with a 1px border of `#2A2A2A` for crisp definition.
- **Level 2 (Modals/Popovers):** `#222222` — Uses a very soft, diffused shadow (`0px 20px 40px rgba(0,0,0,0.8)`) and a glassmorphic backdrop blur (12px) when appearing over imagery.
- **Interactions:** Hovering over an image card should produce a subtle "inner glow" or a 1px gold border to signify selection.

## Shapes

The design system uses **Soft (0.25rem)** roundedness to maintain a precise, professional architectural feel. 

- **Standard Elements:** Buttons and input fields use a `4px` radius. This keeps the look sharp and sophisticated.
- **Large Containers:** Image cards use `rounded-lg` (8px) to subtly soften the "hard" edges of digital photography.
- **Buttons:** CTAs are rectangular with minimal rounding to preserve the serious, high-end gallery tone.
- **Icons:** Use thin-stroke (1.5px) linear icons with sharp corners to match the typography.

## Components

### Buttons
- **Primary:** Background `#D4AF37` (Gold), Text `#0D0D0D`, Bold Manrope. No shadow.
- **Secondary:** Transparent background, 1px Border `#D4AF37`, Text `#D4AF37`.
- **Ghost:** Transparent background, Text `#FFFFFF`.

### Cards
- **Photography Card:** Full-bleed image with a 1px `#2A2A2A` border. Content (title, price) is placed below the image or on a subtle gradient overlay at the bottom.
- **Hover State:** Image scales slightly (1.05x) within the container to create a "magnifying" cinematic effect.

### Input Fields
- **Style:** Dark background (`#1A1A1A`), 1px border (`#2A2A2A`). Focus state changes border to Gold (`#D4AF37`).
- **Typography:** Labels appear above the field in uppercase Manrope at 12px.

### Chips & Tags
- **Category Tags:** Small, border-only (`1px #A0A0A0`), text `#A0A0A0`, `2px` border radius. Used for metadata like "Landscape," "Phnom Penh," or "Leica M11."

### Navigation
- **Top Bar:** Fixed, background `#0D0D0D` with 80% opacity and backdrop-blur. Gold logo placement for brand recognition.