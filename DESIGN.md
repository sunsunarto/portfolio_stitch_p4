---
name: Executive Slate
colors:
  surface: '#f8f9ff'
  surface-dim: '#d0dbed'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dee9fc'
  surface-container-highest: '#d9e3f6'
  on-surface: '#121c2a'
  on-surface-variant: '#454652'
  inverse-surface: '#27313f'
  inverse-on-surface: '#eaf1ff'
  outline: '#767684'
  outline-variant: '#c6c5d4'
  surface-tint: '#4555b7'
  primary: '#1e3093'
  on-primary: '#ffffff'
  primary-container: '#3949ab'
  on-primary-container: '#bbc3ff'
  inverse-primary: '#bbc3ff'
  secondary: '#006398'
  on-secondary: '#ffffff'
  secondary-container: '#5bb8fe'
  on-secondary-container: '#00476e'
  tertiary: '#2b17b5'
  on-tertiary: '#ffffff'
  tertiary-container: '#443acb'
  on-tertiary-container: '#c3c0ff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dee0ff'
  primary-fixed-dim: '#bbc3ff'
  on-primary-fixed: '#000e5e'
  on-primary-fixed-variant: '#2c3c9e'
  secondary-fixed: '#cce5ff'
  secondary-fixed-dim: '#93ccff'
  on-secondary-fixed: '#001d31'
  on-secondary-fixed-variant: '#004b73'
  tertiary-fixed: '#e3dfff'
  tertiary-fixed-dim: '#c3c0ff'
  on-tertiary-fixed: '#100069'
  on-tertiary-fixed-variant: '#372abf'
  background: '#f8f9ff'
  on-background: '#121c2a'
  surface-variant: '#d9e3f6'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.025em
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 34px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.015em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.015em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
    letterSpacing: -0.01em
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: -0.005em
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  badge-caption:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
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
  margin: 3rem
  margin-mobile: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes an executive, modern, and curated aesthetic designed for professional portfolios, digital CVs, and technical dossiers. The visual tone balances authoritative competence with contemporary lightness, eliminating non-essential decoration to allow accomplishments, case studies, and career timelines to lead.

### Design Movement & Aesthetic Principles
The system adopts **Modern Structural Minimalism** characterized by:
- **Calm Atmosphere:** Soft, atmospheric background tints offset by crisp white surfaces to prevent optical fatigue while retaining structure.
- **Architectural Clarity:** Precision in micro-spacing, structured data alignments, and clean typographic hierarchies.
- **Controlled Density:** Balanced layout that supports both rapid executive scanning and deep-dive reading of case studies and credentials.

## Colors

The palette is anchored by a commanding indigo, paired with crisp whites and a subtle cool tint to establish clear separation between layout infrastructure and active content.

### Palette Architecture
- **Primary Indigo (`#3949AB`):** Denotes primary actions, active navigation anchors, key timeline markers, and institutional highlights.
- **Secondary Slate Blue (`#0284C7`):** Reserved for interactive secondary tags, verified badges, and supplemental metrics.
- **Background Canvas (`#E6F7FF`):** The tinted base canvas that frames foreground content.
- **Surface Crisp White (`#FFFFFF`):** High-priority cards, modal layers, floating headers, and input fields.
- **Dark Neutral (`#1F2937`):** Primary headings, role titles, and high-emphasis body text.
- **Muted Neutral (`#6B7280`):** Secondary metadata, dates, employer locations, captions, and structural borders.
- **Hairline Border (`rgba(31, 41, 55, 0.08)`): Used for card outlines and subtle dividers without introducing heavy visual boundaries.

## Typography

The type system is powered entirely by **Plus Jakarta Sans**, offering geometric precision balanced with friendly, open apertures. 

### Typographic Hierarchy Rules
- **Display & Headings:** Use tight negative letter-spacing (`-0.025em` to `-0.01em`) and weights of `600` or `700` to anchor sections such as portfolio case studies and executive summaries.
- **Body Text:** Set predominantly in regular (`400`) weight at `15px` (`body-md`) with relaxed leading (`24px`) to preserve reading flow across long career trajectories.
- **Badges & Labels:** Use medium (`500`) and semibold (`600`) styles with slight uppercase tracking (`0.02em` to `0.04em`) to establish visual separation between metadata and narrative copy.

## Layout & Spacing

The layout is built upon an adaptive 12-column responsive fluid grid anchored by strict content containment.

