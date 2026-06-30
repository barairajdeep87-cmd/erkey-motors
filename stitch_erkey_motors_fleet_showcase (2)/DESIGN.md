---
name: Erkey Velocity System
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#414754'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#717786'
  outline-variant: '#c1c6d7'
  surface-tint: '#005bc0'
  primary: '#0059bb'
  on-primary: '#ffffff'
  primary-container: '#0070ea'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc7ff'
  secondary: '#006688'
  on-secondary: '#ffffff'
  secondary-container: '#00c1fd'
  on-secondary-container: '#004b65'
  tertiary: '#5d5c5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#767474'
  on-tertiary-container: '#f7feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc7ff'
  on-primary-fixed: '#001a41'
  on-primary-fixed-variant: '#004493'
  secondary-fixed: '#c2e8ff'
  secondary-fixed-dim: '#75d1ff'
  on-secondary-fixed: '#001e2b'
  on-secondary-fixed-variant: '#004d67'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474646'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  display-lg:
    fontFamily: Sora
    fontSize: 64px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Sora
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Sora
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Sora
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  nav-label:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.0'
    letterSpacing: 0.1em
  button-label:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.0'
  caption:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.4'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-padding: 80px
---

## Brand & Style

This design system embodies the intersection of heavy-duty commercial utility and high-performance electric innovation. The aesthetic is rooted in **Modern Minimalism** with a **Tactile** edge, reflecting the precision engineering of electric delivery bikes. 

The target audience consists of B2B logistics managers and fleet operators who prioritize efficiency, reliability, and technological advancement. The UI evokes a sense of "EV-native" polish—reminiscent of premium automotive interfaces—using expansive whitespace, sharp geometric arrangements, and high-frequency accent colors to signal movement and energy.

**Key Principles:**
- **Performance-Driven:** Every element must feel fast, responsive, and purposeful.
- **Industrial Precision:** Clean lines and structured layouts that mirror vehicle chassis and hardware components.
- **Clarity over Decoration:** Use depth and color only to indicate status, action, or hierarchy.

## Colors

The palette is anchored in a high-contrast monochromatic base to ensure maximum legibility and a premium B2B feel. The **Electric Blue** primary color is reserved strictly for interactive elements and brand identifiers, ensuring it acts as a functional beacon within the "industrial" white and gray environment.

**Color Usage:**
- **Primary (Electric Blue):** Used for primary action buttons, active toggles, and critical status icons.
- **Secondary (Bright Cyan):** Exclusively used for hover states and active transitions to simulate the "glow" of electrical energy.
- **Surface (Light Gray):** Applied to cards and panels to create subtle separation from the white background without requiring heavy borders.
- **Feedback:** Success (Green), Warning (Amber), and Error (Red) should be desaturated to maintain the professional, understated tone of the design system.

## Typography

The typography strategy utilizes **Sora** for headlines to convey a technical, forward-thinking personality. Its geometric construction feels engineered rather than drawn. For body copy, **Hanken Grotesk** provides a clean, highly legible "Grotesk" style that maintains professional neutrality.

**Styling Rules:**
- **Navigation:** All top-level navigation items must use the `nav-label` token (uppercase with 0.1em tracking) to differentiate functional links from content.
- **Rhythm:** Maintain generous vertical spacing between headlines and body text to emphasize the "Premium" feel. 
- **Contrast:** Always use `#111111` for headlines and `#555555` for long-form body text to reduce eye strain while maintaining accessibility.

## Layout & Spacing

The layout follows a **Fluid Grid** model with strict horizontal constraints to maintain the "Tesla-style" wide-screen cinematic feel on desktop.

**Breakpoints & Grids:**
- **Desktop (1280px+):** 12-column grid, 64px outer margins, 24px gutters.
- **Tablet (768px - 1279px):** 8-column grid, 40px outer margins, 20px gutters.
- **Mobile (Up to 767px):** 4-column grid, 20px outer margins, 16px gutters.

**Spacing Logic:**
Use a base-8 spacing scale. Content sections should be separated by large vertical gaps (`section-padding`) to allow the design to "breathe." Related elements (like an icon and its label) should use `stack-sm`.

## Elevation & Depth

This design system uses a combination of **Tonal Layers** and **Glassmorphism** to establish hierarchy without visual clutter.

- **Header:** Employs a sticky glassmorphism effect—a semi-transparent White (#FFFFFF) with a 20px backdrop blur and a 1px bottom border in Light Gray (#F5F5F5).
- **Cards:** Use a low-altitude shadow (0px 4px 20px rgba(0, 0, 0, 0.05)) to lift the Light Gray surface slightly off the White background.
- **Interactive Elements:** Depth is dynamic. Upon hover, buttons and cards should slightly increase their shadow spread to simulate physical lifting.
- **Overlays:** Modals and drawers use a 40% opacity Black (#111111) backdrop to focus the user's attention entirely on the elevated surface.

## Shapes

The shape language is "Softly Geometric." A consistent **12px (0.75rem)** corner radius is applied to cards and major UI containers to balance the "industrial" feel with modern approachable tech.

- **Primary Components:** (Buttons, Input Fields) use a standard 8px radius.
- **Cards/Panels:** Use a 12px radius (`rounded-lg` in this system).
- **Icons:** Should be encased in circular or 8px rounded squares when used as decorative accents.
- **Selection States:** Use a 2px solid Electric Blue stroke for focus states, offset by 2px from the element.

## Components

**Buttons**
- **Primary:** Electric Blue background, White text. On hover: Scale 1.03x, transition background to Bright Cyan.
- **Secondary:** Transparent background, Electric Blue border (2px), Electric Blue text. On hover: Light Gray fill.

**Cards**
- Background: Light Gray (#F5F5F5).
- Padding: 32px (Desktop), 24px (Mobile).
- Shadow: Soft, diffused 5% black.
- Content: Bold Sora H3 headlines followed by Hanken Grotesk body.

**Input Fields**
- Background: White.
- Border: 1px Solid Light Gray.
- Focus State: 1px Solid Electric Blue with a subtle blue outer glow.

**Navigation Header**
- Height: 80px.
- Effect: Backdrop blur (20px) + 90% opacity White.
- Links: `nav-label` typography, turns Electric Blue on hover.

**Chips / Badges**
- Used for "In Stock" or "Electric" indicators.
- Style: Pill-shaped, Light Gray background, Dark Gray text, 10px font size.

**Progress Bars / Data Viz**
- Track: Light Gray.
- Indicator: Electric Blue gradient moving towards Bright Cyan.