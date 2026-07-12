---
name: Serene Resolve
colors:
  surface: '#fbf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0eded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e1'
  on-surface: '#1b1c1c'
  on-surface-variant: '#4a454d'
  inverse-surface: '#303030'
  inverse-on-surface: '#f3f0f0'
  outline: '#7c757e'
  outline-variant: '#cdc4ce'
  surface-tint: '#6d5483'
  primary: '#27103c'
  on-primary: '#ffffff'
  primary-container: '#3d2652'
  on-primary-container: '#a98dc1'
  inverse-primary: '#d9bbf1'
  secondary: '#496553'
  on-secondary: '#ffffff'
  secondary-container: '#c8e7d1'
  on-secondary-container: '#4d6957'
  tertiary: '#301400'
  on-tertiary: '#ffffff'
  tertiary-container: '#4a280a'
  on-tertiary-container: '#c18d68'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f1dbff'
  primary-fixed-dim: '#d9bbf1'
  on-primary-fixed: '#27103c'
  on-primary-fixed-variant: '#553d6a'
  secondary-fixed: '#cbead4'
  secondary-fixed-dim: '#afceb9'
  on-secondary-fixed: '#052013'
  on-secondary-fixed-variant: '#314d3c'
  tertiary-fixed: '#ffdcc5'
  tertiary-fixed-dim: '#f4bb92'
  on-tertiary-fixed: '#301400'
  on-tertiary-fixed-variant: '#653d1e'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e1'
typography:
  headline-lg:
    fontFamily: Source Serif 4
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Source Serif 4
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Source Serif 4
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Manrope
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: Manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.02em
  label-xs:
    fontFamily: Manrope
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 48px
---

## Brand & Style

The design system embodies a philosophy of "Serene Resolve"—a balance between editorial sophistication and functional precision. It is designed for high-stakes environments that require calm, focused decision-making, such as high-end fintech, health-tech, or premium productivity tools.

The aesthetic follows a **Minimalist-Editorial** direction. It leverages expansive whitespace, a warm and inviting light-mode foundation, and high-contrast accents to create a hierarchy that feels authoritative yet approachable. The UI avoids unnecessary ornamentation, relying instead on deliberate typographic scale and a rich, nature-inspired palette to guide the user. The emotional response is one of clarity, reliability, and quiet confidence.

## Colors

The palette is anchored by a warm, creamy parchment background that reduces eye strain and provides a premium, tactile feel. 

- **Primary (Deep Purple):** Used for primary actions, active states, and high-level branding. It conveys wisdom and stability.
- **Secondary (Forest Green):** Reserved for success states, growth indicators, and secondary interactive elements.
- **Neutral (Charcoal Grey):** The primary color for body text and iconography, ensuring softness without sacrificing legibility.
- **Accents:** Borders and dividers should use a lightened tint of the primary or secondary colors (at 10-15% opacity) to maintain structure without breaking the serene flow of the layout.

## Typography

Typography is the core of the "Serene Resolve" aesthetic. We pair a sturdy, literary Serif for headlines with a clean, modern Grotesque for functional UI elements.

- **Headlines:** Use **Source Serif 4**. It provides a traditional, authoritative voice. Tighten letter spacing for larger sizes to maintain a modern editorial feel.
- **Body & UI:** Use **Manrope**. Its geometric but friendly proportions ensure clarity in data-heavy views.
- **Visual Weight:** Use Charcoal Grey for body text to maintain a soft, readable contrast against the creamy background. Use the Deep Purple for subheaders to add a layer of sophisticated hierarchy.

## Layout & Spacing

The layout follows a **Fixed Grid** model for desktop to preserve editorial intent, while transitioning to a fluid model for mobile devices.

- **Grid:** 12-column structure on desktop with 24px gutters.
- **Rhythm:** An 8px linear scale is used for all internal component spacing (padding/margins).
- **Whitespace:** Emphasize "Negative Space" as a design element. Content should be grouped in clear modules with generous margins (minimum 48px between major sections) to prevent cognitive overload.
- **Mobile:** Margins shrink to 16px. Typography scales down slightly, and multi-column grids collapse into a single vertical stack.

## Elevation & Depth

This design system avoids heavy shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surface Tiers:** Use subtle shifts in background color (e.g., a slightly cooler or darker cream) to distinguish between the canvas and containers.
- **Outlines:** Instead of drop shadows, use 1px borders in a soft Deep Purple tint (#3D2652 at 8% opacity). This creates a "ghost border" effect that feels architectural and clean.
- **Interactions:** Use a very soft, diffused ambient shadow (10% opacity, 20px blur) only for floating elements like dropdowns or modals to separate them from the main page flow.

## Shapes

The shape language is "Soft," utilizing subtle corner radii to bridge the gap between the sharpness of the Serif typography and the fluidity of the modern UI.

- **Components:** Standard buttons and input fields use a 0.25rem (4px) radius.
- **Large Elements:** Cards and containers use a 0.5rem (8px) radius to feel substantial but not overly "bubbly."
- **Consistency:** Never use fully rounded "pill" shapes, as they detract from the professional, grounded nature of the brand.

## Components

- **Buttons:** Primary buttons use a solid Deep Purple background with white text. Secondary buttons use a Forest Green outline with Forest Green text. All buttons should have a subtle hover transition that deepens the color slightly.
- **Input Fields:** Use a transparent background with a 1px Charcoal Grey border (20% opacity). On focus, the border becomes the Deep Purple primary color at 100% opacity.
- **Cards:** Cards should be borderless with a very slight background tint (#F7F4EF) or use the "ghost border" outlined in the Elevation section.
- **Chips/Badges:** Use the Forest Green for positive status indicators and the Deep Purple for category tags, always utilizing a high-transparency fill (10%) and solid text color for readability.
- **Lists:** Use 1px dividers in a very light neutral tint. Ensure generous vertical padding (16px+) between list items to maintain the "Serene" layout rhythm.