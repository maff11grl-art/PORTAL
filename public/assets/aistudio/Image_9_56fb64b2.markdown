---
name: PortalHouse Design System
colors:
  surface: '#f9f9f7'
  surface-dim: '#dadad8'
  surface-bright: '#f9f9f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f4f4f2'
  surface-container: '#eeeeec'
  surface-container-high: '#e8e8e6'
  surface-container-highest: '#e2e3e1'
  on-surface: '#1a1c1b'
  on-surface-variant: '#44474a'
  inverse-surface: '#2f3130'
  inverse-on-surface: '#f1f1ef'
  outline: '#75777a'
  outline-variant: '#c5c6c9'
  surface-tint: '#5e5e5f'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#1b1c1d'
  on-primary-container: '#848485'
  inverse-primary: '#c7c6c7'
  secondary: '#78592d'
  on-secondary: '#ffffff'
  secondary-container: '#fed39c'
  on-secondary-container: '#79592d'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#1c1c18'
  on-tertiary-container: '#86847e'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#e3e2e3'
  primary-fixed-dim: '#c7c6c7'
  on-primary-fixed: '#1b1c1d'
  on-primary-fixed-variant: '#464748'
  secondary-fixed: '#ffddb4'
  secondary-fixed-dim: '#e9c08a'
  on-secondary-fixed: '#291800'
  on-secondary-fixed-variant: '#5e4117'
  tertiary-fixed: '#e6e2dc'
  tertiary-fixed-dim: '#c9c6c0'
  on-tertiary-fixed: '#1c1c18'
  on-tertiary-fixed-variant: '#484742'
  background: '#f9f9f7'
  on-background: '#1a1c1b'
  surface-variant: '#e2e3e1'
typography:
  display:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '400'
    lineHeight: 44px
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '400'
    lineHeight: 36px
    letterSpacing: 0em
  headline-md:
    fontFamily: Playfair Display
    fontSize: 28px
    fontWeight: '500'
    lineHeight: 36px
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 22px
    fontWeight: '500'
    lineHeight: 30px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.06em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 10px
    fontWeight: '600'
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
  gutter-lg: 2.5rem
  margin: 1.25rem
  margin-md: 2.5rem
  margin-lg: 4rem
  space-xs: 0.375rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 2rem
  space-xl: 3.5rem
---

## Brand & Style

The visual identity embodies understated architectural luxury, tranquil refinement, and modern clarity. It serves an affluent global clientele, high-end developers, and discerning architectural enthusiasts who value spatial generosity over loud ornamentation. The emotional response is one of composed authority, serenity, and curated elegance.

The aesthetic philosophy fuses warm European architectural minimalism with subtle editorial craftsmanship:
- **Spatial Expanse:** Generous breathing room across layouts, treating whitespace as an active luxury material.
- **Materiality & Restraint:** Tactile warmth conveyed through alabaster, stone, and delicate brushed bronze, avoiding synthetic saturation.
- **Architectural Precision:** Razor-thin micro-borders (1px), subtle tonal backdrops, and measured typography create a gallery-grade canvas that lets high-fidelity architectural imagery lead.

## Colors

The palette draws directly from classic mineral finishes, honed limestone, and brushed bronze metals:

- **Primary (`#121314` / `#1A1A1A`):** Deep carbon black. Used for high-contrast primary typography, key iconography, and anchor elements. Never pure `#000000`.
- **Secondary (`#B38E5D` / `#C5A880` / `#8C6D41`):** Brushed bronze and refined warm gold. Applied sparingly to highlight signature badges, micro-accents, active states, and editorial highlights.
- **Tertiary & Muted (`#7C7A75`):** Muted stone gray for secondary metadata, property specs, captions, and deactivated controls.
- **Surfaces & Grounds:**
  - Base canvas: Warm white (`#FAFAF8`).
  - Elevated containers & card backgrounds: Soft alabaster (`#F4F3F0`).
  - Dividers & structural micro-borders: Fine stone gray (`#E5E3DE`).
- **Translucent Surfaces:** Dynamic glass backdrops leverage `rgba(250, 250, 248, 0.75)` over high-resolution imagery with subtle light scatter.

## Typography

The type scale balances editorial distinction with clean structural legibility:

- **Headlines (Playfair Display):** Conveys heritage, architectural provenance, and curatorial care. Used exclusively for marquee headlines, property titles, and editorial section leads. Maintains relaxed line heights to honor the serif's natural ascenders and descenders.
- **Body & Functional UI (Plus Jakarta Sans):** Modern geometric sans-serif that ensures effortless scan-ability for numeric specs, architectural floor plans, pricing tiers, and form inputs.
- **Uppercase Labels:** Small labels (`label-md`, `label-sm`) leverage extended letter-spacing (`0.06em` to `0.08em`) and uppercase transformation for architectural metadata (e.g., "PENTHOUSE", "ESTATE", "SQ FT").

## Layout & Spacing

