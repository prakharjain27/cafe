---
name: Celestial Horizon
colors:
  surface: '#131313'
  surface-dim: '#131313'
  surface-bright: '#393939'
  surface-container-lowest: '#0e0e0e'
  surface-container-low: '#1c1b1b'
  surface-container: '#201f1f'
  surface-container-high: '#2a2a2a'
  surface-container-highest: '#353534'
  on-surface: '#e5e2e1'
  on-surface-variant: '#dcc1b1'
  inverse-surface: '#e5e2e1'
  inverse-on-surface: '#313030'
  outline: '#a48c7d'
  outline-variant: '#564337'
  surface-tint: '#ffb783'
  primary: '#ffb783'
  on-primary: '#4f2500'
  primary-container: '#e67e22'
  on-primary-container: '#502600'
  inverse-primary: '#944a00'
  secondary: '#e3beb8'
  on-secondary: '#422a26'
  secondary-container: '#5b403c'
  on-secondary-container: '#d1ada7'
  tertiary: '#86cfff'
  on-tertiary: '#00344c'
  tertiary-container: '#00a3e4'
  on-tertiary-container: '#00354d'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffdcc5'
  primary-fixed-dim: '#ffb783'
  on-primary-fixed: '#301400'
  on-primary-fixed-variant: '#713700'
  secondary-fixed: '#ffdad4'
  secondary-fixed-dim: '#e3beb8'
  on-secondary-fixed: '#2b1613'
  on-secondary-fixed-variant: '#5b403c'
  tertiary-fixed: '#c7e7ff'
  tertiary-fixed-dim: '#86cfff'
  on-tertiary-fixed: '#001e2e'
  on-tertiary-fixed-variant: '#004c6d'
  background: '#131313'
  on-background: '#e5e2e1'
  surface-variant: '#353534'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 80px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '600'
    lineHeight: '1.3'
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: '1.0'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1440px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 24px
  stack-lg: 64px
  stack-md: 32px
  stack-sm: 16px
---

## Brand & Style

The brand personality is evocative of the "Golden Hour"—that transition between the sun's warmth and the moon's elegance. It is premium, romantic, and cinematic, prioritizing high-end storytelling over functional utility. 

The design style is **Modern Luxury Glassmorphism**. It utilizes depth through translucent layers, generous whitespace inspired by Apple’s editorial layouts, and a sophisticated interplay of light and shadow. The interface should feel like a high-end lifestyle magazine, with large-scale imagery, smooth motion, and a sense of physical space. Every interaction is designed to feel deliberate and effortless, mimicking the service of a 5-star rooftop establishment.

## Colors

The palette is anchored by the transition of day into night. **Dark Charcoal** serves as the primary canvas to allow high-contrast photography and golden accents to pop. **Sunset Orange** is used sparingly for primary actions and highlights, evoking the warmth of a setting sun.

**Soft Gold** is reserved for delicate accents—borders, icons, and interactive glows—to convey a sense of prestige. **Muted Beige** and **Cream** provide a soft, tactile alternative for light-themed sections (such as breakfast menus or daytime event pages), ensuring the brand remains approachable yet refined.

## Typography

The typography system relies on a high-contrast pairing. **Playfair Display** provides a romantic, serif elegance for headlines, mimicking the masthead of a luxury publication. **Inter** offers a clean, neutral balance for body copy to ensure legibility across all lighting conditions.

Large display type should be used with tight line-height to create a cinematic impact on hero sections. For body text, generous line-height (1.6) is maintained to enhance the "airy" and "breathable" feel of the layouts. Labels and overlines use increased letter-spacing and uppercase styling to denote categorization and hierarchy without adding visual bulk.

## Layout & Spacing

The layout philosophy follows a **fixed-width centered grid** for desktop and a **fluid safe-margin system** for mobile. We prioritize "generous whitespace" to allow the food photography and rooftop views to breathe.

- **Desktop (1440px+):** A 12-column grid with 80px side margins and 24px gutters. Content should often be offset or asymmetrical to create an editorial, high-fashion aesthetic.
- **Tablet (768px - 1024px):** 8-column grid with 40px margins.
- **Mobile (<768px):** 4-column grid with 24px margins. Vertically, we use a modular scale of 16px to maintain a rhythmic vertical flow between elements.

## Elevation & Depth

This design system eschews traditional shadows in favor of **Glassmorphism and Tonal Layers**. Depth is created through three primary methods:

1.  **Backdrop Blurs:** High-level surfaces (like navigation bars and modals) use a 20px - 30px Gaussian blur with a semi-transparent white or charcoal fill (10-15% opacity).
2.  **Luminous Borders:** Instead of shadows, cards are defined by a 1px solid border with a subtle gradient (Soft Gold to Transparent) to catch the "light."
3.  **Soft Gold Glows:** Interactive elements like buttons or active cards emit a soft, diffused golden glow (#D4AF37 at 20% opacity) on hover, simulating the warmth of candlelight or sunset reflections.

## Shapes

The shape language is sophisticated and organic. A consistent **12px to 24px radius** is applied to all primary containers and buttons. Smaller components like chips use a fully rounded (pill) shape to contrast with the more structured, large-scale glass cards. The "Rounded" setting (Value: 2) ensures the UI feels modern and soft without becoming juvenile or overly playful.

## Components

### Navigation
The navigation is a sticky, transparent bar that utilizes glassmorphism. On scroll, the background blur increases, and a fine gold bottom-border appears. Links are in uppercase `label-sm` style.

### Buttons
- **Primary:** Solid Deep Brown background with Gold text, or Warm Sunset Orange for high-conversion actions.
- **Ghost:** Transparent background with a 1px Soft Gold border. On hover, the button fills with a 10% gold tint.
- **Transition:** All button states must have a 300ms ease-in-out transition for color and glow changes.

### Glass Cards
Used for menu categories and event highlights. These feature a 15% opacity Charcoal background, a 20px backdrop blur, and a subtle golden stroke. Inside padding is generous (minimum 32px).

### Menu Lists
Menu items use a clean layout: The item name in `headline-md` (smaller scale), the description in `body-md` with 60% opacity, and the price in `headline-md` using the Soft Gold accent.

### Interactive Elements
Hover states on images should trigger a subtle "scale-up" (1.05x) and a soft gold overlay vignette to draw the user's eye deeper into the photography.