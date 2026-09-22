---
name: Bharat One NE
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#444748'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#747878'
  outline-variant: '#c4c7c7'
  surface-tint: '#5f5e5e'
  primary: '#0a0a0a'
  on-primary: '#ffffff'
  primary-container: '#212121'
  on-primary-container: '#898888'
  inverse-primary: '#c8c6c5'
  secondary: '#b6171e'
  on-secondary: '#ffffff'
  secondary-container: '#da3433'
  on-secondary-container: '#fffbff'
  tertiary: '#0b0a09'
  on-tertiary: '#ffffff'
  tertiary-container: '#222120'
  on-tertiary-container: '#8b8886'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e5e2e1'
  primary-fixed-dim: '#c8c6c5'
  on-primary-fixed: '#1b1c1c'
  on-primary-fixed-variant: '#474746'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb3ac'
  on-secondary-fixed: '#410003'
  on-secondary-fixed-variant: '#930010'
  tertiary-fixed: '#e6e2e0'
  tertiary-fixed-dim: '#c9c6c4'
  on-tertiary-fixed: '#1c1b1a'
  on-tertiary-fixed-variant: '#484645'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
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
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-bold:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  gutter: 20px
  margin-mobile: 16px
  margin-desktop: 32px
---

## Brand & Style

The design system is a premium, high-density interface specifically engineered for the North-Eastern states of India. It balances the rugged, vibrant cultural heritage of the "Seven Sisters and One Brother" with a sophisticated, Google-quality functionalism.

The aesthetic is **Neo-Brutalist**, characterized by structural integrity and high contrast. It utilizes "Bharat One" signatures—thick 3px strokes and generous 20px radii—to create a UI that feels both physically grounded and approachable. The target emotional response is one of reliability, regional pride, and effortless modern utility.

The UI avoids delicate flourishes in favor of bold, clear communication. Every element is encased in a defined container, ensuring that the diverse color palette of the North-East remains organized and legible within a dense, information-rich environment.

## Colors

The design system utilizes a high-contrast base of **Weave Black (#212121)** and **Neermahal White (#FFFFFF)** to provide the structural scaffolding. The 3px borders always utilize the primary Weave Black or the specific dark-state variant of the regional colors.

Regional color pairs are applied contextually to differentiate state-specific services. 
- **Primary Action Surface:** High-saturation tones (e.g., Tribal Red, Lake Teal).
- **Secondary/Background Surface:** Tinted variations or the lighter regional counterpart (e.g., Tea Green, Cloud Blue).
- **Backgrounds:** Stick to a clean neutral (#F8F9FA) to allow the bold borders and regional accents to pop without causing visual fatigue in high-density layouts.

## Typography

This design system relies exclusively on **Plus Jakarta Sans** to maintain a modern, friendly, and highly legible interface. 

- **Weight Strategy:** Use Bold (700) and ExtraBold (800) for headlines to match the visual weight of the 3px borders. 
- **Clarity:** For body text, a Medium (500) weight is preferred over Regular to ensure text stands its ground against strong container lines.
- **Labels:** Small labels use a heavy weight with increased letter spacing for maximum readability in dense data views.

## Layout & Spacing

The design system employs a **Fluid Grid** model with high-density spacing. 

- **Desktop:** 12-column grid with 20px gutters. Content is strictly contained within bordered modules.
- **Mobile:** 4-column grid with 16px gutters and margins.
- **Rhythm:** An 8px linear scale is used for most spacing, but a 4px "half-step" is permitted for dense data components (like table cells or compact lists) to achieve "Google-quality" information density.
- **Padding:** Internal container padding should never be less than 16px (sm) to ensure content doesn't feel cramped against the heavy 3px borders.

## Elevation & Depth

Depth is conveyed through **Hard Shadows** and **Z-axis Layering** rather than blurs or gradients.

- **The "Lift":** Elements do not use ambient blurs. Instead, they use a "Hard Drop" shadow: a solid offset of 4px or 8px in Weave Black to simulate physical elevation.
- **Tonal Tiers:** Level 0 is the background (#F8F9FA). Level 1 is a bordered container (White). Level 2 is an active state or modal with a hard shadow.
- **Strokes as Depth:** The 3px border is the primary separator. In some cases, a secondary 1px interior border can be used for nested sub-sections to maintain hierarchy without over-cluttering.

## Shapes

The shape language is the core differentiator. 

- **Corners:** Every primary container, button, and input field must utilize a **20px corner radius**. 
- **Stroke:** A constant **3px solid border** is applied to all interactive and container elements. 
- **Consistency:** Even smaller components like chips or checkboxes should maintain a high degree of rounding (minimum 8px) to stay consistent with the "Bharat One" brand language.

## Components

- **Buttons:** Large-format with 20px radius and 3px borders. Primary buttons use the state's signature color (e.g., Tribal Red for Nagaland) with white text. On hover, apply the "Hard Drop" shadow.
- **Input Fields:** White background, 3px Weave Black border, 20px radius. Labels are positioned above the field using `label-bold`.
- **Cards:** The workhorse of the system. 3px borders, 20px radius, white background. Card headers should often feature a solid background color from the regional palette to instantly categorize the content.
- **Chips/Tags:** Pill-shaped (fully rounded) with 1px borders for secondary information, or 3px for high-priority filters.
- **Lists:** High-density items separated by 1px horizontal dividers. The entire list is typically wrapped in a 3px bordered, 20px rounded container.
- **State Selection:** A custom toggle or segmented control using 20px radius that switches the entire theme's accent color based on the selected North-Eastern state.