---
name: Somdet Phra Sangharaj Hospital HHC System
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#43474f'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#747780'
  outline-variant: '#c4c6d0'
  surface-tint: '#405f91'
  primary: '#002753'
  on-primary: '#ffffff'
  primary-container: '#1b3d6d'
  on-primary-container: '#8aa9e0'
  inverse-primary: '#a9c7ff'
  secondary: '#006a6a'
  on-secondary: '#ffffff'
  secondary-container: '#8cf3f3'
  on-secondary-container: '#007070'
  tertiary: '#1e2a28'
  on-tertiary: '#ffffff'
  tertiary-container: '#33403e'
  on-tertiary-container: '#9eaba9'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d6e3ff'
  primary-fixed-dim: '#a9c7ff'
  on-primary-fixed: '#001b3d'
  on-primary-fixed-variant: '#264777'
  secondary-fixed: '#8cf3f3'
  secondary-fixed-dim: '#6fd7d6'
  on-secondary-fixed: '#002020'
  on-secondary-fixed-variant: '#004f4f'
  tertiary-fixed: '#d7e5e2'
  tertiary-fixed-dim: '#bcc9c7'
  on-tertiary-fixed: '#121e1c'
  on-tertiary-fixed-variant: '#3d4947'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  headline-xl:
    fontFamily: Manrope
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
  headline-lg:
    fontFamily: Manrope
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Manrope
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Public Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Public Sans
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
  max-width: 1440px
---

## Brand & Style
The design system is engineered for the Home Health Care (HHC) ecosystem, prioritizing clinical precision, accessibility, and institutional trust. The visual language balances the authority of a major medical institution with the approachability required for patient-centric care. 

The aesthetic follows a **Corporate / Modern** direction with a focus on high-clarity information density. It utilizes a spacious layout to reduce cognitive load for medical practitioners while maintaining high-contrast ratios for senior patients or caregivers in various lighting conditions. The style is defined by structured grids, professional depth, and a hygienic, "clean-room" atmosphere.

## Colors
The palette is rooted in medical professionalism and reliability.

- **Primary (#1B3D6D):** A deep, authoritative blue used for navigation, primary actions, and headers to establish institutional trust.
- **Secondary (#008B8B):** A medical teal/blue that signifies health and vitality. Used for success states, secondary actions, and health-related data points.
- **Tertiary (#E6F4F1):** A very soft teal tint used for large background areas, card fills, and subtle UI differentiation.
- **Neutral:** A range of grays that prioritize legibility. Pure white (#FFFFFF) is the primary surface color to maintain a clinical, sanitary feel.

## Typography
This design system utilizes **Manrope** for headlines to provide a modern, balanced, and calm character. For all functional text, body copy, and labels, **Public Sans** is used due to its exceptional legibility and institutional neutrality, making it ideal for health records and administrative interfaces.

Hierarchy is enforced through weight rather than dramatic size shifts to maintain a professional, data-dense environment. Body text is kept at a comfortable 16px base for accessibility.

## Layout & Spacing
The layout uses a **Fixed Grid** system for desktop to ensure data visualization cards remain readable and predictable. 

- **Desktop:** 12-column grid, 1200px - 1440px max-width, 24px gutters.
- **Tablet:** 8-column grid, fluid width with 24px side margins.
- **Mobile:** 4-column grid, fluid width with 16px side margins.

A strict 8px spatial scale governs all padding and margins. Vertical rhythm is emphasized in forms and medical records to ensure information is easily scannable from top to bottom.

## Elevation & Depth
Depth is used sparingly to signify interactivity and layering without compromising the "flat" professional aesthetic.

1.  **Level 0 (Flat):** Used for background surfaces and secondary inputs.
2.  **Level 1 (Soft Shadow):** Primary cards and data containers. Use a subtle, diffused shadow: `0px 2px 8px rgba(27, 61, 109, 0.08)`.
3.  **Level 2 (Active/Floating):** Modals, dropdowns, and calendar pickers. These use a more pronounced shadow with a slight primary-color tint: `0px 8px 24px rgba(27, 61, 109, 0.12)`.

No heavy gradients are permitted. Interaction states (hover) should be indicated by a slight tonal shift rather than a change in elevation.

## Shapes
The design system employs **Rounded (0.5rem)** corners as the standard for all primary UI elements including buttons, input fields, and cards. This softened geometry reduces the harshness of clinical software, making it feel more modern and user-friendly.

- **Standard Buttons & Inputs:** 8px (0.5rem)
- **Large Cards/Sections:** 16px (1rem)
- **Alerts/Chips:** Pill-shaped for immediate distinction from actionable buttons.

## Components
- **Buttons:** Primary buttons use the Deep Blue (#1B3D6D) with white text. Secondary buttons use an outline of the Primary color. Tertiary actions use the Medical Teal (#008B8B).
- **Form Fields:** Labels must always be top-aligned for readability. Use a 1px border (#CBD5E1) that thickens to 2px Primary Blue on focus. Error states use a high-contrast red (#DC2626).
- **Calendar Pickers:** Use a clean grid layout with the Secondary Teal used to highlight the current date and selected range. Avoid complex animations; prioritize quick date entry.
- **Image Upload Zones:** Dotted border containers using the Neutral palette. Include a large icon and a clear "Drag and drop" label. Successful uploads show a thumbnail with a 4px rounded corner.
- **Data Visualization Cards:** Use the Tertiary Teal (#E6F4F1) for background fills on charts to separate them from the white page surface. Headlines within cards should be "Label-md" weight.
- **Lists:** Medical records and patient lists use alternating row colors (White and Tertiary) for high-density legibility.