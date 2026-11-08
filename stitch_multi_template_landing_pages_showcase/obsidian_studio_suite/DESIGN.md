---
name: Obsidian Studio Suite
colors:
  surface: '#121317'
  surface-dim: '#121317'
  surface-bright: '#38393e'
  surface-container-lowest: '#0d0e12'
  surface-container-low: '#1a1b20'
  surface-container: '#1f1f24'
  surface-container-high: '#292a2e'
  surface-container-highest: '#343439'
  on-surface: '#e3e2e8'
  on-surface-variant: '#e5bdc0'
  inverse-surface: '#e3e2e8'
  inverse-on-surface: '#2f3035'
  outline: '#ac888b'
  outline-variant: '#5c3f42'
  surface-tint: '#ffb2ba'
  primary: '#ffb2ba'
  on-primary: '#670020'
  primary-container: '#ff4f73'
  on-primary-container: '#5a001b'
  inverse-primary: '#bd0042'
  secondary: '#d0bcff'
  on-secondary: '#3c0091'
  secondary-container: '#571bc1'
  on-secondary-container: '#c4abff'
  tertiary: '#4edea3'
  on-tertiary: '#003824'
  tertiary-container: '#00a572'
  on-tertiary-container: '#00311f'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffd9dc'
  primary-fixed-dim: '#ffb2ba'
  on-primary-fixed: '#400011'
  on-primary-fixed-variant: '#910030'
  secondary-fixed: '#e9ddff'
  secondary-fixed-dim: '#d0bcff'
  on-secondary-fixed: '#23005c'
  on-secondary-fixed-variant: '#5516be'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#121317'
  on-background: '#e3e2e8'
  surface-variant: '#343439'
typography:
  display-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 38px
    fontWeight: '800'
    lineHeight: 44px
    letterSpacing: -0.025em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.015em
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
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.06em
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
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
  space-2xl: 4rem
  space-3xl: 6rem
---

## Brand & Style

This design system establishes a premium, high-octane dark-mode aesthetic engineered for high-converting creator economy toolkits. It fuses refined modern minimalism with controlled cyber-luminescence: deep obsidian foundational canvases, tactile glassmorphism, precise 1px specular micro-borders, and targeted gradient glows that amplify purchase intent.

The aesthetic targets ambitious digital creators, influencers, and digital solopreneurs who demand tools that feel both elite and revenue-generating. The UI invokes authority, urgency, and high production value. While each specialized landing page commands its own distinct chromatic personality (Viral Crimson, Pro Amber, Executive Royal Purple, or Fintech Emerald), they are unified under an uncompromising suite architecture characterized by sharp micro-details, ultra-legible typography, and luminous focal states.

## Colors

The color system is architected around an obsidian core (`#0B0C10` and `#12131A`), ensuring absolute chromatic depth without crushing contrast. Rather than pure grayscale, neutrals carry a 2% cold indigo undertone to absorb and complement luminous foreground accents.

The system supports four dedicated product themes through semantic token remapping:
- **Suite Primary (Hooks & FOMO):** Crimson Coral (`#FF3366`) paired with Cyber Violet (`#A855F7`) for high-velocity conversion and urgency.
- **Suite Secondary (Brand Pitch & Rate Card):** Royal Purple (`#8B5CF6`) transitioning into Deep Indigo (`#6366F1`) to convey executive luxury and prestige.
- **Suite Tertiary (Cuan Spreadsheet):** Emerald Fintech (`#10B981`) accented with Electric Cyan (`#06B6D4`) for financial precision and growth metrics.
- **Suite Editorial (Bio Audit Pro):** Warm Amber (`#F59E0B`) with burnished Gold (`#D97706`) anchored over deep Slate (`#18181B`) for authoritative diagnostic tools.

Text tokens prioritize high contrast: Headings are pure `#FFFFFF` (100% luminance), body copy sits at `#94A3B8` (70% luminance), and secondary supporting details at `#64748B`.

## Typography

The typographic hierarchy pairs the geometric, forward-leaning presence of Plus Jakarta Sans for headlines and interactive anchors with the surgical legibility of Inter for continuous reading and data presentation. 

Headlines utilize negative tracking (`-0.01em` to `-0.03em`) and tight line heights to maintain visual density on marketing hero headers. Body text relies on Inter’s neutral, highly legible glyph construction to prevent eye fatigue against dark backgrounds. Labels and pill badges use Plus Jakarta Sans in all-caps or small title-casing with positive tracking (`0.02em` to `0.06em`) to preserve crisp optical legibility at small scale.

## Layout & Spacing

The layout is built upon a 12-column fluid grid system pinned to a maximum content width of 1280px, flanked by adaptive horizontal safe margins. 

