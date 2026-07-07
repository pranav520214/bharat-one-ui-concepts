---
name: Bharat One
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1b1b1c'
  on-surface-variant: '#424753'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0ef'
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
  background: '#fcf9f8'
  on-background: '#1b1b1c'
  surface-variant: '#e5e2e1'
typography:
  headline-xl:
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
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
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
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
  container-max: 1280px
---

## Brand & Style
The design system is a vibrant, structural tribute to Indian cultural heritage, blending modern geometric precision with regional artistic motifs. It utilizes a **Neo-Brutalist** foundation—characterized by thick borders and deliberate shadows—softened by generous organic rounding to feel approachable yet authoritative.

The aesthetic response should be one of "Structured Celebration." The UI acts as a sturdy vessel for rich, dynamic content, using heavy linework to define boundaries while allowing regional "State Themes" to inject soul and texture into the digital experience. It targets a broad demographic, prioritizing legibility and a sense of institutional reliability infused with local pride.

## Colors
The core palette is built upon a high-confidence "Google-inspired" primary set: Blue (Trust), Green (Growth), Yellow (Energy), and Red (Urgency). 

### Dynamic State Themes
The design system employs a "Theme Overlay" logic where secondary surfaces, icons, and decorative patterns transform based on the regional context:
- **Chhattisgarh:** Deep forest greens and terracotta accents, utilizing Bastar Art (dhokra-inspired) linework in background containers.
- **Madhya Pradesh:** Earthy ochres and stone teals, incorporating Gond Art's repetitive dot and dash textures.
- **Uttar Pradesh:** Saffron and royal silk purples, using intricate Banarasi floral patterns and the stepped geometry of Ghats for dividers.

Neutral colors must remain high-contrast (Black #1F1F1F) for all structural borders to maintain the Neo-Brutalist edge.

## Typography
This design system uses **Plus Jakarta Sans** across all levels to maintain a friendly, modern, and highly legible geometric feel. 

Headlines use "Extra Bold" or "Bold" weights to compete with the heavy 3px borders of the UI components. For mobile, headline scales are slightly reduced to prevent awkward line breaks while maintaining the heavy visual weight. Labels are often uppercase with a slight increase in weight to function as "tags" within the structural layout.

## Layout & Spacing
The layout follows a **Fluid Grid** system within a max-width container. 
- **Desktop:** 12-column grid with 24px gutters.
- **Tablet:** 8-column grid with 20px gutters.
- **Mobile:** 4-column grid with 16px gutters.

Spacing follows a 4px base unit. Because of the heavy 3px borders, internal padding for cards and buttons must be generous (minimum 16px) to ensure content does not feel cramped against the structural lines. Negative space is used aggressively to balance the "loudness" of the bold borders.

## Elevation & Depth
In this design system, depth is not conveyed through shadows or blurs, but through **Hard Shadows (Stickers)** and **Tonal Layering**.

- **Level 0:** Background surface (White or State-themed texture).
- **Level 1:** Primary cards with 3px solid black borders.
- **Level 2:** Interactive elements. When hovered or active, these elements use a "Hard Shadow"—a solid offset fill (usually 4px or 8px) in black or a state-specific secondary color—to simulate physical displacement.
- **Overlays:** Modals and tooltips maintain the 3px border and 20px corner radius, appearing to "pop" off the page through a thicker 8px hard shadow offset.

## Shapes
The defining characteristic of this design system is the combination of **20px rounded corners** and **3px solid borders**. 

This applies to all primary containers:
- **Buttons:** Fully rounded (pill) or 20px depending on width.
- **Cards/Modals:** Always 20px.
- **Inputs:** 12px (slightly tighter to maintain vertical alignment within forms).

The 3px border must be applied to all interactive and containment elements to maintain the "Bharat One" structural integrity.

## Components

### Buttons
Primary buttons feature a solid Google-blue fill, 3px black border, and 20px rounded corners. On hover, they shift 4px up/left and reveal a 4px solid black hard shadow. Text is Bold 16px.

### Cards
Cards are the primary content vehicle. They must have a 3px border. For state themes, the top 8px of the card may feature a thematic pattern (e.g., Gond Art patterns for MP) or a solid color header.

### Inputs & Selection
Input fields use a 3px border. On focus, the border color changes to the State's primary theme color (e.g., Forest Green for Chhattisgarh) and the border weight remains 3px. Checkboxes and Radios follow the 3px rule, with checkboxes utilizing a 4px radius and Radios remaining circular.

### State-Specific Chips
Chips are used for categorization. They use a 2px border (lighter than the 3px structural border) and incorporate state-specific iconography (e.g., a Sanchi Stupa icon for MP-related content).

### Navigation
The Navigation bar is anchored with a 3px bottom border. Active states are indicated by a "pill" background behind the text in the primary brand color, rather than a simple underline.