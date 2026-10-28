---
name: Luminescent Atelier
colors:
  surface: '#fbf9f6'
  surface-dim: '#dbdad7'
  surface-bright: '#fbf9f6'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f0'
  surface-container: '#efeeeb'
  surface-container-high: '#eae8e5'
  surface-container-highest: '#e4e2df'
  on-surface: '#1b1c1a'
  on-surface-variant: '#4e4639'
  inverse-surface: '#30312f'
  inverse-on-surface: '#f2f0ed'
  outline: '#7f7667'
  outline-variant: '#d1c5b4'
  surface-tint: '#775a19'
  primary: '#775a19'
  on-primary: '#ffffff'
  primary-container: '#c5a059'
  on-primary-container: '#4e3700'
  inverse-primary: '#e9c176'
  secondary: '#5f5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2dfde'
  on-secondary-container: '#636262'
  tertiary: '#466557'
  on-tertiary: '#ffffff'
  tertiary-container: '#8cad9d'
  on-tertiary-container: '#234134'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdea5'
  primary-fixed-dim: '#e9c176'
  on-primary-fixed: '#261900'
  on-primary-fixed-variant: '#5d4201'
  secondary-fixed: '#e5e2e1'
  secondary-fixed-dim: '#c8c6c5'
  on-secondary-fixed: '#1c1b1b'
  on-secondary-fixed-variant: '#474746'
  tertiary-fixed: '#c8ead8'
  tertiary-fixed-dim: '#adcebd'
  on-tertiary-fixed: '#012116'
  on-tertiary-fixed-variant: '#2f4d40'
  background: '#fbf9f6'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2df'
  champagne-light: '#E8D7AA'
  champagne-pure: '#D4AF37'
  cream-surface: '#F5F0EB'
  onyx-muted: '#2C2C2C'
  emerald-sage: '#2D4B3E'
  hairline-border: '#E5DFD7'
typography:
  display-hero:
    fontFamily: Playfair Display
    fontSize: 56px
    fontWeight: '400'
    lineHeight: 64px
    letterSpacing: -0.02em
  display-hero-mobile:
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
  subhead-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
    letterSpacing: 0.01em
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
  label-caps:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.15em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.02em
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
  space-lg: 1.75rem
  space-xl: 3rem
---

## Brand & Style

The design system projects quiet luxury, conscious permanence, and scientific brilliance. Designed for an audience seeking sustainable high-jewelry without aesthetic compromise, the visual language balances the artisanal romance of classic fine jewelry with the architectural precision of lab-grown gemological engineering.

The style unifies **Editorial Minimalism** with **Warm Tactile Luxury**. Generous negative space, restrained champagne metallic nuances, and disciplined typography invoke the calm reverence of a private salon appointment. Surfaces evoke fine textured stationery and polished gemstone facets rather than generic digital interfaces. The emotional response is serene, highly curated, and unmistakably premium.

## Colors

The palette is rooted in soft alabaster neutrals, midnight carbon contrasts, and tempered champagne golds.

- **Primary (`#C5A059`)**: Muted champagne gold serving as the refined focal accent, interactive affordance, and fine jewelry marker.
- **Secondary (`#1A1A1A`)**: Deep midnight charcoal/onyx providing high-contrast textual grounding and graphic structure without the stark harshness of pure black.
- **Tertiary (`#2D4B3E`)**: Deep emerald sage, used intentionally for ethical/sustainability callouts, certified diamond specs, and limited seasonal focal points.
- **Neutral (`#FAF8F5`)**: Warm alabaster canvas that removes clinical coolness and envelops product imagery in soft editorial warmth.

### Role Intent & Hierarchy
Never use pure digital black (`#000000`) or optical white (`#FFFFFF`) for foundational surfaces. Surfaces grade gradually from alabaster (`#FAF8F5`) down to soft cream (`#F5F0EB`) for tiered containers. Hairline divider tokens (`#E5DFD7`) must maintain a subtle 1px definition to emulate hot-pressed paper edges.

## Typography

The type system pairs the high-fashion, high-contrast serif **Playfair Display** for headline display tiers with the ultra-clean, humanist geometry of **Plus Jakarta Sans** for body and technical gemological data.

- **Editorial Titles**: Headlines prioritize regular and medium weights (`400`, `500`) to evoke classic luxury publications rather than loud, bold modernism. 
- **Data & Gemstone Metrics**: Body text uses `Plus Jakarta Sans` for legibility across carats, cut grades, clarity specifications, and pricing.
- **Letter Spacing**: Extended letter spacing (`0.15em`) is strictly reserved for `label-caps` (eyebrow headers, certification marks, and luxury badges) to establish poise and cadence.

## Layout & Spacing

The layout is constructed around an editorial 12-column grid on desktop and a 4-column system on mobile devices.

