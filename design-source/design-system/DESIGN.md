---
name: Tactile Sanctuary
colors:
  surface: '#f9f9f8'
  surface-dim: '#d9dad9'
  surface-bright: '#f9f9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f3'
  surface-container: '#edeeed'
  surface-container-high: '#e7e8e7'
  surface-container-highest: '#e1e3e2'
  on-surface: '#191c1c'
  on-surface-variant: '#494740'
  inverse-surface: '#2e3131'
  inverse-on-surface: '#f0f1f0'
  outline: '#7a776f'
  outline-variant: '#cbc6bd'
  surface-tint: '#605e5d'
  primary: '#141413'
  on-primary: '#ffffff'
  primary-container: '#292827'
  on-primary-container: '#918f8d'
  inverse-primary: '#c9c6c4'
  secondary: '#a03c4e'
  on-secondary: '#ffffff'
  secondary-container: '#ff8797'
  on-secondary-container: '#771d30'
  tertiary: '#161411'
  on-tertiary: '#ffffff'
  tertiary-container: '#2a2826'
  on-tertiary-container: '#938e8b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e6e2e0'
  primary-fixed-dim: '#c9c6c4'
  on-primary-fixed: '#1c1b1a'
  on-primary-fixed-variant: '#484645'
  secondary-fixed: '#ffd9dc'
  secondary-fixed-dim: '#ffb2ba'
  on-secondary-fixed: '#400011'
  on-secondary-fixed-variant: '#812537'
  tertiary-fixed: '#e8e1dd'
  tertiary-fixed-dim: '#cbc5c2'
  on-tertiary-fixed: '#1d1b19'
  on-tertiary-fixed-variant: '#494643'
  background: '#f9f9f8'
  on-background: '#191c1c'
  surface-variant: '#e1e3e2'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '500'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
    letterSpacing: -0.005em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  title-md:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  label-md:
    fontFamily: Space Grotesk
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Space Grotesk
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
    letterSpacing: 0.08em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-desktop: 2.5rem
  margin: 1.25rem
  margin-desktop: 4rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 3rem
---

## Brand & Style

This design system establishes an atmospheric, gallery-grade digital boutique for tactile squishy collectible objects. It rejects juvenile pastel toy aesthetics in favor of serene Japanese spatial design (*Ma*—negative space), architectural precision, and sensual material appreciation. 

The aesthetic is grounded in a modern Japanese gallery environment: airy white canvas, deliberate silence, crisp linear framing, and weightless structural rhythm. Objects are staged as fine art sculptures rather than disposable playthings. The interaction feel is quiet, restrained, and profoundly physical, evoking smooth matte elastomer, ceramic pedestals, and curated display shelving.

## Colors

The palette relies on absolute balance, restraint, and organic calmness:
- **Canvas (`#F7F8F7`)**: Mist White provides an expansive, non-glaring environment reminiscent of traditional architectural plaster.
- **Surface (`#FFFFFF`)**: Pure White isolates collectible objects, creating defined, pedestal-like elevations without heavy drop shadows.
- **Primary Ink (`#292827`)**: Sumi Charcoal anchors typographic hierarchy with natural depth and zero synthetic glare.
- **Secondary Ink (`#716D6A`)**: Stone Gray manages technical meta-information, dimension labels, and supporting architectural specs.
- **Accent (`#B84F60`)**: Restrained Berry provides a deliberate, singular focal strike used sparingly for edition numbers, scarcity indicators, and deliberate state transitions.
- **Dividers & Outlines (`#EBECE8`)**: Subtle Warm Neutral provides faint structural delineation that respects negative space.

## Typography

Typographic scale is structured around gallery curatorial conventions:
- **Headlines & Display**: Plus Jakarta Sans provides refined soft geometric geometry matching the physical tactile nature of Zen Maru Gothic for Latin characters, paired with Zen Maru Gothic for Japanese headlines.
- **Body & Reading**: Manrope pairs with Zen Kaku Gothic New to deliver neutral, crisp, high-legibility Japanese and Latin reading flow.
- **Labels & Spec Sheets**: Space Grotesk provides a technical, museum-catalog monoline contrast for edition badges, batch numbers, material shore hardness scales, and dimensions.
- Japanese and Latin scripts share balanced baseline heights and relaxed line tracking.

## Layout & Spacing

The structural layout utilizes a disciplined 12-column grid system anchored by expansive perimeter margins to foster a museum exhibition layout:
- **Desktop (1024px+)**: 12 columns, 40px gutters, and 64px outer margins. Products inhabit asymmetric placements mimicking spatial room shelves.
- **Tablet (768px - 1023px)**: 8 columns, 24px gutters, and 32px outer margins.
- **Mobile (< 768px)**: 4 columns, 16px gutters, and 20px outer margins. Vertical cadences open up with generous whitespace (`space-xl`) between collection tiers.

## Elevation & Depth

Visual hierarchy rejects exaggerated drops or layered z-index blurs, prioritizing tonal stillness:
- **Surface Elevation**: Defined primarily through pure white `#FFFFFF` pedestals juxtaposed onto the `#F7F8F7` mist canvas, bounded by hairline `#EBECE8` dividers.
- **Ambient Floor Shadow**: For floating collectible viewports or modal drawer sheets, elevation is rendered via a single, hyper-diffused ambient shadow: `0 12px 32px -8px rgba(41, 40, 39, 0.05)`.
- **Active Tactile Press**: When interacted with, elements do not pop outward; they yield softly downward with a minor micro-inset shift (`transform: scale(0.985)`), mimicking soft-density physical touch.

## Shapes

The form language balances tactile curvature with strict architectural order. Corner radiuses follow Level 1 (`0.25rem` / `4px` base; up to `0.75rem` / `12px` for large containers). 

Overly rounded, bubbly, or pill shapes are avoided to prevent toy-store connotations. Elements retain clean, planar edges with softly eased micro-corners, suggesting hand-cut architectural stone blocks and precision-molded elastomer.

## Components

- **Buttons**:
  - *Primary*: Background `#292827`, text `#FFFFFF`, 4px corner radius, zero border. Hover shifts smoothly to `#B84F60` over 250ms ease.
  - *Secondary / Architectural*: Background `#FFFFFF`, text `#292827`, border 1px solid `#EBECE8`.
  - *Micro-Tactile Interaction*: Active state depresses gently (`transform: scale(0.985)`) with an immediate physical release.
- **Collectible Display Cards**:
  - Crisp `#FFFFFF` backgrounds floating on `#F7F8F7`. 1px perimeter border `#EBECE8`. Generous interior padding (`space-lg`). Images showcase the objects on matte neutral pedestals with ambient studio lighting.
- **Chips & Edition Badges**:
  - 4px radius, monochromatic border `#EBECE8`, background `#F7F8F7`. Typography set in uppercase `label-sm` Space Grotesk. Rare editions feature a hairline left border in `#B84F60`.
- **Form Controls & Inputs**:
  - Inset minimal fields with `#FFFFFF` background, `#292827` text, and subtle `#EBECE8` perimeter. Focus states shift border to `#292827` without colored outer glow rings.
- **Checkboxes & Radios**:
  - 16px geometric squares/circles with 1px `#EBECE8` border. Checked state transitions cleanly to `#292827` fill with mist white glyphs.
- **Curated Room Shelf (Custom Component)**:
  - An asymmetric horizontal layout presenting squishy objects alongside technical metadata (Shore durometer hardness rating, batch number, production mold date, volume in cc).