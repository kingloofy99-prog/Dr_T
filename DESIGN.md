---
name: Lumina Tech Narrative
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
  on-surface-variant: '#3c4a3d'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#6c7b6c'
  outline-variant: '#bbcbba'
  surface-tint: '#006d34'
  primary: '#006d34'
  on-primary: '#ffffff'
  primary-container: '#00cc66'
  on-primary-container: '#004f24'
  inverse-primary: '#37e279'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#5f5e5e'
  on-tertiary: '#ffffff'
  tertiary-container: '#b3b1b1'
  on-tertiary-container: '#444444'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#63ff94'
  primary-fixed-dim: '#37e279'
  on-primary-fixed: '#00210b'
  on-primary-fixed-variant: '#005225'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Bebas Neue
    fontSize: 64px
    fontWeight: '400'
    lineHeight: 72px
    letterSpacing: 0.02em
  display-lg-mobile:
    fontFamily: Bebas Neue
    fontSize: 40px
    fontWeight: '400'
    lineHeight: 48px
    letterSpacing: 0.02em
  headline-md:
    fontFamily: Bebas Neue
    fontSize: 32px
    fontWeight: '400'
    lineHeight: 40px
    letterSpacing: 0.01em
  headline-sm:
    fontFamily: Bebas Neue
    fontSize: 24px
    fontWeight: '400'
    lineHeight: 32px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: Bodoni Moda
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Bodoni Moda
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  label-sm:
    fontFamily: Inter
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
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
  section-gap-lg: 120px
  section-gap-sm: 64px
---

## Brand & Style

The design system is engineered for high-end technology showcases where precision and sophistication are paramount. The brand personality is professional, forward-thinking, and premium. It targets a discerning audience that values clarity, performance, and aesthetic refinement.

The visual style is a blend of **Corporate Modern** and **Glassmorphism**. It utilizes expansive white space to denote quality and focus, accented by high-fidelity gradients that suggest energy and innovation. The emotional response should be one of total confidence and "engineered" elegance—clean, but never cold.

## Colors

The palette is anchored by a "Precision Green" primary color, representing growth and technological vitality. This is contrasted against a deep "Onyx Black" to provide a grounded, high-end feel. 

- **Primary:** Used for key calls to action and active states.
- **Secondary/Tertiary:** Used for structural elements, deep backgrounds, and high-contrast typography.
- **Neutral:** A range of ultra-light grays (#f9fafb) provides soft layering without breaking the minimalist aesthetic.
- **Gradients:** Sophisticated directional gradients (135 degrees) are applied to primary buttons and hero accents to create depth and a "glow" effect against the white background.

## Typography

This design system uses a sophisticated editorial-tech hybrid strategy. **Bebas Neue** provides a tall, impactful, and condensed personality for headlines, while **Bodoni Moda** adds a high-fashion, serif elegance to body copy, creating a unique "Tech-Vogue" aesthetic. **Inter** is retained for maximum legibility in UI labels and micro-copy.

Headlines should use slightly expanded letter-spacing to enhance the architectural feel of the condensed type. Labels use an uppercase treatment with increased tracking to evoke a premium, technical feel similar to luxury watchmaking or aerospace interfaces. On mobile, display sizes scale down while maintaining their distinct vertical presence.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop, centering content within a 1280px container to maintain a high-end "gallery" feel. A 12-column system is used with generous 24px gutters.

Spacing is intentionally expansive. Section gaps use large increments (120px+) to allow the product photography and headlines to breathe. Vertical rhythm is based on an 8px base unit. On mobile devices, margins are reduced to 20px, and complex multi-column grids collapse into a single-column stack with elements ordered by visual hierarchy.

## Elevation & Depth

Depth is achieved through **Ambient Shadows** and **Tonal Layering**. Surfaces are never truly flat; they exist in a defined 3D space.

- **Base Layer:** Pure white (#FFFFFF) or very light neutral (#f9fafb).
- **Cards:** Use an ultra-diffused shadow (0px 12px 32px) with a very low opacity (4-6%) black or dark-green tint.
- **Interactive Depth:** When hovered, cards should subtly lift (reducing shadow blur and increasing offset) to provide tactile feedback.
- **Glassmorphism:** Overlays and navigation bars use a backdrop filter (blur: 20px) with a semi-transparent white fill (opacity: 80%) to maintain context of the content beneath.

## Shapes

The design system utilizes a **Rounded** shape language. This softens the technical nature of the product, making it feel more approachable and modern. 

Standard components (buttons, inputs) use a 0.5rem (8px) radius. Larger containers and cards use 1rem (16px) to emphasize the "shell" of the content. High-contrast elements, like tags or featured badges, may occasionally use a full pill-shape to distinguish them from functional UI controls.

## Components

### Buttons
Primary buttons feature the green-to-dark-green gradient with white text. They should have a subtle inner-glow on the top edge to simulate a physical button. Secondary buttons are outlined in thin (1px) neutral-300 borders or use a "ghost" style with black text.

### Cards
Product cards are the centerpiece. They feature white backgrounds, the standard `rounded-lg` radius, and the ambient shadow defined in the Elevation section. Content inside cards should have a minimum of 32px internal padding.

### Input Fields
Inputs are minimalist: a light-gray background (#f9fafb) with no border in the default state. On focus, they transition to a white background with a 1px solid Primary Green border and a soft green outer glow.

### Chips & Badges
Small, high-contrast labels used for categories. They should use the `label-sm` typography (Inter) and can either be solid black with white text or a soft green tint with dark green text.

### Lists
Lists should avoid dividers where possible, using white space and indentation to signify hierarchy. When dividers are necessary, they must be hair-line (0.5px) and very low contrast.