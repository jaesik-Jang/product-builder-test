---
name: Atelier Minimal Luxury
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f1eee7'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#4d4541'
  inverse-surface: '#31302d'
  inverse-on-surface: '#f3f0ea'
  outline: '#7f7570'
  outline-variant: '#d0c4be'
  surface-tint: '#635d5a'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1f1b19'
  on-primary-container: '#8a827f'
  inverse-primary: '#cdc5c1'
  secondary: '#78583a'
  on-secondary: '#ffffff'
  secondary-container: '#fed2ac'
  on-secondary-container: '#79593a'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b0900'
  on-tertiary-container: '#c8694e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#eae1dd'
  primary-fixed-dim: '#cdc5c1'
  on-primary-fixed: '#1f1b19'
  on-primary-fixed-variant: '#4b4643'
  secondary-fixed: '#ffdcbf'
  secondary-fixed-dim: '#e9bf99'
  on-secondary-fixed: '#2c1601'
  on-secondary-fixed-variant: '#5e4124'
  tertiary-fixed: '#ffdbd1'
  tertiary-fixed-dim: '#ffb5a0'
  on-tertiary-fixed: '#3b0900'
  on-tertiary-fixed-variant: '#7a2f18'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 44px
    fontWeight: '400'
    lineHeight: 52px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 34px
    fontWeight: '400'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 26px
    fontWeight: '500'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 28px
  headline-sm:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.01em
  title-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '500'
    lineHeight: 22px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-lg:
    fontFamily: Hanken Grotesk
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.08em
  label-md:
    fontFamily: Hanken Grotesk
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.1em
  label-sm:
    fontFamily: Hanken Grotesk
    fontSize: 10px
    fontWeight: '600'
    lineHeight: 12px
    letterSpacing: 0.12em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-mobile: 0.75rem
  margin: 1.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system embodies the quiet luxury and curated precision of high-end editorial fashion houses like SSENSE, Zara Atelier, and Vogue. Tailored for personal styling and AI wardrobe curation, the interface projects authoritative elegance, bespoke curation, and calming simplicity.

### Key Tenets
- **Editorial Poise:** High-contrast typographic hierarchy paired with vast, intentional whitespace reminiscent of bespoke fashion print spreads.
- **Warm Minimalist Tactility:** Moving away from cold clinical tech minimalism toward warm tactile neutrals—natural linens, muted ecru, and rich espresso.
- **Curatorial Restraint:** UI controls retreat to the perimeter, allowing photography, silhouettes, and textile textures to lead visual attention. Micro-interactions are featherweight and deliberate.

## Colors

The palette is anchored in warm organic neutrals that flatter garment imagery and evoke quiet sophistication.

- **Primary (`#1B1715` - Deep Espresso Noir):** Dominant for structural typography, crisp icons, primary button fills, and key framing lines.
- **Secondary (`#C29B78` - Champagne Gilded Ochre):** Used sparingly for AI highlights, curated badges, active filter tabs, and bespoke recommendations.
- **Tertiary (`#B85D43` - Burnt Terracotta):** Reserved for contextual alerts, wishlisting, seasonal collections, and vibrant editorial accents.
- **Neutral Surface Baseline (`#EFECE6` - Soft Oat/Ivory):** The primary canvas hue providing an unbleached parchment warmth. Layered with pristine white (`#FFFFFF`) for elevated card surfaces and warm graphite (`#4A443F`) for muted subtext.

## Typography

The type system creates an immediate editorial dialogue between classical high-fashion serif titles and modern, razor-sharp grotesque sans-serifs.

- **Headlines & Feature Display (`Bodoni Moda`):** Delivers dramatic editorial gravity with extreme stroke contrast. Titles remain sentence-case or title-case to maintain effortless poise without screaming.
- **Body & Information Architecture (`Hanken Grotesk`):** Clean, proportioned, and exceptionally legible in dense apparel specification cards, material tags, and AI reasoning dialogues.
- **Labels & Overlines:** Rendered in small caps with wide letter-spacing (`0.08em` to `0.12em`) to mirror archival luxury catalog index markers.

## Layout & Spacing

The layout model pairs a mobile-first fluid grid with strict editorial pacing.

