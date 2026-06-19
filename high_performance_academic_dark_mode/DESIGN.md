---
name: High-Performance Academic Dark Mode
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1b1b1c'
  surface-container: '#202020'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353535'
  on-surface: '#e5e2e1'
  on-surface-variant: '#e6beb2'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#303030'
  outline: '#ad897e'
  outline-variant: '#5c4037'
  surface-tint: '#ffb59e'
  primary: '#ffb59e'
  on-primary: '#5e1700'
  primary-container: '#ff571a'
  on-primary-container: '#521300'
  inverse-primary: '#ae3200'
  secondary: '#c6c6c7'
  on-secondary: '#2f3131'
  secondary-container: '#454747'
  on-secondary-container: '#b4b5b5'
  tertiary: '#a5c8ff'
  on-tertiary: '#00315e'
  tertiary-container: '#2492ff'
  on-tertiary-container: '#002a53'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdbd0'
  primary-fixed-dim: '#ffb59e'
  on-primary-fixed: '#3a0b00'
  on-primary-fixed-variant: '#852400'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#d4e3ff'
  tertiary-fixed-dim: '#a5c8ff'
  on-tertiary-fixed: '#001c3a'
  on-tertiary-fixed-variant: '#004785'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353535'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.1'
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  stack-sm: 12px
  stack-md: 24px
  stack-lg: 48px
---

## Brand & Style

The design system is built for an assignment service that prioritizes speed, authority, and modern professionalism. It targets a student and academic demographic that values efficiency and high-quality results. 

The visual style is **Corporate / Modern** with a distinct **High-Contrast** edge. It utilizes a deep charcoal base to reduce eye strain during late-night study sessions, punctuated by vibrant orange accents that evoke energy and urgency. The aesthetic is clean, utilizing intentional whitespace (or "dark space") and crisp, heavy-weighted typography to establish a clear hierarchy of information. Vector illustrations should remain flat and stylistic, using the brand's primary orange and neutral tones to ensure they feel integrated rather than decorative.

## Colors

This design system is strictly **dark mode first**. The primary color is a vibrant, high-saturation orange used sparingly for calls to action, highlights, and critical status indicators. 

The background hierarchy relies on charcoal tones:
- **Primary Background:** `#1e1e1e` for the main canvas.
- **Surface/Card Background:** `#2a2a2a` to create subtle elevation against the primary background.
- **Inverted Surfaces:** Pure white or the primary orange are used for high-impact cards to draw immediate attention.

Typography uses pure white for headlines to maximize contrast, and a muted grey for secondary body text to maintain a comfortable reading experience.

## Typography

The typography is bold and modern. **Montserrat** is used for all display and headline roles to convey strength and reliability. Headlines should frequently use "All Caps" for secondary titles or short punchy statements to mimic the high-energy editorial style of the reference image.

**Hanken Grotesk** serves as the body face, providing a sharp, highly legible contemporary feel that scales well from desktop to mobile. 

For technical details, metadata, or "code-like" status updates (e.g., "Status: In Progress"), **JetBrains Mono** is introduced to provide a subtle nod to the precision and "engineered" nature of the service.

## Layout & Spacing

The design system utilizes a **12-column fluid grid** for desktop and a **4-column grid** for mobile. The layout philosophy emphasizes a strong vertical "stacking" rhythm using multiples of 8px.

Large sections are separated by generous padding (`stack-lg`) to allow the dark background to provide visual breathing room. Content is often contained within thin-bordered or slightly elevated containers to maintain organization without clutter. On mobile, margins should shrink to 16px to maximize the available real estate for content cards.

## Elevation & Depth

This design system avoids traditional heavy shadows. Instead, it uses **Tonal Layers** and **Low-contrast Outlines** to communicate hierarchy:

1.  **Level 0 (Base):** `#1e1e1e` - The main canvas.
2.  **Level 1 (Cards):** `#2a2a2a` - Subtle elevation for grouped content.
3.  **Level 2 (Active/Hover):** A thin 1px border using `#ffffff` at 10% opacity or the primary orange `#ff4d00` for active states.
4.  **Accent Elevation:** For high-priority items, a solid orange background with black text is used to "pop" the element forward without any shadow.

Vector illustrations should be placed directly on the surface colors or within their own distinct, rounded containers to maintain a clean "sticker-like" aesthetic.

## Shapes

The shape language is defined by **Rounded (level 2)** corners. This provides a approachable, modern feel that softens the "aggressive" nature of the dark/orange high-contrast palette. 

Standard components (buttons, input fields) use a 0.5rem (8px) radius. Larger containers and cards use a 1rem (16px) radius. Special elements, such as "Join" or "Contact" badges, can utilize pill-shaped (fully rounded) corners to distinguish them from standard functional buttons.

## Components

### Buttons
- **Primary:** Solid orange (`#ff4d00`) background with black text. 8px rounded corners. Includes a small "arrow-up-right" icon for external or primary actions.
- **Secondary:** Transparent background with a 1px white border. White text.
- **Ghost:** White text with no background, used for secondary navigation.

### Cards
- **Standard:** Dark grey (`#2a2a2a`) background. Should include a distinct "header" area for labels and an "action" area (usually an icon in a circle) at the top right.
- **Featured:** Solid orange background with black text/icons. Used sparingly for pricing tiers or "Hot" services.

### Inputs & Forms
- **Fields:** Darker charcoal background than the base, with a thin 1px border that turns orange on focus.
- **Labels:** Small, uppercase, and using the monospaced font for a technical look.

### Chips & Badges
- Small, rounded containers with low-opacity orange backgrounds and solid orange text. Used for "Subject Tags" (e.g., "MATH", "ESSAY").

### Illustrations
- Flat, vector-style characters with a limited color palette (Orange, White, Grey, Yellow). Illustrations should be placed in rounded-square containers with a slightly different background shade to separate them from the main UI.