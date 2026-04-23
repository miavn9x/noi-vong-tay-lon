---
name: Unity & Service
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#434652'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#737783'
  outline-variant: '#c3c6d4'
  surface-tint: '#2b5ab6'
  primary: '#002d70'
  on-primary: '#ffffff'
  primary-container: '#00429d'
  on-primary-container: '#97b4ff'
  inverse-primary: '#b0c6ff'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#21333a'
  on-tertiary: '#ffffff'
  tertiary-container: '#384a51'
  on-tertiary-container: '#a5b9c1'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d9e2ff'
  primary-fixed-dim: '#b0c6ff'
  on-primary-fixed: '#001945'
  on-primary-fixed-variant: '#00419c'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d2e6ef'
  tertiary-fixed-dim: '#b6cad2'
  on-tertiary-fixed: '#0b1e24'
  on-tertiary-fixed-variant: '#374951'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  h1:
    fontFamily: Public Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
  h2:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
  h3:
    fontFamily: Public Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-bold:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.2'
    letterSpacing: 0.02em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1.2'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-padding: 80px
---

## Brand & Style

The brand identity centers on the spirit of collective action and the prestigious heritage of Vietnamese youth volunteerism. It aims to evoke feelings of reliability, patriotic energy, and modern professionalism. The target audience includes both enthusiastic young volunteers and established organizations seeking dependable partnerships.

The design system adopts a **Corporate Modern** style with a focus on accessibility and warmth. It balances the "Deep Blue" of the volunteer uniform—symbolizing duty and depth—with expansive white space to ensure the platform feels contemporary and uncluttered. Visuals should emphasize human connection through high-quality photography of real community impact, framed by clean, systematic interface elements.

## Colors

The palette is anchored by **Deep Blue (#00429D)**, the signature color of the Vietnamese Youth Volunteer uniform, used for primary actions, headers, and brand-heavy moments. **White (#FFFFFF)** serves as the primary canvas, ensuring a high-contrast, clean environment that highlights content.

**Light Blue (#E1F5FE)** is used for secondary accents, such as category badges or subtle hover states, providing a breath of freshness. **Soft Gray (#F8F9FA)** is utilized for background sectioning to create a gentle distinction between content blocks without introducing visual noise. Text should primarily use a near-black gray to maintain readability while appearing softer than pure black.

## Typography

This design system utilizes **Public Sans** for headings to convey an institutional yet accessible authority. Its sturdy, neutral shapes provide a sense of stability and trust. For body text and functional UI labels, **Inter** is employed for its exceptional legibility at various sizes and its clean, systematic feel.

Hierarchy is maintained through deliberate weight shifts rather than excessive size changes. Headlines should remain tight and impactful, while body text requires generous line heights (1.6) to facilitate the reading of long project descriptions or community stories.

## Layout & Spacing

The layout follows a **Fixed Grid** model on desktop to maintain a structured, professional appearance, transitioning to a fluid layout on mobile devices. A 12-column grid is standard, allowing for flexible arrangements of volunteer opportunity cards (typically spanning 3, 4, or 6 columns).

The spacing rhythm is based on an 8px base unit. Generous section padding (80px+) is encouraged to evoke a sense of "space" and "openness," reflecting the welcoming nature of the community. Consistent gutters of 24px ensure that even dense information layouts remain breathable and easy to parse.

## Elevation & Depth

Visual hierarchy is achieved through **Tonal Layers** and **Ambient Shadows**. Surfaces should feel integrated rather than floating high above the background. 

- **Level 0 (Background):** Soft Gray (#F8F9FA) for the main page body.
- **Level 1 (Cards/Containers):** Pure White (#FFFFFF) with a very soft, diffused shadow (0px 4px 20px rgba(0, 0, 0, 0.05)).
- **Level 2 (Interactive/Active):** Slightly more pronounced shadow on hover to indicate tactility (0px 8px 30px rgba(0, 66, 157, 0.1)).

Avoid heavy borders; use subtle 1px outlines in a light gray color (#E9ECEF) for form inputs and inactive states to maintain a light, modern touch.

## Shapes

The shape language is consistently **Rounded**, using a 0.5rem (8px) base radius. This softens the professional "Deep Blue" and makes the platform feel more approachable and community-oriented. 

- **Standard Elements (Buttons, Inputs, Cards):** 8px corner radius.
- **Large Containers (Modals, Large Cards):** 16px corner radius.
- **Interactive Tags/Chips:** Full pill-shape (100px) to distinguish them from actionable buttons.

## Components

### Buttons
- **Primary:** Deep Blue background with White text. Bold, clear labels.
- **Secondary:** White background with Deep Blue border and text. 
- **CTA:** Use Primary style but with increased vertical padding for high-impact conversion areas.

### Input Fields
- Clean outlines with 8px rounded corners.
- Active state uses a 2px Deep Blue border.
- Error states use a soft red tint for the background and a bold red for the label.

### Cards
- Used for "Volunteer Opportunities." 
- Features a top-aligned image, a Deep Blue category tag, and a clear "Join" primary button.
- White background with Level 1 elevation.

### Progress Indicators
- Used for tracking fundraising or volunteer recruitment goals. 
- Thick, rounded bars using Light Blue for the track and Deep Blue for the progress fill.

### Community Chips
- Small, pill-shaped tags used for skills (e.g., "Teaching," "Environment") or locations. 
- Use Light Blue background with slightly darker blue text for high legibility.