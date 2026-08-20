---
name: Organic Neo-Brutalism
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#52443b'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
  outline: '#85746a'
  outline-variant: '#d8c2b7'
  surface-tint: '#8a5027'
  primary: '#8a5027'
  on-primary: '#ffffff'
  primary-container: '#e69c6d'
  on-primary-container: '#66330c'
  inverse-primary: '#ffb689'
  secondary: '#576339'
  on-secondary: '#ffffff'
  secondary-container: '#d8e6b1'
  on-secondary-container: '#5b673d'
  tertiary: '#685b59'
  on-tertiary: '#ffffff'
  tertiary-container: '#b9a9a6'
  on-tertiary-container: '#4a3e3b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdbc8'
  primary-fixed-dim: '#ffb689'
  on-primary-fixed: '#321300'
  on-primary-fixed-variant: '#6e3912'
  secondary-fixed: '#dbe8b4'
  secondary-fixed-dim: '#bfcc99'
  on-secondary-fixed: '#151f00'
  on-secondary-fixed-variant: '#404b24'
  tertiary-fixed: '#f1dfdb'
  tertiary-fixed-dim: '#d4c3bf'
  on-tertiary-fixed: '#231917'
  on-tertiary-fixed-variant: '#504441'
  background: '#fcf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '600'
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
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-padding: 40px
  gutter: 24px
  section-gap: 80px
  card-padding: 24px
---

## Brand & Style

This design system is built for a personal portfolio that balances professional credibility with a creative, approachable edge. It draws heavily from **Soft Neo-Brutalism**, characterized by high-contrast outlines and structural shadows, but softened through an organic, muted color palette and rounded geometry.

The aesthetic response should feel tactile and "drawn," moving away from corporate sterility toward a hand-crafted, human-centric experience. The design favors clarity through strong visual anchors—specifically thick 2px borders—and utilizes playful, hand-drawn geometric accents (stars, triangles, squiggles) to punctuate the layout and break the rigidity of the grid.

## Colors

The palette is grounded in an earthy, sophisticated warmth. 

- **Background:** A soft off-white/beige (`#F2F0E9`) acts as the canvas, providing a more comfortable reading experience than pure white.
- **Primary (Coral/Orange):** Used for primary calls to action and energetic highlights.
- **Secondary (Muted Green):** Used for success states, secondary accents, and organic balance.
- **Tertiary (Dusty Rose):** Used for background layering and subtle decorative containers.
- **Neutral (Charcoal):** All borders, text, and shadows use this deep charcoal (`#242424`) rather than true black to maintain the "organic" feel.

## Typography

The design system utilizes **Plus Jakarta Sans** across all levels to maintain a friendly, modern, and cohesive look. The font's inherent roundness complements the UI's rounded corners.

- **Headlines:** Use tight line heights and slight negative letter spacing for a punchy, editorial feel. 
- **Body Text:** Ample line height (1.6) is required to ensure readability against the textured backgrounds.
- **Navigation/Labels:** Use bold, uppercase styling for navigation links to contrast against the playful nature of the illustrative elements.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (max-width: 1280px) and transitions to a fluid model on smaller screens. 

- **Grid:** A 12-column grid with generous 24px gutters.
- **Margins:** Desktop uses 40px outer margins; mobile scales down to 20px.
- **Depth Layering:** Spacing is often used to create "stacking" effects. Elements are frequently offset from their background containers by 8px–12px to reveal the layers beneath.
- **Visual Breathing Room:** Large section gaps (80px+) are encouraged to prevent the "Neo-brutalist" borders from feeling cluttered.

## Elevation & Depth

This system avoids realistic lighting. Instead, depth is achieved through **Hard Offset Shadows**:

- **Shadow Style:** Shadows are solid blocks of the Neutral color (`#242424`) with 0 blur. 
- **Offset:** Standard elevation is a 4px horizontal and 4px vertical offset (Bottom-Right). 
- **Interaction:** On hover, buttons and interactive cards should "press down"—the shadow offset should decrease to 0px or 2px, and the element should translate visually to simulate a physical click.
- **Tonal Layering:** Use the Tertiary or Secondary colors as background "mats" behind primary content cards to create a three-dimensional stack.

## Shapes

The shape language is defined by the tension between rigid 2px borders and very soft, rounded corners.

- **Core Radius:** All standard cards and containers use `rounded-2xl` (1.5rem / 24px).
- **Buttons/Pills:** Interactive triggers and tags use a full pill shape (9999px radius).
- **Icons/Accents:** Hand-drawn geometric primitives (stars, triangles) should be used as floating decorative elements. They do not follow the strict rounding rules of the UI containers, maintaining their "sketchy" character.

## Components

### Buttons
- **Primary:** Pill-shaped, Primary color fill, 2px Charcoal border, 4px Hard Shadow.
- **Secondary:** Pill-shaped, Transparent fill, 2px Charcoal border, no shadow unless hovered.
- **Text:** Uppercase label-bold font style.

### Cards
- **Standard Card:** Background color or Soft Beige fill, 2px Charcoal border, `rounded-2xl`. 
- **Interactive Card:** Adds the 4px Hard Shadow. Often contains a "header" area with a subtle divider line.

### Input Fields
- **Style:** 2px Charcoal border, `rounded-lg`.
- **Focus State:** Background shifts to a very light tint of the Primary color, shadow offset increases.

### Chips & Tags
- Small pill-shaped containers with a 1px or 2px border. Used for skills, categories, or status indicators.

### Progress Indicators
- Linear bars with a 2px border and a solid color fill (Secondary or Primary) for the progress amount. The container background should be white or the system's background color.