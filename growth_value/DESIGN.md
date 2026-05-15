---
name: Growth & Value
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#404943'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#707973'
  outline-variant: '#bfc9c1'
  surface-tint: '#2c694e'
  primary: '#0f5238'
  on-primary: '#ffffff'
  primary-container: '#2d6a4f'
  on-primary-container: '#a8e7c5'
  inverse-primary: '#95d4b3'
  secondary: '#825500'
  on-secondary: '#ffffff'
  secondary-container: '#fdab12'
  on-secondary-container: '#684300'
  tertiary: '#005236'
  on-tertiary: '#ffffff'
  tertiary-container: '#116c4a'
  on-tertiary-container: '#98eabf'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#b1f0ce'
  primary-fixed-dim: '#95d4b3'
  on-primary-fixed: '#002114'
  on-primary-fixed-variant: '#0e5138'
  secondary-fixed: '#ffddb3'
  secondary-fixed-dim: '#ffb951'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#633f00'
  tertiary-fixed: '#a1f4c8'
  tertiary-fixed-dim: '#86d7ad'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
  soft-green: '#D8F3DC'
  off-white: '#F9F9F7'
  dark-charcoal: '#1A1A2E'
  light-gray: '#EFEFEF'
  warm-gold: '#FFD166'
typography:
  display-hero:
    fontFamily: Poppins
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  display-hero-mobile:
    fontFamily: Poppins
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h1:
    fontFamily: Poppins
    fontSize: 40px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Poppins
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h3:
    fontFamily: Poppins
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: normal
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: normal
  button:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: normal
  nav-link:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: normal
  label:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.0'
    letterSpacing: normal
  caption:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: normal
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
  sm: 8px
  md: 16px
  lg: 32px
  xl: 64px
  2xl: 96px
  section-v: 80px
  container-max: 1200px
---

## Brand & Style

The design system is rooted in the "Modern & Minimal" movement, specifically tailored for a youth-oriented financial context. It balances the stability of a traditional credit union with a fresh, approachable energy. The aesthetic is utilitarian yet welcoming, moving away from "stuffy" institutional design toward a clean, growth-focused interface.

The visual narrative is defined by:
- **Clarity and Trust:** High readability and structured layouts that prioritize accessibility.
- **Organic Professionalism:** Using a palette of deep forest tones and soft greens to create a sense of environmental harmony and financial health.
- **Vibrant Accents:** Strategic use of gold to highlight value and drive action without overwhelming the user.
- **Modern Utilitarianism:** A strict adherence to an 8px spacing rhythm and clear geometric shapes that suggest precision and reliability.

## Colors

The color palette is built on a "Forest Green and Gold" foundation, designed to evoke growth and premium value.

- **Primary (Forest Green):** Used for core branding, including headers, primary buttons, and navigation. 
- **Secondary (Gold):** Reserved strictly for high-priority Calls to Action (CTAs), badges, and crucial highlights.
- **Tertiary (Emerald):** Acts as an interaction accent for hover states and feature-specific iconography.
- **Surface Tiers:** Use `off-white` for global backgrounds and `soft-green` for specific UI surfaces like card fills and table headers to create a softer organic feel.
- **Accessibility Note:** To ensure WCAG compliance, gold text should never be placed on green backgrounds. Use `dark-charcoal` for high-contrast headings and body text on light surfaces.

## Typography

This design system uses a dual-font stack to differentiate between brand expression and functional utility.

- **Poppins** is the primary display face, used for all headings and heroic moments. It brings a modern, geometric character to the brand.
- **Inter** handles all body copy, UI elements, labels, and buttons. It is selected for its exceptional legibility and neutral, professional tone.
- **Scale & Hierarchy:** Display styles use tighter line-heights and slight negative letter-spacing to maintain impact, while body styles use a generous 1.6 line-height to ensure comfort during long reading sessions.
- **Constraints:** Limit paragraph widths to a maximum of 680px to prevent eye fatigue.

## Layout & Spacing

The layout is built on a 12-column fluid grid that transitions to a single-column stack on mobile devices.

- **Rhythm:** An 8px base unit governs all spatial relationships. 
- **Margins:** Standard page margins are set to 80px for desktop to provide significant whitespace and focus, reducing to 20px on mobile for maximum content utility.
- **Component Spacing:** Use `32px` (lg) for internal card padding and vertical separation between elements within a section. Use `64px` (xl) to separate major content sections.
- **Navigation:** The navbar is fixed at a height of 72px and is "sticky," remaining at the top of the viewport to provide constant access to key links.

## Elevation & Depth

Hierarchy is established through a combination of tonal layering and subtle ambient shadows. 

- **Surface Tiers:** Use flat color fills (`white` on `off-white` backgrounds) to create containment without unnecessary depth.
- **Shadows:** Shadows are used functionally rather than decoratively. Cards use a very soft, diffused shadow (`0 2px 12px rgba(0,0,0,0.06)`) to lift them slightly from the background. 
- **Interactivity:** On hover, depth is emphasized by increasing shadow spread and opacity. Interactive elements should feel like they are rising toward the user upon engagement.
- **Outlines:** Use low-contrast outlines (`1px light-gray`) for card borders and dividers to maintain a structured, grid-aligned look without relying on heavy shadows.

## Shapes

The shape language is "Rounded," striking a balance between the precision of a financial institution and the approachability of a modern app.

- **8px (Standard):** Applied to all interactive components including buttons and form inputs.
- **12px (Large):** Applied to cards and larger containers to create a softer, more distinct container for content.
- **Borders:** Utilize `1px` strokes for most decorative and structural borders. Secondary buttons use a more prominent `2px` stroke to define their hierarchy against primary green buttons.

## Components

### Buttons
- **Primary:** Forest Green background with White text. Transitions to Emerald on hover.
- **CTA:** Gold background with Dark Charcoal text. Transitions to Warm Gold on hover.
- **Secondary:** Transparent background with a 2px Forest Green border and Forest Green text.
- **Styling:** All buttons use 12px vertical and 28px horizontal padding with an 8px corner radius.

### Cards
- **Base:** White background, 12px border radius, and a 1px `light-gray` border.
- **Interaction:** Increase shadow and shift background slightly on hover to indicate clickability.

### Form Inputs
- **Base:** 1px `D1D5DB` border, 8px radius, and 12px/16px padding.
- **Focus:** 2px Forest Green outline. Labels use 14px Medium Inter, positioned above the field.

### Navigation
- **Top Bar:** 72px height, white background, sticky position with a `light-gray` bottom border. Links use 15px Medium Inter.

### Iconography
- **Style:** 2px stroke weight, strictly outlined. Never use filled icons.
- **Color:** Use Emerald Green for feature icons and Gold for highlight icons.

### Imagery
- **Treatment:** All photography and illustrations must apply a 10% Forest Green (`#2D6A4F`) tint overlay to maintain brand harmony.