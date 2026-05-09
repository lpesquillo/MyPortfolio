---
name: Human-Centered Futurism
colors:
  surface: '#faf8ff'
  surface-dim: '#d9d9e4'
  surface-bright: '#faf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3fe'
  surface-container: '#ededf8'
  surface-container-high: '#e7e7f2'
  surface-container-highest: '#e1e2ec'
  on-surface: '#191b23'
  on-surface-variant: '#434654'
  inverse-surface: '#2e3038'
  inverse-on-surface: '#f0f0fb'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#1454d3'
  primary: '#0d52d0'
  on-primary: '#ffffff'
  primary-container: '#386ceb'
  on-primary-container: '#fefcff'
  inverse-primary: '#b4c5ff'
  secondary: '#046b52'
  on-secondary: '#ffffff'
  secondary-container: '#9cf0d0'
  on-secondary-container: '#0f7056'
  tertiary: '#755700'
  on-tertiary: '#ffffff'
  tertiary-container: '#936f03'
  on-tertiary-container: '#fffbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea7'
  secondary-fixed: '#9ff3d3'
  secondary-fixed-dim: '#83d7b7'
  on-secondary-fixed: '#002117'
  on-secondary-fixed-variant: '#00513d'
  tertiary-fixed: '#ffdf9b'
  tertiary-fixed-dim: '#edc157'
  on-tertiary-fixed: '#251a00'
  on-tertiary-fixed-variant: '#5b4300'
  background: '#faf8ff'
  on-background: '#191b23'
  surface-variant: '#e1e2ec'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
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
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style
The design system embodies "Optimistic Modernism"—a vision of the future where technology serves as a seamless, quiet backdrop to human connection and natural beauty. It moves away from the cold, clinical aesthetics of traditional sci-fi, favoring an "Airy and Light-filled" atmosphere that feels intelligent yet approachable.

The style leverages **Soft Technology**: a mix of high-precision typography and organic, soft-edged containers. Visuals should evoke a sense of openness and sunlight. Key stylistic pillars include:
- **Atmospheric Clarity:** High use of white space and "Cloud" surfaces to mimic the feeling of an open horizon.
- **Human-Centric Tech:** Subtle glassmorphism and thin borders suggest advanced interfaces that are transparent and non-intrusive.
- **Vibrant Growth:** Accents of mint, gold, and lavender represent biological vitality and the warmth of a rising sun, ensuring the interface feels alive.

## Colors
The palette is divided into foundational structural tones and emotive accents.

- **Primary & Foundations:** Horizon Blue (#4F80FF) serves as the primary action color, representing clarity and progress. Deep Space (#0F172A) provides high-contrast grounding for typography, while Cloud (#F8FAFC) forms the vast majority of interface surfaces.
- **Accents (The "Growth" Palette):** Growth Mint, Sunrise Gold, and Soft Lavender are used sparingly to highlight creative work, tags, or success states.
- **Application:** Backgrounds should remain primarily "Cloud." Avoid muddy transitions; gradients should move from Horizon Blue to Soft Lavender or clear transparency to maintain a "light-filled" quality.

## Typography
This design system utilizes **Plus Jakarta Sans** for its friendly yet geometric precision. The type scale is designed for high readability and a calm, intelligent tone.

- **Scale & Rhythm:** Use "Display" weights for hero sections to create an immediate impact. "Body-lg" is the default for portfolio narratives to ensure a comfortable reading experience.
- **Casing:** Labels and small headers should occasionally use uppercase with slight letter-spacing to denote "technical" precision within the soft environment.
- **Color:** Headlines should primarily use "Deep Space" (#0F172A) at 100% opacity, while body text can drop to 80% to soften the visual weight.

## Layout & Spacing
The layout follows a **Fluid Grid** model with generous outer margins to emphasize the "airy" philosophy.

- **Grid Structure:** A 12-column system is used for desktop. Components should often span "inner" columns (e.g., a 10-column centered container) to create breathing room.
- **Spacing Rhythm:** Based on an 8px base unit. Vertical spacing between sections should be significant (96px to 160px) to mimic the feeling of an open horizon.
- **Reflow:** On mobile, margins shrink to 20px, and the grid collapses to 1 column. Inter-component spacing remains high to maintain the "light-filled" aesthetic.

## Elevation & Depth
Depth is created through **Glassmorphism** and **Ambient Shadows** rather than stark layering.

- **Surfaces:** Use backdrop blurs (20px to 40px) on semi-transparent "Cloud" surfaces (80% opacity). This allows background imagery (sunlight, nature) to bleed through the interface.
- **Shadows:** Avoid black shadows. Use highly diffused Horizon Blue tints (e.g., `rgba(79, 128, 255, 0.08)`) with a large blur radius (32px+) to create a soft, glowing lift.
- **Borders:** Every card and container should feature a 1px solid border using a lighter version of the primary color or a white-transparent mix (`rgba(255, 255, 255, 0.4)`), defining the shape without adding visual weight.

## Shapes
The shape language is defined by the **24px corner radius**, creating a soft, approachable "friendly tech" feel.

- **Primary Radius:** Used for cards, modal containers, and hero images.
- **Button Radius:** Buttons should use the "Pill" (full radius) style to provide a distinct interactive contrast against the 24px cards.
- **Media:** Photography should always follow the 24px container radius, ensuring tech and natural imagery feel integrated into the system's structure.

## Components
- **Buttons:** Primary buttons use a solid Horizon Blue fill with white text. Secondary buttons use a transparent background with a 1px Horizon Blue border. All buttons are pill-shaped.
- **Glass Cards:** The signature component. Feature a 24px radius, a 1px semi-transparent border, and a subtle backdrop blur. Used for project showcases and testimonials.
- **Chips:** Soft Lavender or Growth Mint backgrounds at 15% opacity with high-contrast text. Used for skill tags or project categories.
- **Inputs:** Clean, 1px border fields with "Cloud" backgrounds. Focused states should feature a soft Horizon Blue "glow" (outer shadow).
- **Navigation:** Fixed header with a high backdrop blur, making it appear as a transparent layer floating over the content.
- **Imagery:** Use high-key photography. Focus on subjects involving sunlight, plants, and clean architectural lines to reinforce the "Human-Centered Futurism" theme.