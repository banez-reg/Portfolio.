---
name: Obsidian Lumina
colors:
  surface: '#121316'
  surface-dim: '#121316'
  surface-bright: '#38393d'
  surface-container-lowest: '#0d0e11'
  surface-container-low: '#1b1b1f'
  surface-container: '#1f1f23'
  surface-container-high: '#292a2d'
  surface-container-highest: '#343538'
  on-surface: '#e3e2e6'
  on-surface-variant: '#c7c4d8'
  inverse-surface: '#e3e2e6'
  inverse-on-surface: '#2f3034'
  outline: '#918fa1'
  outline-variant: '#464555'
  surface-tint: '#c3c0ff'
  primary: '#c3c0ff'
  on-primary: '#1d00a5'
  primary-container: '#4f46e5'
  on-primary-container: '#dad7ff'
  inverse-primary: '#4d44e3'
  secondary: '#4cd7f6'
  on-secondary: '#003640'
  secondary-container: '#03b5d3'
  on-secondary-container: '#00424e'
  tertiary: '#bdc2ff'
  on-tertiary: '#131e8c'
  tertiary-container: '#4a55be'
  on-tertiary-container: '#d7d8ff'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#e2dfff'
  primary-fixed-dim: '#c3c0ff'
  on-primary-fixed: '#0f0069'
  on-primary-fixed-variant: '#3323cc'
  secondary-fixed: '#acedff'
  secondary-fixed-dim: '#4cd7f6'
  on-secondary-fixed: '#001f26'
  on-secondary-fixed-variant: '#004e5c'
  tertiary-fixed: '#e0e0ff'
  tertiary-fixed-dim: '#bdc2ff'
  on-tertiary-fixed: '#000767'
  on-tertiary-fixed-variant: '#2f3aa3'
  background: '#121316'
  on-background: '#e3e2e6'
  surface-variant: '#343538'
typography:
  display:
    fontFamily: Space Grotesk
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.03em
  display-mobile:
    fontFamily: Space Grotesk
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Space Grotesk
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Space Grotesk
    fontSize: 26px
    fontWeight: '600'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Space Grotesk
    fontSize: 22px
    fontWeight: '600'
    lineHeight: 30px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Space Grotesk
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 26px
    letterSpacing: -0.01em
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 22px
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 18px
    letterSpacing: '0'
  label-lg:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 10px
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
  gutter: 1rem
  gutter-desktop: 1.5rem
  margin: 1rem
  margin-tablet: 2rem
  margin-desktop: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system blends deep obsidian minimalism with futuristic glassmorphism and luminous neon-spectral accents. Built specifically for high-achieving learners, researchers, and technical professionals, it frames academic milestones, verification badges, performance metrics, and activity captures as pristine artifacts. 

The emotional signature is precise, prestigious, and calm. High-contrast typography pairs with pure true-black backdrops (`#08090C`), punctuated by electric indigo and violet bioluminescent glows. Surfaces feel like polished dark smoked glass floating in deep space, catching edge-light without visual noise or gratuitous decoration.

## Colors

The palette relies on absolute darkness paired with hyper-focused spectral lighting.

- **Background Baseline (`#08090C`):** Pure deep charcoal-black that prevents visual fatigue while allowing bright accents to sing.
- **Surface Layer 1 (`#0E1117` / rgba(14, 17, 23, 0.7)):** Semi-translucent obsidian base for standard cards and containers.
- **Surface Layer 2 (`#151923` / rgba(21, 25, 35, 0.8)):** Elevated interactive tier for modals, popovers, and elevated chips.
- **Electric Accent Gradient:** A continuous linear sweep from Indigo (`#4F46E5`) to Cyan (`#06B6D4`) used for hero highlights, glowing outlines, active rings, and progress indicators.
- **Text & Foreground:** Primary text uses crisp high-contrast off-white (`#F8FAFC`), secondary text is muted slate (`#94A3B8`), and tertiary metadata sits in deep slate (`#64748B`).
- **Success / Distinction (`#10B981`):** Precision emerald green for 100% quiz scores, verified credentials, and honor designations.

## Typography

The type hierarchy creates deliberate tension between futuristic technical precision and utilitarian legibility.

- **Headlines (Space Grotesk):** Geometric, wide-aperture display font conveying modern technical prowess and structural clarity. Used for student names, certification titles, and prominent section banners.
- **Body (Inter):** Highly legible, neutral workhorse that renders smoothly across small mobile viewports, academic descriptions, and exam criteria breakdowns.
- **Labels, Metrics, & Scores (JetBrains Mono):** Monospaced type delivers authentic technical weight to test scores, issue dates, verification hashes, and metadata tags.

