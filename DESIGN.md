---
name: Canis & Co.
colors:
  surface: '#fcf9f3'
  surface-dim: '#dcdad4'
  surface-bright: '#fcf9f3'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3ed'
  surface-container: '#f0eee8'
  surface-container-high: '#ebe8e2'
  surface-container-highest: '#e5e2dc'
  on-surface: '#1c1c18'
  on-surface-variant: '#45483f'
  inverse-surface: '#31312d'
  inverse-on-surface: '#f3f0ea'
  outline: '#75786e'
  outline-variant: '#c5c8bb'
  surface-tint: '#54643f'
  primary: '#435330'
  on-primary: '#ffffff'
  primary-container: '#5b6b46'
  on-primary-container: '#d9ebbd'
  inverse-primary: '#bbcda0'
  secondary: '#8e4e00'
  on-secondary: '#ffffff'
  secondary-container: '#fda95a'
  on-secondary-container: '#723e00'
  tertiary: '#624830'
  on-tertiary: '#ffffff'
  tertiary-container: '#7c6046'
  on-tertiary-container: '#ffdec2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d7e9bb'
  primary-fixed-dim: '#bbcda0'
  on-primary-fixed: '#121f03'
  on-primary-fixed-variant: '#3c4b29'
  secondary-fixed: '#ffdcc1'
  secondary-fixed-dim: '#ffb778'
  on-secondary-fixed: '#2e1500'
  on-secondary-fixed-variant: '#6c3a00'
  tertiary-fixed: '#ffdcbf'
  tertiary-fixed-dim: '#e4c0a0'
  on-tertiary-fixed: '#2a1704'
  on-tertiary-fixed-variant: '#5b422a'
  background: '#fcf9f3'
  on-background: '#1c1c18'
  surface-variant: '#e5e2dc'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-xxl: 4rem
---

## Brand & Style
The design system establishes a warm, nurturing, and premium e-commerce environment dedicated to conscientious canine care. Balancing modern organic minimalism with tactile warmth, the aesthetic reflects wholesome ingredients, artisanal quality, and veterinary reassurance.

The visual direction rejects sterile pharmaceutical whites and neon pet-store tropes in favor of an inviting residential kitchen feel. Soft earth tones, gentle curvatures, and ample negative space foster peace of mind, positioning the product catalog as an essential part of a healthy, joyful life for companion animals.

## Colors
The palette evokes nature, nutritional integrity, and craftsmanship:

- **Primary (`#5B6B46` - Warm Olive):** Symbolizes vitality, botany, and dependable care. Used for core actions, hero interactive states, and brand trust elements.
- **Secondary (`#C87D32` - Roasted Amber/Caramel):** Adds warmth, energy, and appetite appeal. Applied selectively for key accents, badges, sale indicators, and conversion highlights.
- **Tertiary (`#7A5E44` - Toasted Bark):** Grounded and artisanal, supporting secondary narratives, subtle borders, and structural framing.
- **Neutral Surface (`#F9F6F0` - Soft Oat Cream):** Replaces harsh stark whites with a welcoming, cozy canvas that reduces eye strain and reinforces organic provenance.
- **Text & Contrast:** Deep forest umber (`#1F241A`) serves as the dominant high-contrast text color, paired with muted olive-slate (`#525B49`) for supporting meta labels.

## Typography
Plus Jakarta Sans serves as both display and running text face. Its geometric structure softened by open apertures and friendly curves reflects human-centered warmth while remaining highly legible in dense shopping environments.

Titles feature tight negative letter-spacing and confident weights (600/700) to anchor hierarchy. Body copy uses generous line heights (1.5x to 1.55x) to maintain a restful reading rhythm when presenting nutritional facts, feeding instructions, and ingredient stories.

## Layout & Spacing
The layout implements a responsive 12-column grid for desktop (max-width 1360px), reflowing to an 8-column structure on tablet devices, and a cohesive 4-column layout on mobile.

Spatial relationships rely on an 8pt base unit. Generous external padding and open spacing between product grids avoid cramped, transactional pressure. Breakpoint transformations collapse dense multi-column product specifications into comfortable stacked touch cards on screens under 768px.

## Elevation & Depth
Depth is created primarily through tonal layering and warm ambient shadows rather than harsh gray drop shadows.

- **Base Layer:** Natural `#F9F6F0` oat cream backdrop.
- **Surface Elevation 1 (Cards, Product Tiles):** Solid `#FFFFFF` or pale warm tint (`#FAF8F3`) lifted by an ambient shadow tinted with warm umber: `0 4px 20px -2px rgba(60, 50, 35, 0.06)`.
- **Surface Elevation 2 (Dropdowns, Floating Cart, Flyouts):** `0 10px 30px -4px rgba(60, 50, 35, 0.10)`.
- **Surface Elevation 3 (Modals & Overlays):** `0 20px 48px -8px rgba(35, 30, 20, 0.16)`.
- **Borders:** Low-contrast organic outlines (`rgba(91, 107, 70, 0.12)`) demarcate boundaries softly without visual clutter.

## Shapes
Roundedness level `2` governs all interactive and structural containers:
- Standard controls, inputs, and small badges apply `0.5rem` (8px).
- Product cards, modular callout blocks, and filter panels use `rounded-lg` (`1rem` / 16px).
- Modals, prominent hero banners, and promotional cards leverage `rounded-xl` (`1.5rem` / 24px).
- Fully pill-shaped geometry (`rounded-full`) is reserved strictly for interactive tag chips, counter badges, and quick-add floating action triggers.

## Components

### Buttons
- **Primary:** Filled with warm olive `#5B6B46` and off-white text `#FDFDFB`. Generous horizontal padding (`space-lg`), medium font weight, `0.5rem` corner radius. Hover transitions to a deepened tone (`#4D5B3A`).
- **Secondary / Accent:** Filled with roasted caramel `#C87D32` with white text for decisive commercial actions like "Comprar ahora" or "Suscribirme".
- **Outlined / Tertiary:** 1.5px border in `#5B6B46` over a transparent or soft cream background, shifting to a 5% olive tint on hover.

### Product Cards
Set on elevated white surfaces with `1rem` corner rounding. Featuring full-bleed soft photography, organic ingredient badges in the top corner, prominent price and pack-size selectors, and a rounded warm olive quick-add button.

### Chips & Badges
- **Nutritional / Benefit Badges:** Pill-shaped, delicate neutral tint (`#EFECE4`) with deep olive text for attributes like "100% Grano Entero", "Libre de Crueldad", or "Veterinario Certificado".
- **Offer / Special Edition Badges:** Amber tone `#C87D32` with crisp off-white typography.

### Input Fields & Controls
- **Inputs:** Cream-tinted field interiors (`#F4F1EA`) framed with 1px border (`#DCD7CA`), transitioning to an olive halo (`#5B6B46`) on focus.
- **Checkboxes & Radios:** Softly rounded, filled with olive `#5B6B46` upon selection, designed with tactile scale shifts upon click.

### Dog Profile & Diet Selector (Specialized Component)
Interactive segment selector allowing pet owners to filter by pet weight, breed, and life stage. Styled as large, clickable rounded cards (`1rem` radius) with illustrative line iconography and warm ochre accents when toggled.