- **Mobile Viewport (up to 480px):** 4-column fluid layout with `1.25rem` screen margins and `0.75rem` gutters. Vertical rhythm relies on asymmetrical breaks—tight spacing between titles and image carousels (`space-sm`), contrasted with luxurious breathing room (`space-xl`) between distinct outfit clusters.
- **Tablet & Compact Desktop (481px to 1024px):** 8-column layout with `1.5rem` margins and `1rem` gutters. Wardrobe moodboards expand into asymmetric two-page lookbook spreads.
- **Wide Screens (1025px+):** Max-width containment at `1200px` centered, utilizing a 12-column structure with generous side breathing space to maintain the feel of an oversized art book.

## Elevation & Depth

Visual hierarchy rejects heavy, artificial drop shadows in favor of tonal layering, soft surface warmth, and gossamer-thin framing.

- **Tonal Stepping:** Depth is achieved by placing pure white or warm ecru cards over the soft oat background canvas. AI-analyzed garment layers sit on subtle ivory tiles (`#F7F5F0`).
- **Low-Contrast Hairlines:** Elevated sections, dividers, and card borders employ faint, semi-transparent warm graphite strokes (`rgba(74, 68, 63, 0.12)`).
- **Subtle Ambient Diffusion:** When an overlay or bottom sheet is elevated above the wardrobe canvas, apply an ultra-diffused shadow with a warm espresso tint:
  - `box-shadow: 0 16px 40px -8px rgba(27, 23, 21, 0.08);`
- **Backdrop Diffusion:** Modal backdrops and bottom navigation bars use gentle frosted blur (`backdrop-filter: blur(16px); background: rgba(239, 236, 230, 0.85);`) to keep ambient wardrobe colors visible beneath navigation controls.

## Shapes

The interface embraces an architectural, slightly softened contouring (`roundedness: 1`).

- **Base Radius (`0.25rem`):** Applied to secondary badges, subtle interaction highlights, swatches, and small input fields. Preserves the disciplined, structured elegance of architectural forms.
- **Large Radius (`0.5rem` / `rounded-lg`):** Reserved for apparel gallery cards, floating AI curation drawers, and modal containers. Soft enough to feel inviting, yet crisp enough to avoid juvenile pill aesthetics.
- **Pill Exceptions:** Used strictly for interactive tags/chips and floating contextual action capsules (e.g., "Ask Stylist") where hand-held touch targets require organic distinctiveness.

## Components

### Buttons
- **Primary:** Solid Deep Espresso (`#1B1715`) with crisp Ivory text (`#FFFFFF`), `0.25rem` radius, and uppercase/tracked label styling (`label-lg`). Understated press-state scaling to 98%.
- **Secondary:** Ghost/transparent background with a 1px border in Espresso (`#1B1715`) or warm graphite hairline, holding crisp label text.
- **AI Action / Stylist Suggestion:** Champagne Gilded Ochre (`#C29B78`) tint background with deep espresso text, signaling smart AI-generated wardrobe recommendations.

### Chips & Filter Tags
- Compact, pill-shaped tags (`height: 32px`) on a warm white or oat background with a `1px` stroke of `rgba(74, 68, 63, 0.18)`.
- Active state transitions smoothly to solid `#1B1715` with ivory text, accompanied by an optional small gold dot indicator.

### Product & Lookbook Cards
- Edge-to-edge photography with `3:4` or `4:5` vertical aspect ratios.
- Subtle inner border (`rgba(27, 23, 21, 0.06)`). Product info rests directly below with minimal distraction: designer/brand in `label-md`, garment name in `body-md`, and price or AI match percentage in `headline-sm`.
- Integrated subtle terracotta wishlist heart icon anchored top-right with low-opacity backdrop circle.

### Input Fields & Search
- Borderless or single bottom-hairline field with spacious vertical padding (`1rem`).
- Placeholder text in muted graphite italic or clean sans-serif. Focus state deepens the bottom rule to `#1B1715` without aggressive glows.

### Checkboxes & Selection Controls
- Unchecked: Fine `1px` border square or circle in warm graphite.
- Checked: Solid `#1B1715` fill featuring an understated custom champagne-toned checkmark or inner dot.

### Specialized AI Styling Modules
- **Wardrobe Match Capsule:** A segmented side-by-side juxtaposition layout showing the user's uploaded clothing item paired with 3 curated algorithmic companion pieces.
- **Palette Swatch Bar:** Horizontal row of minimal micro-rectangles representing the tonal breakdown of the curated ensemble, accompanied by confidence indicators.