---
name: Lumina Tech Noir
colors:
  surface: '#131411'
  surface-dim: '#131411'
  surface-bright: '#393936'
  surface-container-lowest: '#0e0e0c'
  surface-container-low: '#1b1c19'
  surface-container: '#1f201d'
  surface-container-high: '#2a2a27'
  surface-container-highest: '#343532'
  on-surface: '#e4e2dd'
  on-surface-variant: '#c7c9ac'
  inverse-surface: '#e4e2dd'
  inverse-on-surface: '#30312e'
  outline: '#919379'
  outline-variant: '#464833'
  surface-tint: '#bcd200'
  primary: '#ffffff'
  on-primary: '#2d3400'
  primary-container: '#d7ef10'
  on-primary-container: '#5f6a00'
  inverse-primary: '#596400'
  secondary: '#9ccfdb'
  on-secondary: '#00363f'
  secondary-container: '#1a505a'
  on-secondary-container: '#8ec1cc'
  tertiary: '#ffffff'
  on-tertiary: '#24323a'
  tertiary-container: '#d6e5ef'
  on-tertiary-container: '#586670'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#d7ef10'
  primary-fixed-dim: '#bcd200'
  on-primary-fixed: '#191e00'
  on-primary-fixed-variant: '#434b00'
  secondary-fixed: '#b8ebf7'
  secondary-fixed-dim: '#9ccfdb'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#174d58'
  tertiary-fixed: '#d6e5ef'
  tertiary-fixed-dim: '#bac9d3'
  on-tertiary-fixed: '#0f1d25'
  on-tertiary-fixed-variant: '#3b4951'
  background: '#131411'
  on-background: '#e4e2dd'
  surface-variant: '#343532'
typography:
  display-lg:
    fontFamily: Geist
    fontSize: 72px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.04em
  headline-lg:
    fontFamily: Geist
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Geist
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Geist
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-mono:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style

This design system is built for a premium tech portfolio, merging **Hyper-Minimalism** with **High-Contrast Functionalism**. The brand personality is precise, avant-garde, and authoritative. It targets a high-end audience—recruitment leads at top-tier labs and venture capitalists—evoking a feeling of technical mastery and "signal over noise."

The visual style utilizes a dark, atmospheric foundation punctuated by "electrical" lime accents. It leans into a **Corporate Modern** structure but borrows the aggressive clarity of **Minimalism** to ensure every pixel serves a purpose. The result is a sleek, digitized aesthetic that feels fast, focused, and undeniably professional.

## Colors

The palette is driven by the tension between the deep, architectural slate and the hyper-vibrant lime. 

- **Primary (Vibrant Lime):** Used exclusively for high-priority calls to action, active states, and critical information. It represents the "spark" of innovation.
- **Secondary (Deep Slate):** The structural core. Provides a softer, more sophisticated alternative to pure black, allowing for subtle depth layering.
- **Neutral (Off-White):** Used for primary text and high-readability body copy. It avoids the harshness of #FFFFFF to maintain a premium, slightly "printed" feel.
- **Accent Gray (#898A8D):** Reserved for metadata, disabled states, and secondary borders to de-emphasize non-essential UI elements.

## Typography

The typography system uses a tri-font approach to balance technical precision with modern elegance.

- **Geist** handles the heavy lifting for headlines. Its technical, minimalist construction feels engineered rather than drawn. Use tight tracking on larger sizes.
- **Inter** provides maximum legibility for long-form case studies and bio sections, ensuring the reading experience is effortless.
- **JetBrains Mono** is the "accent" font. It is used for labels, category tags, and data points, signaling the "tech portfolio" nature of the product.

Whitespace around typography is as important as the text itself; ensure generous margins between headings and body text to maintain the minimalist breathability.

## Layout & Spacing

This design system employs a **fixed-fluid hybrid grid**. Content is contained within a 1280px max-width container, centered on the screen.

- **Desktop (1200px+):** 12-column grid with 24px gutters. Sections are separated by large 120px gaps to create a cinematic, gallery-like flow.
- **Tablet (768px - 1199px):** 8-column grid with 20px gutters. Section gaps reduce to 80px.
- **Mobile (<767px):** 4-column grid. Margins are 20px. 

Horizontal alignment is strictly enforced to create a sense of structural integrity. Use the "Base 8" spacing system for all internal component padding and margins (8, 16, 24, 32, 48, 64).

## Elevation & Depth

To maintain a "sleek tech" aesthetic, this design system avoids heavy shadows. Instead, depth is conveyed through **Tonal Layering** and **Low-Contrast Outlines**.

- **Level 0 (Background):** #051A1E (Deepest dark).
- **Level 1 (Cards/Containers):** #082E35 (Subtle elevation).
- **Level 2 (Modals/Overlays):** #0B4650 with a subtle 1px border of #E6FF2B at 20% opacity.

Interaction states do not use shadows; instead, use "Glow" effects. For example, a hovered button may emit a subtle, 8px blur of the Primary Lime color to simulate light emission.

## Shapes

The shape language is "Soft-Tech." While the grid is rigid and brutalist, individual components utilize a **0.25rem (4px)** base radius. This prevents the UI from feeling sharp or aggressive while remaining significantly more professional and structured than pill-shaped or highly rounded systems.

Large elements (Project Cards) use `rounded-lg` (8px) to soften the large surface areas. This subtle rounding creates a "premium hardware" feel, similar to high-end electronics.

## Components

- **Primary Buttons:** Solid Vibrant Lime background with black text. No border. Sharp 4px corners. On hover, increase brightness or add a subtle lime outer glow.
- **Ghost Buttons:** Deep Slate background with a 1px border in Lime. Text is Lime.
- **Project Cards:** Deep Slate (#082E35) background. Use the off-white neutral for titles and the accent gray for tech-stack labels. The entire card should feel like a single interactive unit.
- **Chips/Tags:** JetBrains Mono font. 1px border in #898A8D. Background is transparent. Used for categorizing skills or project types.
- **Input Fields:** Darker than the background (#051A1E). 1px border in Deep Slate, turning into a 2px Lime border on focus.
- **Navigation:** Minimalist text links in the header. Use the Lime color for the active page indicator, represented as a small 4px dot below the text.
- **Dividers:** 1px solid lines using #0B4650. Use sparingly to separate logical sections without breaking the flow of whitespace.