### Responsive Breakpoints & Structural Rules
- **Desktop (≥ 1024px):** Max container width of `1200px`, centered. 12 columns with `1.5rem` gutters and `3rem` side margins. Two-column splits are preferred (e.g., sticky bio/nav on the left 4 columns, interactive timeline and projects spanning the remaining 8 columns).
- **Tablet (768px - 1023px):** 8 columns with `1.25rem` gutters and `2rem` side margins. Multi-column blocks collapse into structured single-column panels.
- **Mobile (< 768px):** 4 columns with `1rem` gutters and `1.25rem` margins. All cards expand to full-width containers with zero horizontal floating drift.
- **Rhythm:** Vertical separation between macro-sections (e.g., Experience to Education) uses `space-xl` (`2.5rem`), while internal card components maintain rhythm using `space-md` (`1rem`) and `space-sm` (`0.5rem`).

## Elevation & Depth

To sustain a clean and contemporary portfolio interface, elevation relies on subtle surface isolation rather than dramatic drop shadows.

### Elevation Hierarchy
- **Level 0 (Canvas Base):** Background tint `#E6F7FF`. Completely flat.
- **Level 1 (Crisp Content Cards):** Crisp White (`#FFFFFF`) surface combined with a featherweight ambient shadow:
  - `box-shadow: 0 1px 3px rgba(31, 41, 55, 0.04), 0 8px 24px rgba(57, 73, 171, 0.04);`
  - Outline: `1px solid rgba(31, 41, 55, 0.06)`
- **Level 2 (Hover & Interactive Overlays):** Interactive project cards, active preview drawers, and hover states subtly elevate:
  - `box-shadow: 0 4px 6px -1px rgba(31, 41, 55, 0.05), 0 16px 32px -4px rgba(57, 73, 171, 0.08);`
  - Transform: `translateY(-2px)` with a smooth `200ms ease` transition.
- **Level 3 (Modal Sheets & Floating Navigation Bars):** Frosted floating bars use `rgba(255, 255, 255, 0.85)` with `backdrop-filter: blur(12px)` and a distinct boundary shadow:
  - `box-shadow: 0 12px 32px rgba(31, 41, 55, 0.08);`

## Shapes

The design uses balanced, modern rounded geometry (Scale 2), conveying warmth without compromising executive professionalism.

### Shape Geometry Rules
- **Base Components (`rounded` / 0.5rem):** Standard buttons, text input fields, selection controls, and skill badges.
- **Containers & Surfaces (`rounded-lg` / 1.0rem):** Career timeline entries, project cards, education blocks, and floating action panels.
- **Large Modals & Feature Displays (`rounded-xl` / 1.5rem):** Hero highlight containers and case study preview drawers.
- **Tags & Floating Indicator Pills (`rounded-full` / 9999px):** Status badges (e.g., "Available for Hire", "Full-time") and compact pill tags.

## Components

### Buttons
- **Primary:** Solid `#3949AB` fill with `#FFFFFF` text. Hover state shifts to `#303F9F`. Padding: `0.75rem 1.5rem`. Border radius: `0.5rem`.
- **Secondary / Outlined:** `#FFFFFF` background with `1.5px solid #3949AB` border and `#3949AB` label. Active hover introduces a faint indigo tint (`rgba(57, 73, 171, 0.06)`).
- **Ghost:** Transparent background with `#1F2937` text; turns to `#E6F7FF` on hover.

### Badges & Chips
- **Skill Badges:** Background `#FFFFFF`, border `1px solid rgba(31, 41, 55, 0.1)`, text `#1F2937` (`label-sm`).
- **Status Indicator Pill:** Background `rgba(57, 73, 171, 0.08)`, text `#3949AB` (`badge-caption`), featuring an active pulse dot indicator (`#3949AB`).
- **Secondary Category Tags:** Background `#E6F7FF`, text `#0284C7`.

### Cards & Panels
- **CV / Project Card:** Base background `#FFFFFF`, border `1px solid rgba(31, 41, 55, 0.06)`, padding `1.5rem`, border-radius `1rem`. Houses career timelines, role descriptions, company metadata, and external link icons.
- **Metric Highlight Card:** High-contrast, clean interior padding (`1.25rem`), showcasing prominent career figures (e.g., revenue generated, team size managed).

### Lists & Timeline Trackers
- **Experience Timeline:** A vertical track in `rgba(57, 73, 171, 0.2)` with `12px` solid `#3949AB` nodes. Content blocks align consistently to the right on desktop, with dates highlighted in muted neutral (`#6B7280`).

### Form Elements & Inputs
- **Inputs & Textareas:** Background `#FFFFFF`, border `1px solid rgba(31, 41, 55, 0.15)`, text `#1F2937`, placeholder `#6B7280`. Focus state: border `#3949AB` with a `3px` focus ring in `rgba(57, 73, 171, 0.15)`.
- **Checkboxes & Radios:** Accent color `#3949AB`. Standard rounded check container with crisp white inner glyphs.