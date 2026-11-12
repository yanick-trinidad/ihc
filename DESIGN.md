---
name: Revista 3 de 3
colors:
  surface: '#f7f9fb'
  surface-dim: '#d8dadc'
  surface-bright: '#f7f9fb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f2f4f6'
  surface-container: '#eceef0'
  surface-container-high: '#e6e8ea'
  surface-container-highest: '#e0e3e5'
  on-surface: '#191c1e'
  on-surface-variant: '#43474d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#74777e'
  outline-variant: '#c3c6ce'
  surface-tint: '#49607c'
  primary: '#001428'
  on-primary: '#ffffff'
  primary-container: '#0f2942'
  on-primary-container: '#7991af'
  inverse-primary: '#b0c9e8'
  secondary: '#006d30'
  on-secondary: '#ffffff'
  secondary-container: '#92f5a4'
  on-secondary-container: '#007233'
  tertiary: '#260b00'
  on-tertiary: '#ffffff'
  tertiary-container: '#461b00'
  on-tertiary-container: '#dc712b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d1e4ff'
  primary-fixed-dim: '#b0c9e8'
  on-primary-fixed: '#011d35'
  on-primary-fixed-variant: '#314863'
  secondary-fixed: '#95f8a7'
  secondary-fixed-dim: '#79db8d'
  on-secondary-fixed: '#00210a'
  on-secondary-fixed-variant: '#005323'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68e'
  on-tertiary-fixed: '#331200'
  on-tertiary-fixed-variant: '#763300'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  headline-xl:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-xl-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 30px
    fontWeight: '800'
    lineHeight: 38px
    letterSpacing: -0.015em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 22px
    fontWeight: '700'
    lineHeight: 28px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0em
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
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
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
---

## Brand & Style
This design system defines an accessible, high-trust regional editorial directory and marketplace bridging commerce, tourism, and real estate. The visual philosophy pairs the authoritative structure of classical civic publishing with the clarity and speed of modern utility-first digital platforms. 