Layouts follow an intentional, airy spatial rhythm grounded on an 8pt base grid with a 12-column responsive layout:

- **Desktop (1200px+):** Max layout container capped at 1440px with `margin-lg` (4rem) and `gutter-lg` (2.5rem). Allows properties to sit within wide gallery viewports without edge cramping.
- **Tablet (768px - 1199px):** 8-column layout with `margin-md` (2.5rem) and standard `gutter` (1.5rem). Split listing grids transition to 2-column modules.
- **Mobile (< 768px):** 4-column layout with `margin` (1.25rem) and `gutter` (1rem). Dense specifications collapse into clean vertical accordions.
- **Rhythm:** Section-level separation relies heavily on `space-xl` (3.5rem to 5rem) rather than heavy background fills, preserving an uncluttered environment.

## Elevation & Depth

Visual hierarchy emphasizes surface honesty and featherweight dimensional cues rather than heavy drop shadows:

- **Tonal Layers:** Base canvas is Warm White (`#FAFAF8`). Secondary grouping containers (filters, property feature matrices) rely on Soft Alabaster (`#F4F3F0`) or 1px structural micro-borders (`#E5E3DE`).
- **Glassmorphism Backdrops:** Sticky navigation bars, floating quick-search pods, and image overlay tags use `rgba(250, 250, 248, 0.78)` paired with `backdrop-filter: blur(16px)` and an inner 1px border of `rgba(255, 255, 255, 0.6)`.
- **Ambient Shadows:** Reserved strictly for floating actionable surfaces (e.g., elevated modal sheets, active search dropdowns, hovered property cards). Shadows are ultra-diffused: `0 16px 40px -12px rgba(18, 19, 20, 0.05), 0 2px 6px -1px rgba(18, 19, 20, 0.02)`.

## Shapes

The design system employs a soft, architectural geometry (Scale `1` - Soft):

- **Core Elements:** Inputs, cards, and modal sheets use a controlled `0.25rem` (4px) to `0.5rem` (8px) radius. This echoes squared stone and structural masonry rather than playful consumer curves.
- **Floating Tags & Badges:** Use subtle corner softeners (4px) rather than full capsule pills to preserve an architectural silhouette.
- **Media Containers:** Property imagery frames maintain sharp, crisp corners or subtle 4px corner radii with zero shadow bleed.

## Components

### Buttons
- **Primary:** Solid Carbon Black (`#121314`) fill, warm white typography, 1px border of `#121314`. Hover transitions gently to `#1A1A1A` with a subtle elevation shift.
- **Secondary (Brushed Accent):** Soft Alabaster (`#F4F3F0`) surface with 1px border of `#B38E5D` and bronze text (`#8C6D41`). Hover deepens the border to `#8C6D41` with a tinted gold background overlay (`rgba(179, 142, 93, 0.06)`).
- **Ghost/Tertiary:** No background, 1px micro-border (`#E5E3DE`), text `#121314`. Hover applies a `#F4F3F0` wash.

### Cards (Property & Editorial)
- **Base:** Flat surface in Soft Alabaster (`#F4F3F0`) or pure Warm White (`#FAFAF8`) with a continuous 1px micro-border (`#E5E3DE`).
- **Interaction:** Hover lifts the card 2px upward, replacing the border tone with `#B38E5D` (soft bronze) and introducing a whisper-light ambient blur shadow (`0 20px 35px -10px rgba(18, 19, 20, 0.06)`).
- **Image Treatment:** 4:3 or 16:9 aspect ratios with integrated bronze/glass metadata badges anchored top-left.

### Input Fields & Search Bars
- **Text Inputs:** Background in Warm White (`#FAFAF8`) framed by a 1px border (`#E5E3DE`). Focused state shifts border to Carbon Black (`#121314`) or Soft Bronze (`#B38E5D`) without harsh outline rings.
- **Hero Search Pod:** A continuous glassmorphic unit (`rgba(250, 250, 248, 0.85)`) housing segmented location, price range, and property archetype pickers separated by vertical 1px `#E5E3DE` divider lines.

### Chips & Badges
- **Status Badges (e.g., "EXCLUSIVE", "UNDER CONTRACT"):** Warm alabaster background, 1px `#E5E3DE` border, uppercase `label-sm` tracking with subtle bronze text (`#8C6D41`).
- **Filter Chips:** Unselected chips feature `#FAFAF8` background with `#E5E3DE` micro-border. Selected chips invert to solid Carbon Black (`#121314`) with white typography.

### Form Controls (Checkboxes & Radios)
- **Checkboxes & Radios:** Minimal 18px frames with 1px `#7C7A75` outline. When checked, filled with Carbon Black (`#121314`) or Brushed Bronze (`#B38E5D`) containing an optical white tick.

### Lists & Specifications Matrix
- Key listing metrics (beds, baths, square footage, lot size) are arranged in an open horizontal rule system bordered top and bottom with 1px `#E5E3DE`, using `Plus Jakarta Sans` medium weights and stone gray (`#7C7A75`) metadata keys.