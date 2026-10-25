---
name: Underground Bolognese Editorial
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#4f4352'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#817283'
  outline-variant: '#d3c1d4'
  surface-tint: '#9227bd'
  primary: '#69008e'
  on-primary: '#ffffff'
  primary-container: '#891ab4'
  on-primary-container: '#efb9ff'
  inverse-primary: '#ecb1ff'
  secondary: '#635c69'
  on-secondary: '#ffffff'
  secondary-container: '#eadfef'
  on-secondary-container: '#69626f'
  tertiary: '#543b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#715100'
  on-tertiary-container: '#f3c670'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f9d8ff'
  primary-fixed-dim: '#ecb1ff'
  on-primary-fixed: '#320046'
  on-primary-fixed-variant: '#75009e'
  secondary-fixed: '#eadfef'
  secondary-fixed-dim: '#cdc3d2'
  on-secondary-fixed: '#1f1924'
  on-secondary-fixed-variant: '#4b4451'
  tertiary-fixed: '#ffdea5'
  tertiary-fixed-dim: '#ecc06b'
  on-tertiary-fixed: '#261900'
  on-tertiary-fixed-variant: '#5d4200'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
typography:
  display-hero:
    fontFamily: Anton
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: 0.02em
  display-hero-mobile:
    fontFamily: Anton
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Anton
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 38px
    letterSpacing: 0.02em
  headline-lg-mobile:
    fontFamily: Anton
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 30px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Anton
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: 0.03em
  headline-sm:
    fontFamily: Anton
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: 0.04em
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 18px
    letterSpacing: 0.05em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
spacing:
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system channels the irreverent, street-smart pulse of Bologna’s nightlife, subcultures, and digital meme landscape. It merges raw underground zine energy with a sharp, contemporary digital product infrastructure. The tone is self-aware, sarcastic, hyper-local, and unapologetically bold. 

The aesthetic is grounded in high-contrast neo-brutalism refined for mobile editorial utility: heavy typographic cuts, sharp block layouts, high-impact posterized sections, and high-frequency visual punchlines. Whitespace is active rather than serene, serving as the stark negative void that lets saturated violet accents and jet-black headlines dominate the viewport.

## Colors

- **Primary Violet (`#891AB4`):** The electric signature accent. Used for primary CTAs, active states, key highlight blocks, critical tags, and date badges. Any typography overlaid on this color must strictly be `#FFFFFF`.
- **Secondary Lilac (`#F3E8F8`):** The structural counterweight. Used for pill backgrounds, soft card surfaces, inactive filters, and muted contextual tags, preventing visual fatigue against pure white.
- **Raven Neutral (`#111111`):** Deep, ink-heavy black for primary headlines, solid borders, structural dividers, and maximum contrast against `#FFFFFF`.
- **Secondary Gray (`#6B6670`):** Used strictly for metadata, subheaders, timestamps, venue addresses, and helper text.
- **Pure White (`#FFFFFF`):** Base canvas background, high-contrast reverse cards, and punch-out typography.

## Typography

The type system relies on deliberate tension between two extremes:
- **Anton (Display & Headlines):** Set strictly in uppercase (`text-transform: uppercase`). Emulates silkscreen poster typography, flyposting, and bold club lineups. Used for high-energy hook lines, event titles, calendar dates, and primary banner statements.
- **Inter (Functional Body & Interface):** Rational, neutral, and readable. Handles editorial body copy, micro-metadata, ticket pricing, addresses, form controls, and multi-line descriptions without competing with Anton’s voice.

## Layout & Spacing

A fluid responsive grid tailored for content-heavy feeds and rapid browsing:
- **Mobile (Base to 640px):** 4-column layout with 16px margins and 16px gutters. Compact, high-density listing style.
- **Tablet (641px to 1024px):** 8-column layout with 24px margins and 20px gutters. Event grids shift to two-column mosaic patterns.
- **Desktop (1025px+):** 12-column layout capped at a max-width of 1280px, centered with 48px margins and 24px gutters.

Spacing enforces strict structural blocks rather than soft padding. Sections terminate with visible boundaries or stark background color shifts rather than arbitrary breathing room.

## Elevation & Depth

This system rejects soft atmospheric drop shadows and glossy skeuomorphism. Depth is achieved via:
- **Hard Offset Edge (Brutalist Lift):** Key interactive components (e.g., floating action triggers, selected ticket options) use a solid, zero-blur 3px offset drop shadow in `#111111` (`box-shadow: 3px 3px 0px #111111`).
- **High-Contrast Layering:** Contrast is established by pairing pure white cards with 1.5px or 2px solid `#111111` outlines, or by alternating between `#FFFFFF` canvases and solid `#891AB4` or `#F3E8F8` blocks.
- **Zero Blur Modals:** Overlays use a sharp backdrop tint of `#111111` at 60% opacity with no blur filter, maintaining crisp street-poster clarity.

## Shapes

The shape profile is intentionally sharp (`0px` border radius across core structures). Every element—from full-width hero cards to buttons, list rows, and images—features sharp 90-degree corners. 

Pill exceptions are permitted exclusively for dynamic categorization tags and social badge labels (utilizing fully rounded border caps) to create immediate contrast against the heavy rectangular geometry of the grid.

## Components

### Buttons
- **Primary Action:** Solid `#891AB4` background, `#FFFFFF` text (Inter, bold, uppercase), sharp edges (0px radius), bordered with 2px solid `#111111`. On press, shifts down-right by 2px with zero-blur shadow collapse.
- **Secondary / Ghost:** `#FFFFFF` background, `#111111` text, 2px solid `#111111` border.
- **Trash / Destructive:** Solid `#111111` background, `#FFFFFF` text, paired with neon hover underlines.

### Chips & Filter Pills
- **Active Filter:** Background `#891AB4`, text `#FFFFFF`, 1.5px solid `#111111`.
- **Inactive Filter:** Background `#F3E8F8`, text `#111111`, 1px solid transparent.
- **Shape Rule:** Fully rounded ends (`rounded-full`) exclusively used on chips to stand out against rectangular event cards.

### Cards (Events & Memes)
- Sharp 0px corners, bordered by 1.5px solid `#111111`.
- Image containers sit edge-to-edge at the top of the card with no inner padding.
- Event dates are presented as stacked Anton badges pinned to the top-left corner (solid `#891AB4` block with white text).
- Metadata sits below in high-legibility Inter body text.

### Lists & Lineups
- Heavy, row-based listing separated by 1px solid `#111111` borders.
- Hovering or tapping a row inverts the selection to a solid `#F3E8F8` or `#891AB4` highlight.
- Time badges use uppercase Anton typography for immediate scanning.

### Input Fields & Search
- Flat `#FFFFFF` fields with a 2px solid `#111111` outline, 0px border-radius.
- Placeholder text set in `#6B6670`.
- Focus state thickens border to 3px solid `#891AB4` with no soft outer glow rings.

### Specialized Custom Components
- **Meme Banner Callout:** Inset containers using diagonal edge cut accents (clip-path corners) or stark dual-color checkerboard separators.
- **Parvenza Sticky Ticker:** Persistent bottom/top text scroller in `#111111` with inverted white/violet Anton typography for breaking party announcements and hot take updates.