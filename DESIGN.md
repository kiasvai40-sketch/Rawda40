---
name: Rawda Fashion System
colors:
  surface: '#131318'
  surface-dim: '#131318'
  surface-bright: '#39383e'
  surface-container-lowest: '#0e0e13'
  surface-container-low: '#1b1b20'
  surface-container: '#1f1f25'
  surface-container-high: '#2a292f'
  surface-container-highest: '#35343a'
  on-surface: '#e4e1e9'
  on-surface-variant: '#b9cacb'
  inverse-surface: '#e4e1e9'
  inverse-on-surface: '#303036'
  outline: '#849495'
  outline-variant: '#3b494b'
  surface-tint: '#00dbe9'
  primary: '#dbfcff'
  on-primary: '#00363a'
  primary-container: '#00f0ff'
  on-primary-container: '#006970'
  inverse-primary: '#006970'
  secondary: '#dfb7ff'
  on-secondary: '#4b007e'
  secondary-container: '#9d05ff'
  on-secondary-container: '#f7e6ff'
  tertiary: '#f6f5ff'
  on-tertiary: '#002780'
  tertiary-container: '#d0d8ff'
  on-tertiary-container: '#004eea'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#7df4ff'
  primary-fixed-dim: '#00dbe9'
  on-primary-fixed: '#002022'
  on-primary-fixed-variant: '#004f54'
  secondary-fixed: '#f1daff'
  secondary-fixed-dim: '#dfb7ff'
  on-secondary-fixed: '#2d004f'
  on-secondary-fixed-variant: '#6b00b0'
  tertiary-fixed: '#dce1ff'
  tertiary-fixed-dim: '#b6c4ff'
  on-tertiary-fixed: '#001550'
  on-tertiary-fixed-variant: '#003ab3'
  background: '#131318'
  on-background: '#e4e1e9'
  surface-variant: '#35343a'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Montserrat
    fontSize: 20px
    fontWeight: '500'
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
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: '1'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1440px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 64px
---

## Brand & Style

This design system targets a digitally-native, fashion-forward audience that seeks a blend of luxury aesthetics and high-performance utility. The brand personality is electric, sophisticated, and innovative. 

The visual style is **Glassmorphic Futurism**. It utilizes high-fidelity translucent layers, vibrant background blurs, and hyper-saturated gradients derived from the logo’s electric cyan and deep purple palette. The UI evokes the feeling of a premium physical flagship store translated into a digital space—clean, spacious, but pulsing with energy. By combining the structured utility of global e-commerce leaders with a boutique, high-contrast aesthetic, the system provides a frictionless yet memorable shopping experience.

## Colors

The palette is anchored in a deep, "obsidian" dark mode to allow the electric accents to pop. 

- **Electric Cyan (#00F0FF):** Used for primary actions, success states, and high-priority price highlights.
- **Deep Purple (#9D00FF):** Used for secondary accents, category tags, and brand moments.
- **Vibrant Blue (#2962FF):** Used for interactive elements and informational states.
- **The Obsidian Base (#0A0A0F):** Provides a high-contrast canvas that reduces eye strain while maintaining a premium, "night-mode" luxury feel.

Gradients should be applied sparingly to buttons, progress bars, and active navigation states to maintain visual hierarchy without overwhelming the content.

## Typography

This design system uses a dual-font approach to balance editorial impact with functional clarity. 

**Montserrat** is used for headlines to convey confidence and a geometric, urban fashion aesthetic. It should be set with tighter letter spacing for large display sizes to maintain a "tight" editorial look.

**Inter** is the workhorse for body text, product descriptions, and labels. Its high x-height ensures maximum legibility in dense product grids and checkout flows. For labels and "Buy Now" CTAs, use the Bold/Uppercase style of Inter to ensure they stand out against the high-energy backgrounds.

## Layout & Spacing

The system follows a **Fixed-Fluid Grid** hybrid. Content is contained within a 1440px max-width container on desktop, utilizing a 12-column structure. 

- **Desktop (1440px+):** 12 columns, 24px gutters, 64px outside margins.
- **Tablet (768px - 1439px):** 8 columns, 16px gutters, 32px outside margins.
- **Mobile (Up to 767px):** 4 columns, 12px gutters, 16px outside margins.

Spacing follows an 8px base unit. Use generous vertical padding (64px - 128px) between homepage sections to create a "breathing" luxury feel, contrasting with the tighter, high-efficiency spacing used in the search and filtering results.

## Elevation & Depth

Hierarchy is established through **Glassmorphism** and light-source simulation rather than heavy drop shadows.

- **Level 1 (Base):** Obsidian background.
- **Level 2 (Cards/Inputs):** Semi-transparent surfaces (10% opacity white) with a 20px backdrop blur and a 1px "inner glow" border (20% opacity white).
- **Level 3 (Modals/Popovers):** Higher transparency (15% opacity), 40px backdrop blur, and a subtle "Cyan-to-Purple" 1px gradient border.
- **Floating Actions:** Use a diffused, colored outer glow (`box-shadow: 0 10px 30px -10px #00F0FF`) to indicate interactability and "lift" the button off the dark surface.

## Shapes

The shape language is extremely soft and approachable, utilizing `rounded-2xl` as the standard for major containers.

- **Product Cards:** 1.5rem (24px) corner radius to create a friendly, modern frame for fashion imagery.
- **Buttons:** Fully pill-shaped (100px) to signify a distinctive "actionable" area.
- **Inputs:** 0.75rem (12px) for a balanced look that accommodates text comfortably.
- **Selection Indicators:** Small dots or 4px rounded rectangles for tabs.

The generous curves are designed to contrast with the sharp, high-energy neon colors, balancing "tech" with "fashion."

## Components

### Elegant Product Cards
Cards feature a full-bleed image with a subtle gradient overlay at the bottom to ensure text legibility. The price is highlighted in **Electric Cyan**. A "Quick Add" button appears on hover using a glassmorphic blur effect.

### Professional Navigation
The header is a "sticky" glassmorphic bar. On scroll, it increases in blur intensity. Menu items use Montserrat with a thin Cyan underline for the active state. Search bars are wide with a low-opacity border that glows Cyan when focused.

### Call-to-Action Buttons
Primary "Buy Now" buttons use the **Electric Flow** gradient with white text for maximum contrast. They should have a subtle hover scale effect (1.05x) and a soft cyan glow.

### Chips & Tags
Discount tags use a Deep Purple background with a small Cyan dot icon. Category chips are outlined with a 1px cyan border, filling with the gradient only when selected.

### Input Fields
Inputs are dark with 1px borders. Upon focus, the border transitions to a Cyan-to-Purple gradient, and the background blur increases slightly to give the user a sense of "focus depth."