The aesthetic is grounded in **Contemporary Editorial Functionalism**: rigorous information hierarchy, generous breathing room, crisp structural borders, and purposeful chromatic signaling. Every interaction is designed under strict adherence to WCAG 2.1 AA accessibility guidelines, cognitive load minimization (Hick’s Law), and touch ergonomical safety (Fitts's Law). The emotional response should be reassuring, deeply rooted in regional credibility, and actionable for commerce and community exploration.

## Colors
The palette balances institutional regional authority with immediate conversion channels and cultural warmth. All core text-to-background combinations maintain contrast ratios exceeding 4.5:1 (WCAG 2.1 AA) and target 7:1 where viable for primary readability.

- **Primary (`#0F2942`) — Deep Institutional Navy**: Anchors navigation, editorial headlines, structural framing, and primary text tokens. Used to convey governance, trust, and permanence.
- **Secondary (`#15803D`) — Direct Conversion Green**: Reserved for transactional and contact drivers, specifically WhatsApp integration, direct calls, and inquiry confirmation. High visibility with contrast compliance over light neutral surfaces. Hover/active states scale to `#16A34A` for responsive feedback.
- **Tertiary (`#B45309`) — Regional Ochre / Amber**: Applied selectively to editorial tags, regional certifications, curated badges, and highlighted commercial real-estate tiers.
- **Neutral Canvas (`#F8FAFC`) & Clean Surfaces (`#FFFFFF`)**: Establishes crisp readability without harsh optic glare. 
- **Structural Stroke (`#CBD5E1`)**: Standard divider and border boundary defining cards, inputs, and directory listings with explicit physical definition.

## Typography
The system deploys **Plus Jakarta Sans** for headlines to inject architectural rhythm and regional editorial warmth, while **Inter** governs body copy and interface labels to maintain absolute legibility across dense data listings, real-estate specs, and directory cards.

Large titles automatically transition to their corresponding mobile variations below the 768px viewport threshold to prevent orphan words and viewport overruns. Numerical parameters (e.g., pricing, square footage, telephone numbers) utilize tabular numerals (`tnum`) to maintain tabular alignment in directory grids.

## Layout & Spacing
The layout adheres to a fluid, 12-column responsive grid on desktop systems (`>= 1024px`), transitioning to a 6-column format on tablet devices (`768px - 1023px`), and a 4-column flow on mobile viewports (`< 768px`).

Grid gutters scale dynamically between `1rem` on mobile and `1.5rem` on desktop, while outer canvas margins step from `1rem` on mobile up to a maximum constrained content boundary of `1280px` on wide screens. Vertical rhythm relies on standard spacing increments (`space-sm` to `space-xl`) to enforce visual groupings: grouping related elements within `space-sm` or `space-md`, and separating distinct editorial articles or business classifications with `space-xl`.

## Elevation & Depth
Depth in this system avoids ambiguous, heavy drop shadows in favor of **structural containment and low-contrast borders**. Visual layering is communicated via clean tonal separation and subtle ambient projection:

- **Flat / Ground Layer**: Background canvas set to `#F8FAFC`.
- **Card / Surface Layer**: Solid `#FFFFFF` elevated strictly with a 1px border stroke using `#CBD5E1`.
- **Hover & Overlay Elevation**: Used exclusively when an interactive card is focused or hovered, consisting of a subtle tinted ambient shadow: `0 4px 12px -2px rgba(15, 41, 66, 0.08)`.
- **Modal & Navigation Drawers**: Elevated using `0 12px 32px -4px rgba(15, 41, 66, 0.16)` with a backdrop curtain tinted in deep navy `#0F2942` at 40% opacity.
- **Accessibility Outlines**: All interactive elements in focus states trigger a mandatory `3px` solid `#0F2942` outline with a `2px` offset, ensuring absolute clarity under keyboard navigation.

## Shapes
The shape language uses subtle, clean rounding (`roundedness: 1`, `0.25rem` standard). This keeps interface cards and listings aligned with editorial print conventions while softening digital interaction points. Buttons and form controls employ `rounded-lg` (`0.5rem`) for enhanced tap affordance, while status tags, price chips, and category indicators remain compact and crisp at `0.25rem`.

## Components

### Touch Targets & Accessibility Baseline
Every standalone interactive control (buttons, links, form inputs, checkboxes, dismiss triggers) adheres to an uncompromising minimum hit footprint of **44x44px** in accordance with Fitts's Law. Interactive focus rings are defined by a high-contrast `3px` solid stroke (`#0F2942`) separated by a `2px` white outline offset.

### Buttons
- **Primary Action (Editorial / Search)**: `#0F2942` background, `#FFFFFF` text, `0.5rem` radius, minimum height of `48px`, padding `0 1.5rem`.
- **Direct Conversion (WhatsApp / Call)**: `#15803D` background, `#FFFFFF` text, bold icon prefix, minimum height of `48px`. Hover shifts to `#16A34A`.
- **Secondary / Tertiary**: White `#FFFFFF` background with a 1.5px `#CBD5E1` border and `#0F2942` typography. Hover shifts background to `#F8FAFC`.

### Directory & Real Estate Cards
- Constructed with `#FFFFFF` background, a 1px `#CBD5E1` border, and `0.5rem` outer radius.
- Includes mandatory metadata zones: category tag (Amber `#B45309`), primary title, address/region subtext, and an anchored direct-contact action strip (WhatsApp trigger meeting the 44px height standard).

### Chips & Filters
- Compact `36px` height desktop, `44px` mobile.
- Unselected: `#FFFFFF` background, `1px solid #CBD5E1`, text `#0F2942`.
- Active: `#0F2942` background, text `#FFFFFF`, clear categorical selection.

### Form Inputs & Search Fields
- Structural height of `48px` with internal vertical alignment.
- Background `#FFFFFF`, border `1px solid #CBD5E1`. On active typing and focus, the border shifts to `2px solid #0F2942` without shifting layout dimensions.

### Checkboxes & Radios
- Size `24x24px` centered inside a minimum bounding container of `44x44px`.
- High contrast check state in `#0F2942` or conversion green `#15803D` for transaction agreements.