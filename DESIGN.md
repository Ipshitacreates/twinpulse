---
name: Clinical Precision
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
  on-surface-variant: '#45464d'
  inverse-surface: '#2d3133'
  inverse-on-surface: '#eff1f3'
  outline: '#76777d'
  outline-variant: '#c6c6cd'
  surface-tint: '#565e74'
  primary: '#000000'
  on-primary: '#ffffff'
  primary-container: '#131b2e'
  on-primary-container: '#7c839b'
  inverse-primary: '#bec6e0'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#000000'
  on-tertiary: '#ffffff'
  tertiary-container: '#0b1c30'
  on-tertiary-container: '#75859d'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#d3e4fe'
  tertiary-fixed-dim: '#b7c8e1'
  on-tertiary-fixed: '#0b1c30'
  on-tertiary-fixed-variant: '#38485d'
  background: '#f7f9fb'
  on-background: '#191c1e'
  surface-variant: '#e0e3e5'
typography:
  display:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '600'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '500'
    lineHeight: 32px
  headline-sm:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '500'
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
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
  disclaimer:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  container-max: 1280px
  gutter: 24px
  margin-desktop: 48px
  margin-mobile: 16px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style
The design system is engineered for high-stakes medical technology environments where trust, clarity, and authority are paramount. The brand personality is objective and sterile yet deeply empathetic, balancing the cold precision of clinical data with the accessibility of modern patient care.

The design style follows a **Corporate / Modern** aesthetic with **Minimalist** influences. It prioritizes information density without clutter, utilizing significant whitespace to reduce cognitive load during medical decision-making. The visual language is structured and systematic, evoking the feeling of a premium genomic report or a high-end private healthcare interface.

## Colors
The palette is anchored by **Deep Navy (#0F172A)** and **Slate Blues**, establishing a foundation of institutional authority. **Calming Teal (#0D9488)** serves as the primary action color, providing a distinct but soothing visual cue for interactivity.

Status indicators depart from traditional "traffic light" palettes in favor of a sophisticated, muted scale. These colors are desaturated to avoid an "alarmist" feel, ensuring that "High Risk" data remains professional rather than frightening. Backgrounds use **Cool Grays** and **Pure Whites** to maintain a sterile, clinical environment that highlights medical data as the primary focus.

## Typography
The system utilizes **Public Sans** for headings to provide a sturdy, institutional feel. Headings feature tight tracking and medium-to-semibold weights to ensure they feel modern and precise.

**Inter** is utilized for all body copy and UI labels. It is chosen for its exceptional legibility in data-heavy contexts. Body text should always prioritize generous line heights (minimum 1.5x) to ensure that complex medical terminologies are easy to scan and digest. A specialized `disclaimer` style is defined for legal and medical warnings, ensuring they are distinct but unobtrusive.

## Layout & Spacing
The layout follows a **Fixed Grid** philosophy for desktop dashboards to maintain a consistent data density. A 12-column grid is used with 24px gutters to allow for complex multi-column data views. 

Spacing follows a strict 4px baseline rhythm. Information is organized into logical "clusters" using vertical stacking units (8px, 16px, 32px) to separate patient metadata from diagnostic results. On mobile, the grid collapses to a single column with 16px side margins, ensuring that tables and data visualizations remain readable via horizontal scrolling or card-based reflowing.

## Elevation & Depth
The design system uses **Low-contrast outlines** combined with **Tonal layers** to establish hierarchy. Surfaces do not "float" aggressively; instead, they appear as distinct, organized layers within the UI.

- **Primary Surface:** White (#FFFFFF) for cards and main content areas.
- **Background:** Cool Gray (#F8FAFC) to provide a neutral canvas.
- **Borders:** 1px solid Slate-200 (#E2E8F0) used for all container boundaries.
- **Shadows:** Extremely subtle, highly diffused shadows (Blur: 12px, Opacity: 4%, Color: Navy) are used only on interactive cards to indicate hover states.

This approach creates a "flat-plus" look that feels more like a physical medical chart than a typical consumer application.

## Shapes
The design system uses a **Soft (0.25rem)** roundedness level. This small radius provides enough "humanity" to feel approachable while maintaining the professional rigor associated with sharp geometric forms. 

Interactive elements like buttons use the base roundedness, while larger information containers (cards) may scale up to `rounded-lg` (0.5rem) to soften the overall interface. Risk indicators and badges use the same logic—avoiding fully round "pills" unless used for specific status chips, keeping the aesthetic grounded in medical documentation.

## Components
- **Buttons:** Primary buttons use the Teal accent with white text. Secondary buttons use a Slate-200 border and Navy text. No gradients are used.
- **Information Cards:** White backgrounds, 1px Slate-200 borders, and a 4px accent top-border color-coded to the patient's risk status.
- **Risk Progress Bars:** Thin, 8px tall tracks. The "fill" uses the sophisticated status colors (e.g., Amber for moderate). The track background is a faint tint of the status color (10% opacity).
- **Status Badges:** Small, rectangular labels with slightly rounded corners. They use a "subtle" style: a light tint background with dark text in the same color family (e.g., Light Red background with Deep Red text for High Risk).
- **Data Tables:** High-density, horizontal-only borders. Header cells use the `label-md` typography style with a faint gray background. 
- **Medical Disclaimers:** Contained within a light-blue tinted box with a "soft info" icon, using the `disclaimer` font style to ensure legal compliance without distracting from the primary clinical workflow.