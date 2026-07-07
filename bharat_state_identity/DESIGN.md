---
name: Bharat State Identity
colors:
  surface: '#f9f9ff'
  surface-dim: '#d8d9e3'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f3fd'
  surface-container: '#ecedf7'
  surface-container-high: '#e7e7f1'
  surface-container-highest: '#e1e2eb'
  on-surface: '#191b22'
  on-surface-variant: '#424753'
  inverse-surface: '#2e3038'
  inverse-on-surface: '#eff0fa'
  outline: '#727785'
  outline-variant: '#c2c6d5'
  surface-tint: '#005ac1'
  primary: '#0058bd'
  on-primary: '#ffffff'
  primary-container: '#2771df'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#006e2c'
  on-secondary: '#ffffff'
  secondary-container: '#86f898'
  on-secondary-container: '#00722f'
  tertiary: '#765700'
  on-tertiary: '#ffffff'
  tertiary-container: '#956e00'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004494'
  secondary-fixed: '#89fa9b'
  secondary-fixed-dim: '#6ddd81'
  on-secondary-fixed: '#002108'
  on-secondary-fixed-variant: '#005320'
  tertiary-fixed: '#ffdea0'
  tertiary-fixed-dim: '#fbbc06'
  on-tertiary-fixed: '#261a00'
  on-tertiary-fixed-variant: '#5c4300'
  background: '#f9f9ff'
  on-background: '#191b22'
  surface-variant: '#e1e2eb'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Geist
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Geist
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 4px
  xs: 8px
  sm: 16px
  md: 24px
  lg: 40px
  xl: 64px
  border-width: 3px
  grid-columns-mobile: '4'
  grid-columns-desktop: '12'
  gutter: 20px
---

## Brand & Style
This design system establishes a unified digital infrastructure for Bharat One, blending the systematic reliability of **Material Design 3** with a **Neo-Brutalist** edge that reflects India's vibrant structural diversity. The brand personality is institutional yet accessible, balancing government-grade stability with local cultural pride.

The aesthetic utilizes "structural playfulness": heavy 3px borders provide a physical, grounded feel, while 20px rounded corners soften the interface for a modern, mobile-first experience. Each state theme functions as a dynamic skin over a rigid, high-contrast framework, ensuring that while the cultural "vibe" shifts, the functional ergonomics remain consistent.

## Colors
The core palette leverages the four Google foundation colors for functional signifiers: Blue for primary actions, Green for success/growth, Yellow for warnings, and Red for critical alerts. The primary background is a soft, warm off-white (`#FAFAFA`) to reduce eye strain and provide a neutral canvas for state-specific accents.

**Thematic State Tokens:**
- **State-Accent:** Applied to active tab indicators, primary icons, and focused border states.
- **State-Pattern:** 10-20% opacity abstract SVG backgrounds.
- **State-Illustration:** Minimalist line art used in hero sections or empty states.

State-specific gradients should be applied subtly to header surfaces or featured cards, always maintaining high legibility against black (`#1A1A1A`) text.

## Typography
The typography system uses a tri-font approach to balance personality and utility. **Plus Jakarta Sans** provides a friendly, geometric presence for headings. **Inter** handles the heavy lifting of body text for maximum legibility across diverse screen qualities. **Geist** is reserved for labels and technical data, providing a precise, developer-friendly touch that resonates with modern digital governance.

Scale headlines aggressively on desktop to lean into the Neo-Brutalist aesthetic, but ensure they collapse into readable stacks on mobile. All labels should use `Geist` to provide a distinct visual "mode" for metadata.

## Layout & Spacing
The spacing rhythm is based on a 4px baseline grid. The layout follows a fluid-to-fixed model: 
- **Mobile:** 4-column fluid grid with 16px side margins.
- **Tablet:** 8-column fluid grid with 24px side margins.
- **Desktop:** 12-column fixed grid (max-width 1280px) centered in the viewport.

Spacing between major UI blocks should be generous (`lg` or `xl`) to allow the 3px borders to breathe. Small components like chips and input fields use `xs` padding internally. Elements should snap to the grid to maintain the structural integrity required by the Neo-Brutalist style.

## Elevation & Depth
This design system rejects traditional soft shadows in favor of **Tonal Layering** and **Hard Shadows (Hard-Drops)**. 

1.  **Level 0 (Surface):** The `#FAFAFA` background.
2.  **Level 1 (Cards/Fields):** Pure white background with a `3px` solid black (`#1A1A1A`) border.
3.  **Level 2 (Interactive/Hover):** When an element is hovered or active, it gains a "Hard-Drop" shadow: `4px 4px 0px 0px #1A1A1A`. 
4.  **Level 3 (Modals):** Elements are lifted with an 8px Hard-Drop shadow and a high-contrast overlay (`rgba(0,0,0,0.4)`).

State-specific backgrounds utilize the `state-pattern` at 10% opacity, layered behind all content but above the base surface color.

## Shapes
The shape language is defined by the tension between "Harsh" and "Soft." Every primary container—buttons, cards, and input fields—must use a **20px corner radius** and a **3px border**. 

- **Primary Radius:** 20px (for large cards and main containers).
- **Secondary Radius:** 12px (for nested elements or smaller components).
- **Interactive Radius:** 20px (for buttons to maintain the chunky, tactile feel).

This high radius ensures that the heavy black borders do not feel overly aggressive, maintaining the "Friendly Government" aesthetic.

## Components

### Buttons
Buttons are high-contrast and tactile. The **Primary Button** uses a solid `primary-color` fill, 3px black border, and 20px radius. On hover, the button shifts +4px up and left, revealing a 4px black hard-drop shadow. 

### Cards
Cards are the primary content vessel. They must use the `3px` border. For state-themed cards, the top border or a small corner "Jharokha" or "Metro" icon should use the `state-accent`.

### Input Fields
Fields use a 3px border that changes from black to `primary-blue` (or `state-accent`) on focus. Labels always use the `Geist` font and are positioned above the field, never as placeholder-only.

### Chips & Tags
Chips are pill-shaped (100px radius) but retain the 3px border. They are used for state selection or filtering. When a state chip is selected (e.g., "Punjab"), it should adopt the mustard `state-accent` fill.

### State Patterns & Illustrations
- **Patterns:** Applied as a CSS `mask-image` or background-pattern to headers.
- **Illustrations:** Use thin 1.5pt strokes. For Kerala, use coconut fronds; for Delhi, use Lotus Temple curves. Keep all illustrations as abstract vector line art to ensure they don't distract from the core utility of the UI.