## Layout & Spacing

A mobile-first, 12-column adaptive layout built on an 8pt base grid ensures fluid transitions between compact phone interfaces and broad desktop portfolios.

- **Mobile (< 768px):** 4-column layout with 16px outer margins and 16px gutters. Cards stack vertically; metric badges wrap dynamically.
- **Tablet (768px - 1024px):** 8-column layout with 32px outer margins and 20px gutters. Allows side-by-side certificate views and dual-column activity summaries.
- **Desktop (> 1024px):** 12-column layout capped at a maximum width of 1280px with 48px outer margins and 24px gutters. Provides room for persistent interactive filter bars and expansive media lightbox galleries.

## Elevation & Depth

Depth is established through translucent stacking, selective backdrop blur, and directional luminance rather than flat muddy drop-shadows.

- **Base Ambient Canvas:** Flat `#08090C` background with subtle, fixed radial gradients of indigo (`rgba(79, 70, 229, 0.08)`) blooming behind hero showcases.
- **Level 1 (Card Surfaces):** `rgba(14, 17, 23, 0.7)` backdrop with a `12px` Gaussian blur, bounded by a 1px border of `rgba(255, 255, 255, 0.08)`.
- **Level 2 (Interactive Hover / Featured Artifacts):** Card borders shift to a gradient border (`rgba(79, 70, 229, 0.4)` to `rgba(6, 182, 212, 0.4)`) accompanied by an outer soft aura: `0 0 24px rgba(79, 70, 229, 0.15)`.
- **Level 3 (Modals & Fullscreen Certificate Lightboxes):** Solid deep surface `rgba(15, 20, 30, 0.92)` supported by a `24px` backdrop blur, a crisp perimeter ring `rgba(255, 255, 255, 0.15)`, and a deep falloff shadow `0 24px 48px rgba(0, 0, 0, 0.7)`.

## Shapes

The interface balances sharp digital clarity with organic human touchpoints using rounded tier 2 tokens:

- **Standard Containers & Cards:** `0.75rem` to `1rem` corner radii prevent visually rigid corners while preserving a technical, tailored edge.
- **Inputs & Buttons:** `0.5rem` radius creates confident, tactile click targets.
- **Status Pills, Score Badges, & Chips:** Pill styling (`9999px` / fully rounded) gives metadata distinct isolation from angular cards and screenshots.
- **Media Containers:** Screenshots and credentials share an inner clip radius of `0.75rem` with a nested hairline containment border.

## Components

### Buttons & Interactive Controls
- **Primary Action:** Solid electric indigo background (`#4F46E5`) with an active subtle cyan glow (`0 0 16px rgba(79, 70, 229, 0.5)`). Crisp white label typography, smoothly scaling down on press (`transform: scale(0.98)`).
- **Secondary Action:** Glass surface (`rgba(255, 255, 255, 0.04)`) with a 1px border of `rgba(255, 255, 255, 0.12)`. Shifts to electric blue border on hover.
- **Icon Buttons:** Circular or softly squared tap targets with subtle backplates (`rgba(255, 255, 255, 0.03)`), providing clear optical alignment for verification copy links and share buttons.

### Credential & Certificate Cards
- Constructed with smoked glass surfaces, carrying a top-edge 1px highlight (`rgba(255, 255, 255, 0.15)` fading downward) mimicking light on chamfered glass.
- Built-in preview frame with an aspect-ratio container for activity screenshots or PDF certificates, equipped with a hover zoom-in cue.
- Footer displays issuing institution logo, credential identifier, and a verified seal badge.

### Luminous Status Pills & Quiz Score Chips
- Compact pills utilizing monospaced labels (`JetBrains Mono`).
- **High Honors / 90%+ Score:** Emerald tone (`rgba(16, 185, 129, 0.12)`) background, emerald border (`rgba(16, 185, 129, 0.3)`), and emerald text with a tiny pulsing green indicator dot.
- **In Progress / Standard:** Deep indigo tint with electric indigo glow accents.

### Form Inputs & Search Filters
- Inactive state: Dark container (`rgba(255, 255, 255, 0.02)`) with a low-contrast slate border (`rgba(255, 255, 255, 0.1)`).
- Active/Focused state: Outer neon ring pulse with border illuminated by the electric indigo gradient (`#4F46E5`), with floating slate labels.

### Modal & Lightbox Overlays
- Dynamic backdrop fade (`rgba(8, 9, 12, 0.85)`) with an instantaneous `16px` background blur.
- Modals present high-resolution activity proofs, zoomable credential images, and interactive verification trees without leaving page context.