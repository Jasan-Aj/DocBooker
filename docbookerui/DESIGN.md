---
name: Clinical Clarity
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
  on-surface-variant: '#424754'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#727785'
  outline-variant: '#c2c6d6'
  surface-tint: '#005ac2'
  primary: '#0058be'
  on-primary: '#ffffff'
  primary-container: '#2170e4'
  on-primary-container: '#fefcff'
  inverse-primary: '#adc6ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#4648d4'
  on-tertiary: '#ffffff'
  tertiary-container: '#6063ee'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d8e2ff'
  primary-fixed-dim: '#adc6ff'
  on-primary-fixed: '#001a42'
  on-primary-fixed-variant: '#004395'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#e1e0ff'
  tertiary-fixed-dim: '#c0c1ff'
  on-tertiary-fixed: '#07006c'
  on-tertiary-fixed-variant: '#2f2ebe'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  h1:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  data-mono:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: -0.01em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-page: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is anchored in the principles of reliability, efficiency, and clinical precision. It is designed to evoke a sense of calm and competence for patients while providing high-density utility for medical professionals. The target audience includes tech-savvy patients seeking quick access to care and healthcare providers who require clear, actionable data.

The visual style follows a **Corporate / Modern** aesthetic. It prioritizes extreme legibility and functional minimalism, using generous white space to reduce cognitive load in stressful medical contexts. The interface avoids unnecessary decorative elements, favoring structural clarity and a "soft-professional" feel that balances high-tech capability with human-centric accessibility.

## Colors

This design system utilizes a palette optimized for healthcare trust and status communication. 

*   **Primary Blue (#3B82F6):** Used for primary brand elements, main action buttons, and active states. It represents stability and medical authority.
*   **Emerald (#10B981):** Specifically reserved for "Available" indicators, success messages, and verified status. Its high-visibility nature ensures patients can quickly scan for open slots.
*   **Neutral Palette:** A range of Slate grays provides sophisticated hierarchy for secondary text and borders without appearing harsh.
*   **Highlight Background (#EFF6FF):** A very light blue tint used to differentiate content sections, such as sidebar navigation or secondary dashboard modules, without breaking the clean white aesthetic.

## Typography

The design system employs **Inter** for all interface levels to ensure maximum legibility of medical data and scheduling information. 

The type hierarchy is structured to support rapid scanning of doctor names, specialties, and time slots. Headlines use a tighter letter-spacing for a modern, compact feel, while body text maintains a generous line height (1.5–1.6x) to ensure readability during long reading sessions, such as reviewing medical histories or procedure descriptions. A specialized "data-mono" style is used for numeric values like dates and times to ensure consistent vertical alignment in the calendar grid.

## Layout & Spacing

This design system follows a **12-column fixed grid** for desktop, centering the content within a 1280px maximum width. A strict 8px base unit (0.5rem) governs all padding and margins to maintain rhythmic consistency.

Section highlights are treated as full-width or container-width blocks with the light blue background variable, providing a clear visual break between different types of information (e.g., separating the doctor search filters from the results). Gutters are set to 24px to ensure distinct separation between doctor cards and calendar modules, reinforcing the system's emphasis on "ample white space."

## Elevation & Depth

Visual hierarchy is achieved through a combination of **tonal layers** and **ambient shadows**. 

*   **Level 0 (Background):** Pure white (#FFFFFF) for the main canvas or light blue (#EFF6FF) for highlighted regions.
*   **Level 1 (Cards):** White surfaces with a very soft, diffused shadow (Blur: 12px, Y: 4px, Color: rgba(0,0,0, 0.05)). This elevates the primary doctor profiles and booking cards.
*   **Level 2 (Hover/Active):** An increased shadow (Blur: 20px, Y: 8px, Color: rgba(59, 130, 246, 0.08)) is used to provide tactile feedback when a user interacts with a doctor card.
*   **Interactive Elements:** Buttons and input fields use low-contrast outlines (1px solid #E2E8F0) rather than heavy shadows to maintain a clean, clinical appearance.

## Shapes

The design system adopts a **Rounded** shape language to appear approachable and modern. 

The core unit is `rounded-lg` (0.5rem / 8px) for cards, buttons, and input fields. This moderate rounding strikes a balance between the precision of a medical environment and the friendliness of a consumer platform. Specialized elements, such as status badges and "Verified" indicators, may utilize pill-shaped (full) rounding to distinguish them from interactive buttons.

## Components

*   **Doctor Cards:** Clean white surfaces with 16px internal padding. Doctor avatars are placed on the left, with the name and specialty in high-contrast Slate. Verified badges appear as a small Emerald checkmark icon adjacent to the name.
*   **Calendar Grid:** A structured system using 1px neutral borders. Available time slots are rendered as Secondary Emerald-outlined boxes that transition to a solid Emerald fill on hover. Unavailable slots are muted with a light gray diagonal pattern.
*   **Verified Badges:** Small, non-intrusive icons using the Emerald color. They include a "Verified" text label in the `label-caps` typography style for clarity.
*   **Buttons:** Primary buttons use the Brand Blue with white text. Secondary buttons use a light blue ghost style (Brand Blue text on a transparent or Highlight Blue background).
*   **Input Fields:** Large, 48px height fields with 8px rounded corners. The focus state is indicated by a 2px Primary Blue border and a soft blue outer glow.
*   **Status Indicators:** Small circular dots. Emerald for "Available Now," Amber for "Limited Slots," and Gray for "Fully Booked."