- **Desktop (>= 1024px):** 12 columns with `1.5rem` gutters and minimum `2rem` outer canvas padding. Section gaps expand to `space-3xl` (`6rem`) to let high-impact product mockups breathe.
- **Tablet (768px - 1023px):** 8 columns with `1.25rem` gutters and `1.5rem` margins. Complex pricing cards collapse from 4-column decks to 2x2 grids.
- **Mobile (< 768px):** 4 columns with `1rem` gutters and `1rem` outer canvas margin. Multi-column feature grids stack vertically into single-column flows.

Vertical cadence follows strict multiples of `0.5rem` (8px base). Layouts leverage generous vertical section intervals (`space-2xl` to `space-3xl`) to establish high-drama separation between offer hooks, proof galleries, checklist modules, and conversion footers.

## Elevation & Depth

Visual hierarchy is constructed through stacked surface-container luminosity, glassmorphic backdrop filters, and radial ambient light leaks rather than muddy opaque drop shadows:

- **Surface Floor (`base`):** Solid `#0B0C10`. Absolute canvas backdrop.
- **Surface Layer 1 (`surface-raised`):** Semi-transparent `#12131A` at 80% opacity with `16px` backdrop-filter blur and a `1px` top specular border (`rgba(255, 255, 255, 0.08)`).
- **Surface Layer 2 (`surface-overlay` / Glass Cards):** `#1E202B` at 60% opacity with `24px` backdrop-filter blur, nested inside a dual border: an outer `1px` stroke at `rgba(255, 255, 255, 0.1)` and an inner directional highlight.
- **Luminous Accent Glows:** Key CTA zones and feature hero items cast non-directional, colored Gaussian blooms (`blur(60px)` to `blur(120px)`) at 15–25% opacity beneath surfaces, using the respective page theme color (e.g., `#FF3366` for hooks, `#10B981` for the cuan calculator).

## Shapes

The design system employs a refined rounded shape language (`roundedness: 2`). Standard functional components—such as cards, panels, inputs, and preview modules—feature `0.5rem` (8px) corner radii, scaling to `1rem` (16px) for major product showcase containers and `1.5rem` (24px) for full-width highlight wrappers.

Interactive call-to-action buttons, status chips, and promotional category pills intentionally override to full-pill circular geometry (`9999px`) to create an ergonomic, fluid contrast against structured rectangular data grids and split-panel layouts.

## Components

### Buttons & High-Converting CTAs
- **Primary Action CTA:** Full-pill geometry (`rounded-full`), generous padding (`1rem 2rem`), bold label typography (`label-lg`). Styled with high-contrast vibrant gradients matching the landing page theme (e.g., `#FF3366` to `#FF5E8A` for Reels Hook; `#10B981` to `#06B6D4` for Spreadsheet). Accompanied by a 20% opacity matching drop-shadow bloom (`0 10px 30px -5px [theme-color]`). Hover state translates `-2px` on the Y-axis with a 1.02x subtle scale.
- **Secondary / Ghost CTA:** Full-pill with 1px border (`rgba(255, 255, 255, 0.15)`), filled with subtle translucent obsidian (`rgba(255, 255, 255, 0.03)`). Hover transitions border color to active theme accent.

### Badge Pills & Value Tags
- Height fixed at `28px` or `32px` with full-pill radius.
- Background uses 10% theme accent tint paired with a crisp `1px` translucent border of the same hue at 30% opacity. Text rendered in theme color using `label-md` uppercase with `0.04em` tracking. Ideal for FOMO alerts ("🔥 84 Tersisa", "Pro Verified", "Instant Download").

### Glassmorphic Product & Feature Cards
- Constructed with `surface-overlay` token: 60% opacity dark background, `24px` backdrop-blur, `1rem` corner rounding, and `1px` border stroke. 
- Top-level tier cards (such as rate card previews or spreadsheet summary outputs) feature an ambient accent gradient rim that brightens on hover.

### Audit Checklists & Feature Rows
- Clean horizontal rows with `0.75rem` vertical spacing, separated by faint divider lines (`rgba(255, 255, 255, 0.05)`).
- Custom check states: Circular indicator (`20px`) with theme accent stroke and semi-transparent fill containing a crisp white vector checkmark.

### Input Fields & Calculator Cells
- Dark charcoal base (`#161722`) with `0.5rem` radius and `1px` border (`rgba(255, 255, 255, 0.1)`).
- Focus states eliminate standard browser outlines, deploying a sharp `1px` theme-colored border with an ambient `0 0 12px` accent ring. Number values rendered in monospace or bold tabular Plus Jakarta Sans.

### Interactive Rate & Pricing Tiers
- Distinct highlight states for recommended packages with an elevated glowing gradient header pill ("Paling Laris" / "Recommended").
- Metric indicators display bold currency outputs with stacked small-caps subtext to ensure instant scanability.