- **Rhythm & Breathing Room**: Negative space serves as a primary luxury material. Product showcases utilize generous outer canvas margins (`margin-desktop: 4rem`) to allow standalone pieces to float calmly.
- **Grid Discipline**:
  - **Desktop (≥ 1024px)**: 12-column fluid grid, 40px gutters, max-width bounded at 1440px for editorial catalog integrity.
  - **Tablet (768px - 1023px)**: 8-column fluid grid, 24px gutters, 32px canvas margins.
  - **Mobile (< 768px)**: 4-column fluid grid, 16px gutters, 20px canvas margins. Full-bleed horizontal swipe containers allowed for ring and pendant discovery galleries.
- **Reflow Rule**: Editorial banners and split product detail layouts collapse cleanly to single-column stacking with staggered image-then-spec pacing.

## Elevation & Depth

Visual hierarchy is communicated through **ambient diffuse shadows**, **subtle hairline boundaries**, and **tonal paper layering**, rejecting harsh drop shadows.

- **Surface Layering**: The primary canvas rests on warm alabaster (`#FAF8F5`). Cards and showcase modules rest upon soft cream (`#F5F0EB`) or pristine white elevated planes with 1px hairline perimeter borders (`#E5DFD7`).
- **Ambient Shadow Character**: When elevation is required for floating navigation, quick-view modals, or cart sidebars, shadows use an expansive blur with warm golden-charcoal tinting:
  - *Resting Card Elevation*: `0 2px 12px -2px rgba(26, 26, 26, 0.03), 0 0 1px 0 rgba(197, 160, 89, 0.25)`
  - *Floating Layer Elevation*: `0 16px 40px -8px rgba(26, 26, 26, 0.07), 0 1px 2px 0 rgba(26, 26, 26, 0.04)`
- **Luster Effects**: Diamond highlights leverage crisp hairline outlines rather than heavy inner bevels, preserving a sleek, modern architectural aesthetic.

## Shapes

The design language favors architectural precision with soft, tailored finishes. A micro-radius of `0.25rem` (`roundedness: 1`) is applied uniformly across cards, form inputs, and interactive surfaces.

Sharp structural geometry reflects diamond cuts (emerald, princess, and radiant cuts), while slight corner softening prevents the layout from feeling severe. Distinctively, tags and luxury certification badges utilize a pill-like shape or neat rectangular cut to differentiate gem metadata from structural commerce elements.

## Components

### Buttons
- **Primary Action (Atelier Button)**: Midnight charcoal background (`#1A1A1A`), warm cream text (`#FAF8F5`), 1px solid border (`#1A1A1A`), `roundedness: 1`. Padding: 14px 28px. Font: `label-caps`. Hover transitions smoothly into champagne gold (`#C5A059`) with matching border.
- **Secondary Action (Prestige Outline)**: Transparent background, midnight charcoal text (`#1A1A1A`), crisp 1px hairline border (`#C5A059`). Hover shifts to subtle cream wash (`#F5F0EB`).
- **Tertiary / Editorial Link**: Playfair serif or uppercase sans link with a thin animated underline spaced 4px beneath the text baseline.

### Badges & Tags
- **Luxury Metal & Cut Tags**: High-polish luxury tags (`11px`, `label-caps`) with 0.5rem padding, bordered in hairline champagne gold (`#E5DFD7`). Background utilizes subtle champagne wash (`rgba(197, 160, 89, 0.08)`) with text set in `#1A1A1A`.
- **Sustainability & Lab-Grown Authenticity Tag**: Tertiary emerald sage (`#2D4B3E`) background, crisp alabaster text (`#FAF8F5`), celebrating ethical craftsmanship.

### Cards (Jewelry & Collection Showcase)
- **Structure**: Flat cream background (`#F5F0EB`) surrounded by a 1px border (`#E5DFD7`). Corner radius: 4px (`roundedness: 1`).
- **Product Imagery**: Centered within a generous padding envelope with soft alabaster backdrops. Hover state smoothly reveals carat spec overlay or alternate model perspective via a 300ms cross-fade.
- **Detail Lockup**: Title rendered in `headline-sm`, subtitle/metal purity in `label-caps` muted onyx, and price positioned cleanly in `body-md` bold.

### Form Inputs & Selectors
- **Text Inputs**: Minimalist framing with 1px border (`#E5DFD7`), soft alabaster fill (`#FAF8F5`), and dark charcoal label positioned above. On active focus, the border shifts to champagne gold (`#C5A059`) without browser-native outer rings.
- **Ring Size & Carat Selectors**: Pill or tailored squared toggles with delicate numerals. Active selection marked by midnight onyx fill and alabaster text.

### Selection Controls (Checkboxes & Radios)
- Custom square or circular controls featuring thin 1px `#C5A059` framing. Checked state displays a solid inner dot or minimalist gold tick against a deep onyx background.